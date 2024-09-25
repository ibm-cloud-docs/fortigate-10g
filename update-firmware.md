---

copyright:
  years: 2017, 2024
lastupdated: "2024-09-25"

keywords: updating, firmware, fortigate

subcollection: vsrx

---

{{site.data.keyword.attribute-definition-list}}

# Updating the FSA 10 Gbps firmware
{: #updating-fsa-10g}

You can update a FortiGate Security Appliance (FSA) FG-1500DT 10 Gbps to the latest available firmware version by opening a [support case](/docs/fortigate-10g?topic=fortigate-10g-getting-help-and-support-for-fortigate-security-appliance-10gbps) in the IBM Cloud portal with the following information:
{: shortdesc}

* The firmware version to which you want to update
* The name or IP address of your FortiGate appliance
* A requested (2 hour) maintenance window that includes your time zone

IBM support will then schedule and perform the required maintenance and update for you.

Due to customer VDOM restrictions, the FortiGate Security Appliance (FSA) 10 Gbps can only be updated to the latest available firmware by the security support engineering team. Network engineering determines which firmware version is the most appropriate for the IBM Cloud Infrastructure environment. At this time, `7.2.9` is available.
{: note}

For each FortiGate (HA pair or standalone), the security support engineering team requests a 2 hour maintenance window to complete the update. The actual completion time is generally less than 2 hours and is determined by the amount of hops in the upgrade path to the desired version, cluster synchronization troubleshooting, and any other troubleshooting necessary during the upgrade. Versions are updated as vulnerabilities are released. As a result, multihops in firmware are generally no longer necessary, and the FortiManager automated process reduces issues and the amount of time this takes. Sometimes, this will take only 10 or 20 minutes. For standalone FortiGates, there will be an outage to servers routed behind them, as well as an outage on the FortiGate itself during reboot. That outage occurs for each hop in the upgrade path, because each hop requires a reboot. For HA FortiGates, the process has brief outages as failovers occur during the process. These failovers and reboots occur for each hop in the upgrade path, and brief outages can occur for each one.

Fortinet's best practices for firmware upgrades require that you to review the resolved and known issues in the release notes for your desired version.
{: tip}
