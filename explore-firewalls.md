---

copyright:
  years: 2017, 2018
lastupdated: "2018-11-10"

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}
{:codeblock: .codeblock}
{:pre: .pre}
{:screen: .screen}
{:tip: .tip}
{:download: .download}


# Exploring Firewalls
IBM© Cloud offers several firewalls to choose from. The table below compares the firewall solutions to help you choose the one that's right for you. To learn more about the individual offering, click its name in the table.

Scroll to the right to view the rest of the table!

|        | [Security Groups](/docs/infrastructure/security-groups?topic=security-groups-getting-started-with-security-groups) (VSI only) | [IBM Cloud Juniper vSRX Standard](/docs/infrastructure/vsrx?topic=vsrx-getting-started-with-ibm-cloud-juniper-vsrx-gateway) |[Virtual Router Appliance](/docs/infrastructure/virtual-router-appliance?topic=virtual-router-appliance-getting-started-with-ibm-virtual-router-appliance) | [FortiGate Security Appliance 10Gbps](/docs/infrastructure/fortigate-10g?topic=fortigate-10g-getting-started-with-fortigate-security-appliance-10gbps) | [FortiGate Security Appliance 1Gbps](/docs/infrastructure/fortigate-1g?topic=fortigate-1g-getting-started-with-fortigate-security-appliance-1gbps) | [Hardware Firewall (Shared)](/docs/infrastructure/hardware-firewall-shared?topic=hardware-firewall-shared-getting-started-with-hardware-firewall-shared) | [Hardware Firewall (Dedicated)](/docs/infrastructure/hardware-firewall-dedicated?topic=hardware-firewall-dedicated-getting-started-with-hardware-firewall-dedicated) |
| ------- | :------: | :------: | :------: | :------: | :------: | :------: | :------: |
|**Stateful Packet Inspection**|Yes|Yes|Yes|Yes|Yes|Yes|Yes|
|**Public Network Protection**|Yes|Yes|Yes|Yes|Yes|Yes|Yes|
|**Private Network Protection**|Yes|Yes|Yes|Yes|No|No|No|
|**Ingress Rules**|Yes|Yes|Yes|Yes|Yes|Yes|Yes|
|**Egress Rules**|Yes|Yes|Yes|Yes|Yes|No|No|
|**Single Tenant Appliance**|No|Yes|Yes|Yes|Yes|No|Yes|
|**VLAN Protection**|No|Yes|Yes|Yes|Yes|No|Yes|
|**Multi-VLAN Support**|No|Yes|Yes|Yes|No|No|No|
|**NAT Support**|No|Yes|Yes|Yes|Yes|No|No|
|**SSL/IPsec VPN Termination**|No|Yes|Yes|Yes|Yes|No|No|
|**Open VPN Termination**|No|Yes|Yes|No|No|No|No|
|**HA Option**|N/A|Yes|Yes|Yes|Yes|No|Yes|
|**Manage from API & Portal**|Yes|Appliance GUI|Appliance GUI|Appliance GUI|Appliance GUI|Yes|Yes|
|**10Gbps Support**|N/A|Yes|Yes|Yes|No|No|No|
|**NGFW Add-ons (IPS, AV, WF)**|No|No|No|Yes|Yes|No|No|
|**Cost**|$0/Month|Starting $299.00/month + Cost of Bare Metal Server | Starting $219.00/month + Cost of Bare Metal Server|Starting $4,999.00/month|Starting $999.00/month|Starting $99.00/month|Starting $999.00/month|
