---
layout: knowhow
title:  "Security measures for small and medium-sized enterprises – Threats to infrastructure"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: f-bestpract
toc: true
---
Infrastructure includes all the essential assets and services on which the information system is based, such as the supply of power, communication or processing services. These services are therefore critical to the operation of the information system and exposed to certain threats. The section below describes the most common [threats]({{site.url}}) in this area and suggests appropriate protective measures for a small or medium-sized enterprise.

<h3 class="titre-page">Fire</h3>
A fire can be a totally destructive [threat]({{site.url}}), both to physical media (paper files) and to data stored on electronic devices (loss of [availability]({{site.url}})). The source of this threat may be internal or external, deliberate or accidental. In order to prevent it, the following instructions should be followed:

* [Keep a separate premises]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.html#physical-security-perimeter) specifically for IT equipment and for the most sensitive physical devices (Draft and enforce a sectoral policy on physical and environmental security – [Physical security perimeter]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.html#physical-security-perimeter) and [Rules within the perimeter]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.html#rules-within-the-perimeter))
  * without a sprinkler system
  * protected by a fire door
  * with CO2 fire extinguishers or an inert gas fire extinguishing system
  * with no inflammable materials and surfaces inside
* Media (paper files, for example) should preferably be stored in locked cabinets. (Draft and enforce a Sectoral policy on the classification and control of resources – [Classification and responsibilities for resources]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources.html), as well as a Sectoral policy on physical and environmental security – [Clean desk]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.html#tidy-office-policy))
* Safeguard documents of which only one copy exists in cabinets or fire-resistant containers. (Draft and enforce a Sectoral policy on physical and environmental security – [Clean desk]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.html#tidy-office-policy))
* Draft an alarm and evacuation procedure (sounding of an alarm and opening of fire exits). (Draft and enforce a Sectoral policy on Human factors).
* Introduce a backup policy, including decentralisation. (Draft and enforce a Sectoral policy on Operational and communication aspects – [Backups]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.html#data-backups))
* The organisation could potentially fall back on a disaster recovery site in downgraded mode based on a [business continuity plan]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-ManagingBusinessContinuity.html#operational-continuity) (BCP)

<h3 class="titre-page">Service interruption</h3>
Service interruption means the inability of the IT system to provide the desired service and/or the requested data and therefore entails at least temporary loss of [availability]({{site.url}}). There are specific measures you can use to protect against it:

* appropriate sizing of IT equipment (processor, network, storage), in particular for systems that operate in real time, and therefore a previous assessment of requirements (Draft and enforce a Sectoral policy on the classification and control of resources – [Classification and responsibilities for resources]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources.html))
* identification of peak periods
* prioritisation of certain activities during these periods
* installation of traffic regulation equipment, such as a load balancer or, in extreme cases, a cluster
* monitoring of equipment and network connections
* monitoring of the systems’ performances
* installation of redundant systems

<h3 class="titre-page">Denial of service/distributed service</h3>
DoS (Denial of Service) or DDoS (Distributed DoS) attacks cause the IT system to overload, notably blocking web or network services. They are usually the result of a deliberate and malicious act. How can you protect yourself?

* Set up advanced filtering rules for routers and [firewalls]({{site.url}}), [segment the network]({{site.url}}/knowhow/glossary/NetworkSegmentation.html) (Draft and enforce a Sectoral policy on Access control – [External connections]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-AccessControl.html#external-connections) and [Network separation]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-AccessControl.html#separation-of-networks)).
* Configure high [availability]({{site.url}}) system equipment that can recognise these attempts and repel them and/or adapt accordingly.

Please consult the CIRCL file for more information in case of DDoS attacks: [https://www.circl.lu/pub/dfak/DDoSMitigation/](https://www.circl.lu/pub/dfak/DDoSMitigation/)

<h3 class="titre-page">Disrupted transmission of wireless communications</h3>
Disrupted transmission of wireless [WiFi]({{site.url}}/publications/recommendationsecuring/SecuringWifiNetwork.html)) communications may be the results of a DoS attack (botnets, for example), or of a radio wave transmission problem (loss of availability). To avoid these problems, make sure that:

* the physical environment does not block communications (e.g. reinforced concrete, lead)
* the wireless access points are located in places with a lot of traffic, but remain inaccessible (e.g. located high up). (Draft and enforce a Sectoral policy on Physical and environmental security – [Physical security perimeter]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.html#physical-security-perimeter) and [Rules within the perimeter]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.html#rules-within-the-perimeter))
* the signal given out from the access points is not disturbed by waves from other electromagnetic sources in the surrounding areas (radio antenna, GSM, TV)

<h3 class="titre-page">Wireless network tapping</h3>
Wireless [WiFi]({{site.url}}/publications/recommendationsecuring/SecuringWifiNetwork.html)) networks do not rely on any physical media. They are transmitted through the air, meaning they can be tapped with a simple passive sensor. This may result in loss of [confidentiality]({{site.url}}) for your data. You can avoid this risk by making sure the following security measures are applied:

* communications must be encrypted using a secure protocol (e.g. WPA2 for WiFi) (Draft and enforce a Sectoral policy on systems development and maintenance – [Use of encryption]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.html#encryption))
* The WiFi range from the access points should be limited to the physical confines of the organisation
* access to these networks must to limited to authorised users (filtered by MAC address, for example)
* the WiFi network must not be directly connected to the organisation’s internal network, but rather separated by a [firewall]({{site.url}}) or using a dedicated connection (Draft and enforce a Sectoral policy on access control – [Network separation]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-AccessControl.html#separation-of-networks))

See also [Securing the internal WiFi network]({{site.url}}/publications/recommendationsecuring/SecuringWifiNetwork.html#wifi-for-employees) and [Securing the customer WiFi network]({{site.url}}/publications/recommendationsecuring/SecuringWifiNetwork.html#wifi-for-visitorsexternal-users).

<h3 class="titre-page">Interception of communications</h3>
A third party may intercept, corrupt or delete transmitted data (man-in-the-middle attacks) and thereby compromise the [confidentiality]({{site.url}}), [integrity]({{site.url}}) or [availability]({{site.url}}) of the data. You can protect the transmission of your communications and: 

* put in place the protective measures described in “wireless network tapping”
* use encryption methods to prevent access to and corruption of transmitted data. (Draft and enforce a Sectoral policy on System development and maintenance – [Use of encryption]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.html#encryption)).
* separate the networks (Draft and enforce a Sectoral policy on access control – [External connections]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-AccessControl.html#external-connections) and [Network separation]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-AccessControl.html#separation-of-networks)).
* ensure the cabling is inaccessible to malicious persons. (Draft and enforce a Sectoral policy on Physical and environmental security – [Physical security perimeter]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.html#physical-security-perimeter) and [Rules within the perimeter]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.html#rules-within-the-perimeter)).
* introduce an access rights policy (Draft and enforce a Sectoral policy on access control – [Access control policy]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-AccessControl.html#access-control-policy) and [Access rights management]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-AccessControl.html#access-rights-management) and [Connections procedures]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-AccessControl.html#connection-procedures) and [External connections]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-AccessControl.html#external-connections)).

Please consult the CIRCL file for more information about secure communication: [https://www.circl.lu/pub/dfak/SecureCommunication/](https://www.circl.lu/pub/dfak/SecureCommunication/)

<h3 class="titre-page">Network unavailability</h3>
Loss of telecommunications (loss of [availability]({{site.url}})) paralyses IT systems. It is advisable to have access to a redundant source point, if possible with a second telecommunications provider using different connection equipment tested on a regular basis.

<h3 class="titre-page">Power cut</h3>
A power cut may cause a loss of [availability]({{site.url}}) for the whole IT system. Energy supply is especially vital for organisations that run ‘real-time’ operations. Guard against this [threat]({{site.url}}) by having:

* an alarm that sounds whenever a failure is detected in the electricity network
* a UPS for sensitive devices
* an emergency generator for vital systems
* circuit breakers to protect equipment against power surges
* a power-down procedure for IT equipment (Draft and enforce a Sectoral policy on physical and environmental security – [Electrical equipment safety]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.html#electrical-equipment-safety).

<h3 class="titre-page">Discontinuity of service providers</h3>
An entity depends on its providers. Unavailability at service provider level can consequently have serious repercussions on its own operations. It is therefore preferable to provide for:

* [availability]({{site.url}}) (SLA service level) in the service agreement. (Draft and enforce a Sectoral policy on Physical and environmental security – [Maintenance]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.html#maintenance))
* service provider redundancy for downgraded modes
* the provision, by the service provider, of information (procedures, source code, technical documentation) needed to maintain activity

<h3 class="titre-page">Infiltrating the premises</h3>
A violation of the secure perimeters may have serious consequences on [confidentiality]({{site.url}}), [integrity]({{site.url}}) and [availability]({{site.url}}) for any organisation. An ill-intentioned person with access to [assets]({{site.url}}) within the company could steal, sabotage or make copies of these assets, causing a lot of [damage]({{site.url}}) in the process. Ensure that:

* individuals’ identities can be checked on the way into and out of the building. (Draft and enforce a Sectoral policy on Physical and environmental security – [Physical security perimeter]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.html#physical-security-perimeter) and [Rules within the perimeter]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.html#rules-within-the-perimeter))
* visitors and suppliers are always accompanied
* emergency exits only open from the inside
* server rooms remain locked at all times and are equipped with alarm systems and, if necessary, cameras
* a “clean desk” policy is respected (in other words, sensitive papers should be stored out of view (filing system) and workstations should be locked). (Draft and enforce a Sectoral policy on the Classification and control of resources – [Classification and responsibilities for resources]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources.html#classification-and-responsibility-for-resources), as well as a Sectoral policy on physical and environmental security – [Clean desk]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.html#tidy-office-policy))
* when the premises are closed, an alarm system or security company should monitor the site
* badges should be worn in accordance with the badge policy and should be easily visible
* quarantine zones should be available for deliveries
