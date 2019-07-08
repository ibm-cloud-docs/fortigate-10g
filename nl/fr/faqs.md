---

copyright:
  years: 2017
lastupdated: "2018-11-10"

keywords: faqs, fortigate, 10gbps, firewall, fsa, gateway

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
{:faq: data-hd-content-type='faq'}

# Foire aux questions concernant le dispositif de sécurité FortiGate 10 Gbit/s
{: #faqs-for-fortigate-security-appliance-10gbps}

Voici certaines des questions fréquemment posées lors de l'utilisation du pare-feu FortiGate 10g.

## Quelles sont les différences entre FSA 10G et FSA 1G ? Qu'en est-il du dispositif VRA (Virtual Router Appliance) ?
{: faq}

Le dispositif FSA 10G offre un débit plus rapide que le dispositif FSA 1G. Le dispositif permet au client de protéger plusieurs réseaux locaux virtuels (publics et privés). Des modules complémentaires comme AV (antivirus), IPS (prévention des intrusions) et FW (filtrage Web) peuvent être activés à la demande.

Le dispositif Virtual Router Appliance protège également plusieurs réseaux locaux virtuels. Cependant, il ne propose pas de module complémentaire NGFW (Next Generation FireWall) ni de processeur de sécurité spécifiquement conçu.

## Est-il possible d'associer un dispositif FSA 10G et une passerelle réseau au même réseau local virtuel ?
{: faq}

Non, un dispositif FSA 10G et une passerelle réseau ne peuvent pas être associés au même réseau local virtuel client.

## Est-ce que cette offre facture la connectivité au réseau privé ?
{: faq}

IBM© propose gratuitement la connectivité au réseau privé, ce qui constitue l'un de nos principaux facteurs de différenciation sur le marché.

## Le dispositif FSA 1 Gbit/s est-il également une offre pour protéger plusieurs réseaux locaux virtuels ?
{: faq}

Non, seul le dispositif FSA 10 Gbit/s prend en charge plusieurs réseaux locaux virtuels.

## Le dispositif FSA 10 Gbit/s est-il disponible dans les centres de données fédéraux ?
{: faq}

Le dispositif FSA 10 Gbit/s n'est actuellement pas disponible dans les centres de données fédéraux.

## Est-il possible d'utiliser un dispositif FSA 10 Gbit/s à la place d'un dispositif Virtual Router Appliance ?
{: faq}

Oui.

## Prévoyez-vous de mettre à niveau le dispositif FSA 1G avec la même fonctionnalité que le dispositif FSA 10G ?
{: faq}

Pas actuellement.

## Est-ce que le dispositif FSA 10 Gbit/s peut couvrir plusieurs pods d'un centre de données ?
{: faq}

Pas actuellement. Le dispositif FSA 10 Gbit/s ne peut protéger que les réseaux locaux virtuels du pod sur lequel il est déployé.
