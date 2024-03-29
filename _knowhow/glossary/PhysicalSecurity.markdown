---
layout: article
title:  "Securing a Fixed Workstation"
menutitle:
logo:
date:   2017-11-06 00:00:00 +0100
short:
categories: knowhow
toc: true
ref: glossaryphysicalsecurity
lang: en
---
## In Brief

Physical security is intended to work towards the exploitation of IT equipment under optimal conditions in order to benefit from the best possible performance for the longest possible amount of time.

When talking about measures or demonstrations, the difference between preventive actions and protective actions should be highlighted.

* Preventive measures aim to avoid an incident.
* Protective measures aim to protect property in the event of an incident.

It would be foolhardy to believe that preventive measures could prevent all incidents. Even if such remediation measures are implemented, it is recommended that other protective measures should be implemented, too.

The scope of the necessary protective measures is inversely proportional to the protective measures already implemented.

## Computer/IT Room
For various reasons relating to the type of equipment, its operating equipment, its criticality, noise and heat produced, etc., it is prudent to use dedicated IT/computer rooms separated from the working areas used by employees.

There are different types of IT/computer room:

#### 'Data Centre' Computer/IT Rooms
Rooms such as this usually hold specialist equipment necessary for the provision of IT resources. They hold servers, large-scale computers, [backup]({% link _knowhow/glossary/DataBackups.markdown %}) and data restore solutions, storage bays, etc.

In most medium-sized companies, such rooms also contain critical network elements (exchanges, routers, etc.) and access points and equipment used to connect the company to the outside world (telephone switchboard, Internet access, etc.).

In most large structures, there are various specialised rooms, known as the network room, telephony room, and connections room.

In the largest computer centres, it is even possible to make the distinction between 'dead' rooms, which host equipment which requires very little human intervention (processors, storage, etc.) and 'live' rooms, hosting equipment which requires frequent human intervention (backup automation, etc.).

#### Upper Floor Connection Room
There are often rooms on upper floors used to connect equipment on that floor to the wiring leading to the main IT/computer room. These rooms usually include patch panels and floor switches.

These rooms and their connections are usually designed with maximum redundancy to prevent disruption to the fullest possible extent.

Given the criticality of this equipment, these rooms are deemed to be IT/computer rooms and are therefore subject to the same design and monitoring requirements.

## Protection Against Incidents
The prevention and protection measures detailed in this document are not intended to be exhaustive, or even obligatory in all cases. The choice of applying prevention and protection measures should come as a result of studies including risk analysis, combined with a budgetary assessment and suitable remediation measures.

To ensure the effectiveness of all the proposed prevention and protection measures, they must all be included in an organisational and procedural strategy.

The following aspects are the subject of this chapter:

* Water damage,
* Fire damage (SMEs: see [Fire]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}#fire))
* Damage relating to electricity (SMEs: see [Service interruption]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}#service-interruption), [Power cut]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}#power-cut)),
* Air-conditioning faults,
* Telecommunications incidents (SMEs: see [Denial of service attacks and Distributed denial of service attacks]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}#denial-of-servicedistributed-service), [Service interruption]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}#service-interruption), [Disrupted transmission of wireless communications]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}#disrupted-transmission-of-wireless-communications), [Network access unavailable]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}#network-unavailability), [Failure of IT or communications equipment]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware.markdown %}#failure-of-it-or-communications-equipment)),
* Physical intrusions (SMEs: see [Infiltrating the premises]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}#infiltrating-the-premises), [Insertion or removal of hardware]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware.markdown %}#addition-or-removal-of-hardware), [Device recovery]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware.markdown %}#device-recovery), [Aggravated theft]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware.markdown %}#aggravated-theft)),
* Electrostatic phenomena,
* Inaccessibility of the IT/computer centre.

#### Organisational Security Measures
* [Organisation of security]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity.markdown %})
  * [Attribution of responsibilities]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity.markdown %}#attribution-of-responsibilities)
  * [Third party access and outsourcing]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity.markdown %}#third-party-access-and-outsourcing)
* [Classification and monitoring of resources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources.markdown %})
  * [Classification of and responsibility for resources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources.markdown %}#classification-and-responsibility-for-resources)
* [Human factors]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown %})
  * [Training and information]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown %}#training-and-information)
  * [Response to incidents and security malfunctions]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown %}#response-to-incidents-and-malfunctions)
* [Physical and environmental security]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %})
  * [Physical security perimeter]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %}#physical-security-perimeter)
  * [Rules within the perimeter]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %}#rules-within-the-perimeter)
  * [Electrical equipment safety]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %}#electrical-equipment-safety)
  * [Maintenance]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %}#maintenance)
  * [Off-site equipment security]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %}#off-site-equipment-security)
  * [Disposal or reuse of equipment]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %}#disposal-and-reuse-of-equipment)
  * [Clean desk]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %}#tidy-office-policy)
* [Operational and communications aspects]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %})
  * [Documented procedures]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}#documentation-of-procedures)
  * [Data backups]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}#data-backups)
* [Access control]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %})
  * [Access control policy]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#access-control-policy)
  * [Access rights management]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#access-rights-management)
* [Managing business continuity]({% link _knowhow/cisoapproach/SecurityPolicy-ManagingBusinessContinuity.markdown %})
  * [Operational continuity]({% link _knowhow/cisoapproach/SecurityPolicy-ManagingBusinessContinuity.markdown %}#operational-continuity)
* [Compliance]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance.markdown %})
  * [Intellectual property]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance.markdown %}#intellectual-property)
  * [Protection of operational data]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance.markdown %}#protection-of-operational-data)
  * [Personal data protection]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance.markdown %}#personal-data-protection)

## Water Damage

#### Incidents
This type of incident can arise for various reasons, including:

* ruptured domestic water pipes,
* ruptured refrigeration duct,
* water ingress from the facade or roof,
* triggering of fire prevention systems,
* obstruction of wastewater drainage.

>NB:<br />
This point is all the more critical given that most IT/computer rooms are fitted with false ceilings which prevent the easy detection of an incident. Cable routing between floors also provides an easy route for water to pass, making it easy for water to disperse through all types of 'online' rooms.

#### Consequences
The [consequences]({% link _knowhow/glossary/Impact.markdown %}) will naturally depend on the scope of the incident, but the areas likely to be affected are:

* short-circuits leading to equipment service breakdown,
* electrocution hazards,
* the operation of certain alarms or other security measures,
* damage to equipment,
* corrosion of cables and connectors.

#### Countermeasures
##### Preventive

* take care when deciding which room should be used as the IT/computer room, avoiding flooding risks (avoid basements and top floors, etc.),
* avoid water running through the IT/computer room (position air-conditioning units outside the computer/IT room, etc.),
* choose routes for cabling carefully, avoiding them crossing or overhanging the computer/IT room.

##### Protective

* install leak detection systems,
* raise IT equipment off the floor, use hermetically sealed tubes for the cables,
* use sealed tubes for power cables (220 V) and network cables,
* compartmentalise the floor in such a way as to contain and direct water towards the drainage systems.

## Fire Damage

#### Fire Incident
Be it accidental or criminal, this type of incident can lead to the partial destruction of the company, and more particularly to damage to IT equipment.

#### Consequences
The consequences can be very significant at all levels of the company. Regarding the IT system, this can cause all or part of the architecture to become unavailable for a fairly long period of time. The damage is often paired with water damage caused by attempts to extinguish the fire and with damage caused by smoke.

There are different types of damage usually experienced in this way, such as:

* total or partial destruction of the IT/computer centre,
* total or partial destruction of the copper and fibre-optic cabling,
* damage relating to smoke pollution and fire extinguishers,
* physical damage to IT equipment.

#### Countermeasures
##### Preventive

* take into account neighbouring buildings,
* avoid storing flammable products in or near the computer/IT rooms,
* check the electrical circuits regularly,
* avoid 'multi-socket' plug units,
* install smoke detection systems,
* study fire propagation routes and install compartmental separation equipment (airlocks, firebreaks, etc.).

##### Protective

* introduce fire extinguishing mechanisms using chemicals which do not harm IT hardware and which cannot harm people (refer to your local fire brigade for more information),
* carefully select the emergency exits,
* ensure that nobody smokes,
* draw up and practise a disaster plan, including a fallback to a specific computer centre,
* use fireproof cabinets to store digital storage media (make sure these cabinets are kept locked).

SMEs: see [Fire]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}#fire)

## Damage Relating to Electricity

#### Incidents Relating to Electricity
Electrical incidents can manifest themselves through power disruptions due to over-voltage, drops in voltage, or even power cuts. This type of cut can affect all parts of the company and may have internal or external origins.

Unfortunately, the appearance and duration of these phenomena cannot usually be forecast, except for power cuts announced by the supplier or by the logistics service responsible for the building.

A power cut could be malicious or it could result from an unintended action, and also by natural phenomena such as storms, etc;

#### Consequences
The risk of damage depends on the severity of the power cut, as some equipment is capable of managing this type of phenomenon so as to properly complete outstanding transactions.

The consequences can be many and varied:

* loss of data,
* equipment breakdown,
* risk of fire,
* electrocution of staff.

##### Comments
Do not forget that online equipment distributed across more than one floor, along with personal computers and peripherals are also critical elements that are often sensitive power cuts. 

#### Countermeasures

* Preventive
* install lightning rods,
* fit the building with a mechanism avoiding voltage returns caused by lightning,
* implement measures aimed at avoiding 'multi-socket' plugs,
* fit critical IT. etc. with dual power-supply,
* keep up to date with designs suited to the electrical power supply (tables, power, etc.),
* make sure the power circuits have redundant electricity wiring.

##### Protective
* use UPS solutions (Uninterruptible Power Supply) with alarm software in rooms that have no emergency circuit breakers,
* set the circuits to 'no break' across the entire building and connect with sensitive machines and peripherals,
* implement emergency circuits in the event of a breakdown (generator set).

###### Comments
The effects of a power cut often continue upon restarting. When attempting to restart everything, there is often an overload that trips the fuses. A sequential restart of equipment should instead be performed.

SMEs: see

* [Service interruption]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}#service-interruption)
* [Power cut]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}#power-cut)

## Electrical Faults

#### Incidents Relating to Electrical Faults
Computer equipment is designed to work in specific environments to avoid the following incidents:

* water or network current supply fault,
* cooling system malfunction or breakdown,
* effects of direct sunlight.

#### Consequences
Normal operating conditions should be respected at all times; otherwise, several malfunctions could arise that are difficult to diagnose. However, the usual consequences of an air-conditioning breakdown are as follows:

* need to shut down and cyclically restart the equipment,
* premature wear to IT components,
* deterioration of UPS backup batteries. 

#### Countermeasures
##### Preventive

* implement mechanisms to limit direct sunlight,
* install a backup ventilation system with sufficient capacity to cater for current and future needs,
* introduce a temperature control solution fitted with an alert module.

##### Protective

* install a physical access control mechanism in IT/computer rooms,
* implement a backup procedure (for use in restricted mode), enabling the non-critical elements of your IT infrastructure to be shut down. 

## Telecommunications Incidents

#### Incidents

We can cite the following, among such incidents:

* sabotage,
* breakdown or loss of equipment,
* signal disruption,
* breakage of connecting channels,
* breakdown in a supplier’s service,
* breakdown of a telephone exchange.

This heading includes incidents which directly affect physical elements, such as logical intrusions on IT systems. These, however, are not the subject of this section.

#### Consequences
The impact depends on the usage that is made of the services affected in the critical production chains. The consequences are as follows:

* breakdown in the operation of certain software,
* isolation of the company from the outside world,
* potential corruption of data,
* deactivation of certain monitoring mechanisms (video, alarm, etc.). 

#### Countermeasures
##### Preventive

* carefully protect the telecommunications rooms,
* fit sheathing to external connections (shielding, warning, terminals, etc.),
* separate strong current, weak current and air-conditioning ducts,
* protect communications equipment (antennas, etc.) against lightning.

##### Protective

* fit 'dual' links with separate access paths, through two central pathways,
* duplicate any critical equipment and set up load distribution systems,
* install emergency connections where possible,
* use more than one operator capable of ensuring transfers in the event of a breakdown in service.  

SMEs: see

* [Service interruption]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}#service-interruption)
* [Denial of service attacks and distributed denial of service attacks]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}#denial-of-servicedistributed-service)
* [Disrupted transmission of wireless communications]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}#disrupted-transmission-of-wireless-communications)
* [Network access unavailable]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}#network-unavailability)
* [Failure of IT or communications equipment]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware.markdown %}#failure-of-it-or-communications-equipment)

## Physical Intrusions

#### Incidents
The entry of unauthorised people in IT/computer rooms (and in the company’s premises) can lead to many unwanted situations, including:

* [theft of hardware]({% link _knowhow/glossary/PhysicalTheft.markdown %}),
* loss of confidentiality,
* sabotage.

#### Consequences
The [consequences]({% link _knowhow/glossary/Impact.markdown %}) can be as follows:

* loss of reputation (credibility damaged in the event of the disclosure of highly confidential information, etc.),
* direct financial losses (destruction of crucial data, computer systems disabled, etc.),
* time wasted (attempts to re-establish destroyed data, etc.).

#### Countermeasures
Particularly in this area, it is crucial to frame everything with organisational, procedural and audit measures.

##### Preventive

* implement general protection for the building (shielding, 'bunker', etc.) limiting the number of opening elements (windows, doors, etc.),
* use a movement and intrusion detection service linked to a 24-hour control room,
* introduce access control (badge, biometrics, etc.) enabling all access to critical areas to be controlled and traced,
* introduce a visitor identification policy.

#### Protective

* Use anti-theft mechanisms for peripherals and personal or laptop computers,
* make sure the tidy office policy is being followed – this is a very important measure to counter the risk of data and hardware theft,
* implement video surveillance.

##### Comments
Before implementing these surveillance measures, please seek authorisation from the National Committee for Data Protection ([Commission Nationale pour la Protection des Données](https://cnpd.public.lu/en.html)).

SMEs: see

* [Infiltrating the premises]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}#infiltrating-the-premises)
* [Insertion or removal of hardware]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware.markdown %}#addition-or-removal-of-hardware)
* [Device recovery]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware.markdown %}#device-recovery)
* [Aggravated theft]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware.markdown %}#aggravated-theft)

## Electrostatic Phenomena

#### Incident
This section deals with all types of electromagnetic and electrostatic phenomena.

This issue can originate from a source outside the company, such as weather phenomena, radio waves or miscellaneous electrical devices. The source can also be related to the building.

#### Consequences
The consequences can be as follows:

* random malfunctions,
* corruption of data stored on magnetic storage media.

##### Comments
Another phenomenon is the use of radiation emitted by the computer system to intercept data. Such is the case with wireless networks, for example.

#### Countermeasures
##### Preventive

* keep IT/computer rooms (processing and connections) away from electrical facilities, lifts/elevators and other sources of electrical disturbance,
* use fibre optics in vertical links (e.g.: between different floors), in order to limit risks,
* ground all equipment – not just computer components,
* take care of the choice of floor covering.

##### Protective
* wear grounding straps when working on any computer architecture.

## Inaccessibility of the IT/Computer Centre

#### Incidents
Access to the computer/IT centre can be blocked for reasons such as:

* natural disasters and terrorist attacks,
* legal ruling following an incident,
* demonstrations, rioting and social movements.

#### Consequences
There can be a number of different consequences to any loss of accessibility:

* halt to the operation of a processing centre,
* changes in the proper operation of equipment – especially sensitive equipment.

#### Countermeasures
##### Preventive

* set up your sites in places with a lower risk of natural disaster,
* set up protection against any intrusion.

##### Protective

* set up a secure remote control solution,
* plan for a backup site.
