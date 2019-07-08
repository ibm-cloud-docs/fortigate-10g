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

# ファイアウォールの検討
{: #exploring-firewalls}

IBM© Cloud では、使用するファイアウォールを複数のファイアウォールから選択できます。 以下の表では、適切なファイアウォールを選択できるようにするために、ファイアウォール・ソリューションを比較しています。 表内の個々のオファリングの名前をクリックすると、その詳細を確認できます。

右側にスクロールすると、表の残りの部分を表示できます。
{: important}

|        | [Security Groups](/docs/infrastructure/security-groups?topic=security-groups-getting-started) (VSI のみ) | [IBM Cloud Juniper vSRX Standard](/docs/infrastructure/vsrx?topic=vsrx-getting-started) |[Virtual Router Appliance](/docs/infrastructure/virtual-router-appliance?topic=virtual-router-appliance-getting-started) | [FortiGate Security Appliance 10Gbps](/docs/infrastructure/fortigate-10g?topic=fortigate-10g-getting-started) | [FortiGate Security Appliance 1Gbps](/docs/infrastructure/fortigate-1g?topic=fortigate-1g-getting-started) | [ハードウェア・ファイアウォール](/docs/infrastructure/hardware-firewall-shared?topic=hardware-firewall-shared-getting-started)| [ハードウェア・ファイアウォール (専用)](/docs/infrastructure/hardware-firewall-dedicated?topic=hardware-firewall-dedicated-getting-started) |
| ------- | :------: | :------: | :------: | :------: | :------: | :------: | :------: |
|**ステートフル・パケット検査**|![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)|![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)|![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)|![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)|![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)|![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)|![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)|
|**パブリック・ネットワークの保護**|![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)|![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)|![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)|![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)|![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)|![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)|![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)|
|**プライベート・ネットワークの保護**|![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)|![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)|![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)|![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)||||
|**進入ルール**|![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)|![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)|![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)|![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)|![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)|![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)|![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)|
|**退出ルール**|![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)|![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)|![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)|![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)|![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)|||
|**単一テナント・アプライアンス**||![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)|![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)|![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)|![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)||![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)|
|**VLAN 保護**||![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)|![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)|![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)|![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)||![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)|
|**複数 VLAN サポート**||![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)|![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)|![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)||||
|**NAT サポート**||![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)|![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)|![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)|![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)|||
|**SSL/IPsec VPN 終端**||![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)|![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)|![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)|![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)|||
|**オープン VPN 終端**|||![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)|||||
|**HA オプション**|適用外|![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)|![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)|![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)|![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)||![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)|
|**API & ポータルからの管理**|可|アプライアンス GUI|アプライアンス GUI|アプライアンス GUI|アプライアンス GUI|可|可|
|**10Gbps サポート**|適用外|![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)|![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)|![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)||||
|**NGFW アドオン (IPS、AV、WF)**||近日公開||![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)|![チェック・マーク・アイコン](../../icons/checkmark-icon.svg)|||
|**費用**|$0/月|$299.00/月 + ベア・メタル・サーバーの費用から | $219.00/月 + ベア・メタル・サーバーの費用から|$4,999.00/月から|$999.00/月から|$99.00/月から|$999.00/月から|
{: row-headers}
{: class="comparison-table"}
{: caption="IBM のファイアウォール製品の比較" caption-side="top"}
{: summary="This table all of IBM's firewall offerings, and provides links to their documentation."}
