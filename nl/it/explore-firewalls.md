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

# Esplorazione dei firewall
{: #exploring-firewalls}

IBM© Cloud offre diversi firewall tra cui scegliere. La seguente tabella confronta le soluzioni firewall per aiutarti a scegliere quella giusta per te. Per ulteriori informazioni sulle singole offerte, fai clic sul nome dell'offerta nella tabella.

Scorri a destra per visualizzare il resto della tabella!
{: important}

|        | [Gruppi di sicurezza](/docs/infrastructure/security-groups?topic=security-groups-getting-started) (solo VSI) | [IBM Cloud Juniper vSRX Standard](/docs/infrastructure/vsrx?topic=vsrx-getting-started) |[VRA (Virtual Router Appliance)](/docs/infrastructure/virtual-router-appliance?topic=virtual-router-appliance-getting-started) | [FortiGate Security Appliance 10Gbps](/docs/infrastructure/fortigate-10g?topic=fortigate-10g-getting-started) | [FortiGate Security Appliance 1Gbps](/docs/infrastructure/fortigate-1g?topic=fortigate-1g-getting-started) | [Hardware Firewall ](/docs/infrastructure/hardware-firewall-shared?topic=hardware-firewall-shared-getting-started) | [Hardware Firewall (Dedicated)](/docs/infrastructure/hardware-firewall-dedicated?topic=hardware-firewall-dedicated-getting-started) |
| ------- | :------: | :------: | :------: | :------: | :------: | :------: | :------: |
|**Filtraggio stateful dei pacchetti**|![Icona di segno di spunta](../../icons/checkmark-icon.svg)|![Icona di segno di spunta](../../icons/checkmark-icon.svg)|![Icona di segno di spunta](../../icons/checkmark-icon.svg)|![Icona di segno di spunta](../../icons/checkmark-icon.svg)|![Icona di segno di spunta](../../icons/checkmark-icon.svg)|![Icona di segno di spunta](../../icons/checkmark-icon.svg)|![Icona di segno di spunta](../../icons/checkmark-icon.svg)|
|**Protezione della rete pubblica**|![Icona di segno di spunta](../../icons/checkmark-icon.svg)|![Icona di segno di spunta](../../icons/checkmark-icon.svg)|![Icona di segno di spunta](../../icons/checkmark-icon.svg)|![Icona di segno di spunta](../../icons/checkmark-icon.svg)|![Icona di segno di spunta](../../icons/checkmark-icon.svg)|![Icona di segno di spunta](../../icons/checkmark-icon.svg)|![Icona di segno di spunta](../../icons/checkmark-icon.svg)|
|**Protezione della rete privata**|![Icona di segno di spunta](../../icons/checkmark-icon.svg)|![Icona di segno di spunta](../../icons/checkmark-icon.svg)|![Icona di segno di spunta](../../icons/checkmark-icon.svg)|![Icona di segno di spunta](../../icons/checkmark-icon.svg)||||
|**Regole Ingress**|![Icona di segno di spunta](../../icons/checkmark-icon.svg)|![Icona di segno di spunta](../../icons/checkmark-icon.svg)|![Icona di segno di spunta](../../icons/checkmark-icon.svg)|![Icona di segno di spunta](../../icons/checkmark-icon.svg)|![Icona di segno di spunta](../../icons/checkmark-icon.svg)|![Icona di segno di spunta](../../icons/checkmark-icon.svg)|![Icona di segno di spunta](../../icons/checkmark-icon.svg)|
|**Regole Egress**|![Icona di segno di spunta](../../icons/checkmark-icon.svg)|![Icona di segno di spunta](../../icons/checkmark-icon.svg)|![Icona di segno di spunta](../../icons/checkmark-icon.svg)|![Icona di segno di spunta](../../icons/checkmark-icon.svg)|![Icona di segno di spunta](../../icons/checkmark-icon.svg)|||
|**Applicazione a singolo tenant**||![Icona di segno di spunta](../../icons/checkmark-icon.svg)|![Icona di segno di spunta](../../icons/checkmark-icon.svg)|![Icona di segno di spunta](../../icons/checkmark-icon.svg)|![Icona di segno di spunta](../../icons/checkmark-icon.svg)||![Icona di segno di spunta](../../icons/checkmark-icon.svg)|
|**Protezione della VLAN**||![Icona di segno di spunta](../../icons/checkmark-icon.svg)|![Icona di segno di spunta](../../icons/checkmark-icon.svg)|![Icona di segno di spunta](../../icons/checkmark-icon.svg)|![Icona di segno di spunta](../../icons/checkmark-icon.svg)||![Icona di segno di spunta](../../icons/checkmark-icon.svg)|
|**Supporto per più VLAN**||![Icona di segno di spunta](../../icons/checkmark-icon.svg)|![Icona di segno di spunta](../../icons/checkmark-icon.svg)|![Icona di segno di spunta](../../icons/checkmark-icon.svg)||||
|**Supporto NAT**||![Icona di segno di spunta](../../icons/checkmark-icon.svg)|![Icona di segno di spunta](../../icons/checkmark-icon.svg)|![Icona di segno di spunta](../../icons/checkmark-icon.svg)|![Icona di segno di spunta](../../icons/checkmark-icon.svg)|||
|**Terminazione VPN SSL/IPsec**||![Icona di segno di spunta](../../icons/checkmark-icon.svg)|![Icona di segno di spunta](../../icons/checkmark-icon.svg)|![Icona di segno di spunta](../../icons/checkmark-icon.svg)|![Icona di segno di spunta](../../icons/checkmark-icon.svg)|||
|**Terminazione VPN Open**|||![Icona di segno di spunta](../../icons/checkmark-icon.svg)|||||
|**Opzione HA**|N/D|![Icona di segno di spunta](../../icons/checkmark-icon.svg)|![Icona di segno di spunta](../../icons/checkmark-icon.svg)|![Icona di segno di spunta](../../icons/checkmark-icon.svg)|![Icona di segno di spunta](../../icons/checkmark-icon.svg)||![Icona di segno di spunta](../../icons/checkmark-icon.svg)|
|**Gestione dall'API e dal portale**|Sì|GUI applicazione|GUI applicazione|GUI applicazione|GUI applicazione|Sì|Sì|
|**Supporto 10Gbps**|N/D|![Icona di segno di spunta](../../icons/checkmark-icon.svg)|![Icona di segno di spunta](../../icons/checkmark-icon.svg)|![Icona di segno di spunta](../../icons/checkmark-icon.svg)||||
|**Componenti aggiuntivi NGFW (IPS, AV, WF)**||Disponibile a breve||![Icona di segno di spunta](../../icons/checkmark-icon.svg)|![Icona di segno di spunta](../../icons/checkmark-icon.svg)|||
|**Costo**|$0/Mese|A partire da $299.00/mese + costo del Bare Metal Server | A partire da $219.00/mese + costo del Bare Metal Server|A partire da $4.999,00/mese|A partire da $999.00/mese|A partire da $99.00/mese|A partire da $999.00/mese|
{: row-headers}
{: class="comparison-table"}
{: caption="Un confronto delle offerte di firewall di IBM" caption-side="top"}
{: summary="This table all of IBM's firewall offerings, and provides links to their documentation."}
