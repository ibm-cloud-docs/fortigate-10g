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


# ファイアウォールの検討
{: #exploring-firewalls}

IBM© Cloud では、使用するファイアウォールを複数のファイアウォールから選択できます。以下の表では、適切なファイアウォールを選択できるようにするために、ファイアウォール・ソリューションを比較しています。 表内の個々のオファリングの名前をクリックすると、その詳細を確認できます。

右側にスクロールすると、表の残りの部分を表示できます。

|        | [Security Groups](/docs/infrastructure/security-groups?topic=security-groups-getting-started-with-security-groups) (VSI のみ) | [IBM Cloud Juniper vSRX Standard](/docs/infrastructure/vsrx?topic=vsrx-getting-started-with-ibm-cloud-juniper-vsrx-gateway) |[Virtual Router Appliance](/docs/infrastructure/virtual-router-appliance?topic=virtual-router-appliance-getting-started-with-ibm-virtual-router-appliance) | [FortiGate Security Appliance 10Gbps](/docs/infrastructure/fortigate-10g?topic=fortigate-10g-getting-started-with-fortigate-security-appliance-10gbps) | [FortiGate Security Appliance 1Gbps](/docs/infrastructure/fortigate-1g?topic=fortigate-1g-getting-started-with-fortigate-security-appliance-1gbps) | [ハードウェア・ファイアウォール (共有)](/docs/infrastructure/hardware-firewall-shared?topic=hardware-firewall-shared-getting-started-with-hardware-firewall-shared) | [ハードウェア・ファイアウォール (専用)](/docs/infrastructure/hardware-firewall-dedicated?topic=hardware-firewall-dedicated-getting-started-with-hardware-firewall-dedicated) |
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
|**費用**|$0/月|$299.00/月 + ベア・メタル・サーバーの費用から | $219.00/月 + ベア・メタル・サーバーの費用から|$4,999.00/月から|$999.00/月から|$99.00/月から|$999.00/月から|
