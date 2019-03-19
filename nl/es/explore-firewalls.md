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


# Explorar cortafuegos
{: #exploring-firewalls}

IBM© Cloud ofrece una amplia selección de cortafuegos. La siguiente tabla compara las soluciones de cortafuegos para ayudarle a elegir la más adecuada para usted. Para obtener más información sobre una oferta, pulse sobre su nombre en la tabla.

Desplácese a la derecha para visualizar el resto de la tabla.

|        | [Grupos de seguridad](/docs/infrastructure/security-groups?topic=security-groups-getting-started-with-security-groups) (solo VSI) | [IBM Cloud Juniper vSRX Standard](/docs/infrastructure/vsrx?topic=vsrx-getting-started-with-ibm-cloud-juniper-vsrx-gateway) |[Virtual Router Appliance](/docs/infrastructure/virtual-router-appliance?topic=virtual-router-appliance-getting-started-with-ibm-virtual-router-appliance) | [FortiGate Security Appliance 10Gbps](/docs/infrastructure/fortigate-10g?topic=fortigate-10g-getting-started-with-fortigate-security-appliance-10gbps) | [FortiGate Security Appliance 1Gbps](/docs/infrastructure/fortigate-1g?topic=fortigate-1g-getting-started-with-fortigate-security-appliance-1gbps) | [Cortafuegos de hardware (compartido)](/docs/infrastructure/hardware-firewall-shared?topic=hardware-firewall-shared-getting-started-with-hardware-firewall-shared) | [Cortafuegos de hardware (dedicado)](/docs/infrastructure/hardware-firewall-dedicated?topic=hardware-firewall-dedicated-getting-started-with-hardware-firewall-dedicated) |
| ------- | :------: | :------: | :------: | :------: | :------: | :------: | :------: |
|**Inspección de paquetes con estado**|Sí|Sí|Sí|Sí|Sí|Sí|Sí|
|**Protección de red pública**|Sí|Sí|Sí|Sí|Sí|Sí|Sí|
|**Protección de red privada**|Sí|Sí|Sí|Sí|No|No|No|
|**Reglas de ingreso**|Sí|Sí|Sí|Sí|Sí|Sí|Sí|
|**Reglas de salida**|Sí|Sí|Sí|Sí|Sí|No|No|
|**Dispositivo de arrendatario único**|No|Sí|Sí|Sí|Sí|No|Sí|
|**Protección de VLAN**|No|Sí|Sí|Sí|Sí|No|Sí|
|**Soporte para varias VLAN**|No|Sí|Sí|Sí|No|No|No|
|**Soporte para NAT**|No|Sí|Sí|Sí|Sí|No|No|
|**Terminación de VPN SSL/IPsec**|No|Sí|Sí|Sí|Sí|No|No|
|**Terminación de VPN abierta**|No|Sí|Sí|No|No|No|No|
|**Opción de alta disponibilidad**|N/D|Sí|Sí|Sí|Sí|No|Sí|
|**Gestión desde API y Portal**|Sí|GUI del dispositivo|GUI del dispositivo|GUI del dispositivo|GUI del dispositivo|Sí|Sí|
|**Soporte para 10Gbps**|N/D|Sí|Sí|Sí|No|No|No|
|**Complementos NGFW (IPS, AV, WF)**|No|No|No|Sí|Sí|No|No|
|**Coste**|0$/mes|Desde 299,00$/mes + Coste de servidor nativo | Desde 219,00$/mes + Coste de servidor nativo|Desde 4.999,00$/mes|Desde 999,00$/mes|Desde 99,00$/mes|Desde 999,00$/mes|
