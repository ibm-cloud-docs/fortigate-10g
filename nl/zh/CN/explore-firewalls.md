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

# 探索防火墙
{: #exploring-firewalls}

IBM© Cloud 提供了数个防火墙可供选择。下表对防火墙解决方案进行了比较，以帮助您选择适合的解决方案。要了解各个产品的更多信息，请单击表中的名称。

滚动到右侧以查看表的其余部分！
{: important}

|        | [安全组](/docs/infrastructure/security-groups?topic=security-groups-getting-started)（仅限 VSI）| [IBM Cloud Juniper vSRX Standard](/docs/infrastructure/vsrx?topic=vsrx-getting-started) |[Virtual Router Appliance](/docs/infrastructure/virtual-router-appliance?topic=virtual-router-appliance-getting-started) | [FortiGate Security Appliance 10Gbps](/docs/infrastructure/fortigate-10g?topic=fortigate-10g-getting-started) | [FortiGate Security Appliance 1Gbps](/docs/infrastructure/fortigate-1g?topic=fortigate-1g-getting-started) | [Hardware Firewall ](/docs/infrastructure/hardware-firewall-shared?topic=hardware-firewall-shared-getting-started) | [Hardware Firewall (Dedicated)](/docs/infrastructure/hardware-firewall-dedicated?topic=hardware-firewall-dedicated-getting-started) |
| ------- | :------: | :------: | :------: | :------: | :------: | :------: | :------: |
|**有状态包检查**|![复选标记图标](../../icons/checkmark-icon.svg)|![复选标记图标](../../icons/checkmark-icon.svg)|![复选标记图标](../../icons/checkmark-icon.svg)|![复选标记图标](../../icons/checkmark-icon.svg)|![复选标记图标](../../icons/checkmark-icon.svg)|![复选标记图标](../../icons/checkmark-icon.svg)|![复选标记图标](../../icons/checkmark-icon.svg)|
|**公用网络保护**|![复选标记图标](../../icons/checkmark-icon.svg)|![复选标记图标](../../icons/checkmark-icon.svg)|![复选标记图标](../../icons/checkmark-icon.svg)|![复选标记图标](../../icons/checkmark-icon.svg)|![复选标记图标](../../icons/checkmark-icon.svg)|![复选标记图标](../../icons/checkmark-icon.svg)|![复选标记图标](../../icons/checkmark-icon.svg)|
|**专用网络保护**|![复选标记图标](../../icons/checkmark-icon.svg)|![复选标记图标](../../icons/checkmark-icon.svg)|![复选标记图标](../../icons/checkmark-icon.svg)|![复选标记图标](../../icons/checkmark-icon.svg)||||
|**入口规则**|![复选标记图标](../../icons/checkmark-icon.svg)|![复选标记图标](../../icons/checkmark-icon.svg)|![复选标记图标](../../icons/checkmark-icon.svg)|![复选标记图标](../../icons/checkmark-icon.svg)|![复选标记图标](../../icons/checkmark-icon.svg)|![复选标记图标](../../icons/checkmark-icon.svg)|![复选标记图标](../../icons/checkmark-icon.svg)|
|**出口规则**|![复选标记图标](../../icons/checkmark-icon.svg)|![复选标记图标](../../icons/checkmark-icon.svg)|![复选标记图标](../../icons/checkmark-icon.svg)|![复选标记图标](../../icons/checkmark-icon.svg)|![复选标记图标](../../icons/checkmark-icon.svg)|||
|**单租户设备**||![复选标记图标](../../icons/checkmark-icon.svg)|![复选标记图标](../../icons/checkmark-icon.svg)|![复选标记图标](../../icons/checkmark-icon.svg)|![复选标记图标](../../icons/checkmark-icon.svg)||![复选标记图标](../../icons/checkmark-icon.svg)|
|**VLAN 保护**||![复选标记图标](../../icons/checkmark-icon.svg)|![复选标记图标](../../icons/checkmark-icon.svg)|![复选标记图标](../../icons/checkmark-icon.svg)|![复选标记图标](../../icons/checkmark-icon.svg)||![复选标记图标](../../icons/checkmark-icon.svg)|
|**多 VLAN 支持**||![复选标记图标](../../icons/checkmark-icon.svg)|![复选标记图标](../../icons/checkmark-icon.svg)|![复选标记图标](../../icons/checkmark-icon.svg)||||
|**NAT 支持**||![复选标记图标](../../icons/checkmark-icon.svg)|![复选标记图标](../../icons/checkmark-icon.svg)|![复选标记图标](../../icons/checkmark-icon.svg)|![复选标记图标](../../icons/checkmark-icon.svg)|||
|**SSL/IPsec VPN 终止**||![复选标记图标](../../icons/checkmark-icon.svg)|![复选标记图标](../../icons/checkmark-icon.svg)|![复选标记图标](../../icons/checkmark-icon.svg)|![复选标记图标](../../icons/checkmark-icon.svg)|||
|**打开 VPN 终止**|||![复选标记图标](../../icons/checkmark-icon.svg)|||||
|**HA 选项**|不适用|![复选标记图标](../../icons/checkmark-icon.svg)|![复选标记图标](../../icons/checkmark-icon.svg)|![复选标记图标](../../icons/checkmark-icon.svg)|![复选标记图标](../../icons/checkmark-icon.svg)||![复选标记图标](../../icons/checkmark-icon.svg)|
|**从 API 和门户网站管理**|是|设备 GUI|设备 GUI|设备 GUI|设备 GUI|是|是|
|**10Gbps 支持**|不适用|![复选标记图标](../../icons/checkmark-icon.svg)|![复选标记图标](../../icons/checkmark-icon.svg)|![复选标记图标](../../icons/checkmark-icon.svg)||||
|**NGFW 附件（IPS、AV 和 WF）**||即将推出||![复选标记图标](../../icons/checkmark-icon.svg)|![复选标记图标](../../icons/checkmark-icon.svg)|||
|**开销**|$0/月|起始 $299.00/月 + 裸机服务器开销|起始 $219.00/月 + 裸机服务器开销|起始 $4,999.00/月|起始 $999.00/月|起始 $99.00/月|起始 $999.00/月|
{: row-headers}
{: class="comparison-table"}
{: caption="IBM 防火墙产品的比较" caption-side="top"}
{: summary="This table all of IBM's firewall offerings, and provides links to their documentation."}
