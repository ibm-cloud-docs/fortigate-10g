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

# 방화벽 탐색
{: #exploring-firewalls}

IBM© Cloud에서는 선택 가능한 여러 방화벽을 제공합니다. 아래 표에는 적합한 방화벽을 선택하는 데 도움이 되도록 방화벽 솔루션이 비교되어 있습니다. 개별 오퍼링에 대해 자세히 알아보려면 표에서 해당 이름을 클릭하십시오.

표의 나머지 부분을 보려면 오른쪽으로 스크롤하십시오.
{: important}

|        | [보안 그룹](/docs/infrastructure/security-groups?topic=security-groups-getting-started)(VSI 전용) | [IBM Cloud Juniper vSRX Standard](/docs/infrastructure/vsrx?topic=vsrx-getting-started) |[Virtual Router Appliance](/docs/infrastructure/virtual-router-appliance?topic=virtual-router-appliance-getting-started) | [FortiGate Security Appliance 10Gbps](/docs/infrastructure/fortigate-10g?topic=fortigate-10g-getting-started) | [FortiGate Security Appliance 1Gbps](/docs/infrastructure/fortigate-1g?topic=fortigate-1g-getting-started) | [Hardware Firewall](/docs/infrastructure/hardware-firewall-shared?topic=hardware-firewall-shared-getting-started) | [Hardware Firewall(Dedicated)](/docs/infrastructure/hardware-firewall-dedicated?topic=hardware-firewall-dedicated-getting-started) |
| ------- | :------: | :------: | :------: | :------: | :------: | :------: | :------: |
|**Stateful 패킷 검사**|![체크 표시 아이콘](../../icons/checkmark-icon.svg)|![체크 표시 아이콘](../../icons/checkmark-icon.svg)|![체크 표시 아이콘](../../icons/checkmark-icon.svg)|![체크 표시 아이콘](../../icons/checkmark-icon.svg)|![체크 표시 아이콘](../../icons/checkmark-icon.svg)|![체크 표시 아이콘](../../icons/checkmark-icon.svg)|![체크 표시 아이콘](../../icons/checkmark-icon.svg)|
|**공용 네트워크 보호**|![체크 표시 아이콘](../../icons/checkmark-icon.svg)|![체크 표시 아이콘](../../icons/checkmark-icon.svg)|![체크 표시 아이콘](../../icons/checkmark-icon.svg)|![체크 표시 아이콘](../../icons/checkmark-icon.svg)|![체크 표시 아이콘](../../icons/checkmark-icon.svg)|![체크 표시 아이콘](../../icons/checkmark-icon.svg)|![체크 표시 아이콘](../../icons/checkmark-icon.svg)|
|**사설 네트워크 보호**|![체크 표시 아이콘](../../icons/checkmark-icon.svg)|![체크 표시 아이콘](../../icons/checkmark-icon.svg)|![체크 표시 아이콘](../../icons/checkmark-icon.svg)|![체크 표시 아이콘](../../icons/checkmark-icon.svg)||||
|**Ingress 규칙**|![체크 표시 아이콘](../../icons/checkmark-icon.svg)|![체크 표시 아이콘](../../icons/checkmark-icon.svg)|![체크 표시 아이콘](../../icons/checkmark-icon.svg)|![체크 표시 아이콘](../../icons/checkmark-icon.svg)|![체크 표시 아이콘](../../icons/checkmark-icon.svg)|![체크 표시 아이콘](../../icons/checkmark-icon.svg)|![체크 표시 아이콘](../../icons/checkmark-icon.svg)|
|**Egress 규칙**|![체크 표시 아이콘](../../icons/checkmark-icon.svg)|![체크 표시 아이콘](../../icons/checkmark-icon.svg)|![체크 표시 아이콘](../../icons/checkmark-icon.svg)|![체크 표시 아이콘](../../icons/checkmark-icon.svg)|![체크 표시 아이콘](../../icons/checkmark-icon.svg)|||
|**싱글 테넌트 어플라이언스**||![체크 표시 아이콘](../../icons/checkmark-icon.svg)|![체크 표시 아이콘](../../icons/checkmark-icon.svg)|![체크 표시 아이콘](../../icons/checkmark-icon.svg)|![체크 표시 아이콘](../../icons/checkmark-icon.svg)||![체크 표시 아이콘](../../icons/checkmark-icon.svg)|
|**VLAN 보호**||![체크 표시 아이콘](../../icons/checkmark-icon.svg)|![체크 표시 아이콘](../../icons/checkmark-icon.svg)|![체크 표시 아이콘](../../icons/checkmark-icon.svg)|![체크 표시 아이콘](../../icons/checkmark-icon.svg)||![체크 표시 아이콘](../../icons/checkmark-icon.svg)|
|**다중 VLAN 지원**||![체크 표시 아이콘](../../icons/checkmark-icon.svg)|![체크 표시 아이콘](../../icons/checkmark-icon.svg)|![체크 표시 아이콘](../../icons/checkmark-icon.svg)||||
|**NAT 지원**||![체크 표시 아이콘](../../icons/checkmark-icon.svg)|![체크 표시 아이콘](../../icons/checkmark-icon.svg)|![체크 표시 아이콘](../../icons/checkmark-icon.svg)|![체크 표시 아이콘](../../icons/checkmark-icon.svg)|||
|**SSL/IPsec VPN 종료**||![체크 표시 아이콘](../../icons/checkmark-icon.svg)|![체크 표시 아이콘](../../icons/checkmark-icon.svg)|![체크 표시 아이콘](../../icons/checkmark-icon.svg)|![체크 표시 아이콘](../../icons/checkmark-icon.svg)|||
|**Open VPN 종료**|||![체크 표시 아이콘](../../icons/checkmark-icon.svg)|||||
|**HA 옵션**|해당사항 없음|![체크 표시 아이콘](../../icons/checkmark-icon.svg)|![체크 표시 아이콘](../../icons/checkmark-icon.svg)|![체크 표시 아이콘](../../icons/checkmark-icon.svg)|![체크 표시 아이콘](../../icons/checkmark-icon.svg)||![체크 표시 아이콘](../../icons/checkmark-icon.svg)|
|**API 및 포털에서 관리**|예|어플라이언스 GUI|어플라이언스 GUI|어플라이언스 GUI|어플라이언스 GUI|예|예|
|**10Gbps 지원**|해당사항 없음|![체크 표시 아이콘](../../icons/checkmark-icon.svg)|![체크 표시 아이콘](../../icons/checkmark-icon.svg)|![체크 표시 아이콘](../../icons/checkmark-icon.svg)||||
|**NGFW 추가 기능(IPS, AV, WF)**||지원 예정||![체크 표시 아이콘](../../icons/checkmark-icon.svg)|![체크 표시 아이콘](../../icons/checkmark-icon.svg)|||
|**비용**|$0/월|$299.00/월부터 시작 + Bare Metal Server 비용 |$219.00/월부터 시작 + Bare Metal Server 비용|$4,999.00/월부터 시작|$999.00/월부터 시작|$99.00/월부터 시작|$999.00/월부터 시작|
{: row-headers}
{: class="comparison-table"}
{: caption="IBM의 방화벽 오퍼링 비교" caption-side="top"}
{: summary="This table all of IBM's firewall offerings, and provides links to their documentation."}
