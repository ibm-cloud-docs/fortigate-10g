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


# 방화벽 탐색
{: #exploring-firewalls}

IBM© Cloud에서는 선택 가능한 여러 방화벽을 제공합니다. 아래 표에는 적합한 방화벽을 선택하는 데 도움이 되도록 방화벽 솔루션이 비교되어 있습니다. 개별 오퍼링에 대해 자세히 알아보려면 표에서 해당 이름을 클릭하십시오.

표의 나머지 부분을 보려면 오른쪽으로 스크롤하십시오.

|        | [보안 그룹](/docs/infrastructure/security-groups?topic=security-groups-getting-started-with-security-groups)(VSI 전용) | [IBM Cloud Juniper vSRX Standard](/docs/infrastructure/vsrx?topic=vsrx-getting-started-with-ibm-cloud-juniper-vsrx-gateway) |[Virtual Router Appliance](/docs/infrastructure/virtual-router-appliance?topic=virtual-router-appliance-getting-started-with-ibm-virtual-router-appliance) | [FortiGate Security Appliance 10Gbps](/docs/infrastructure/fortigate-10g?topic=fortigate-10g-getting-started-with-fortigate-security-appliance-10gbps) | [FortiGate Security Appliance 1Gbps](/docs/infrastructure/fortigate-1g?topic=fortigate-1g-getting-started-with-fortigate-security-appliance-1gbps) | [Hardware Firewall(공유)](/docs/infrastructure/hardware-firewall-shared?topic=hardware-firewall-shared-getting-started-with-hardware-firewall-shared) | [Hardware Firewall(Dedicated)](/docs/infrastructure/hardware-firewall-dedicated?topic=hardware-firewall-dedicated-getting-started-with-hardware-firewall-dedicated) |
| ------- | :------: | :------: | :------: | :------: | :------: | :------: | :------: |
|**Stateful 패킷 검사**|예|예|예|예|예|예|예|
|**공용 네트워크 보호**|예|예|예|예|예|예|예|
|**사설 네트워크 보호**|예|예|예|예|아니오|아니오|아니오|
|**Ingress 규칙**|예|예|예|예|예|예|예|
|**Egress 규칙**|예|예|예|예|예|아니오|아니오|
|**싱글 테넌트 어플라이언스**|아니오|예|예|예|예|아니오|예|
|**VLAN 보호**|아니오|예|예|예|예|아니오|예|
|**다중 VLAN 지원**|아니오|예|예|예|아니오|아니오|아니오|
|**NAT 지원**|아니오|예|예|예|예|아니오|아니오|
|**SSL/IPsec VPN 종료**|아니오|예|예|예|예|아니오|아니오|
|**Open VPN 종료**|아니오|예|예|아니오|아니오|아니오|아니오|
|**HA 옵션**|해당사항 없음|예|예|예|예|아니오|예|
|**API 및 포털에서 관리**|예|어플라이언스 GUI|어플라이언스 GUI|어플라이언스 GUI|어플라이언스 GUI|예|예|
|**10Gbps 지원**|해당사항 없음|예|예|예|아니오|아니오|아니오|
|**NGFW 추가 기능(IPS, AV, WF)**|아니오|아니오|아니오|예|예|아니오|아니오|
|**비용**|$0/월|$299.00/월부터 시작 + Bare Metal Server 비용 |$219.00/월부터 시작 + Bare Metal Server 비용|$4,999.00/월부터 시작|$999.00/월부터 시작|$99.00/월부터 시작|$999.00/월부터 시작|
