---

copyright:
  years: 2017
lastupdated: "2019-02-22"

keywords: manage, vlans, managing, disassociate, route, vlan, firewall

subcollection: fortigate-10g

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}
{:codeblock: .codeblock}
{:pre: .pre}
{:screen: .screen}
{:tip: .tip}
{:note: .note}
{:important: .important}
{:download: .download}

# 管理 VLAN
{: #managing-vlans}

若要管理與防火牆相關聯的 VLAN，請先移至「裝置概觀」頁面。然後，按一下側邊導覽中的 **VLAN**、「狀態模組」中的**管理**，或是「VLAN 模組」中的**管理全部**鏈結。將會導向至 VLAN 頁面。

## 將 VLAN 和防火牆相關聯
{: #associate-a-vlan-with-a-firewall}

按一下**新增 VLAN**，然後從下拉選取 VLAN。 接著按一下**儲存**，確認您選取的項目。VLAN 關聯動作不會設定 VLAN 通過防火牆的路徑。

## 取消 VLAN  和防火牆相關聯
{: #disassociate-a-vlan-with-a-firewall}

切換核取方塊以選取所要的 VLAN。然後按一下**取消關聯**，確認您選取的項目。
如果 VLAN 設定通過防火牆的路徑，此動作會在取消關聯之前設定繞過防火牆的路徑。

## 設定 VLAN 繞過防火牆的路徑
{: #route-a-vlan-around-a-firewall}

切換核取方塊以選取所要的 VLAN。接著按一下**設定路徑繞過**，確認您選取的項目。

## 設定 VLAN 通過防火牆的路徑
{: #route-a-vlan-through-a-firewall}

切換核取方塊以選取所要的 VLAN。接著按一下**設定路徑通過**，確認您選取的項目。
