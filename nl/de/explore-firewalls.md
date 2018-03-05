---

copyright:
  years: 2017, 2018
lastupdated: "2018-01-11"

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

|        | [Sicherheitsgruppen (nur VSI)](https://console.bluemix.net/docs/infrastructure/security-groups/sg_index.html) | [Hardware-Firewall](https://console.bluemix.net/docs/infrastructure/hardware-firewall-shared/getting-started.html#getting-started) (gemeinsam genutzt) | [Hardware-Firewall](https://console.bluemix.net/docs/infrastructure/hardware-firewall-dedicated/getting-started.html#getting-started) (dediziert) | [Fortigate Security Appliance 1Gbps](https://console.bluemix.net/docs/infrastructure/fortigate-1g/getting-started.html#getting-started) | [virtuelle Router-Appliance](https://console.bluemix.net/docs/infrastructure/virtual-router-appliance/getting-started.html#getting-started) | [Fortigate Security Appliance 10Gbps](https://console.bluemix.net/docs/infrastructure/fortigate-10g/getting-started.html#getting-started) |
| ------- | :------: | :------: | :------: | :------: | :------: | :------: |
|**Statusabhängige Paketüberprüfung**|Ja|Ja|Ja|Ja|Ja|Ja|
|**Schutz öffentlicher Netze**|Ja|Ja|Ja|Ja|Ja|Ja|
|**Schutz privater Netze**|Ja|Nein|Nein|Nein|Ja|Ja|
|**Ingress-Regeln**|Ja|Ja|Ja|Ja|Ja|Ja|
|**Egress-Regeln**|Ja|Nein|Nein|Ja|Ja|Ja|
|**Appliance für einzelnen Tenant**|Nein|Nein|Ja|Ja|Ja|Ja|
|**VLAN-Schutz**|Nein|Nein|Ja|Ja|Ja|Ja|
|**Unterstützung für mehrere VLANs**|Nein|Nein|Nein|Nein|Ja|Ja|
|**NAT-Unterstützung**|Nein|Nein|Nein|Ja|Ja|Ja|
|**Beendigung von VPN-Tunneln (SSL/IPsec)**|Nein|Nein|Nein|Ja|Ja|Ja|
|**Beendigung von VPN-Tunneln (offen)**|Nein|Nein|Nein|Nein|Ja|Nein|
|**HA-Option**|Nicht zutreffend|Nein|Ja|Ja|Ja|Ja|
|**Verwaltung über API & Portal**|Ja|Ja|Ja|Appliance-GUI|Appliance-GUI|Appliance-GUI|
|**Unterstützung für 10Gbps**|Nicht zutreffend|Nein|Nein|Nein|Ja|Ja|
|**NGFW -Add-ons (IPS, AV, WF)**|Nein|Nein|Nein|Ja|Nein|Ja|
|**Kosten**|$ 0/Monat|Ab $ 99,00/Monat|Ab $ 999,00/Monat|Ab $ 999,00/Monat|Ab $ 219,00/Monat + Bare-Metal-Server-Kosten|Ab $ 4.999,00/Monat|
