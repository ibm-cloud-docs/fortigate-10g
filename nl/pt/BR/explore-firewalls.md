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

# Explorando firewalls
{: #exploring-firewalls}

O IBM© Cloud oferece vários firewalls para escolher. A tabela a seguir compara as soluções de firewall para ajudá-lo a escolher aquele mais adequado para você. Para saber mais sobre a oferta individual, clique em seu nome na tabela.

Role para a direita para visualizar o restante da tabela!
{: important}

|        | [Security Groups](/docs/infrastructure/security-groups?topic=security-groups-getting-started) (VSI somente) | [IBM Cloud Juniper vSRX Standard](/docs/infrastructure/vsrx?topic=vsrx-getting-started) |[Virtual Router Appliance](/docs/infrastructure/virtual-router-appliance?topic=virtual-router-appliance-getting-started) | [FortiGate Security Appliance 10Gbps](/docs/infrastructure/fortigate-10g?topic=fortigate-10g-getting-started) | [FortiGate Security Appliance 1Gbps](/docs/infrastructure/fortigate-1g?topic=fortigate-1g-getting-started) | [Hardware Firewall ](/docs/infrastructure/hardware-firewall-shared?topic=hardware-firewall-shared-getting-started) | [Hardware Firewall (Dedicated)](/docs/infrastructure/hardware-firewall-dedicated?topic=hardware-firewall-dedicated-getting-started) |
| ------- | :------: | :------: | :------: | :------: | :------: | :------: | :------: |
|**Stateful Packet Inspection**|![Ícone de visto](../../icons/checkmark-icon.svg)|![Ícone de visto](../../icons/checkmark-icon.svg)|![Ícone de visto](../../icons/checkmark-icon.svg)|![Ícone de visto](../../icons/checkmark-icon.svg)|![Ícone de visto](../../icons/checkmark-icon.svg)|![Ícone de visto](../../icons/checkmark-icon.svg)|![Ícone de visto](../../icons/checkmark-icon.svg)|
|**Public Network Protection**|![Ícone de visto](../../icons/checkmark-icon.svg)|![Ícone de visto](../../icons/checkmark-icon.svg)|![Ícone de visto](../../icons/checkmark-icon.svg)|![Ícone de visto](../../icons/checkmark-icon.svg)|![Ícone de visto](../../icons/checkmark-icon.svg)|![Ícone de visto](../../icons/checkmark-icon.svg)|![Ícone de visto](../../icons/checkmark-icon.svg)|
|**Private Network Protection**|![Ícone de visto](../../icons/checkmark-icon.svg)|![Ícone de visto](../../icons/checkmark-icon.svg)|![Ícone de visto](../../icons/checkmark-icon.svg)|![Ícone de visto](../../icons/checkmark-icon.svg)||||
|**Regras de Ingresso**|![Ícone de visto](../../icons/checkmark-icon.svg)|![Ícone de visto](../../icons/checkmark-icon.svg)|![Ícone de visto](../../icons/checkmark-icon.svg)|![Ícone de visto](../../icons/checkmark-icon.svg)|![Ícone de visto](../../icons/checkmark-icon.svg)|![Ícone de visto](../../icons/checkmark-icon.svg)|![Ícone de visto](../../icons/checkmark-icon.svg)|
|**Regras de Egresso**|![Ícone de visto](../../icons/checkmark-icon.svg)|![Ícone de visto](../../icons/checkmark-icon.svg)|![Ícone de visto](../../icons/checkmark-icon.svg)|![Ícone de visto](../../icons/checkmark-icon.svg)|![Ícone de visto](../../icons/checkmark-icon.svg)|||
|**Dispositivo de Locatário Único**||![Ícone de visto](../../icons/checkmark-icon.svg)|![Ícone de visto](../../icons/checkmark-icon.svg)|![Ícone de visto](../../icons/checkmark-icon.svg)|![Ícone de visto](../../icons/checkmark-icon.svg)||![Ícone de visto](../../icons/checkmark-icon.svg)|
|**Proteção de VLAN**||![Ícone de visto](../../icons/checkmark-icon.svg)|![Ícone de visto](../../icons/checkmark-icon.svg)|![Ícone de visto](../../icons/checkmark-icon.svg)|![Ícone de visto](../../icons/checkmark-icon.svg)||![Ícone de visto](../../icons/checkmark-icon.svg)|
|**Suporte a múltiplas VLANs**||![Ícone de visto](../../icons/checkmark-icon.svg)|![Ícone de visto](../../icons/checkmark-icon.svg)|![Ícone de visto](../../icons/checkmark-icon.svg)||||
|**Suporte NAT**||![Ícone de visto](../../icons/checkmark-icon.svg)|![Ícone de visto](../../icons/checkmark-icon.svg)|![Ícone de visto](../../icons/checkmark-icon.svg)|![Ícone de visto](../../icons/checkmark-icon.svg)|||
|**Finalização de VPN SSL/IPsec**||![Ícone de visto](../../icons/checkmark-icon.svg)|![Ícone de visto](../../icons/checkmark-icon.svg)|![Ícone de visto](../../icons/checkmark-icon.svg)|![Ícone de visto](../../icons/checkmark-icon.svg)|||
|**Finalização de VPN aberta**|||![Ícone de visto](../../icons/checkmark-icon.svg)|||||
|**Opção de HA**|N/A|![Ícone de visto](../../icons/checkmark-icon.svg)|![Ícone de visto](../../icons/checkmark-icon.svg)|![Ícone de visto](../../icons/checkmark-icon.svg)|![Ícone de visto](../../icons/checkmark-icon.svg)||![Ícone de visto](../../icons/checkmark-icon.svg)|
|**Gerenciar por meio da API & e do Portal**|Sim|GUI do dispositivo|GUI do dispositivo|GUI do dispositivo|GUI do dispositivo|Sim|Sim|
|**Suporte a 10Gbps**|N/A|![Ícone de visto](../../icons/checkmark-icon.svg)|![Ícone de visto](../../icons/checkmark-icon.svg)|![Ícone de visto](../../icons/checkmark-icon.svg)||||
|**Complementos NGFW (IPS, AV, WF)**||Em Breve||![Ícone de visto](../../icons/checkmark-icon.svg)|![Ícone de visto](../../icons/checkmark-icon.svg)|||
|**Total**|$0/Mês|A partir de US$299,00/mês + Custo de Bare Metal Server | A partir de $219,00/mês + Custo do Bare Metal Server|A partir de $4.999,00/mês|A partir de $999,00/mês|A partir de $99,00/mês|A partir de $999,00/mês|
{: row-headers}
{: class="comparison-table"}
{: caption="Uma comparação das ofertas de firewall da IBM" caption-side="top"}
{: summary="This table all of IBM's firewall offerings, and provides links to their documentation."}
