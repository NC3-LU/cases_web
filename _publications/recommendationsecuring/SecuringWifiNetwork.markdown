---
layout: publication-list
category: "In depth articles"
title:  "Securing a Wi-Fi Network"
menutitle: "Securing a wifi network"
logo:
date:  2017-11-06 00:00:00 +0100
short: "Security measures for employees and visitors"
categories: securing
toc: true
ref: securingwifinetwork
lang: en
---
## In Brief
Within an entity, a Wi-Fi network can be implemented to enable:

* employees to log in with their portable devices (GSM, smartphones, tablets);
* visitors to access the Internet using their laptop without accessing the local network.

See also the article on [network segmentation]({% link _knowhow/glossary/NetworkSegmentation.markdown %}) for further information.

## Wi-Fi for Employees
More and more employees take their mobile or portable device to work with them. Providing Internet access for these devices can reduce many security issues such as attempts to log in to the company network or logging in using work computers. This access should be reserved for employees and be protected against any attempt at intrusion, using suitable methods.

The recommended encryption method for this type of application is the **WPA2**-Enterprise protocol which enables each employee to enter their own password or certificate and which enables the proper management of [access rights]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#access-rights-management).

Employees should also be made to sign a Wi-Fi usage charter.

*Advice*: introduce a sectoral policy on system development and maintenance – [Use of encryption]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.markdown %}#encryption) – and a sectoral policy on compliance – [protection of personal data]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance.markdown %}#personal-data-protection).

## Security Measures
The following recommendations should be followed:

1. **Do not connect the Wi-Fi network to the fixed network of the entity**. Draft and enforce a sectoral policy on access control – [Separation of networks]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#separation-of-networks).
2. Activate a **DHCP** server for the allocation of IP addresses.
3. Install a [web filter]({% link _knowhow/glossary/WebFilterProxy.markdown %}) **(proxy)** within the Wi-Fi network to prevent any access to malicious websites or websites offering inappropriate content (games, gambling, pornography, etc.). Draft and enforce a sectoral policy on access control – [Use of external]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#use-of-external-networks) networks.
4. Add an anti-virus to the proposed web filter.
5. Block all non-web access to the Internet, except certain exceptions such as VPN access (clients may wish to connect to their company network) or email.
6. Encrypt the network. To do this, there are numerous possible strategies. These are detailed below.
7. Make physical access to aerials and the Wi-Fi router difficult. Draft and enforce a sectoral policy on physical and environmental security – [Physical security perimeter]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %}#physical-security-perimeter) and [Rules within the perimeter]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %}#rules-within-the-perimeter).

## Wi-Fi for Visitors/External Users
Visitors seeking to use the Internet within your organisation should have specific access dedicated to them. Given that, as opposed to employees, they have not signed a Wi-Fi usage charter, this should be presented to them the first time they connect.

Typical configuration:

* a hotspot with captive portal which restricts visitor access until they accept the general user conditions and enter a temporary password provided to them;
* an encryption method to avoid certain users from listening into the communications of others; it would be best to implement a secure network with a simple password in this case, even if the password is known to everyone.
