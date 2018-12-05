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


# Firewalls erkunden
IBM Cloud bietet eine Reihe von Firewalls, aus denen Sie auswählen können. In der folgenden Tabelle werden die Firewall-Lösungen verglichen, damit Sie die für Sie am besten geeignete Lösung auswählen können. Wenn Sie weitere Informationen zu den einzelnen Angeboten lesen möchten, klicken Sie auf den entsprechenden Namen in der Tabelle.

Blättern Sie nach rechts, um den Rest der Tabelle anzuzeigen.

|        | [SicherheitsgruppenGroups](../security-groups/sg_index.html) (nur VSI) | [IBM Cloud Juniper vSRX-Standard](../vsrx/getting-started.html#getting-started) |[Virtual Router Appliance](../virtual-router-appliance/getting-started.html#getting-started) | [FortiGate Security Appliance 10Gbps](../fortigate-10g/getting-started.html#getting-started) | [FortiGate Security Appliance 1Gbps](../fortigate-1g/getting-started.html#getting-started) | [Hardware-Firewall](../hardware-firewall-shared/getting-started.html#getting-started) (gemeinsam genutzt) | [Hardware-Firewall](../hardware-firewall-dedicated/getting-started.html#getting-started) (dediziert) |
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
