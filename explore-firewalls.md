---

copyright:
  years: 2017, 2018
lastupdated: "2019-11-13"

keywords: explore, firewalls, fsa, fortigate, juniper, vsrx, vra, virtual router appliance, security, vyatta, comparison, features

subcollection: fortigate-10g

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}
{:codeblock: .codeblock}
{:pre: .pre}
{:screen: .screen}
{:tip: .tip}
{:download: .download}
{:note: .note}
{:important: .important}
{:row-headers: .row-headers}
{:deprecated: .deprecated}

# Exploring firewalls
{: #exploring-firewalls}

IBM© Cloud offers several firewalls to choose from. The following table compares the firewall solutions to help you choose the one that's right for you. To learn more about the individual offering, click its name in the table.
{: shortdesc}

All instances of the FortiGate Security Appliance 1 Gbps and Hardware Firewall Dedicated services are deprecated. Existing instances can be used until they are no longer supported on 30 May 2021. Use one of the following available firewall options to get our latest security capabilities on IBM Cloud. For migration information, see [Migrating FortiGate Security Appliance 1Gbps](/docs/fortigate-1g?topic=fortigate-1g-migration-overview) and [Migrating Hardware Firewall (Dedicated)](/docs/hardware-firewall-dedicated?topic=hardware-firewall-dedicated-migration-overview#migration-overview).
{: deprecated}

|        | [Security Groups](/docs/security-groups?topic=security-groups-getting-started) (VSI only) | [IBM Cloud Juniper vSRX Standard](/docs/vsrx?topic=vsrx-getting-started) |[Virtual Router Appliance](/docs/virtual-router-appliance?topic=virtual-router-appliance-getting-started) | [FortiGate Security Appliance 10 Gbps](/docs/fortigate-10g?topic=fortigate-10g-getting-started) | [FortiGate Security Appliance 1 Gbps](/docs/fortigate-1g?topic=fortigate-1g-getting-started) | [Hardware Firewall ](/docs/hardware-firewall-shared?topic=hardware-firewall-shared-getting-started) | [Hardware Firewall (Dedicated)](/docs/hardware-firewall-dedicated?topic=hardware-firewall-dedicated-getting-started) | [Cloud Internet Services](/docs/cis?topic=cis-getting-started)
| ------- | :------: | :------: | :------: | :------: | :------: | :------: | :------: | :------: |
|**Stateful Packet Inspection**|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|IP Firewall only|
|**Public Network Protection**|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|
|**Private Network Protection**|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|||||
|**Ingress Rules**|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|IP Firewall only
|**Egress Rules**|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)||||
|**Single Tenant Appliance**||![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)||![Checkmark icon](../../icons/checkmark-icon.svg)||
|**VLAN Protection**||![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)||![Checkmark icon](../../icons/checkmark-icon.svg)||
|**Multi-VLAN Support**||![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|||||
|**NAT Support**||![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)||||
|**SSL/IPsec VPN Termination**||![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)||||
|**Open VPN Termination**|||![Checkmark icon](../../icons/checkmark-icon.svg)|||||Only with single port on TCP/UDP|
|**HA Option**|N/A|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)||![Checkmark icon](../../icons/checkmark-icon.svg)|Using Range and Load Balancers|
|**Manage from API & Portal**|Yes|Appliance GUI|Appliance GUI|Appliance GUI|Appliance GUI|Yes|Yes|Cloud console|
|**10 Gbps Support**|N/A|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|||||
|**NGFW Add-ons (IPS, AV, WF)**||![Checkmark icon](../../icons/checkmark-icon.svg)||![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|||TLS encryption, IP Firewall rules, and Proxy Protocol v1
|**Cost**|$0 per Month|Starting $299.00 per month + Cost of Bare Metal Server | Starting $219.00 per month + Cost of Bare Metal Server|Starting $4,999.00 per month|Starting $999.00 per month|Starting $99.00 per month|Starting $999.00 per month|Starting $275.00/Domain|
{: row-headers}
{: class="comparison-table"}
{: caption="A comparison of IBM's firewall offerings" caption-side="top"}
{: summary="This table all of IBM's firewall offerings, and provides links to their documentation."}
