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


# 探索防火墙
IBM Cloud 提供了数个可选择的防火墙。下表对防火墙解决方案进行了比较，以帮助您选择适合的解决方案。要了解各个产品的更多信息，请单击表中的名称。

滚动到右侧以查看表的其余部分！

|        | [Security Groups（仅限 VSI）](https://console.bluemix.net/docs/infrastructure/security-groups/sg_index.html) | [硬件防火墙](https://console.bluemix.net/docs/infrastructure/hardware-firewall-shared/getting-started.html#getting-started)（共享）| [硬件防火墙](https://console.bluemix.net/docs/infrastructure/hardware-firewall-dedicated/getting-started.html#getting-started)（专用）| [Fortigate Security Appliance 1Gbps](https://console.bluemix.net/docs/infrastructure/fortigate-1g/getting-started.html#getting-started) | [Virtual Router Appliance](https://console.bluemix.net/docs/infrastructure/virtual-router-appliance/getting-started.html#getting-started) | [Fortigate Security Appliance 10Gbps](https://console.bluemix.net/docs/infrastructure/fortigate-10g/getting-started.html#getting-started) |
| ------- | :------: | :------: | :------: | :------: | :------: | :------: |
|**状态包检查**|是|是|是|是|是|是|
|**公用网络检查**|是|是|是|是|是|是|
|**专用网络检查**|是|否|否|否|是|是|
|**入口规则**|是|是|是|是|是|是|
|**出口规则**|是|否|否|是|是|是|
|**单租户设备**|否|否|是|是|是|是|
|**VLAN 保护**|否|否|是|是|是|是|
|**多 VLAN 支持**|否|否|否|否|是|是|
|**NAT 支持**|否|否|否|是|是|是|
|**SSL/IPsec VPN 终止**|否|否|否|是|是|是|
|**打开 VPN 终止**|否|否|否|否|是|否|
|**HA 选项**|不适用|否|是|是|是|是|
|**从 API 和门户网站管理**|是|是|是|设备 GUI|设备 GUI|设备 GUI|
|**10Gbps 支持**|不适用|否|否|否|是|是|
|**NGFW 附件（IPS、AV 和 WF）**|否|否|否|是|否|是|
|**开销**|$0/月|起始 $99.00/月|起始 $999.00/月|起始 $999.00/月|起始 $219.00/月 + 裸机服务器开销|起始 $4,999.00/月|
