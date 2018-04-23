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
Infrastructure includes all the essential assets and services on which the information system is based, such as the supply of power, communication or processing services. These services are therefore critical to the operation of the information system and exposed to certain threats. The section below describes the most common threats in this area and suggests appropriate protective measures for a small or medium-sized enterprise.

## Fire
A fire can be a totally destructive threat, both to physical media (paper files) and to data stored on electronic devices (loss of availability). The source of this threat may be internal or external, deliberate or accidental. In order to prevent it, the following instructions should be followed:

* Keep a separate premises specifically for IT equipment and for the most sensitive physical devices (Draft and enforce a sectoral policy on physical and environmental security – Physical security  perimeter and Rules within the perimeter)
  * without a sprinkler system
  * protected by a fire door
  * with CO2 fire extinguishers or an inert gas fire extinguishing system
  * with no inflammable materials and surfaces inside
* Media (paper files, for example) should preferably be stored in locked cabinets. (Draft and enforce a Sectoral policy on the classification and control of resources – Classification and responsibilities for resources, as well as a Sectoral policy on physical and environmental security – Clean desk)
* Safeguard documents of which only one copy exists in cabinets or fire-resistant containers. (Draft and enforce a Sectoral policy on physical and environmental security – Clean desk)
* Draft an alarm and evacuation procedure (sounding of an alarm and opening of fire exits). (Draft and enforce a Sectoral policy on Human factors).
* Introduce a backup policy, including decentralisation. (Draft and enforce a Sectoral policy on Operational and communication aspects – Backups)
* The organisation could potentially fall back on a disaster recovery site in downgraded mode based on a business continuity plan (BCP)

## Service interruption
Service interruption means the inability of the IT system to provide the desired service and/or the requested data and therefore entails at least temporary loss of availability. There are specific measures you can use to protect against it:

* appropriate sizing of IT equipment (processor, network, storage), in particular for systems that operate in real time, and therefore a previous assessment of requirements (Draft and enforce a Sectoral policy on the classification and control of resources – Classification and responsibilities for resources)
* identification of peak periods
* prioritisation of certain activities during these periods
* installation of traffic regulation equipment, such as a load balancer or, in extreme cases, a cluster
* monitoring of equipment and network connections
* monitoring of the systems’ performances
* installation of redundant systems

## Denial of service/distributed service
DoS (Denial of Service) or DDoS (Distributed DoS) attacks cause the IT system to overload, notably blocking web or network services. They are usually the result of a deliberate and malicious act. How can you protect yourself?

* Set up advanced filtering rules for routers and firewalls, segment the network (Draft and enforce a Sectoral policy on Access control – External connections and Network separation).
* Configure high availability system equipment that can recognise these attempts and repel them and/or adapt accordingly.

Please consult the CIRCL file for more information in case of DDoS attacks: [https://www.circl.lu/pub/dfak/DDoSMitigation/](https://www.circl.lu/pub/dfak/DDoSMitigation/)

## Disrupted transmission of wireless communications
Disrupted transmission of wireless (WiFi) communications may be the results of a DoS attack (botnets, for example), or of a radio wave transmission problem (loss of availability). To avoid these problems, make sure that:

* the physical environment does not block communications (e.g. reinforced concrete, lead)
* the wireless access points are located in places with a lot of traffic, but remain inaccessible (e.g. located high up). (Draft and enforce a Sectoral policy on Physical and environmental security – Physical security perimeter and Rules within the perimeter)
* the signal given out from the access points is not disturbed by waves from other electromagnetic sources in the surrounding areas (radio antenna, GSM, TV)

## Wireless network tapping
Wireless (WiFi) networks do not rely on any physical media. They are transmitted through the air, meaning they can be tapped with a simple passive sensor. This may result in loss of confidentiality for your data. You can avoid this risk by making sure the following security measures are applied:

* communications must be encrypted using a secure protocol (e.g. WPA2 for WiFi) (Draft and enforce a Sectoral policy on systems development and maintenance – Use of encryption)
* The WiFi range from the access points should be limited to the physical confines of the organisation
* access to these networks must to limited to authorised users (filtered by MAC address, for example)
* the WiFi network must not be directly connected to the organisation’s internal network, but rather separated by a firewall or using a dedicated connection (Draft and enforce a Sectoral policy on access control – Network separation)

See also Securing the internal WiFi network and Securing the customer WiFi network.

## Interception of communications
A third party may intercept, corrupt or delete transmitted data (man-in-the-middle attacks) and thereby compromise the confidentiality, integrity or availability of the data. You can protect the transmission of your communications and: 

* put in place the protective measures described in “wireless network tapping”
* use encryption methods to prevent access to and corruption of transmitted data. (Draft and enforce a Sectoral policy on System development and maintenance – Use of encryption).
* separate the networks (Draft and enforce a Sectoral policy on access control – External connections and Network separation).
* ensure the cabling is inaccessible to malicious persons. (Draft and enforce a Sectoral policy on Physical and environmental security – Physical security perimeter and Rules within the perimeter).
* introduce an access rights policy (Draft and enforce a Sectoral policy on access control – Access control policy and Access rights management and Connections procedures and External connections).

Please consult the CIRCL file for more information about secure communication: [https://www.circl.lu/pub/dfak/SecureCommunication/](https://www.circl.lu/pub/dfak/SecureCommunication/)

## Network unavailability
Loss of telecommunications (loss of availability) paralyses IT systems. It is advisable to have access to a redundant source point, if possible with a second telecommunications provider using different connection equipment tested on a regular basis.

## Power cut
A power cut may cause a loss of availability for the whole IT system. Energy supply is especially vital for organisations that run ‘real-time’ operations. Guard against this threat by having:

* an alarm that sounds whenever a failure is detected in the electricity network
* a UPS for sensitive devices
* an emergency generator for vital systems
* circuit breakers to protect equipment against power surges
* a power-down procedure for IT equipment (Draft and enforce a Sectoral policy on physical and environmental security – Electrical equipment safety.)

## Discontinuity of service providers
An entity depends on its providers. Unavailability at service provider level can consequently have serious repercussions on its own operations. It is therefore preferable to provide for:

* availability (SLA service level) in the service agreement. (Draft and enforce a Sectoral policy on Physical and environmental security – Maintenance)
* service provider redundancy for downgraded modes
* the provision, by the service provider, of information (procedures, source code, technical documentation) needed to maintain activity

## Infiltrating the premises
A violation of the secure perimeters may have serious consequences on confidentiality, integrity and availability for any organisation. An ill-intentioned person with access to assets within the company could steal, sabotage or make copies of these assets, causing a lot of damage in the process. Ensure that:

* individuals’ identities can be checked on the way into and out of the building. (Draft and enforce a Sectoral policy on Physical and environmental security – Physical security perimeter and Rules within the perimeter)
* visitors and suppliers are always accompanied
* emergency exits only open from the inside
* server rooms remain locked at all times and are equipped with alarm systems and, if necessary, cameras
* a “clean desk” policy is respected (in other words, sensitive papers should be stored out of view (filing system) and workstations should be locked). (Draft and enforce a Sectoral policy on the Classification and control of resources – Classification and responsibilities for resources, as well as a Sectoral policy on physical and environmental security – Clean desk)
* when the premises are closed, an alarm system or security company should monitor the site
* badges should be worn in accordance with the badge policy and should be easily visible
* quarantine zones should be available for deliveries
