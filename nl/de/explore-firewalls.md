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


# Informationen zu Firewalls
{: #exploring-firewalls}

IBM© Cloud bietet eine Reihe von Firewalls, aus denen Sie auswählen können. In der folgenden Tabelle werden die Firewall-Lösungen verglichen, damit Sie die für Sie am besten geeignete Lösung auswählen können. Wenn Sie weitere Informationen zu den einzelnen Angeboten lesen möchten, klicken Sie auf den entsprechenden Namen in der Tabelle.

Blättern Sie nach rechts, um den Rest der Tabelle anzuzeigen.

|        | [SicherheitsgruppenGroups](/docs/infrastructure/security-groups?topic=security-groups-getting-started-with-security-groups) (nur VSI) | [IBM Cloud Juniper vSRX-Standard](/docs/infrastructure/vsrx?topic=vsrx-getting-started-with-ibm-cloud-juniper-vsrx-gateway) |[Virtual Router Appliance](/docs/infrastructure/virtual-router-appliance?topic=virtual-router-appliance-getting-started-with-ibm-virtual-router-appliance) | [FortiGate Security Appliance 10Gbps](/docs/infrastructure/fortigate-10g?topic=fortigate-10g-getting-started-with-fortigate-security-appliance-10gbps) | [FortiGate Security Appliance 1Gbps](/docs/infrastructure/fortigate-1g?topic=fortigate-1g-getting-started-with-fortigate-security-appliance-1gbps) | [Hardware-Firewall (gemeinsam genutzt)](/docs/infrastructure/hardware-firewall-shared?topic=hardware-firewall-shared-getting-started-with-hardware-firewall-shared) | [Hardware-Firewall (dediziert)](/docs/infrastructure/hardware-firewall-dedicated?topic=hardware-firewall-dedicated-getting-started-with-hardware-firewall-dedicated) |
| ------- | :------: | :------: | :------: | :------: | :------: | :------: | :------: |
|**Statusabhängige Paketüberprüfung**|Ja|Ja|Ja|Ja|Ja|Ja|Ja|
|**Schutz öffentlicher Netze**|Ja|Ja|Ja|Ja|Ja|Ja|Ja|
|**Schutz privater Netze**|Ja|Ja|Ja|Ja|Nein|Nein|Nein|
|**Ingress-Regeln**|Ja|Ja|Ja|Ja|Ja|Ja|Ja|
|**Egress-Regeln**|Ja|Ja|Ja|Ja|Ja|Nein|Nein|
|**Appliance für einzelnen Tenant**|Nein|Ja|Ja|Ja|Ja|Nein|Ja|
|**VLAN-Schutz**|Nein|Ja|Ja|Ja|Ja|Nein|Ja|
|**Unterstützung für mehrere VLANs**|Nein|Ja|Ja|Ja|Nein|Nein|Nein|
|**NAT-Unterstützung**|Nein|Ja|Ja|Ja|Ja|Nein|Nein|
|**Beendigung von VPN-Tunneln (SSL/IPsec)**|Nein|Ja|Ja|Ja|Ja|Nein|Nein|
|**Beendigung von VPN-Tunneln (offen)**|Nein|Ja|Ja|Nein|Nein|Nein|Nein|
|**HA-Option**|Nicht zutreffend|Ja|Ja|Ja|Ja|Nein|Ja|
|**Verwaltung über API & Portal**|Ja|Appliance-GUI|Appliance-GUI|Appliance-GUI|Appliance-GUI|Ja|Ja|
|**Unterstützung für 10Gbps**|Nicht zutreffend|Ja|Ja|Ja|Nein|Nein|Nein|
|**NGFW -Add-ons (IPS, AV, WF)**|Nein|Nein|Nein|Ja|Ja|Nein|Nein|
|**Kosten**|$ 0/Monat|Ab $ 299,00/Monat + Bare-Metal-Server-Kosten | Ab $ 219,00/Monat + Bare-Metal-Server-Kosten|Ab $ 4.999,00/Monat|Ab $ 999,00/Monat|Ab $ 99,00/Monat|Ab $ 999,00/Monat|
