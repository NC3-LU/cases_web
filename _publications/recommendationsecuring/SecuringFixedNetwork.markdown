---
layout: publication-list
category: "In depth articles"
title:  "Securing a Fixed Network"
menutitle: "Securing a Fixed Network"
logo:
date:  2017-11-06 00:00:00 +0100
short: "How to guarantee IT security in a fixed network"
categories: securing
toc: true
ref: securingfixednetwork
lang: en
---
## In Brief
Security measures are behavioural, organisational or technical measures seeking to ensure the [confidentiality]({% link _knowhow/glossary/Confidentiality.markdown %}), [integrity]({% link _knowhow/glossary/Integrity.markdown %}) and [availability]({% link _knowhow/glossary/Availability.markdown %}) of an [asset]({% link _knowhow/glossary/Assets.markdown %}). Security measures seek to reduce the [vulnerabilities]({% link _knowhow/glossary/Vulnerabilities.markdown %}) exploited by [threats]({% link _knowhow/glossary/Threat.markdown %}) and thereby lower the [impacts]({% link _knowhow/glossary/Impact.markdown %}). They are defined during the [risk treatment]({% link _knowhow/bestpractices/RiskManagement.markdown %}#risk-treatment) phase in the risk management process. Within an entity, a fixed network links different machines ('assets') together. To be secure, this network needs to respond to certain security measures, as detailed below.

## Security Measures
To guarantee IT security in a fixed network:

1. It is strongly recommended to activate a **DHCP** server to verify the allocation of IP addresses. Servers should be allocated fixed IP addresses or DHCP static addresses.
2. It is strongly recommended to allocate **fixed IP addresses** (using a DHCP server) to computers which have specific rules for the company firewall or web filter. Draft and enforce a sectoral policy on access control – [Connection procedures]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#connection-procedures) and [Access rights management]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#access-rights-management).
3. It is strongly recommended to implement a network access control (NAC) system  to prevent access by machines not intended to be on the network.
4. It is strongly recommended to install a [web filter (proxy)]({% link _knowhow/glossary/WebFilterProxy.markdown %}) within the network to prohibit access to malicious websites or sites offering inappropriate content (games, pornography, etc.). Draft and enforce a sectoral policy on access control – [Use of external networks]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#use-of-external-networks).
5. For larger structures, it is recommended to [partition the network]({% link _knowhow/glossary/NetworkSegmentation.markdown %}) with firewalls. Draft and enforce a sectoral policy on access control – [External connections]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#external-connections) and [Separation of networks]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#separation-of-networks).
6. It is strongly recommended to create a **specific network** for laptop computers also used outside the company. To do this, specific switches may be necessary. Draft and enforce a sectoral policy on access control – [Separation of networks]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#separation-of-networks).
7. If a wireless network is set up, it is strongly recommended to set up a dedicated network for portable or personal devices.
8. In a WINDOWS environment, it is strongly recommended to implement a **domain server**  as well as an Active Directory. Draft and enforce a sectoral policy on the [Classification and control of resources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources.markdown %}) as well as a sectoral policy on access control – [Access rights management]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#access-rights-management).
9. It is strongly recommended to limit access to areas of the network not accessible to the general public. Draft and enforce a sectoral policy on Physical and environmental security – [Physical security perimeter]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %}#physical-security-perimeter) and [Rules within the perimeter]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %}#rules-within-the-perimeter).
