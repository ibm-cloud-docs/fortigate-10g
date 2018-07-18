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


# Explorar firewalls
O IBM Cloud oferece vários firewalls para escolher. A tabela a seguir compara as soluções de firewall para ajudá-lo a escolher aquele mais adequado para você. Para saber mais sobre a oferta individual, clique em seu nome na tabela.

Role para a direita para visualizar o restante da tabela!

|        | [Grupos de segurança (somente VSI)](https://console.bluemix.net/docs/infrastructure/security-groups/sg_index.html) | [Hardware Firewall](https://console.bluemix.net/docs/infrastructure/hardware-firewall-shared/getting-started.html#getting-started) (Compartilhado) | [Hardware Firewall](https://console.bluemix.net/docs/infrastructure/hardware-firewall-dedicated/getting-started.html#getting-started) (Dedicated) | [Fortigate Security Appliance 1Gbps](https://console.bluemix.net/docs/infrastructure/fortigate-1g/getting-started.html#getting-started) | [Virtual Router Appliance](https://console.bluemix.net/docs/infrastructure/virtual-router-appliance/getting-started.html#getting-started) | [Fortigate Security Appliance 10Gbps](https://console.bluemix.net/docs/infrastructure/fortigate-10g/getting-started.html#getting-started) |
| ------- | :------: | :------: | :------: | :------: | :------: | :------: |
|**Stateful Packet Inspection**|Sim|Sim|Sim|Sim|Sim|Sim|
|**Public Network Protection**|Sim|Sim|Sim|Sim|Sim|Sim|
|**Private Network Protection**|Sim|Não|Não|Não|Sim|Sim|
|**Regras de Ingresso**|Sim|Sim|Sim|Sim|Sim|Sim|
|**Regras de Egresso**|Sim|Não|Não|Sim|Sim|Sim|
|**Dispositivo de Locatário Único**|Não|Não|Sim|Sim|Sim|Sim|
|**Proteção de VLAN**|Não|Não|Sim|Sim|Sim|Sim|
|**Suporte a múltiplas VLANs**|Não|Não|Não|Não|Sim|Sim|
|**Suporte NAT**|Não|Não|Não|Sim|Sim|Sim|
|**Finalização de VPN SSL/IPsec**|Não|Não|Não|Sim|Sim|Sim|
|**Finalização de VPN aberta**|Não|Não|Não|Não|Sim|Não|
|**Opção de HA**|N/A|Não|Sim|Sim|Sim|Sim|
|**Gerenciar por meio da API & e do Portal**|Sim|Sim|Sim|GUI do dispositivo|GUI do dispositivo|GUI do dispositivo|
|**Suporte a 10Gbps**|N/A|Não|Não|Não|Sim|Sim|
|**Complementos NGFW (IPS, AV, WF)**|Não|Não|Não|Sim|Não|Sim|
|**Total**|$0/Mês|A partir de $99,00/mês|A partir de $999,00/mês|A partir de $999,00/mês|A partir de $219,00/mês + Custo do Bare Metal Server|A partir de $4.999,00/mês|
