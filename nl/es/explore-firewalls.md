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

# Explorar cortafuegos
{: #exploring-firewalls}

IBM© Cloud ofrece una amplia selección de cortafuegos. La siguiente tabla compara las soluciones de cortafuegos para ayudarle a elegir la más adecuada para usted. Para obtener más información sobre una oferta, pulse sobre su nombre en la tabla.

Desplácese a la derecha para visualizar el resto de la tabla.
{: important}

|        | [Grupos de seguridad](/docs/infrastructure/security-groups?topic=security-groups-getting-started) (solo VSI) | [IBM Cloud Juniper vSRX Standard](/docs/infrastructure/vsrx?topic=vsrx-getting-started) |[Virtual Router Appliance](/docs/infrastructure/virtual-router-appliance?topic=virtual-router-appliance-getting-started) | [FortiGate Security Appliance 10Gbps](/docs/infrastructure/fortigate-10g?topic=fortigate-10g-getting-started) | [FortiGate Security Appliance 1Gbps](/docs/infrastructure/fortigate-1g?topic=fortigate-1g-getting-started) | [Cortafuegos de hardware](/docs/infrastructure/hardware-firewall-shared?topic=hardware-firewall-shared-getting-started) | [Cortafuegos de hardware (dedicado)](/docs/infrastructure/hardware-firewall-dedicated?topic=hardware-firewall-dedicated-getting-started) |
| ------- | :------: | :------: | :------: | :------: | :------: | :------: | :------: |
|**Inspección de paquetes con estado**|![Icono de marca de verificación](../../icons/checkmark-icon.svg)|![Icono de marca de verificación](../../icons/checkmark-icon.svg)|![Icono de marca de verificación](../../icons/checkmark-icon.svg)|![Icono de marca de verificación](../../icons/checkmark-icon.svg)|![Icono de marca de verificación](../../icons/checkmark-icon.svg)|![Icono de marca de verificación](../../icons/checkmark-icon.svg)|![Icono de marca de verificación](../../icons/checkmark-icon.svg)|
|**Protección de red pública**|![Icono de marca de verificación](../../icons/checkmark-icon.svg)|![Icono de marca de verificación](../../icons/checkmark-icon.svg)|![Icono de marca de verificación](../../icons/checkmark-icon.svg)|![Icono de marca de verificación](../../icons/checkmark-icon.svg)|![Icono de marca de verificación](../../icons/checkmark-icon.svg)|![Icono de marca de verificación](../../icons/checkmark-icon.svg)|![Icono de marca de verificación](../../icons/checkmark-icon.svg)|
|**Protección de red privada**|![Icono de marca de verificación](../../icons/checkmark-icon.svg)|![Icono de marca de verificación](../../icons/checkmark-icon.svg)|![Icono de marca de verificación](../../icons/checkmark-icon.svg)|![Icono de marca de verificación](../../icons/checkmark-icon.svg)||||
|**Reglas de ingreso**|![Icono de marca de verificación](../../icons/checkmark-icon.svg)|![Icono de marca de verificación](../../icons/checkmark-icon.svg)|![Icono de marca de verificación](../../icons/checkmark-icon.svg)|![Icono de marca de verificación](../../icons/checkmark-icon.svg)|![Icono de marca de verificación](../../icons/checkmark-icon.svg)|![Icono de marca de verificación](../../icons/checkmark-icon.svg)|![Icono de marca de verificación](../../icons/checkmark-icon.svg)|
|**Reglas de salida**|![Icono de marca de verificación](../../icons/checkmark-icon.svg)|![Icono de marca de verificación](../../icons/checkmark-icon.svg)|![Icono de marca de verificación](../../icons/checkmark-icon.svg)|![Icono de marca de verificación](../../icons/checkmark-icon.svg)|![Icono de marca de verificación](../../icons/checkmark-icon.svg)|||
|**Dispositivo de arrendatario único**||![Icono de marca de verificación](../../icons/checkmark-icon.svg)|![Icono de marca de verificación](../../icons/checkmark-icon.svg)|![Icono de marca de verificación](../../icons/checkmark-icon.svg)|![Icono de marca de verificación](../../icons/checkmark-icon.svg)||![Icono de marca de verificación](../../icons/checkmark-icon.svg)|
|**Protección de VLAN**||![Icono de marca de verificación](../../icons/checkmark-icon.svg)|![Icono de marca de verificación](../../icons/checkmark-icon.svg)|![Icono de marca de verificación](../../icons/checkmark-icon.svg)|![Icono de marca de verificación](../../icons/checkmark-icon.svg)||![Icono de marca de verificación](../../icons/checkmark-icon.svg)|
|**Soporte para varias VLAN**||![Icono de marca de verificación](../../icons/checkmark-icon.svg)|![Icono de marca de verificación](../../icons/checkmark-icon.svg)|![Icono de marca de verificación](../../icons/checkmark-icon.svg)||||
|**Soporte para NAT**||![Icono de marca de verificación](../../icons/checkmark-icon.svg)|![Icono de marca de verificación](../../icons/checkmark-icon.svg)|![Icono de marca de verificación](../../icons/checkmark-icon.svg)|![Icono de marca de verificación](../../icons/checkmark-icon.svg)|||
|**Terminación de VPN SSL/IPsec**||![Icono de marca de verificación](../../icons/checkmark-icon.svg)|![Icono de marca de verificación](../../icons/checkmark-icon.svg)|![Icono de marca de verificación](../../icons/checkmark-icon.svg)|![Icono de marca de verificación](../../icons/checkmark-icon.svg)|||
|**Terminación de VPN abierta**|||![Icono de marca de verificación](../../icons/checkmark-icon.svg)|||||
|**Opción de alta disponibilidad**|N/D|![Icono de marca de verificación](../../icons/checkmark-icon.svg)|![Icono de marca de verificación](../../icons/checkmark-icon.svg)|![Icono de marca de verificación](../../icons/checkmark-icon.svg)|![Icono de marca de verificación](../../icons/checkmark-icon.svg)||![Icono de marca de verificación](../../icons/checkmark-icon.svg)|
|**Gestión desde API y Portal**|Sí|GUI del dispositivo|GUI del dispositivo|GUI del dispositivo|GUI del dispositivo|Sí|Sí|
|**Soporte para 10Gbps**|N/D|![Icono de marca de verificación](../../icons/checkmark-icon.svg)|![Icono de marca de verificación](../../icons/checkmark-icon.svg)|![Icono de marca de verificación](../../icons/checkmark-icon.svg)||||
|**Complementos NGFW (IPS, AV, WF)**||Próximamente||![Icono de marca de verificación](../../icons/checkmark-icon.svg)|![Icono de marca de verificación](../../icons/checkmark-icon.svg)|||
|**Coste**|0$/mes|Desde 299,00$/mes + Coste de servidor nativo | Desde 219,00$/mes + Coste de servidor nativo|Desde 4.999,00$/mes|Desde 999,00$/mes|Desde 99,00$/mes|Desde 999,00$/mes|
{: row-headers}
{: class="comparison-table"}
{: caption="Comparación de las ofertas de cortafuegos de IBM" caption-side="top"}
{: summary="This table all of IBM's firewall offerings, and provides links to their documentation."}
