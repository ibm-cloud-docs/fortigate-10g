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


# Exploration des pare-feux
IBM Cloud offre plusieurs pare-feux. Le tableau ci-dessous compare les solutions de pare-feu pour vous aider à sélectionner celle qui est adaptée à vos besoins. Pour en savoir plus sur une offre, cliquez sur son nom dans le tableau.

Faites défiler vers la droite pour afficher le reste du tableau

|        | [Groupes de sécurité (VSI uniquement)](https://console.bluemix.net/docs/infrastructure/security-groups/sg_index.html) | [Pare-feu matériel](https://console.bluemix.net/docs/infrastructure/hardware-firewall-shared/getting-started.html#getting-started) (partagé) | [Pare-feu matériel](https://console.bluemix.net/docs/infrastructure/hardware-firewall-dedicated/getting-started.html#getting-started) (dédié) | [Dispositif de sécurité FortiGate 1 Gbit/s](https://console.bluemix.net/docs/infrastructure/fortigate-1g/getting-started.html#getting-started) | [Virtual Router Appliance](https://console.bluemix.net/docs/infrastructure/virtual-router-appliance/getting-started.html#getting-started) | [Dispositif de sécurité FortiGate 10 Gbit/s](https://console.bluemix.net/docs/infrastructure/fortigate-10g/getting-started.html#getting-started) |
| ------- | :------: | :------: | :------: | :------: | :------: | :------: |
|**Filtrage dynamique de paquets (SPI)**|Oui|Oui|Oui|Oui|Oui|Oui|
|**Protection de réseau public**|Oui|Oui|Oui|Oui|Oui|Oui|
|**Protection de réseau privé**|Oui|Non|Non|Non|Oui|Oui|
|**Règles d'entrée**|Oui|Oui|Oui|Oui|Oui|Oui|
|**Règles de sortie**|Oui|Non|Non|Oui|Oui|Oui|
|**Dispositif à service exclusif**|Non|Non|Oui|Oui|Oui|Oui|
|**Protection de réseau local virtuel (VLAN)**|Non|Non|Oui|Oui|Oui|Oui|
|**Prise en charge de plusieurs réseaux locaux virtuels**|Non|Non|Non|Non|Oui|Oui|
|**Prise en charge de la conversion d'adresses réseau (NAT)**|Non|Non|Non|Oui|Oui|Oui|
|**Terminaison de réseau privé virtuel (VPN) SSL/IPsec**|Non|Non|Non|Oui|Oui|Oui|
|**Terminaison de réseau privé virtuel (VPN) ouvert**|Non|Non|Non|Non|Oui|Non|
|**Option haute disponibilité (HA)**|N/A|Non|Oui|Oui|Oui|Oui|
|**Gestion à partir de l'API & du portail**|Oui|Oui|Oui|Interface graphique du dispositif|Interface graphique du dispositif|Interface graphique du dispositif|
|**Prise en charge de 10 Gbit/s**|N/A|Non|Non|Non|Oui|Oui|
|**Modules complémentaires NGFW (IPS, AV, WF)**|Non|Non|Non|Oui|Non|Oui|
|**Coût**|0 $ / mois|A partir de 99 $ / mois|A partir de 999 $ / mois|A partir de 999 $ / mois|A partir de 219 $ / mois + coût du serveur bare metal|A partir de 4 999 $ / mois|
