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


# 探索防火牆
IBM Cloud 提供許多防火牆供選擇。以下表格比較各個防火牆解決方案，協助您正確選擇適用的防火牆解決方案。若要進一步瞭解個別產品與服務，請按一下表格中的名稱。

向右捲動可檢視表格的其餘部分！

|        | [安全群組（僅限 VSI）](https://console.bluemix.net/docs/infrastructure/security-groups/sg_index.html) | [硬體防火牆](https://console.bluemix.net/docs/infrastructure/hardware-firewall-shared/getting-started.html#getting-started)（共用）| [硬體防火牆](https://console.bluemix.net/docs/infrastructure/hardware-firewall-dedicated/getting-started.html#getting-started)（專用）| [Fortigate Security Appliance 1Gbps](https://console.bluemix.net/docs/infrastructure/fortigate-1g/getting-started.html#getting-started) | [Virtual Router Appliance](https://console.bluemix.net/docs/infrastructure/virtual-router-appliance/getting-started.html#getting-started) | [Fortigate Security Appliance 10Gbps](https://console.bluemix.net/docs/infrastructure/fortigate-10g/getting-started.html#getting-started) |
| ------- | :------: | :------: | :------: | :------: | :------: | :------: |
|**狀態封包檢驗**|是|是|是|是|是|是|
|**公用網路保護**|是|是|是|是|是|是|
|**專用網路保護**|是|否|否|否|是|是|
|**輸入規則**|是|是|是|是|是|是|
|**輸出規則**|是|否|否|是|是|是|
|**單一承租戶應用裝置**|否|否|是|是|是|是|
|**VLAN 保護**|否|否|是|是|是|是|
|**多重 VLAN 支援**|否|否|否|否|是|是|
|**NAT 支援**|否|否|否|是|是|是|
|**SSL/IPsec VPN 終止**|否|否|否|是|是|是|
|**Open VPN 終止**|否|否|否|否|是|否|
|**HA 選項**|N/A|否|是|是|是|是|
|**從 API 及入口網站進行管理**|是|是|是|應用裝置 GUI|應用裝置 GUI|應用裝置 GUI|
|**10Gbps 支援**|N/A|否|否|否|是|是|
|**NGFW 附加元件（IPS、AV、WF）**|否|否|否|是|否|是|
|**費用**|$0/月|$99.00/月起|$999.00/月起|$999.00/月起|$219.00/月起 + 裸機伺服器費用|$4,999.00/月起|
