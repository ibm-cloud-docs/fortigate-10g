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

要管理与防火墙关联的 VLAN，请先转至“设备概述”页面。再单击侧边导航中的 **VLAN**、“状态模块”中的**管理**，或“VLAN 模块”中的**管理所有**链接。然后，系统会将您定向到 VLAN 页面。

## 将 VLAN 与防火墙关联
{: #associate-a-vlan-with-a-firewall}

单击**添加 VLAN**，并从下拉菜单选择 VLAN。然后，单击**保存**，并确认您的选择。VLAN 关联操作不会通过防火墙路由 VLAN。

## 解除 VLAN 与防火墙的关联
{: #disassociate-a-vlan-with-a-firewall}

通过切换复选框，选择所需的 VLAN。然后，单击**解除关联**，并确认您的选择。如果 VLAN 通过防火墙进行路由，那么此操作会绕过防火墙路由 VLAN，然后再解除关联。

## 绕过防火墙路由 VLAN
{: #route-a-vlan-around-a-firewall}

通过切换复选框，选择所需的 VLAN。然后，单击**绕过路由**，并确认您的选择。

## 通过防火墙路由 VLAN
{: #route-a-vlan-through-a-firewall}

通过切换复选框，选择所需的 VLAN。然后，单击**通过路由**，并确认您的选择。
