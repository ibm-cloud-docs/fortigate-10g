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


# ファイアウォールの詳細
IBM Cloud では、使用するファイアウォールを複数のファイアウォールから選択できます。 以下の表では、適切なファイアウォールを選択できるようにするために、ファイアウォール・ソリューションを比較しています。 表内の個々のオファリングの名前をクリックすると、その詳細を確認できます。

右側にスクロールすると、表の残りの部分を表示できます。

|        | [Security Groups](../security-groups/sg_index.html) (VSI のみ) | [IBM Cloud Juniper vSRX Standard](../vsrx/getting-started.html#getting-started) |[Virtual Router Appliance](../virtual-router-appliance/getting-started.html#getting-started) | [FortiGate Security Appliance 10Gbps](../fortigate-10g/getting-started.html#getting-started) | [FortiGate Security Appliance 1Gbps](../fortigate-1g/getting-started.html#getting-started) | [ハードウェア・ファイアウォール](../hardware-firewall-shared/getting-started.html#getting-started) (共有) | [ハードウェア・ファイアウォール](../hardware-firewall-dedicated/getting-started.html#getting-started) (専用) |
| ------- | :------: | :------: | :------: | :------: | :------: | :------: | :------: |
|**ステートフル・パケット検査**|可|可|可|可|可|可|可|
|**パブリック・ネットワークの保護**|可|可|可|可|可|可|可|
|**プライベート・ネットワークの保護**|可|可|可|可|不可|不可|不可|
|**進入ルール**|可|可|可|可|可|可|可|
|**退出ルール**|可|可|可|可|可|不可|不可|
|**単一テナント・アプライアンス**|不可|可|可|可|可|不可|可|
|**VLAN 保護**|不可|可|可|可|可|不可|可|
|**複数 VLAN サポート**|不可|可|可|可|不可|不可|不可|
|**NAT サポート**|不可|可|可|可|可|不可|不可|
|**SSL/IPsec VPN 終端**|不可|可|可|可|可|不可|不可|
|**オープン VPN 終端**|不可|可|可|不可|不可|不可|不可|
|**HA オプション**|適用外|可|可|可|可|不可|可|
|**API & ポータルからの管理**|可|アプライアンス GUI|アプライアンス GUI|アプライアンス GUI|アプライアンス GUI|可|可|
|**10Gbps サポート**|適用外|可|可|可|不可|不可|不可|
|**NGFW アドオン (IPS、AV、WF)**|不可|不可|不可|可|可|不可|不可|
|**費用**|$0/月|$299.00/月 + ベア・メタル・サーバーの費用から |$219.00/月 + ベア・メタル・サーバーの費用から|$4,999.00/月から|$999.00/月から|$99.00/月から|$999.00/月から|
