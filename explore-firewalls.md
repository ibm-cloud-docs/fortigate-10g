---

copyright:
  years: 2017, 2020
lastupdated: "2020-10-12"

keywords: explore, firewalls, fsa, fortigate, juniper, vsrx, vra, vfsa, virtual router appliance, security, vyatta, comparison, features

subcollection: fortigate-10g

---

{{site.data.keyword.attribute-definition-list}}

# Exploring firewalls
{: #exploring-firewalls}

{{site.data.keyword.cloud}} offers several firewalls to choose from. The following table compares the firewall solutions to help you choose the one that's right for you. To learn more about the individual offering, click its name in the table.
{: shortdesc}

|        | [Security Groups](/docs/security-groups?topic=security-groups-getting-started) (VSI only) | [IBM Cloud Juniper vSRX Standard](/docs/vsrx?topic=vsrx-getting-started) |[Virtual Router Appliance](/docs/virtual-router-appliance?topic=virtual-router-appliance-getting-started-vra) | [FortiGate Security Appliance 10 Gbps](/docs/fortigate-10g?topic=fortigate-10g-getting-started) | [Hardware Firewall](/docs/hardware-firewall-shared?topic=hardware-firewall-shared-getting-started) | [Cloud Internet Services](/docs/cis?topic=cis-getting-started)| [Virtual FortiGate Security Appliance](/docs/vfsa?topic=vfsa-getting-started)
| ------- | :------: | :------: | :------: | :------: | :------: | :------: | :------: |
|**Stateful Packet Inspection**|![Checkmark icon](../icons/checkmark-icon.svg)|![Checkmark icon](../icons/checkmark-icon.svg)|![Checkmark icon](../icons/checkmark-icon.svg)|![Checkmark icon](../icons/checkmark-icon.svg)|![Checkmark icon](../icons/checkmark-icon.svg)|IP firewall only|![Checkmark icon](../icons/checkmark-icon.svg)|
|**Public Network Protection**|![Checkmark icon](../icons/checkmark-icon.svg)|![Checkmark icon](../icons/checkmark-icon.svg)|![Checkmark icon](../icons/checkmark-icon.svg)|![Checkmark icon](../icons/checkmark-icon.svg)|![Checkmark icon](../icons/checkmark-icon.svg)|![Checkmark icon](../icons/checkmark-icon.svg)|![Checkmark icon](../icons/checkmark-icon.svg)|
|**Private Network Protection**|![Checkmark icon](../icons/checkmark-icon.svg)|![Checkmark icon](../icons/checkmark-icon.svg)|![Checkmark icon](../icons/checkmark-icon.svg)|![Checkmark icon](../icons/checkmark-icon.svg)| | |![Checkmark icon](../icons/checkmark-icon.svg)|
|**Ingress Rules**|![Checkmark icon](../icons/checkmark-icon.svg)|![Checkmark icon](../icons/checkmark-icon.svg)|![Checkmark icon](../icons/checkmark-icon.svg)|![Checkmark icon](../icons/checkmark-icon.svg)|![Checkmark icon](../icons/checkmark-icon.svg)|IP Firewall only|![Checkmark icon](../icons/checkmark-icon.svg)|
|**Egress Rules**|![Checkmark icon](../icons/checkmark-icon.svg)|![Checkmark icon](../icons/checkmark-icon.svg)|![Checkmark icon](../icons/checkmark-icon.svg)|![Checkmark icon](../icons/checkmark-icon.svg)| | |![Checkmark icon](../icons/checkmark-icon.svg)|
|**Single Tenant Appliance**| |![Checkmark icon](../icons/checkmark-icon.svg)|![Checkmark icon](../icons/checkmark-icon.svg)|![Checkmark icon](../icons/checkmark-icon.svg)|![Checkmark icon](../icons/checkmark-icon.svg)| |![Checkmark icon](../icons/checkmark-icon.svg)|
|**VLAN Protection**| |![Checkmark icon](../icons/checkmark-icon.svg)|![Checkmark icon](../icons/checkmark-icon.svg)|![Checkmark icon](../icons/checkmark-icon.svg)|![Checkmark icon](../icons/checkmark-icon.svg)| |![Checkmark icon](../icons/checkmark-icon.svg)|
|**Multi-VLAN Support**| |![Checkmark icon](../icons/checkmark-icon.svg)|![Checkmark icon](../icons/checkmark-icon.svg)|![Checkmark icon](../icons/checkmark-icon.svg)| | |![Checkmark icon](../icons/checkmark-icon.svg)|
|**NAT Support**| |![Checkmark icon](../icons/checkmark-icon.svg)|![Checkmark icon](../icons/checkmark-icon.svg)|![Checkmark icon](../icons/checkmark-icon.svg)| | |![Checkmark icon](../icons/checkmark-icon.svg)|
|**SSL/IPsec VPN Termination**| |![Checkmark icon](../icons/checkmark-icon.svg)|![Checkmark icon](../icons/checkmark-icon.svg)|![Checkmark icon](../icons/checkmark-icon.svg)|![Checkmark icon](../icons/checkmark-icon.svg)| |![Checkmark icon](../icons/checkmark-icon.svg)|
|**Open VPN Termination**| | |![Checkmark icon](../icons/checkmark-icon.svg)| | |Only with single port on TCP/UDP|![Checkmark icon](../icons/checkmark-icon.svg)|
|**HA Option**|N/A|![Checkmark icon](../icons/checkmark-icon.svg)|![Checkmark icon](../icons/checkmark-icon.svg)|![Checkmark icon](../icons/checkmark-icon.svg)|Using range and load balancers|![Checkmark icon](../icons/checkmark-icon.svg)|![Checkmark icon](../icons/checkmark-icon.svg)|
|**Manage from API & Portal**|Yes|Appliance GUI|Appliance GUI|Appliance GUI|Yes|Cloud console|Appliance GUI|
|**10 Gbps Support**|N/A|![Checkmark icon](../icons/checkmark-icon.svg)|![Checkmark icon](../icons/checkmark-icon.svg)| | |![Checkmark icon](../icons/checkmark-icon.svg)|![Checkmark icon](../icons/checkmark-icon.svg)|
|**NGFW Add-ons (IPS, AV, WF)**| |![Checkmark icon](../icons/checkmark-icon.svg)| |![Checkmark icon](../icons/checkmark-icon.svg)| |TLS encryption, IP Firewall rules, and Proxy Protocol v1|![Checkmark icon](../icons/checkmark-icon.svg)|
|**Remote Access VPN**| |![Checkmark icon](../icons/checkmark-icon.svg)|||||![Checkmark icon](../icons/checkmark-icon.svg)|
{: row-headers}
{: class="comparison-table"}
{: caption="Table 1: A comparison of IBM's firewall offerings" caption-side="bottom"}
{: summary="This table shows all of IBM's firewall offerings, and provides links to their documentation."}
