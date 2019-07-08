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

# Gestione delle VLAN
{: #managing-vlans}

Per gestire le VLAN associate al tuo firewall, vai prima alla pagina della panoramica del dispositivo. Fai quindi clic su **VLANs** nella navigazione laterale, su **Manage** nel modulo dello stato o sul collegamento **Manage All** nel modulo delle VLAN. Sarai quindi reindirizzato alla pagina delle VLAN.

## Associa una VLAN a un firewall
{: #associate-a-vlan-with-a-firewall}

Fai clic su **Add VLAN** e seleziona una VLAN dal menu a discesa. Fai quindi clic su **Save** e conferma la tua selezione.
L'azione di associazione della VLAN non instrada la VLAN tramite il firewall.

## Annulla l'associazione di una VLAN a un firewall
{: #disassociate-a-vlan-with-a-firewall}

Seleziona le VLAN desiderate selezionando le caselle di spunta. Fai quindi clic su **Disassociate** e conferma la tua selezione.
Se la VLAN viene instradata tramite il firewall, questa azione instraderà la VLAN intorno al firewall prima dell'annullamento dell'associazione.

## Instrada una VLAN intorno a un firewall
{: #route-a-vlan-around-a-firewall}

Seleziona le VLAN desiderate selezionando le caselle di spunta. Fai quindi clic su **Route Around** e conferma la tua selezione.

## Instrada una VLAN tramite un firewall
{: #route-a-vlan-through-a-firewall}

Seleziona le VLAN desiderate selezionando le caselle di spunta. Fai quindi clic su **Route Through** e conferma la tua selezione.
