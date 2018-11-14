---
layout: article
title:  "Virtual Private Networks (VPNs)"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: knowhow
toc: true
ref: glossaryvpn
lang: fr
---

## In brief
The growth in Internet usage has given rise to new ways of working such as working from home, the exchange of classified information between different subsidiaries of the same company, and even viewing the websites and IT systems of suppliers or clients. As a consequence of this, a genuine security issue relating to these new methods of working is starting to emerge. 

“Virtual Private Networks” (VPNs) can provide an answer to some of these issues, and they are coming into increasing usage. The purpose of this article is to show the different types of VPN in existence, and also to detail a few user scenarios.
 
## Explanations
A virtual private network is a means of communication which ensures secure data transfer over public or shared networks (such as cable distribution and even ADSL). A VPN is, in fact, a communications network which uses the same security parameters as a private network. Its main features are:

* data confidentiality: encryption guarantees that the content of data transmitted can only be known to the parties exchanging the information. Because of this, any third party intercepting VPN traffic will not be able to determine its content;
* data integrity: cryptographic methods employed ensure that the data received by the recipient over a VPN is identical to the data sent by the sender;
* authentication of VPN users: it is important to know who is taking part in procedures to avoid security issues relating to identity theft and therefore illicit access to private networks.

VPN is a technology enabling a logical extension of a network or a sub-network of the organisation through the addition of workstations or sub-networks outside its physical boundaries. More specifically, employees working from home will be virtually acting within the internal network of the organisation, or between two remote sites or even a world apart, and sharing the same network.

## Threats encountered
The Internet provides no guarantees over the confidentiality or the integrity of data circulating over the web. For example, if you send an email, it is entirely possible that a third party could intercept it, read it and even alter some of the content.

This is clearly totally unacceptable, especially with regard to sensitive connections such as transactions with clients or partners or remote access to a company’s classified information (on a file server, for example).

The best means to counter such threats is currently the use of a VPN.

## Recommendations
There are many different VPN protocols available and choosing the right one is not a simple matter. It is important to find out about the strength of the cryptographic algorithms being used. For example, the PPTP protocol – the protocol traditionally used in Windows infrastructures – is known to be no longer reliable because the authentication data can be stolen by third parties.

In general, the easiest thing to do is to use the type of VPN offered with the firewall solution of your organisation.

## Security policy
Draft and enforce the following sectoral policies:

* [Organisation of security]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity_fr.markdown %})
  * [Third party access and outsourcing]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity_fr.markdown %}#third-party-access-and-outsourcing)
* [Classification and monitoring of resources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %})
  * [Classification of and responsibility for resources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %}#classification-and-responsibility-for-resources)
* [Physical and environmental security]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %})
  * [Physical security perimeter]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#physical-security-perimeter )
  * [Rules within the perimeter]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#rules-within-the-perimeter)
  * [Off-site equipment security]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#off-site-equipment-security)
* [Operational and communications aspects]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %})
  * [Documented procedures]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#documentation-of-procedures)
  * [Separation of development and production environments]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#separation-of-environments)
  * [External management of resources]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#outsourcing-of-resource-management)
  * [Protection against malware]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#protection-against-malware)
* [Access control]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %})
  * [Access control policy]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-control-policy %})
  * [Access rights management]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-rights-management)
  * [Use of external networks]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#use-of-external-networks)
  * [External connections]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#external-connections)
  * [Separation of networks]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#separation-of-networks)
  * [Login procedure]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#connection-procedures)
* [Development and maintenance of systems]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %})
  * [Use of encryption]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}#encryption)
* [Management of security incidents](% link _knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents_fr.markdown %})
  * [Reporting information security events]({% link _knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents_fr.markdown %}#reporting-information-security-events)
  * [Incident management and improvements information security]({% link _knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents_fr.markdown %}#incident-management-and-improvements-information-security)
  * [Analysis of non-fulfilment of obligations]({% link _knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents_fr.markdown %}#analysis-of-non-fulfilment-of-obligations)
* [Compliance]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %})
  * [Intellectual property]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %}#intellectual-property})
  * [Protection of operational data]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %}#protection-of-operational-data)
  * [Personal data protection]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %}#personal-data-protection)
