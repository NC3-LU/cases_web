---
layout: article
title: "Assets"
menutitle:	
logo:
date: 2017-11-06 00:00:00 +0100
short: "Security Measures"
categories: knowhow
toc: true
ref: glossaryassets
lang: en
---

## In Brief
By ‘Assets’, we mean goods or services which are valuable for the company. Assets have some [vulnerabilities]({% link _knowhow/glossary/Vulnerabilities.markdown %}), which can be exploited by threats that will have [impacts]({% link _knowhow/glossary/Impact.markdown %}) on the company. To protect those assets, the company should take some security measures. These are selected during the [risk management]({% link _knowhow/bestpractices/RiskManagement.markdown %}) phase.

Two types of assets could be distinguished:

* Primary assets: processes and information

* Support assets: all other assets, like people, equipment, etc. 

## Primary Assets
Primary assets are business processes as well as information related to the company. Each primary asset has a certain [criticality]({% link _knowhow/cisoapproach/SecurityPolicy-Classification.markdown %}) for the company. That is we have some business processes which are more or less important, whereas some other where [integrity]({% link _knowhow/glossary/Integrity.markdown %}) has a more important part than [confidentiality]({% link _knowhow/glossary/Confidentiality.markdown %}) (surveying office), and so on. It pertains to information as well. Some of them are really important, while others are not. Confidentiality is more important than [availability]({% link _knowhow/glossary/Availability.markdown %}) regarding certain pieces of information.

The [risk analysis]({% link _knowhow/bestpractices/RiskManagement.markdown %}#risk-estimation) is calculated with the criticality of primary assets. Support assets which are necessary to achieve business process inherit the criticality assigned to primary assets. 

## Support Assets
EBIOSv2 gives us a categorisation of entities and support assets of seven different types:

1. MAT: Hardware

2. LOG: Software

3. RES: Network

4. PER: Personnel

5. PHY: Infrastructure

6. ORG: Organisation

7. SYS: System

## Hardware

‘Hardware’ consists of all physical elements of an information system (SME: [See the threats to hardware]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware.markdown %})).

* MAT_ACT: Data Processing Equipment (active)
Automatic information processing equipment that includes the items it requires to operate independently.

  * MAT_ACT.1: Transportable Equipment
Computer equipment designed to be carried by hand and used in different places.

  * MAT_ACT.2: Fixed Equipment
Computer equipment that belongs to the organisation or used in the organisation’s premises.

  * MAT_ACT.3: Processing Peripheral
Equipment connected to a computer via a communication port (serial, parallel link, etc.) for entering, conveying or transmitting data.

* MAT_PAS: Data Medium (passive)
These are media for storing data or functions.

  * MAT_PAS.1: Electronic Medium
An information medium that can be connected to a computer or computer network for data storage. Despite their compact size, these media may contain a large amount of data. They can be used with standard computing equipment.

  * MAT_PAS.2: Other Media
Static, non-electronic media containing data.

## Software

‘Software’ consists of all the programs contributing to the operation of a data processing set (SME: [See the threats to software]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Software.markdown %})).

* LOG_OS: Operating System
This title includes all the programs of a computer making up the operational base from which all the other programs (services or applications) are run. It includes a kernel and basic functions or services. Depending on the architecture, an operating system may be monolithic or made up of a micro-kernel and a set of system services. The main components of the operating system are the equipment management services (CPU, memory, discs, peripherals and network interfaces), task or process management services, and user and user rights management services.  

* LOG_SRV: Service, Maintenance or Administration Software
Software characterised by the fact that it complements the operating system services and is not directly at the service of the users or applications (even though it is usually essential or even indispensable for the global operation of the information system).

* LOG_STD: Package Software or Standard Software
Standard software or package software is a complete product commercialised with medium, release, and maintenance. They provide ‘generic’ services for users and applications, but are not personalised or specific in the way that business applications are.

* LOG_APP: Business Application

  * LOG_APP .1: Standard Business Application
This is commercial software designed to give users direct access to the services and functions they require from their information system in their professional context. There is a very wide, theoretically limitless, range of fields.

  * LOG_APP .2: Specific Business Application
This is software in which various aspects (primarily support, maintenance, upgrading, etc.) have been specifically developed to give users direct access to the services and functions they require from their information system in their professional context. There is a very wide, theoretically limitless, range of fields.

## Networks

‘Network’ consists of all telecommunication devices to interconnect several physically remote computers or components of an information system. 

* RES_INF: Medium and Supports
Communication and telecommunication media or equipment are characterised mainly by the physical and technical characteristics of the equipment (point-to-point, broadcast) and by the communication protocols (link or network - levels 2 and 3 of the OSI 7-layer model).

* RES_REL: Passive or Active Relay
This sub-type includes all devices that are not the logical terminations of communications (IS vision), but are intermediate or relay devices. These relays employ ad hoc hardware, and often ad hoc software. They are characterised by the supported network communication protocols. In addition to the basic relay, they often include routing and/or filtering functions and services, employing communication switches and routers with filters. They can often be administrated remotely and are sometimes capable of generating logs.

* RES_INT: Communication Interface
They are the communication interfaces of the processing units, but characterised by the media and supported protocols. They have installed filtering, log creation or warning generation functions. Also, there is a requirement for the possibility of remote administration.

## Personnel

‘Personnel’ consists of all the groups of persons involved in the information system (SME: [See the threats to human resources]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2HR.markdown %})).

* PER_DEC: Decision Maker
Decision makers are the owners of the essential elements (information and functions) and the line managers of the organisation or specific project.

* PER_UTI: Users
Users are the personnel who handle sensitive elements in the context of their activity and who have a special responsibility in this respect. They may have special access rights to the information system to carry out their everyday tasks.

* PER_EXP: Operator/Maintenance
They are the personnel in change of operating and maintaining the information system. They have special access rights to the information system to carry out their everyday tasks.

* PER_DEV: Developer
Developers are in charge of developing the organisation’s applications. They have access to part of the information system with high-level rights but do not take any action on the production data.

## Organisation

‘Organisation’ describes the organisational framework, consisting of all the personnel structures assigned to a task and the procedures controlling these structures.

* ORG_DEP: Higher-Tier Organisation
These are organisations on which the studied organisation depends. They may be legally affiliated or external. This imposes constraints on the studied organisation in terms of regulations, decisions, actions or reporting of information.

* ORG_GEN: Structure of the Organisation
This consists of the various branches of the organisation, including its cross-functional activities, under the control of its management.

* ORG_PRO: Project or System Organisation
This concerns the organisation set up for a specific project or service. 

* ORG_EXT: Subcontractors/Suppliers/Manufacturers
An organisation providing the organisation with a service or resources and bound to it by contract.

## Site

‘Site’ comprises all the places containing the system, or part of the system, and the physical means required for it to operate (SME: [See the threats to the infrastructure]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %})).

* PHY_LIE: Places
Perimeters, physical enclosures.

  * PHY_LIE.1: External environment
This concerns all the places in which the organisation’s means of security cannot be applied.

  * PHY_LIE.2: Premises
This place is bounded by the organisation’s perimeter directly in contact with the outside. This may be a physical protective boundary obtained by creating physical barriers or means of surveillance around buildings.

  * PHY_LIE.3: Zone
A zone is formed by a physical protective boundary forming partitions within the organisation’s premises. It is obtained by creating physical barriers around the organisation’s information processing infrastructures.

* PHY_SRV: Essential Service
All the services required for the organisation’s equipment to operate. 

  * PHY_SRV.1: Communication
Telecommunication services and equipment provided by an operator.

  * PHY_SRV.2: Power
Services and means (sources and wiring) required for providing power to information technology equipment and peripherals.

  * PHY_SRV.3: Cooling/Pollution
Services and means (equipment, control) for cooling and purifying the air.

## System

‘System’ consists of all specific facilities linked to information technologies, with a specific objective and operational environment. It is composed of various entities belonging to other types described above.

* SYS_INT: Internet Access Device
A device that dials the interconnection between the organisation’s network and the Internet network and provides access services to or from the Internet.

* SYS_MES: Electronic Messaging
A device allowing authorised users to type, query and send computerised documents or electronic messages from or to computers connected to the network.

* SYS_ITR: Intranet
Shared and private data and information services, using communication protocols and core technologies (Internet technology for example).

* SYS_ANU: Company directory
A device for managing and accessing a database describing the company’s personnel and their characteristics.

* SYS_WEB: External Portal
An external portal is a point of access that a user will find or use when he looks for information or a service provided by the organisation. Portals provide a wide range of resources and services.
