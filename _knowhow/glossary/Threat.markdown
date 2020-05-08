---
layout: article
title:  "Threat"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short: "Security Measures"
categories: knowhow
toc: true
ref: glossarythreat
lang: en
---

Threats exploit asset vulnerabilities and create impact. The interactions between assets, threats, and vulnerabilities are analysed during risk management. 

It is impossible for an organisation to completely exclude the existence of threats. In terms of security, we therefore generally apply EBIOSv2.

## EBIOSv2
EBIOS: Expression of Needs and Identification of Security Objectives (Expression des Besoins et Identification des Objectifs de Sécurité).

## Threats by Groups
EBIOSv2 [1] offers a list of generic Threatening Agents (e.g. threats):

### **PHYSICAL DAMAGE**
* Fire (SME: see [Fire]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}#fire))
* Water damage
* Pollution
* Major disaster
* Destruction of equipment or supports (SME: see [Computer or communication equipment broken down]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware.markdown %}#failure-of-it-or-communications-equipment))
* Dust, corrosion, frost

### **NATURAL EVENTS**
* Climatic phenomenon
* Seismic phenomenon
* Volcanic phenomenon
* Meteorological phenomenon
* Flood

### **LOSS OF ESSENTIAL SERVICES**
* Air conditioning failure
* Energy Power Loss (SME: see [Power Failure]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}#power-cut))
* Loss of telecommunication (SME: see [Unavailable network access]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}#network-unavailability), [Interruption of communications]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}#interception-of-communications) and [Discontinuity of service providers]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}#discontinuity-of-service-providers))

### **DISTRIBUTION DUE TO RADIATION**
* Electromagnetic radiation
* Thermal radiation
* Electromagnetic pulses (EMI)

### **COMPROMISING INFORMATION**
* Interception of compromising spurious signals
* Remote spying (SME: see [Interception of communication]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}#interception-of-communications) and [Spam/Phishing and Measures against malicious code]({% link _knowhow/bestpractices/MaliciousSoftwareBP.markdown %}))
* Passive listening (SME: see [Listening to wireless networks]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}#wireless-network-tapping))
* Theft of media or documents (SME: see [Robbery]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware.markdown %}#aggravated-theft) and [Penetration in premises]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}#infiltrating-the-premises))
* Theft of equipment (SME: see [Robbery]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware.markdown %}#aggravated-theft) and [Penetration in premises]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}#infiltrating-the-premises))
* Recovery of recycled or discarded media (SME: see [Recovery of media]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware.markdown %}#device-recovery))
* Disclosure (SME: see [Social engineering/Inadequate communication]({% link _knowhow/glossary/SocialEngineering.markdown %}))
* Information without guarantee of origin
* Equipment trapping
* Software trapping (SME: see [Measures against malicious codes]({% link _knowhow/glossary/MaliciousCodes.markdown %}))
* Geolocation

### **TECHNICAL FAILURES**
* Hardware failure (SME: see [Computer or communication equipment broken down]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware.markdown %}#failure-of-it-or-communications-equipment) and [Damage to equipment during transport]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware.markdown %}#hardware-damaged-during-transport)))
* Equipment malfunction (SME: [Insertion or removal of equipment]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware.markdown %}#addition-or-removal-of-hardware))
* Information system saturation
* Software malfunction
* Attack on the maintainability of the information system (SME: see [Unusable backups]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware.markdown %}#unusable-backups), [Impossible administration]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2HR.markdown %}#the-administrator) and [Inappropriate software environment]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Software.markdown %}#unsuitable-software-environment))

### **UNAUTHORISED ACTIONS**
* Illegal use of equipment (SME: see [Abuse of organisation resources]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2HR.markdown %}#misuse-of-it-resources))
* Fraudulent copying of software (SME: see [Use of unauthorised software]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Software.markdown %}#use-of-unapproved-software))

## Threat Qualification
EBIOSv2 threats can be classified according to:

### **THEIR ORIGIN**
* E: Environmental - all incidents that are not caused by human actions
* D: Deliberate - for all deliberate actions targeting assets
* A: Accidental - used for all human actions that can accidentally damage assets

### **THEIR ATTACK**
* D: Availability
* I: Integrity
* C: Confidentiality

### **THEIR TYPE**
* N: Natural
* H: Human
* E: Environmental

## Vulnerabilities/Threats/Assets Link
This section refers to the generic vulnerabilities of the EBIOS v2 document - Section 4 - Tools (Assessment). 

We can identify:

## Security Goals
Section 2 Generic security objectives of the EBIOS v2 document - Section 5 - Tools (Processing) [4] proposes for each of the 7 types of high-level entities/[assets]({% link _knowhow/glossary/Assets.markdown %}) a list of generic security objectives effectively addressing the identified generic [vulnerabilities]({% link _knowhow/glossary/Vulnerabilities.markdown %}) previously.

Section 3.2 Requirements from ISO 17799 of the same EBIOS v2 document - Section 5 - Tools (Processing) [5] proposes safety requirements related to each of the clauses of ISO/IEC 17799: 2000 (and not the version of the standard published in 2005 [ISO/IEC 27002: 2005]({% link _publications/ISO27000SF.markdown %})).

## EBIOS 2010
EBIOS 2010 [6] offers a different presentation from version 2, both in terms of the presentation of threats and the overall approach. 

EBIOS 2010 is divided into the following areas:

### **TYPES OF SUPPORT GOODS**
* SYS - IT and telephony systems
* ORG - Organisations
* LOC - Premises

## IMPACTS
* Impacts on the operation
* Human impacts
* Impacts on property
* Other impacts

### **SOURCES OF THREATS**
* Human sources
  * Malicious deliberate
	* Internal (human) source 
		* Weak capacities
		* Important capacities
		* Unlimited capacities
	* External (human) source
		* Low capacities
		* Important capacities
		* Unlimited capacities
  * Accidental without intention to harm
	* Internal (human) source
		* Low capacities
		* Important capacities
		* Unlimited capacities
	* External (human) source
		* Low capacities
		* Important capacities
		* Unlimited capacities
	* Non-human sources
	
## MEHARI Threats by Threat Group
* Natural disasters
  * Fire
  * Water damage
  * Natural disasters
* Industrial disasters
  * Fire
  * Water damage
  * Industrial disasters
  * Mechanical pollution
  * Electromagnetic pollution
  * Physical or logical failure
  * Power cut
  * Inadequate temperature and/or humidity conditions
  * Communication services failure
  * Interruption of other essential services and supplies
  * Degradation of information storage media
  * Electromagnetic emanations
* Unintended errors and failures
  * User errors
  * Administrator errors
  * Control errors (log)
  * Configuration errors
  * Organizational deficiencies
  * Diffusion of harmful software
  * Redirection errors
  * Sequence errors
  * Information leaks
  * Information alteration
* Introduction of false information
  * Information degradation
  * Information destruction
  * Disclosure of information
  * Program vulnerabilities (software)
  * Maintenance/program update errors (software)
  * Equipment maintenance/updating errors
  * System collapse caused by resource depletion
  * Loss of equipment
  * Staff unavailability
* Deliberate attacks
  * Configuration manipulation
  * Beating user identity
  * Abuse of access privileges
  * Unintended use
  * Diffusion of harmful software
  * Message redirection
  * Sequence alteration
  * Unauthorised access
  * Traffic analysis
  * Repudiation
  * Information interception (listening)
  * Modification of information
  * Introduction of false information
  * Information corruption
  * Disclosure of information
  * Program manipulation
  * Refusal of service
  * Theft of equipment
  * Destructive attack
  * Enemy occupation
  * Staff unavailability
  * Extortion
  * Social engineering
