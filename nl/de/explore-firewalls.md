---

copyright:
  years: 2017, 2018
lastupdated: "2019-03-05"

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
{:row-headers .row-headers}

# Informationen zu Firewalls
{: #exploring-firewalls}

IBM© Cloud bietet eine Reihe von Firewalls, aus denen Sie auswählen können. In der folgenden Tabelle werden die Firewall-Lösungen verglichen, damit Sie die für Sie am besten geeignete Lösung auswählen können. Wenn Sie weitere Informationen zu den einzelnen Angeboten lesen möchten, klicken Sie auf den entsprechenden Namen in der Tabelle.

Blättern Sie nach rechts, um den Rest der Tabelle anzuzeigen.
{: important}

|        | [SicherheitsgruppenGroups](/docs/infrastructure/security-groups?topic=security-groups-getting-started) (nur VSI) | [IBM Cloud Juniper vSRX-Standard](/docs/infrastructure/vsrx?topic=vsrx-getting-started) |[Virtual Router Appliance](/docs/infrastructure/virtual-router-appliance?topic=virtual-router-appliance-getting-started) | [FortiGate Security Appliance 10Gbps](/docs/infrastructure/fortigate-10g?topic=fortigate-10g-getting-started) | [FortiGate Security Appliance 1Gbps](/docs/infrastructure/fortigate-1g?topic=fortigate-1g-getting-started) | [Hardware-Firewall ](/docs/infrastructure/hardware-firewall-shared?topic=hardware-firewall-shared-getting-started) | [Hardware-Firewall (dediziert)](/docs/infrastructure/hardware-firewall-dedicated?topic=hardware-firewall-dedicated-getting-started) |
| ------- | :------: | :------: | :------: | :------: | :------: | :------: | :------: |
|**Statusabhängige Paketüberprüfung**|![Häkchensymbol](../../icons/checkmark-icon.svg)|![Häkchensymbol](../../icons/checkmark-icon.svg)|![Häkchensymbol](../../icons/checkmark-icon.svg)|![Häkchensymbol](../../icons/checkmark-icon.svg)|![Häkchensymbol](../../icons/checkmark-icon.svg)|![Häkchensymbol](../../icons/checkmark-icon.svg)|![Häkchensymbol](../../icons/checkmark-icon.svg)|
|**Schutz öffentlicher Netze**|![Häkchensymbol](../../icons/checkmark-icon.svg)|![Häkchensymbol](../../icons/checkmark-icon.svg)|![Häkchensymbol](../../icons/checkmark-icon.svg)|![Häkchensymbol](../../icons/checkmark-icon.svg)|![Häkchensymbol](../../icons/checkmark-icon.svg)|![Häkchensymbol](../../icons/checkmark-icon.svg)|![Häkchensymbol](../../icons/checkmark-icon.svg)|
|**Schutz privater Netze**|![Häkchensymbol](../../icons/checkmark-icon.svg)|![Häkchensymbol](../../icons/checkmark-icon.svg)|![Häkchensymbol](../../icons/checkmark-icon.svg)|![Häkchensymbol](../../icons/checkmark-icon.svg)||||
|**Ingress-Regeln**|![Häkchensymbol](../../icons/checkmark-icon.svg)|![Häkchensymbol](../../icons/checkmark-icon.svg)|![Häkchensymbol](../../icons/checkmark-icon.svg)|![Häkchensymbol](../../icons/checkmark-icon.svg)|![Häkchensymbol](../../icons/checkmark-icon.svg)|![Häkchensymbol](../../icons/checkmark-icon.svg)|![Häkchensymbol](../../icons/checkmark-icon.svg)|
|**Egress-Regeln**|![Häkchensymbol](../../icons/checkmark-icon.svg)|![Häkchensymbol](../../icons/checkmark-icon.svg)|![Häkchensymbol](../../icons/checkmark-icon.svg)|![Häkchensymbol](../../icons/checkmark-icon.svg)|![Häkchensymbol](../../icons/checkmark-icon.svg)|||
|**Appliance für einzelnen Tenant**||![Häkchensymbol](../../icons/checkmark-icon.svg)|![Häkchensymbol](../../icons/checkmark-icon.svg)|![Häkchensymbol](../../icons/checkmark-icon.svg)|![Häkchensymbol](../../icons/checkmark-icon.svg)||![Häkchensymbol](../../icons/checkmark-icon.svg)|
|**VLAN-Schutz**||![Häkchensymbol](../../icons/checkmark-icon.svg)|![Häkchensymbol](../../icons/checkmark-icon.svg)|![Häkchensymbol](../../icons/checkmark-icon.svg)|![Häkchensymbol](../../icons/checkmark-icon.svg)||![Häkchensymbol](../../icons/checkmark-icon.svg)|
|**Unterstützung für mehrere VLANs**||![Häkchensymbol](../../icons/checkmark-icon.svg)|![Häkchensymbol](../../icons/checkmark-icon.svg)|![Häkchensymbol](../../icons/checkmark-icon.svg)||||
|**NAT-Unterstützung**||![Häkchensymbol](../../icons/checkmark-icon.svg)|![Häkchensymbol](../../icons/checkmark-icon.svg)|![Häkchensymbol](../../icons/checkmark-icon.svg)|![Häkchensymbol](../../icons/checkmark-icon.svg)|||
|**Beendigung von VPN-Tunneln (SSL/IPsec)**||![Häkchensymbol](../../icons/checkmark-icon.svg)|![Häkchensymbol](../../icons/checkmark-icon.svg)|![Häkchensymbol](../../icons/checkmark-icon.svg)|![Häkchensymbol](../../icons/checkmark-icon.svg)|||
|**Beendigung von VPN-Tunneln (offen)**|||![Häkchensymbol](../../icons/checkmark-icon.svg)|||||
|**HA-Option**|Nicht zutreffend|![Häkchensymbol](../../icons/checkmark-icon.svg)|![Häkchensymbol](../../icons/checkmark-icon.svg)|![Häkchensymbol](../../icons/checkmark-icon.svg)|![Häkchensymbol](../../icons/checkmark-icon.svg)||![Häkchensymbol](../../icons/checkmark-icon.svg)|
|**Verwaltung über API & Portal**|Ja|Appliance-GUI|Appliance-GUI|Appliance-GUI|Appliance-GUI|Ja|Ja|
|**Unterstützung für 10Gbps**|Nicht zutreffend|![Häkchensymbol](../../icons/checkmark-icon.svg)|![Häkchensymbol](../../icons/checkmark-icon.svg)|![Häkchensymbol](../../icons/checkmark-icon.svg)||||
|**NGFW -Add-ons (IPS, AV, WF)**||Demnächst||![Häkchensymbol](../../icons/checkmark-icon.svg)|![Häkchensymbol](../../icons/checkmark-icon.svg)|||
|**Kosten**|$ 0/Monat|Ab $ 299,00/Monat + Bare-Metal-Server-Kosten | Ab $ 219,00/Monat + Bare-Metal-Server-Kosten|Ab $ 4.999,00/Monat|Ab $ 999,00/Monat|Ab $ 99,00/Monat|Ab $ 999,00/Monat|
{: row-headers}
{: class="comparison-table"}
{: caption="Vergleich der Firewall-Angebote von IBM" caption-side="top"}
{: summary="This table all of IBM's firewall offerings, and provides links to their documentation."}
