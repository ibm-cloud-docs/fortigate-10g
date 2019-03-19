---

copyright:
  years: 2017
lastupdated: "2018-11-10"

keywords: manage, vlans, managing, disassociate, route, vlan, firewall

subcollection: fortigate-10g

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}
{:codeblock: .codeblock}
{:pre: .pre}
{:screen: .screen}
{:tip: .tip}
{:download: .download}

# Managing VLANs
{: #managing-vlans}

To manage the VLANs associated with your firewall, click **VLANs** in the side navigation, **Manage** in the Status Module, or the **Manage All** link in the VLANs Module. You will then be directed to the VLANs page.

## Associate a VLAN with a Firewall

Click **Add VLAN** and select a VLAN from the dropdown. Then click **Save** and confirm your selection.
The VLAN association action does not route the VLAN through the firewall.

## Disassociate a VLAN with a Firewall

Select the desired VLAN(s) by toggling the checkboxes. Then click **Disassociate** and confirm your selection.
If the VLAN is routed through the firewall, this action will route the VLAN around the firewall prior to disassociation.

## Route a VLAN Around a Firewall

Select the desired VLAN(s) by toggling the checkboxes. Then click **Route Around** and confirm your selection.

## Route a VLAN Through a Firewall

Select the desired VLAN(s) by toggling the checkboxes. Then click **Route Through** and confirm your selection.
