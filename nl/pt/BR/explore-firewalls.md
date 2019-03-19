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


# Explorando firewalls
{: #exploring-firewalls}

O IBM© Cloud oferece vários firewalls para escolher. A tabela a seguir compara as soluções de firewall para ajudá-lo a escolher aquele mais adequado para você. Para saber mais sobre a oferta individual, clique em seu nome na tabela.

Role para a direita para visualizar o restante da tabela!

|        | [Security Groups](/docs/infrastructure/security-groups?topic=security-groups-getting-started-with-security-groups) (VSI somente) | [IBM Cloud Juniper vSRX Standard](/docs/infrastructure/vsrx?topic=vsrx-getting-started-with-ibm-cloud-juniper-vsrx-gateway) |[Virtual Router Appliance](/docs/infrastructure/virtual-router-appliance?topic=virtual-router-appliance-getting-started-with-ibm-virtual-router-appliance) | [FortiGate Security Appliance 10Gbps](/docs/infrastructure/fortigate-10g?topic=fortigate-10g-getting-started-with-fortigate-security-appliance-10gbps) | [FortiGate Security Appliance 1Gbps](/docs/infrastructure/fortigate-1g?topic=fortigate-1g-getting-started-with-fortigate-security-appliance-1gbps) | [Hardware Firewall (Shared)](/docs/infrastructure/hardware-firewall-shared?topic=hardware-firewall-shared-getting-started-with-hardware-firewall-shared) | [Hardware Firewall (Dedicated)](/docs/infrastructure/hardware-firewall-dedicated?topic=hardware-firewall-dedicated-getting-started-with-hardware-firewall-dedicated) |
| ------- | :------: | :------: | :------: | :------: | :------: | :------: | :------: |
|**Stateful Packet Inspection**|Sim|Sim|Sim|Sim|Sim|Sim|Sim|
|**Public Network Protection**|Sim|Sim|Sim|Sim|Sim|Sim|Sim|
|**Private Network Protection**|Sim|Sim|Sim|Sim|Não|Não|Não|
|**Regras de Ingresso**|Sim|Sim|Sim|Sim|Sim|Sim|Sim|
|**Regras de Egresso**|Sim|Sim|Sim|Sim|Sim|Não|Não|
|**Dispositivo de Locatário Único**|Não|Sim|Sim|Sim|Sim|Não|Sim|
|**Proteção de VLAN**|Não|Sim|Sim|Sim|Sim|Não|Sim|
|**Suporte a múltiplas VLANs**|Não|Sim|Sim|Sim|Não|Não|Não|
|**Suporte NAT**|Não|Sim|Sim|Sim|Sim|Não|Não|
|**Finalização de VPN SSL/IPsec**|Não|Sim|Sim|Sim|Sim|Não|Não|
|**Finalização de VPN aberta**|Não|Sim|Sim|Não|Não|Não|Não|
|**Opção de HA**|N/A|Sim|Sim|Sim|Sim|Não|Sim|
|**Gerenciar por meio da API & e do Portal**|Sim|GUI do dispositivo|GUI do dispositivo|GUI do dispositivo|GUI do dispositivo|Sim|Sim|
|**Suporte a 10Gbps**|N/A|Sim|Sim|Sim|Não|Não|Não|
|**Complementos NGFW (IPS, AV, WF)**|Não|Não|Não|Sim|Sim|Não|Não|
|**Total**|$0/Mês|A partir de US$299,00/mês + Custo de Bare Metal Server | A partir de $219,00/mês + Custo do Bare Metal Server|A partir de $4.999,00/mês|A partir de $999,00/mês|A partir de $99,00/mês|A partir de $999,00/mês|
