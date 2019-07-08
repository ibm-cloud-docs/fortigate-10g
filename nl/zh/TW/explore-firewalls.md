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

# 探索防火牆
{: #exploring-firewalls}

IBM© Cloud 提供許多防火牆供選擇。以下表格比較各個防火牆解決方案，協助您正確選擇適用的防火牆解決方案。若要進一步瞭解個別產品與服務，請按一下表格中的名稱。

向右捲動可檢視表格的其餘部分！
{: important}

|        | [安全群組](/docs/infrastructure/security-groups?topic=security-groups-getting-started)（僅限 VSI）| [IBM Cloud Juniper vSRX Standard](/docs/infrastructure/vsrx?topic=vsrx-getting-started) |[Virtual Router Appliance](/docs/infrastructure/virtual-router-appliance?topic=virtual-router-appliance-getting-started) | [FortiGate Security Appliance 10Gbps](/docs/infrastructure/fortigate-10g?topic=fortigate-10g-getting-started) | [FortiGate Security Appliance 1Gbps](/docs/infrastructure/fortigate-1g?topic=fortigate-1g-getting-started) | [Hardware Firewall](/docs/infrastructure/hardware-firewall-shared?topic=hardware-firewall-shared-getting-started) | [Hardware Firewall（專用）](/docs/infrastructure/hardware-firewall-dedicated?topic=hardware-firewall-dedicated-getting-started) |
| ------- | :------: | :------: | :------: | :------: | :------: | :------: | :------: |
|**狀態封包檢驗**|![勾號圖示](../../icons/checkmark-icon.svg)|![勾號圖示](../../icons/checkmark-icon.svg)|![勾號圖示](../../icons/checkmark-icon.svg)|![勾號圖示](../../icons/checkmark-icon.svg)|![勾號圖示](../../icons/checkmark-icon.svg)|![勾號圖示](../../icons/checkmark-icon.svg)|![勾號圖示](../../icons/checkmark-icon.svg)|
|**公用網路保護**|![勾號圖示](../../icons/checkmark-icon.svg)|![勾號圖示](../../icons/checkmark-icon.svg)|![勾號圖示](../../icons/checkmark-icon.svg)|![勾號圖示](../../icons/checkmark-icon.svg)|![勾號圖示](../../icons/checkmark-icon.svg)|![勾號圖示](../../icons/checkmark-icon.svg)|![勾號圖示](../../icons/checkmark-icon.svg)|
|**專用網路保護**|![勾號圖示](../../icons/checkmark-icon.svg)|![勾號圖示](../../icons/checkmark-icon.svg)|![勾號圖示](../../icons/checkmark-icon.svg)|![勾號圖示](../../icons/checkmark-icon.svg)||||
|**輸入規則**|![勾號圖示](../../icons/checkmark-icon.svg)|![勾號圖示](../../icons/checkmark-icon.svg)|![勾號圖示](../../icons/checkmark-icon.svg)|![勾號圖示](../../icons/checkmark-icon.svg)|![勾號圖示](../../icons/checkmark-icon.svg)|![勾號圖示](../../icons/checkmark-icon.svg)|![勾號圖示](../../icons/checkmark-icon.svg)|
|**輸出規則**|![勾號圖示](../../icons/checkmark-icon.svg)|![勾號圖示](../../icons/checkmark-icon.svg)|![勾號圖示](../../icons/checkmark-icon.svg)|![勾號圖示](../../icons/checkmark-icon.svg)|![勾號圖示](../../icons/checkmark-icon.svg)|||
|**單一承租戶應用裝置**||![勾號圖示](../../icons/checkmark-icon.svg)|![勾號圖示](../../icons/checkmark-icon.svg)|![勾號圖示](../../icons/checkmark-icon.svg)|![勾號圖示](../../icons/checkmark-icon.svg)||![勾號圖示](../../icons/checkmark-icon.svg)|
|**VLAN 保護**||![勾號圖示](../../icons/checkmark-icon.svg)|![勾號圖示](../../icons/checkmark-icon.svg)|![勾號圖示](../../icons/checkmark-icon.svg)|![勾號圖示](../../icons/checkmark-icon.svg)||![勾號圖示](../../icons/checkmark-icon.svg)|
|**多重 VLAN 支援**||![勾號圖示](../../icons/checkmark-icon.svg)|![勾號圖示](../../icons/checkmark-icon.svg)|![勾號圖示](../../icons/checkmark-icon.svg)||||
|**NAT 支援**||![勾號圖示](../../icons/checkmark-icon.svg)|![勾號圖示](../../icons/checkmark-icon.svg)|![勾號圖示](../../icons/checkmark-icon.svg)|![勾號圖示](../../icons/checkmark-icon.svg)|||
|**SSL/IPsec VPN 終止**||![勾號圖示](../../icons/checkmark-icon.svg)|![勾號圖示](../../icons/checkmark-icon.svg)|![勾號圖示](../../icons/checkmark-icon.svg)|![勾號圖示](../../icons/checkmark-icon.svg)|||
|**Open VPN 終止**|||![勾號圖示](../../icons/checkmark-icon.svg)|||||
|**HA 選項**|N/A|![勾號圖示](../../icons/checkmark-icon.svg)|![勾號圖示](../../icons/checkmark-icon.svg)|![勾號圖示](../../icons/checkmark-icon.svg)|![勾號圖示](../../icons/checkmark-icon.svg)||![勾號圖示](../../icons/checkmark-icon.svg)|
|**從 API 及入口網站進行管理**|是|應用裝置 GUI|應用裝置 GUI|應用裝置 GUI|應用裝置 GUI|是|是|
|**10Gbps 支援**|N/A|![勾號圖示](../../icons/checkmark-icon.svg)|![勾號圖示](../../icons/checkmark-icon.svg)|![勾號圖示](../../icons/checkmark-icon.svg)||||
|**NGFW 附加元件（IPS、AV、WF）**||即將推出||![勾號圖示](../../icons/checkmark-icon.svg)|![勾號圖示](../../icons/checkmark-icon.svg)|||
|**費用**|$0/月|$299.00/月起 + 裸機伺服器費用|$219.00/月起 + 裸機伺服器費用|$4,999.00/月起|$999.00/月起|$99.00/月起|$999.00/月起|
{: row-headers}
{: class="comparison-table"}
{: caption="IBM 防火牆供應項目的比較" caption-side="top"}
{: summary="這個表格列出所有 IBM 防火牆供應項目，並提供其文件的鏈結。"}
