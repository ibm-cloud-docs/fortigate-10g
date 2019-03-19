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


# 探索防火牆
{: #exploring-firewalls}

IBM© Cloud 提供許多防火牆供選擇。以下表格比較各個防火牆解決方案，協助您正確選擇適用的防火牆解決方案。若要進一步瞭解個別產品與服務，請按一下表格中的名稱。

向右捲動可檢視表格的其餘部分！

|        | [安全群組](/docs/infrastructure/security-groups?topic=security-groups-getting-started-with-security-groups)（僅限 VSI）| [IBM Cloud Juniper vSRX Standard](/docs/infrastructure/vsrx?topic=vsrx-getting-started-with-ibm-cloud-juniper-vsrx-gateway) |[Virtual Router Appliance](/docs/infrastructure/virtual-router-appliance?topic=virtual-router-appliance-getting-started-with-ibm-virtual-router-appliance) | [FortiGate Security Appliance 10Gbps](/docs/infrastructure/fortigate-10g?topic=fortigate-10g-getting-started-with-fortigate-security-appliance-10gbps) | [FortiGate Security Appliance 1Gbps](/docs/infrastructure/fortigate-1g?topic=fortigate-1g-getting-started-with-fortigate-security-appliance-1gbps) | [Hardware Firewall（共用）](/docs/infrastructure/hardware-firewall-shared?topic=hardware-firewall-shared-getting-started-with-hardware-firewall-shared) | [Hardware Firewall（專用）](/docs/infrastructure/hardware-firewall-dedicated?topic=hardware-firewall-dedicated-getting-started-with-hardware-firewall-dedicated) |
| ------- | :------: | :------: | :------: | :------: | :------: | :------: | :------: |
|**狀態封包檢驗**|是|是|是|是|是|是|是|
|**公用網路保護**|是|是|是|是|是|是|是|
|**專用網路保護**|是|是|是|是|否|否|否|
|**輸入規則**|是|是|是|是|是|是|是|
|**輸出規則**|是|是|是|是|是|否|否|
|**單一承租戶應用裝置**|否|是|是|是|是|否|是|
|**VLAN 保護**|否|是|是|是|是|否|是|
|**多重 VLAN 支援**|否|是|是|是|否|否|否|
|**NAT 支援**|否|是|是|是|是|否|否|
|**SSL/IPsec VPN 終止**|否|是|是|是|是|否|否|
|**Open VPN 終止**|否|是|是|否|否|否|否|
|**HA 選項**|N/A|是|是|是|是|否|是|
|**從 API 及入口網站進行管理**|是|應用裝置 GUI|應用裝置 GUI|應用裝置 GUI|應用裝置 GUI|是|是|
|**10Gbps 支援**|N/A|是|是|是|否|否|否|
|**NGFW 附加元件（IPS、AV、WF）**|否|否|否|是|是|否|否|
|**費用**|$0/月|$299.00/月起 + 裸機伺服器費用|$219.00/月起 + 裸機伺服器費用|$4,999.00/月起|$999.00/月起|$99.00/月起|$999.00/月起|
