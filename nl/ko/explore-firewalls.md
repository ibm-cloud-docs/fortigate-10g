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
IBM Cloud에서는 선택 가능한 여러 방화벽을 제공합니다. 아래 표에는 적합한 방화벽을 선택하는 데 도움이 되도록 방화벽 솔루션이 비교되어 있습니다. 개별 오퍼링에 대해 자세히 알아보려면 표에서 해당 이름을 클릭하십시오.

표의 나머지 부분을 보려면 오른쪽으로 스크롤하십시오.

|        | [보안 그룹](../security-groups/sg_index.html)(VSI 전용) | [IBM Cloud Juniper vSRX Standard](../vsrx/getting-started.html#getting-started) |[Virtual Router Appliance](../virtual-router-appliance/getting-started.html#getting-started) | [FortiGate Security Appliance 10Gbps](../fortigate-10g/getting-started.html#getting-started) | [FortiGate Security Appliance 1Gbps](../fortigate-1g/getting-started.html#getting-started) |[하드웨어 방화벽](../hardware-firewall-shared/getting-started.html#getting-started)(Shared) |[Hardware Firewall](../hardware-firewall-dedicated/getting-started.html#getting-started)(Dedicated) |
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
