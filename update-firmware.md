---

copyright:
  years: 2018, 2022
lastupdated: "2022-10-26"

keywords: updating, firmware, fortigate

subcollection: vsrx

---

{{site.data.keyword.attribute-definition-list}}

# Updating the FSA 10 Gbps firmware
{: #Updating-fsa-10g}

You can update a FortiGate Security Appliance (FSA) FG-1500DT 10 Gbps to the latest available firmware version by opening a [support case](/docs/fortigate-10g?topic=fortigate-10g-getting-help-and-support-for-fortigate-security-appliance-10gbps) in the IBM Cloud portal with the following information:
{: shortdesc}

* The firmware version to which you want to update
* The name or IP address of your FortiGate appliance
* A requested (4 hour) maintenance window that includes your time zone

IBM support will then schedule and perform the required maintenance and update for you.

Due to customer VDOM restrictions, the FortiGate Security Appliance (FSA) 10 Gbps can only be updated to the latest available firmware by the security support engineering team. Network engineering determines which firmware version is the most appropriate for the IBM Cloud Infrastructure environment. At this time, `6.4.8` and `7.0.7` are both available. 
{: note}

For each FortiGate (HA pair or standalone), the security support engineering team requests a 4 hour maintenance window. The actual completion time can be less than 4 hours and is determined by the amount of hops in the upgrade path to the desired version, cluster synchronization troubleshooting, and any other troubleshooting that becomes necessary during the upgrade. For standalone FortiGates, there will be an outage to servers routed behind the FortiGate, as well as an outage on the FortiGate itself during its reboot. That outage occurs for each hop in the upgrade path, because each hop requires a reboot. For HA FortiGates, the process has no downtime for servers behind the pair, but brief outages can occur as failovers happen during the process. These failovers and reboots happen for each hop in the upgrade path, so brief outages can occur for each one.

Fortinet's best practices for firmware upgrades require that you to review the resolved and known issues in the release notes for your desired version. 
{: tip}
