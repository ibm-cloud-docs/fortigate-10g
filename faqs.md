---

copyright:
  years: 2017, 2025
lastupdated: "2025-07-14"

keywords: faqs, firewall, gateway

subcollection: fortigate-10g

---

{{site.data.keyword.attribute-definition-list}}

# FAQ for FortiGate Security Appliance 10 Gbps
{: #faqs-for-fortigate-security-appliance-10gbps}

The following are some frequently asked questions you may have about working with the FortiGate Security Appliance 10 Gbps firewall.
{: shortdesc}

## What is the difference between FortiGate Security Appliance (FSA) 10 Gbps and FSA 1 Gbps? What about Virtual Router Appliance?
{: #differences}
{: faq}
{: support}

FSA 10 Gbps provides faster throughput compared to FSA 1 Gbps. It allows the customer to protect multiple VLANs (both private and public). More add-ons such as Anti-Virus (AV), Intrusion Prevention (IPS), and web filtering can be enabled on demand.

Virtual Router Appliance also protects multiple VLANs. However, Virtual Router Appliance does not provide next-generation firewall add-ons and purpose-built security processors.

## Can FSA 10G and a network gateway be associated with the same VLAN?
{: #vlan}
{: faq}
{: support}

No, it is not possible to have an FSA 10G and a network gateway device to be associated with the same customer VLAN.

## Does this offering charge for private network connectivity?
{: #network}
{: faq}
{: support}

IBM offers private connectivity free of charge, which is one of the key differentiators in the marketplace.

## Is FSA 1 Gbps also a multi-VLAN offering?
{: #multi-vlan}
{: faq}
{: support}

No, only FSA 10 Gbps supports multiple VLANs.

## Is FSA 10 Gbps available in Federal data centers?
{: #federal}
{: faq}
{: support}

FSA 10 Gbps is not currently available in Federal data centers.

## Can an FSA 10 Gbps be used in place of a Virtual Router Appliance?
{: #vra}
{: faq}
{: support}

Yes.

## Do you plan to upgrade FSA 1G with the same capability of the FSA 10G appliance?
{: #upgrade}
{: faq}
{: support}

Not currently.

## Can the FSA 10 Gbps span over multiple pods in a data center?
{: #multiple-pods}
{: faq}
{: support}

Not currently. FSA 10 Gbps is only able to protect VLANs for the pod it is deployed in.

## What are the default DNS servers of FortiGate 10 Gbps?
{: #default-dns-servers}

By default, FortiGate uses the following FortiGuard's DNS servers.

* Primary: `208.91.112.53`
* Secondary: `208.91.112.52`
