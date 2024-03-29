---
layout: article
title:  "Physical Faults"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: knowhow
toc: true
ref: glossaryphysicalfaults
lang: en
---
## In Brief
By physical failures, we mean the disruption of the service or the faulty operation of one or more physical elements that make up the IT system.

## Possible Causes
There are as many causes as elements or layers are making up the IT system in question. However, we will try to distinguish between: 

#### Software Faults and Equipment Faults
There are faults which have a direct effect on a physical element of the system and those which affect the software layer of the physical elements. Most electronic equipment is run by software. Faults in the software layer may make the equipment inoperable or even destroy it.

#### Environment
In many cases, the inoperability of the IT elements is due to the lack of suitable conditions for them to work correctly. The environment in which the IT equipment is located may be affected by external factors, such as:

* [Power cuts]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}#power-cut)
* Problems with the air conditioning, resulting in overheating
* [Fire]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}#fire)
* [Service interruption]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}#service-interruption)
* [Disrupted transmission of wireless communications]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}#disrupted-transmission-of-wireless-communications)
* [Network unavailability ]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}#network-unavailability)
* [Discontinuity of service providers]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}#discontinuity-of-service-providers)

The environment may lead to the unavailability of the system, but may also cause physical faults at component level.

## Possible Impacts
The estimation of damage incurred is going to depend on the domains affected by the physical fault or faults, as well as by the ability to deal with any corruption of the data and systems.

#### Loss of Equipment
Equipment which has suffered a fault sometimes needs to be replaced. The direct cost is therefore equivalent to the cost of purchasing and setting up the new equipment.

We strongly advise against the use of hybrid or highly proprietary technologies, the replacement of which may lead to additional costs or an obligation to review the system entirely.

#### Data Loss
If no preventative measures are installed before the disruption to the service, significant damage may be caused by the loss of data.

## Categories
The classification of physical faults is based on the part of the system that is directly affected and differentiates between:

#### Faults Affecting Calculation Functions
This category includes all faults that prevent data from being properly processed by a server or a personal computer. Disruption at this level applies to physical elements such as:

* the memory
* the processor
* the motherboard.

#### Faults Affecting Storage Systems
This category includes all disruptions that affect access to data, whether in editing or read-only mode.

## Vulnerabilities Exploited
In this context, this means events that occur inevitably and which are associated with the fallible nature of an IT system’s components. There are only limited ways of preventing the occurrence of such a breakdown, e.g. correct maintenance of the systems and devices. However, as explained below, measures can be taken to limit the impact caused.

## Preventative Measures
The primary preventative measures aiming to limit physical faults are:

#### Setting up an Organised IT Room
All critical elements of the IT system must operate under optimal conditions. This begins with the provision of an IT room, as well as rooms reserved for 'connectivity' equipped with services such as 'no break' (permanent power supply), UPS systems, air conditioning, a fire detection system, and controlled access. Draft and enforce a Sectoral policy on [Physical and environmental security]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %}) – [Physical security perimeter]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %}#physical-security-perimeter) and [Rules within the perimeter]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %}#rules-within-the-perimeter) and [Electrical equipment safety and Maintenance]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %}#electrical-equipment-safety).

#### Design of a 'Fault Tolerance' Redundant Architecture
When designing an IT architecture, there are ways to protect it against physical faults in such a way as to make any service disruption of one or the other of the components 'transparent'.

This redundancy can be implemented at one of the following levels:

* cabling
* telecommunications network (HSRP – Hot Standby Router Protocol)
* server (Clustering)
* storage (RAID – Redundant Array of Inexpensive/Independent Disks)

#### Ability to Respond to Incidents
Set up internal skill sets to respond to incidents. Draft and enforce a Sectoral policy on [Human factors]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown %}) – [Training and information]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown %}#training-and-information) and [Responding to incidents and security malfunctions]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown %}#response-to-incidents-and-malfunctions).

#### A Functional Archiving Policy
In order to limit the risk of [loss of data]({% link _knowhow/glossary/DataLoss.markdown %}) as much as possible, the implementation and application of data archiving procedures, both at server level and on personal computers, is strongly recommended. Draft and enforce a Sectoral policy on [Operational and communication aspects]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}) – [Data backups]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}#data-backups).

#### Choice of Standards
The choice of proprietary solutions, which may initially appear enticing, may become a real 'nightmare' when one element or another that is no longer in production needs to be replaced. The risk could run as far as the need to completely review and replace the processing chain, should a physical element break down. It is, therefore, advisable to use standard elements fabricated by a large number of manufacturers wherever possible.
