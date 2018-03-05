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


# 방화벽 탐색
IBM Cloud에서는 선택 가능한 여러 방화벽을 제공합니다. 아래 표에는 적합한 방화벽을 선택하는 데 도움이 되도록 방화벽 솔루션이 비교되어 있습니다. 개별 오퍼링에 대해 자세히 알아보려면 표에서 해당 이름을 클릭하십시오.

표의 나머지 부분을 보려면 오른쪽으로 스크롤하십시오.

|        | [보안 그룹(VSI 전용)](https://console.bluemix.net/docs/infrastructure/security-groups/sg_index.html) | [하드웨어 방화벽](https://console.bluemix.net/docs/infrastructure/hardware-firewall-shared/getting-started.html#getting-started)(공유) | [하드웨어 방화벽](https://console.bluemix.net/docs/infrastructure/hardware-firewall-dedicated/getting-started.html#getting-started)(전용) | [Fortigate Security Appliance 1Gbps](https://console.bluemix.net/docs/infrastructure/fortigate-1g/getting-started.html#getting-started) | [가상 라우터 어플라이언스](https://console.bluemix.net/docs/infrastructure/virtual-router-appliance/getting-started.html#getting-started) | [Fortigate Security Appliance 10Gbps](https://console.bluemix.net/docs/infrastructure/fortigate-10g/getting-started.html#getting-started) |
| ------- | :------: | :------: | :------: | :------: | :------: | :------: |
|**Stateful 패킷 검사**|예|예|예|예|예|예|
|**공용 네트워크 보호**|예|예|예|예|예|예|
|**사설 네트워크 보호**|예|아니오|아니오|아니오|예|예|
|**Ingress 규칙**|예|예|예|예|예|예|
|**Egress 규칙**|예|아니오|아니오|예|예|예|
|**싱글 테넌트 어플라이언스**|아니오|아니오|예|예|예|예|
|**VLAN 보호**|아니오|아니오|예|예|예|예|
|**다중 VLAN 지원**|아니오|아니오|아니오|아니오|예|예|
|**NAT 지원**|아니오|아니오|아니오|예|예|예|
|**SSL/IPsec VPN 종료**|아니오|아니오|아니오|예|예|예|
|**Open VPN 종료**|아니오|아니오|아니오|아니오|예|아니오|
|**HA 옵션**|해당사항 없음|아니오|예|예|예|예|
|**API 및 포털에서 관리**|예|예|예|어플라이언스 GUI|어플라이언스 GUI|어플라이언스 GUI|
|**10Gbps 지원**|해당사항 없음|아니오|아니오|아니오|예|예|
|**NGFW 추가 기능(IPS, AV, WF)**|아니오|아니오|아니오|예|아니오|예|
|**비용**|$0/월|$99.00/월부터 시작|$999.00/월부터 시작|$999.00/월부터 시작|$219.00/월부터 시작 + 베어메탈 서버 비용|$4,999.00/월부터 시작|
