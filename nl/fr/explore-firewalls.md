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

# Exploration des pare-feux
{: #exploring-firewalls}

IBM© Cloud propose plusieurs pare-feux. Le tableau ci-dessous compare les solutions de pare-feu pour vous aider à sélectionner celle qui est adaptée à vos besoins. Pour en savoir plus sur une offre, cliquez sur son nom dans le tableau.

Faites défiler vers la droite pour afficher le reste du tableau
{: important}

|        | [Groupes de sécurité](/docs/infrastructure/security-groups?topic=security-groups-getting-started) (VSI uniquement) | [IBM Cloud Juniper vSRX Standard](/docs/infrastructure/vsrx?topic=vsrx-getting-started) |[Dispositif Virtual Router Appliance](/docs/infrastructure/virtual-router-appliance?topic=virtual-router-appliance-getting-started) | [Dispositif de sécurité FortiGate 10 Gbit/s](/docs/infrastructure/fortigate-10g?topic=fortigate-10g-getting-started) | [Dispositif de sécurité FortiGate 1 Gbit/s](/docs/infrastructure/fortigate-1g?topic=fortigate-1g-getting-started) | [Pare-feu matériel ](/docs/infrastructure/hardware-firewall-shared?topic=hardware-firewall-shared-getting-started) | [Pare-feu matériel (dédié)](/docs/infrastructure/hardware-firewall-dedicated?topic=hardware-firewall-dedicated-getting-started) |
| ------- | :------: | :------: | :------: | :------: | :------: | :------: | :------: |
|**Filtrage dynamique de paquets (SPI)**|![Icône de coche](../../icons/checkmark-icon.svg)|![Icône de coche](../../icons/checkmark-icon.svg)|![Icône de coche](../../icons/checkmark-icon.svg)|![Icône de coche](../../icons/checkmark-icon.svg)|![Icône de coche](../../icons/checkmark-icon.svg)|![Icône de coche](../../icons/checkmark-icon.svg)|![Icône de coche](../../icons/checkmark-icon.svg)|
|**Protection de réseau public**|![Icône de coche](../../icons/checkmark-icon.svg)|![Icône de coche](../../icons/checkmark-icon.svg)|![Icône de coche](../../icons/checkmark-icon.svg)|![Icône de coche](../../icons/checkmark-icon.svg)|![Icône de coche](../../icons/checkmark-icon.svg)|![Icône de coche](../../icons/checkmark-icon.svg)|![Icône de coche](../../icons/checkmark-icon.svg)|
|**Protection de réseau privé**|![Icône de coche](../../icons/checkmark-icon.svg)|![Icône de coche](../../icons/checkmark-icon.svg)|![Icône de coche](../../icons/checkmark-icon.svg)|![Icône de coche](../../icons/checkmark-icon.svg)||||
|**Règles d'entrée**|![Icône de coche](../../icons/checkmark-icon.svg)|![Icône de coche](../../icons/checkmark-icon.svg)|![Icône de coche](../../icons/checkmark-icon.svg)|![Icône de coche](../../icons/checkmark-icon.svg)|![Icône de coche](../../icons/checkmark-icon.svg)|![Icône de coche](../../icons/checkmark-icon.svg)|![Icône de coche](../../icons/checkmark-icon.svg)|
|**Règles de sortie**|![Icône de coche](../../icons/checkmark-icon.svg)|![Icône de coche](../../icons/checkmark-icon.svg)|![Icône de coche](../../icons/checkmark-icon.svg)|![Icône de coche](../../icons/checkmark-icon.svg)|![Icône de coche](../../icons/checkmark-icon.svg)|||
|**Dispositif à service exclusif**||![Icône de coche](../../icons/checkmark-icon.svg)|![Icône de coche](../../icons/checkmark-icon.svg)|![Icône de coche](../../icons/checkmark-icon.svg)|![Icône de coche](../../icons/checkmark-icon.svg)||![Icône de coche](../../icons/checkmark-icon.svg)|
|**Protection de réseau local virtuel (VLAN)**||![Icône de coche](../../icons/checkmark-icon.svg)|![Icône de coche](../../icons/checkmark-icon.svg)|![Icône de coche](../../icons/checkmark-icon.svg)|![Icône de coche](../../icons/checkmark-icon.svg)||![Icône de coche](../../icons/checkmark-icon.svg)|
|**Prise en charge de plusieurs réseaux locaux virtuels**||![Icône de coche](../../icons/checkmark-icon.svg)|![Icône de coche](../../icons/checkmark-icon.svg)|![Icône de coche](../../icons/checkmark-icon.svg)||||
|**Prise en charge de la conversion d'adresses réseau (NAT)**||![Icône de coche](../../icons/checkmark-icon.svg)|![Icône de coche](../../icons/checkmark-icon.svg)|![Icône de coche](../../icons/checkmark-icon.svg)|![Icône de coche](../../icons/checkmark-icon.svg)|||
|**Terminaison de réseau privé virtuel (VPN) SSL/IPsec**||![Icône de coche](../../icons/checkmark-icon.svg)|![Icône de coche](../../icons/checkmark-icon.svg)|![Icône de coche](../../icons/checkmark-icon.svg)|![Icône de coche](../../icons/checkmark-icon.svg)|||
|**Terminaison de réseau privé virtuel (VPN) ouvert**|||![Icône de coche](../../icons/checkmark-icon.svg)|||||
|**Option haute disponibilité (HA)**|N/A|![Icône de coche](../../icons/checkmark-icon.svg)|![Icône de coche](../../icons/checkmark-icon.svg)|![Icône de coche](../../icons/checkmark-icon.svg)|![Icône de coche](../../icons/checkmark-icon.svg)||![Icône de coche](../../icons/checkmark-icon.svg)|
|**Gestion à partir de l'API & du portail**|Oui|Interface graphique du dispositif|Interface graphique du dispositif|Interface graphique du dispositif|Interface graphique du dispositif|Oui|Oui|
|**Prise en charge de 10 Gbit/s**|N/A|![Icône de coche](../../icons/checkmark-icon.svg)|![Icône de coche](../../icons/checkmark-icon.svg)|![Icône de coche](../../icons/checkmark-icon.svg)||||
|**Modules complémentaires NGFW (IPS, AV, WF)**||Prochainement||![Icône de coche](../../icons/checkmark-icon.svg)|![Icône de coche](../../icons/checkmark-icon.svg)|||
|**Coût**|0 $ / mois|A partir de 299 $ / mois + coût du serveur bare metal | A partir de 219 $ / mois + coût du serveur bare metal|A partir de 4 999 $ / mois|A partir de 999 $ / mois|A partir de 99 $ / mois|A partir de 999 $ / mois|
{: row-headers}
{: class="comparison-table"}
{: caption="Comparaison des offres de pare-feu d'IBM" caption-side="top"}
{: summary="This table all of IBM's firewall offerings, and provides links to their documentation."}
