# Fortigate Security Appliance 10Gbps

The FortiGate Security Appliance (FSA) 10Gbps is a single tenant (dedicated), high throughput (10Gbps) hardware firewall with next generation features, such as AntiVirus (AV), Intrusion Prevention (IPS), deep packet inspection, and web application firewall (WAF).

This firewall can be configured to protect traffic on multiple VLANs for both public and private networks. In the Customer Portal it is referred to as a “Multi VLAN Firewall”.

## Table of Contents

 * [Welcome](#welcome)
 * [Overview of Features](#overview-of-features)
 * [Getting Started](#getting-started)
 * [Viewing a List of Firewalls](#viewing-a-list-of-firewalls)
 * [Managing Firewall Device Details](#managing-firewall-device-details)
 * [Managing VLANs](#managing-vlans)
 * [Cancelling Your Firewall](#cancelling-your-firewall)
 * [External Documentation](#external-documentation)

## Welcome

As the demand for high-speed, in-cloud networks for enterprise grows, so does the customer need for securing workload and network. Big data, SAN, compute intensive servers, and highly scalable applications are pushing the bandwidth and network speed requirements for workloads in the cloud. IBM recognizes that security solutions must evolve with the new demands in order to offer efficient protection. IBM’s new high-end high-throughput firewall offering is perfect for large businesses and enterprises who need a reliable, powerful, consolidated way to manage and control high-speed network traffic in the cloud.

With the exception of IBM, no other cloud service provider currently offers hardware firewalls for robust perimeter security in the cloud. FortiGate Security Appliance 10Gbps allows our customers to grow their workload and networks in IBM Cloud.

## Overview of Features

Features of the Fortigate Security Appliance 10Gbps include:

* High throughput (up to 10 Gbps)
* NGFW add-ons (IPS/AV/WAF/Deep Packet Inspection)
* Public and private network connectivity
* Ability to associate multiple VLANs to a single firewall device

## Getting Started

To get started, order a Multi VLAN Firewall from the order page:

1. From your browser, open [https://control.softlayer.com/](https://control.softlayer.com/) and log into your account.
2. In the Customer Portal navigation, select **Security > Network Security  > Firewalls**.
3. From the **Firewalls** page, select the **Order Multi VLAN Firewall** link in the top right corner. This link opens the Multi VLAN Firewall order page.
If your account does not currently have any Multi VLAN Firewalls, a message displays with a link to the order page.

You can order your firewall from the order page:

1. Give the firewall a name.
2. Select the desired Datacenter and Pod from the dropdown menus. Availability is limited to select locations.
3. Choose the desired VLANs Configuration.
4. Choose to have a single FSA or enable failover protection with the High Availability option.
5. Choose from the list of Add-ons or bundle all of them together for a discounted price. The Order Summary box displays the updated information for your current order. 
6. Select the **Master Service Agreement** checkbox once you review your order. 
7. Submit your order by clicking **Place Order**.

## Viewing a List of Firewalls
To see a list of the current FortiGate Security Appliance 10Gbps firewalls associated with your account, navigate to the list page:

1. From your browser, open [https://control.softlayer.com/](https://control.softlayer.com/) and log into your account.
2. In the Customer Portal navigation, select **Security > Network Security > Firewalls**.
3. On the Firewalls page, select the **Multi VLAN Firewalls** tab. 
4. If your account does not have a Multi VLAN Firewall, a message displays with a link to the order page. 

## Managing Firewall Device Details

To see the device details for a FortiGate Security Appliance 10Gbps, click the link for the device under the Firewall Name column. 

This link directs you to the Device Overview page.
### Restoring default firewall settings

To reset your device back to its factory settings, select the overflow menu, then select **Restore Defaults** from the dropdown menu.

### Accessing the FSA Portal

To log into the Device Portal you will need your management credentials. Locate the device username and password in the General Information Section. 

Toggle showing your device password by selecting the Eye icon.

Next, select the Portal button in the Status Module. This link directs you to the device login page.

## Managing VLANs

To manage the VLANs associated with your firewall, click **Manage** in the Status Module or click the **Manage All** link in the VLANs Module. You will then be directed to the VLANs page.

### Associate a VLAN with a Firewall

Click **Add VLAN** and select a VLAN from the dropdown. Then click **Save** and confirm your selection.
The VLAN association action does not route the VLAN through the firewall.

### Disassociate a VLAN with a Firewall

Select the desired VLAN(s) by toggling the checkboxes. Then click **Disassociate** and confirm your selection.
If the VLAN is routed through the firewall, this action will route the VLAN around the firewall prior to disassociation.

### Route a VLAN Around a Firewall

Select the desired VLAN(s) by toggling the checkboxes. Then click **Route Around** and confirm your selection.

### Route a VLAN Through a Firewall

Select the desired VLAN(s) by toggling the checkboxes. Then click **Route Through** and confirm your selection.

## Cancelling Your Firewall

A FortiGate Security Appliance 10Gbps can be cancelled immediately or on the anniversary date. Cancelling on the anniversary date will keep the firewall active until the beginning of the next billing period. Take the following steps to cancel a firewall:

1. Navigate to the Device Overview page by selecting the name of the firewall under the **Firewall Name** column.
2. Click the overflow menu and select **Cancel Device**.
3. Choose to either cancel immediately or on the anniversary date (next billing cycle).
4. Confirm your selection.
	
## External Documentation 

External documentation on the Fortigate Security Appliance 10Gbps can be found on the [Fortinet website.](https://www.fortinet.com/) 	
