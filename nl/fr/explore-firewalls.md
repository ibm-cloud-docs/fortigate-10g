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


# Exploration des pare-feux
{: #exploring-firewalls}

IBM© Cloud propose plusieurs pare-feux. Le tableau ci-dessous compare les solutions de pare-feu pour vous aider à sélectionner celle qui est adaptée à vos besoins. Pour en savoir plus sur une offre, cliquez sur son nom dans le tableau.

Faites défiler vers la droite pour afficher le reste du tableau

|        | [Groupes de sécurité](/docs/infrastructure/security-groups?topic=security-groups-getting-started-with-security-groups) (VSI uniquement) | [IBM Cloud Juniper vSRX Standard](/docs/infrastructure/vsrx?topic=vsrx-getting-started-with-ibm-cloud-juniper-vsrx-gateway) |[Dispositif Virtual Router Appliance](/docs/infrastructure/virtual-router-appliance?topic=virtual-router-appliance-getting-started-with-ibm-virtual-router-appliance) | [Dispositif de sécurité FortiGate 10 Gbit/s](/docs/infrastructure/fortigate-10g?topic=fortigate-10g-getting-started-with-fortigate-security-appliance-10gbps) | [Dispositif de sécurité FortiGate 10 Gbit/s](/docs/infrastructure/fortigate-1g?topic=fortigate-1g-getting-started-with-fortigate-security-appliance-1gbps) | [Pare-feu matériel (partagé)](/docs/infrastructure/hardware-firewall-shared?topic=hardware-firewall-shared-getting-started-with-hardware-firewall-shared) | [Pare-feu matériel (dédié)](/docs/infrastructure/hardware-firewall-dedicated?topic=hardware-firewall-dedicated-getting-started-with-hardware-firewall-dedicated) |
| ------- | :------: | :------: | :------: | :------: | :------: | :------: | :------: |
|**Filtrage dynamique de paquets (SPI)**|Oui|Oui|Oui|Oui|Oui|Oui|Oui|
|**Protection de réseau public**|Oui|Oui|Oui|Oui|Oui|Oui|Oui|
|**Protection de réseau privé**|Oui|Oui|Oui|Oui|Non|Non|Non|
|**Règles d'entrée**|Oui|Oui|Oui|Oui|Oui|Oui|Oui|
|**Règles de sortie**|Oui|Oui|Oui|Oui|Oui|Non|Non|
|**Dispositif à service exclusif**|Non|Oui|Oui|Oui|Oui|Non|Oui|
|**Protection de réseau local virtuel (VLAN)**|Non|Oui|Oui|Oui|Oui|Non|Oui|
|**Prise en charge de plusieurs réseaux locaux virtuels**|Non|Oui|Oui|Oui|Non|Non|Non|
|**Prise en charge de la conversion d'adresses réseau (NAT)**|Non|Oui|Oui|Oui|Oui|Non|Non|
|**Terminaison de réseau privé virtuel (VPN) SSL/IPsec**|Non|Oui|Oui|Oui|Oui|Non|Non|
|**Terminaison de réseau privé virtuel (VPN) ouvert**|Non|Oui|Oui|Non|Non|Non|Non|
|**Option haute disponibilité (HA)**|N/A|Oui|Oui|Oui|Oui|Non|Oui|
|**Gestion à partir de l'API & du portail**|Oui|Interface graphique du dispositif|Interface graphique du dispositif|Interface graphique du dispositif|Interface graphique du dispositif|Oui|Oui|
|**Prise en charge de 10 Gbit/s**|N/A|Oui|Oui|Oui|Non|Non|Non|
|**Modules complémentaires NGFW (IPS, AV, WF)**|Non|Non|Non|Oui|Oui|Non|Non|
|**Coût**|0 $ / mois|A partir de 299 $ / mois + coût du serveur bare metal | A partir de 219 $ / mois + coût du serveur bare metal|A partir de 4 999 $ / mois|A partir de 999 $ / mois|A partir de 99 $ / mois|A partir de 999 $ / mois|
