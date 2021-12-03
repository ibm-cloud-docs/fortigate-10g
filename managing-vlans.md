---

copyright:
  years: 2017, 2019
lastupdated: "2019-11-13"

keywords: manage, vlans, managing, disassociate, route, vlan, firewall

subcollection: fortigate-10g

---

{{site.data.keyword.attribute-definition-list}}

# Managing VLANs
{: #managing-vlans}

You can manage the VLAN associated with your FortiGate Security Appliance (FSA) 10 Gbps with the instructions here.
{: shortdesc}

First, go to the Device Overview page. Then, click **VLANs** in the side navigation, **Manage** in the Status Module, or the **Manage All** link in the VLAN module.

## Associating a VLAN with a firewall
{: #associate-a-vlan-with-a-firewall}

Click **Add VLAN** and select a VLAN from the menu. Then, click **Save** and confirm your selection.
The VLAN association action does not route the VLAN through the firewall.

## Disassociating a VLAN with a firewall
{: #disassociate-a-vlan-with-a-firewall}

Select your VLAN by toggling the checkboxes. Then, click **Disassociate** and confirm your selection.
If the VLAN is routed through the firewall, this action routes the VLAN around the firewall before disassociation.

## Routing a VLAN around a firewall
{: #route-a-vlan-around-a-firewall}

Select your VLAN by toggling the checkboxes. Then, click **Route Around** and confirm your selection.

## Routing a VLAN through a firewall
{: #route-a-vlan-through-a-firewall}

Select your VLAN by toggling the checkboxes. Then, click **Route Through** and confirm your selection.
