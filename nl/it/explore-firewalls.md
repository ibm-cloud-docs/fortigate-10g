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


# Esplorazione dei firewall
{: #exploring-firewalls}

IBM© Cloud offre diversi firewall tra cui scegliere. La seguente tabella confronta le soluzioni firewall per aiutarti a scegliere quella giusta per te. Per ulteriori informazioni sulle singole offerte, fai clic sul nome dell'offerta nella tabella.

Scorri a destra per visualizzare il resto della tabella!

|        | [Gruppi di sicurezza](/docs/infrastructure/security-groups?topic=security-groups-getting-started-with-security-groups) (solo VSI) | [IBM Cloud Juniper vSRX Standard](/docs/infrastructure/vsrx?topic=vsrx-getting-started-with-ibm-cloud-juniper-vsrx-gateway) |[VRA (Virtual Router Appliance)](/docs/infrastructure/virtual-router-appliance?topic=virtual-router-appliance-getting-started-with-ibm-virtual-router-appliance) | [FortiGate Security Appliance 10Gbps](/docs/infrastructure/fortigate-10g?topic=fortigate-10g-getting-started-with-fortigate-security-appliance-10gbps) | [FortiGate Security Appliance 1Gbps](/docs/infrastructure/fortigate-1g?topic=fortigate-1g-getting-started-with-fortigate-security-appliance-1gbps) | [Hardware Firewall (Shared)](/docs/infrastructure/hardware-firewall-shared?topic=hardware-firewall-shared-getting-started-with-hardware-firewall-shared) | [Hardware Firewall (Dedicated)](/docs/infrastructure/hardware-firewall-dedicated?topic=hardware-firewall-dedicated-getting-started-with-hardware-firewall-dedicated) |
| ------- | :------: | :------: | :------: | :------: | :------: | :------: | :------: |
|**Filtraggio stateful dei pacchetti**|Sì|Sì|Sì|Sì|Sì|Sì|Sì|
|**Protezione della rete pubblica**|Sì|Sì|Sì|Sì|Sì|Sì|Sì|
|**Protezione della rete privata**|Sì|Sì|Sì|Sì|No|No|No|
|**Regole Ingress**|Sì|Sì|Sì|Sì|Sì|Sì|Sì|
|**Regole Egress**|Sì|Sì|Sì|Sì|Sì|No|No|
|**Applicazione a singolo tenant**|No|Sì|Sì|Sì|Sì|No|Sì|
|**Protezione della VLAN**|No|Sì|Sì|Sì|Sì|No|Sì|
|**Supporto per più VLAN**|No|Sì|Sì|Sì|No|No|No|
|**Supporto NAT**|No|Sì|Sì|Sì|Sì|No|No|
|**Terminazione VPN SSL/IPsec**|No|Sì|Sì|Sì|Sì|No|No|
|**Terminazione VPN Open**|No|Sì|Sì|No|No|No|No|
|**Opzione HA**|N/D|Sì|Sì|Sì|Sì|No|Sì|
|**Gestione dall'API e dal portale**|Sì|GUI applicazione|GUI applicazione|GUI applicazione|GUI applicazione|Sì|Sì|
|**Supporto 10Gbps**|N/D|Sì|Sì|Sì|No|No|No|
|**Componenti aggiuntivi NGFW (IPS, AV, WF)**|No|No|No|Sì|Sì|No|No|
|**Costo**|$0/Mese|A partire da $299.00/mese + costo del Bare Metal Server | A partire da $219.00/mese + costo del Bare Metal Server|A partire da $4.999,00/mese|A partire da $999.00/mese|A partire da $99.00/mese|A partire da $999.00/mese|
