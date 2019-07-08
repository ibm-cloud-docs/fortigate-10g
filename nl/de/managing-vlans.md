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

# VLANs verwalten
{: #managing-vlans}

Zur Verwaltung der Ihrer Firewall zugeordneten VLANs rufen Sie zuerst die Seite mit der Geräteübersicht auf. Klicken Sie dann auf **VLANs** in der seitlichen Navigationsleiste, auf **Verwalten** im Statusmodul oder auf den Link **Alle verwalten** im VLAN-Modul. Sie werden dann zur VLAN-Seite weitergeleitet.

## VLAN einer Firewall zuordnen
{: #associate-a-vlan-with-a-firewall}

Klicken Sie auf **VLAN hinzufügen** und wählen Sie ein VLAN im Dropdown-Menü aus. Klicken Sie dann auf **Speichern** und bestätigen Sie die Auswahl.
Durch die Zuordnung eines VLAN wird für dieses VLAN kein Routing durch die Firewall konfiguriert.

## Zuordnung eines VLAN zu einer Firewall aufheben
{: #disassociate-a-vlan-with-a-firewall}

Wählen Sie ein oder mehrere gewünschte VLANs mithilfe der Kontrollkästchen aus. Klicken Sie dann auf **Zuordnung aufheben** und bestätigen Sie die Auswahl.
Wenn für das VLAN Routing durch die Firewall konfiguriert ist, wird mit dieser Aktion Routing um die Firewall für das VLAN konfiguriert, bevor die Zuordnung aufgehoben wird.

## VLAN-Routing um eine Firewall
{: #route-a-vlan-around-a-firewall}

Wählen Sie ein oder mehrere gewünschte VLANs mithilfe der Kontrollkästchen aus. Klicken Sie dann auf **Routing um eine Firewall** und bestätigen Sie die Auswahl.

## VLAN-Routing durch eine Firewall
{: #route-a-vlan-through-a-firewall}

Wählen Sie ein oder mehrere gewünschte VLANs mithilfe der Kontrollkästchen aus. Klicken Sie dann auf **Routing durch eine Firewall** und bestätigen Sie die Auswahl.
