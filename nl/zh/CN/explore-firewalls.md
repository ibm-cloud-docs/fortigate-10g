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


# 探索防火墙
IBM Cloud 提供了数个防火墙可供选择。下表对防火墙解决方案进行了比较，以帮助您选择适合的解决方案。要了解各个产品的更多信息，请单击表中的名称。

滚动到右侧以查看表的其余部分！

|        | [安全组](../security-groups/sg_index.html)（仅限 VSI）| [IBM Cloud Juniper vSRX Standard](../vsrx/getting-started.html#getting-started) |[Virtual Router Appliance](../virtual-router-appliance/getting-started.html#getting-started) | [FortiGate Security Appliance 10Gbps](../fortigate-10g/getting-started.html#getting-started) | [FortiGate Security Appliance 1Gbps](../fortigate-1g/getting-started.html#getting-started) |[硬件防火墙](../hardware-firewall-shared/getting-started.html#getting-started)（共享）|[硬件防火墙](../hardware-firewall-dedicated/getting-started.html#getting-started)（专用）|
| ------- | :------: | :------: | :------: | :------: | :------: | :------: | :------: |
|**有状态包检查**|是|是|是|是|是|是|是|
|**公用网络保护**|是|是|是|是|是|是|是|
|**专用网络保护**|是|是|是|是|否|否|否|
|**入口规则**|是|是|是|是|是|是|是|
|**出口规则**|是|是|是|是|是|否|否|
|**单租户设备**|否|是|是|是|是|否|是|
|**VLAN 保护**|否|是|是|是|是|否|是|
|**多 VLAN 支持**|否|是|是|是|否|否|否|
|**NAT 支持**|否|是|是|是|是|否|否|
|**SSL/IPsec VPN 终止**|否|是|是|是|是|否|否|
|**打开 VPN 终止**|否|是|是|否|否|否|否|
|**HA 选项**|不适用|是|是|是|是|否|是|
|**从 API 和门户网站管理**|是|设备 GUI|设备 GUI|设备 GUI|设备 GUI|是|是|
|**10Gbps 支持**|不适用|是|是|是|否|否|否|
|**NGFW 附件（IPS、AV 和 WF）**|否|否|否|是|是|否|否|
|**开销**|$0/月|起始 $299.00/月 + 裸机服务器开销|起始 $219.00/月 + 裸机服务器开销|起始 $4,999.00/月|起始 $999.00/月|起始 $99.00/月|起始 $999.00/月|
