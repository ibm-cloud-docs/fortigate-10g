---

copyright:
  years: 2017, 2025
lastupdated: "2025-07-21"

keywords: updating, firmware, fortigate

subcollection: fortigate-10g

---

{{site.data.keyword.attribute-definition-list}}

# Updating the FSA 10 Gbps firmware
{: #updating-fsa-10g}

You can update a FortiGate Security Appliance (FSA) FG-1500DT 10 Gbps to the latest available firmware version by opening a [support case](/docs/fortigate-10g?topic=fortigate-10g-getting-help-and-support-for-fortigate-security-appliance-10gbps) in the IBM Cloud portal with the following information:
{: shortdesc}

* The firmware version to which you want to update, which is predetermined now.
* The name or IP address of your FortiGate appliance.
* A requested 2-hour maintenance window that includes your time zone.

IBM Cloud support schedules and performs the required maintenance and update for you.

Due to customer VDOM restrictions, the FortiGate Security Appliance (FSA) 10 Gbps can be updated to the latest available firmware only by the IBM Cloud Support Security team. The network engineering team determines the appropriate firmware version based on the compatibility with the IBM Cloud Infrastructure environment. Currently, the version `7.2.11` is the latest available.
{: note}

For each FortiGate device, whether High-Availability (HA) pair or a stand-alone unit, the security support engineering team requires a 2-hour maintenance window to complete the update. Typically, the actual update time is less than 2 hours. The duration depends on the number of hops required to reach the target version, cluster synchronization, and any other troubleshooting required during the process. Updates are applied across the whole fleet consistently, which minimizes the need for multiple firmware hops. Therefore, if your device already runs a mature firmware version, fewer hops are needed, which can reduce the update time to as little as 10 to 20 minutes.

## Downtime considerations during firmware updates
{: #updating-fsa-10g-downtime}

During firmware upgrades, FortiGate HA clusters can experience brief outages due to failovers. Each hop in the upgrade path involves failovers and restarts, which can result in temporary outages. Keep in mind that even with HA configurations, seamless failovers aren't guaranteed. Outages occur during failovers, regardless of optimizations that are made to session synchronization and session pickup settings. Certain traffic types, such as GRE and IPsec, might not be compatible with session pickup and require session restarts. For more details, see [HA session-pickup](https://community.fortinet.com/t5/FortiGate/Technical-Tip-HA-session-failover-session-pickup/ta-p/191165){: external}.

The primary goal of session pickup and HA is to minimize outages during failover. However, management traffic, also known as control plane traffic, disconnects during failovers, and you must restart the session for it to work. This process applies to GRE and various other traffic types that are discussed in the linked article.
{: note}

Typically, a FortiGate cluster experiences one or two failovers during a version upgrade, primarily influenced by the `override` and `ha-uptime-margin` settings. The `override` setting, if enabled, allows the original primary device to automatically reclaim its role after it restarts, which can cause repeated failovers and additional downtime. When you keep it disabled, which is the default value, you can avoid the failover. The `ha-uptime-margin` setting controls how long a device must remain stable after it restarts before it can become primary again.

If you observe multiple failovers during firmware updates, contact IBM Cloud Support Security to confirm that the HA `override` setting is disabled. Additionally, request an increase in the `ha-uptime-margin` value from the default 300 seconds to 600 seconds, which reduces the likelihood of premature role switching.
{: tip}

### BGP considerations during failover
{: #updating-fsa-10g-bgp-downtime}

During a firmware upgrade, FortiGate HA clusters that use BGP might experience outages because the BGP process on the secondary device starts only when the device becomes primary. This mechanism causes BGP to restart (flap), and if GRE or IPsec tunnels are in use, they might also reset unless you enable the `ha-sync-esp-seqno` option in the phase1-interface configurations. BGP flapping and convergence can lead to significant issues and prolonged outages during firmware updates. However, tuning the settings can facilitate faster failover and convergence.

For further information, see [BGP Timers](https://community.fortinet.com/t5/FortiGate/Technical-Tip-All-configurable-BGP-timers-on-the-FortiGate/ta-p/356270){: external} and [Graceful Restart](https://community.fortinet.com/t5/FortiGate/Technical-Tip-Configuring-FortiGate-HA-and-BGP-graceful-restart/ta-p/196150){: external}

By default, FortiGate devices have a global HA configuration parameter `route-ttl`, which is set to 10 seconds in version 7.2. This parameter determines how long the new primary unit retains routes during a failover that are synchronized with it. The new primary has only 10 seconds to reestablish BGP, relearn and advertise routes; otherwise, it discards those routes, which can lead to dropped traffic.

Additionally, an extra setting `advertisement-interval` is set to 30 seconds by default. This setting requires the new primary to wait 30 seconds, which means even after BGP comes up, the new primary must wait half a minute before it can relearn and advertise routes. During a failover in an FGCP cluster, a 20-second outage exists for traffic that uses BGP routes, and for any routes in the kernel routing table (FIB).

To reduce the impact during a failover, adjust the following settings:

* Increase the `route-ttl` to at least 30 seconds so that the new primary has more time to reestablish BGP and retain synchronized routes.
* Reduce the `advertisement-interval` from 30 seconds to 1 second so that it accelerates route advertisement.
* At the VDOM level, set the BGP `keepalive timer` to 5 seconds and the `hold timer` to 15 seconds.
* Enable the `link-down-failover` and `graceful-restart` settings for both BGP neighbors to help BGP recover faster.

With these configurations in place, your FortiGate can fail over with minimal disruption and the remote BGP neighbor can continue to send traffic to the failing-over FortiGate cluster. The new primary negotiates BGP to relearn and readvertise routes, which help ensure that the routes are incorporated into the kernel routing table. After 30 seconds (which is the new `route-ttl` value), the new primary discards the stale synchronized routes and replaces them with newly acquired routes. For further optimization, configure a bidirectional forwarding detection (BFD).

Before you update your Fortigate firmware, review the release notes for the version you're upgrading to. These announcements list known issues and fixes, which can help you raise relevant concerns to the IBM Cloud Support Security team when you prepare for version updates. With this approach, you can collaborate with the support team to identify and address potential issues before they escalate in the production environment.
{: tip}
