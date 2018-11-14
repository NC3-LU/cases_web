---
layout: knowhow
title:  "Security Policy – Operational and communication aspects"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: f-ciso
toc: true
ref: cisooperationalcommunicationaspects
lang: fr
---
## Documentation of procedures
All operations concerning the processing of information must be documented. This applies to planned processing (batches), system shut-downs and restarts and data backup procedures.

In addition to the everyday operations to be carried out, these procedures must specify:

* the instructions in case of error
* start-up conditions
* what to do with the output (listings, print-outs, etc.)
* ...

The procedures are updated by the IT manager and saved in specific, easily accessible locations. It goes without saying that the employees concerned must know about these procedures and follow them.

The attached section is optional, but important for organisations that use servers. Nevertheless, documenting at least the backup procedures still applies in all other cases.

### Applying security measures to:

* file servers
* email servers
* potentially to describe the installation of new computers and laptops (‘Ghost’)

### Directly associated organisational measures:

* [Organisation of security]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity_fr.markdown %})
  * [Attribution of responsibilities]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity_fr.markdown %}#attribution-of-responsibilities)

## Separation of environments
It is preferable to separate devices that deal with software development activities or test activities from those on which products in production are installed.

This separation aims to limit the risk of modifications to actual data.

The use of production data located in test environments (which tend to be less well protected) is, in fact, not recommended.

In particular if critical data (from the point of view of [confidentiality]({% link _knowhow/glossary/Confidentiality_fr.markdown %})), trade secrets or personal data is processed there.

### Applying security measures to:

* Servers that run applications (accounting, Customer Relationship Management, Stock Management, etc.) if the organisation is making or testing developments.

### Directly associated organisational measures:

* [Classification and monitoring of resources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %})
  * [Classification of and responsibility for resources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %}#classification-and-responsibility-for-resources)
* [Compliance]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %})
  * [Protection of operational data]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %}#protection-of-operational-data)
  * [Personal data protection]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %}#personal-data-protection)

## Outsourcing of resource management
With regard to resources managed by external companies, it is important to first assess the organisation’s critical security points and indicate the specific management measures in the service agreement.

Here, we talk about “outsourcing” or “facilities management”.

### Applying security measures to:
* Computers and servers that are managed by external companies. In the case of remote management, it is very important to provide specific terms for access controls (see [External connections]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#external-connections)).

## Protection against malware
An attack by a virus or other [malicious software]({% link _knowhow/glossary/MaliciousCodes_fr.markdown %}) is one of the most likely risks for any computer user. They can infiltrate the “organisation” through [removable devices]({% link _knowhow/glossary/RemovableDevices_fr.markdown %}), such as, in particular, CD-ROMs,

The “organisation’s” computers and servers must be equipped with [antivirus software]({% link _knowhow/glossary/AntiVirus_fr.markdown %}). The IT manager is responsible for installing these tools on each device and ensuring they are always up to date. This concerns both the users’ workstations and the servers (see [security measures for file servers]({% link _publications/recommendationsecuring/Recommendations4securingWebServer_fr.markdown %}) and [security measures for email servers]({% link _publications/recommendationsecuring/Recommendations4securingEmailServer_fr.markdown %})).

On the other hand, a large number of measures must be respected by the users to avoid compromising security. It is prohibited to:

* prevent the antivirus tools from running (deactivating them, reconfiguring them, turning off updates, etc.);
* install software that has not been approved by the IT manager (SMEs: see [Use of unapproved software]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Software_fr.markdown %}#use-of-unapproved-software));
* launch programs or files received by email sent unsolicited to the recipient, even if they know the sender (SMEs: [see Social engineering/Inadequate communication]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2HR_fr.markdown %}#manipulation-of-people) and [Handling malicious codes]({% link _knowhow/glossary/MaliciousCodes_fr.markdown %})). Such emails must be destroyed and advice may be requested from the IT manager.

Incoming email verification tools deal not only with viruses, but can also eliminate potentially dangerous attachments (executables, scripts, macros).

### Applying security measures to:

* [File servers]({% link _publications/recommendationsecuring/Recommendations4securingWebServer_fr.markdown %})
* [Email servers]({% link _publications/recommendationsecuring/Recommendations4securingEmailServer_fr.markdown %})
* [Computers connected to the Internet]({% link _publications/recommendationsecuring/SecuringFixedWorkstation_fr.markdown %})
* [Laptop computers]({% link _publications/recommendationsecuring/SecuringLaptops_fr.markdown %})

### Behavioural measures:

* [Malicious software – best practice]({% link _knowhow/glossary/MaliciousCodes_fr.markdown %})
* [Emails]({% link _knowhow/bestpractices/EMail-BestPractices_fr.markdown %})
* [Removable devices]({% link _knowhow/glossary/RemovableDevices_fr.markdown %})
* [Malicious websites]({% link _knowhow/glossary/MaliciousWebsites_fr.markdown %})

### Directly associated organisational measures:

* [Classification and monitoring of resources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %})
  * [Classification of and responsibility for resources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %}#classification-and-responsibility-for-resources)
* [Human factors]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %})
  * [Training and information]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %}#training-and-information)
  * [Response to incidents and security malfunctions]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %}#response-to-incidents-and-malfunctions)
* [Operational and communications aspects]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %})
  * [Email]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#email)
* [Access control]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %})
  * [Access control policy]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-control-policy)
  * [Use of external networks]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#use-of-external-networks)
  * [Separation of networks]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#separation-of-networks)
* [Development and maintenance of systems]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %})
  * [Management of technical vulnerabilities]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}#managing-technical-vulnerabilities)
* [Management of security incidents]({% link _knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents_fr.markdown %})
  * [Reporting information security events]({% link _knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents_fr.markdown %}#reporting-information-security-events)
  * [Incident management and improvements information security]({% link _knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents_fr.markdown %}#incident-management-and-improvements-information-security)
*[Managing business continuity]({% link _knowhow/cisoapproach/SecurityPolicy-ManagingBusinessContinuity_fr.markdown %})
  * [Operational continuity]({% link _knowhow/cisoapproach/SecurityPolicy-ManagingBusinessContinuity_fr.markdown %}#operational-continuity)


### Technical measures:

* [Antivirus]({% link _knowhow/glossary/AntiVirus_fr.markdown %})
* [Firewall]({% link _knowhow/glossary/Firewall_fr.markdown %})
* [Network segmentation]({% link _knowhow/glossary/NetworkSegmentation_fr.markdown %})
* [Patches]({% link _knowhow/glossary/Patches_fr.markdown %})
* [Backups]({% link _publications/ProtectingYourCompany_fr.markdown %}#data-backups)
* [Cryptography]({% link _knowhow/glossary/Cryptography_fr.markdown %})

## Data backups
It is essential for an organisation to back up their data and their specific, or specifically configured, software. A disaster (fire, flood) or, more commonly, a hard drive problem could easily destroy all of this information. (SMEs: see [Fire]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure_fr.markdown %}#fire) and [Failure of IT or communications equipment]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware_fr.markdown %}#failure-of-it-or-communications-equipment) and [Hardware damaged during transport]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware_fr.markdown %}#hardware-damaged-during-transport)).

In the event of a large disaster, equipment that has been destroyed can usually be replaced; however, it is often impossible to reproduce lost data, which may lead to a company’s closure.

Backing up important or crucial information ([classification]({% link _knowhow/cisoapproach/SecurityPolicy-Classification_fr.markdown %})) should be done at a regularity compatible with the level of importance of the *organisation’s* activities.

The backup cycle can take place at 3 levels, depending on the type of information. A daily backup on a device that is reused weekly (Monday’s backup erases the backup from Monday of the previous week, for example). A weekly backup with a cycle of 4 to 5 weeks. A monthly backup with an annual cycle. The weekly backup can in fact be turned into a monthly backup once a month (the last day of the month). The last annual backup is archived “indefinitely” in case of legal requirements.

The weekly and monthly backups must be stored in a specific location that guarantees the same security conditions as those used in the security perimeter, if possible at a remote location.

Unused devices must be erased or destroyed. This applies to all media, whether digital, paper or otherwise (SMEs: see [Disposal]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#disposal-and-reuse-of-equipment) and [Device recovery]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware_fr.markdown %}#device-recovery) and [Aggravated theft]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware_fr.markdown %}#aggravated-theft)).

Data backups can also be useful in the event of human error (SMEs: see [Human errors]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %})), in order to restart the IT system from a previously reliable position. A data recovery procedure is necessary in this case and, additionally, it will give you an opportunity to test the procedure. In fact, the procedures should be tested annually.

### Applying security measures to:

* [File servers]({% link _publications/recommendationsecuring/Recommendations4securingWebServer_fr.markdown %})
* [Email servers]({% link _publications/recommendationsecuring/Recommendations4securingEmailServer_fr.markdown %})
* [Computers connected to the Internet]({% link _publications/recommendationsecuring/SecuringFixedWorkstation_fr.markdown %})
* [Laptop computers]({% link _publications/recommendationsecuring/SecuringLaptops_fr.markdown %})

### Directly associated organisational measures:

* [Organisation of security]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity_fr.markdown %})
  * [Attribution of responsibilities]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity_fr.markdown %}#attribution-of-responsibilities)
* [Classification and monitoring of resources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %})
  * [Classification of and responsibility for resources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %}#classification-and-responsibility-for-resources)
* [Physical and environmental security]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %})
  * [Physical security perimeter]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#physical-security-perimeter)
  * [Off-site equipment security]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#off-site-equipment-security)
* [Operational and communications aspects]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %})
  * [Documented procedures]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#documentation-of-procedures)
  * [Device security during transport]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#device-security-during-transport)
* [Access control]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %})
  * [Access control policy]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-control-policy)
  * [Access rights management]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-rights-management)
* [Managing business continuity]({% link _knowhow/cisoapproach/SecurityPolicy-ManagingBusinessContinuity_fr.markdown %})
  * [Operational continuity]({% link _knowhow/cisoapproach/SecurityPolicy-ManagingBusinessContinuity_fr.markdown %}#operational-continuity)

### Technical measures:

* [Data backups]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#data-backups)

## Device security during transport
When transporting or sending devices containing the “organisation’s” data, it is important to take the following measures into account, depending on the level of importance of the data (SMEs: see [Hardware damaged during transport]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware_fr.markdown %}#hardware-damaged-during-transport)):

* use specific packaging (which leaves traces of forced opening)
* use a briefcase with a combination lock
* have a member of the “organisation” transport the delivery
* encrypt the data

### Applying security measures to:

* The transportation of backups
* Communication by email
* Communication by Internet (FTP, etc.)[

### Organisational measures:

* [Classification and monitoring of resources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %})
  * [Classification of and responsibility for resources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %}#classification-and-responsibility-for-resources)
* [Development and maintenance of systems]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %})
  * [Use of encryption]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}#encryption)

### Technical measures:
* [encryption]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}#encryption)

## Email
Email that is transmitted across the Internet can in no way be considered a secure means of communication. This is because the email may be accidentally sent to the wrong recipients, or be edited or read by a third party. As a result, any operation for which the “organisation” is responsible would be better confirmed by an additional means (telephone, letter, fax, etc.). This would prevent recipient error or changes to prices or quantities on orders, for example. (good email practices)

Avoid sending confidential information by email. If applicable, use an approved encryption tool with your correspondents.

The “organisation’s” messaging system is intended for professional use. Moderate personal use may be tolerated. The user is held personally responsible in the case of the criminal use of tools. Please note that, in response to traceability restrictions, it is possible that part or all of the messages exchanged by members of the “organisation” will be saved. (SMEs: see [Misuse of organisation’s resources]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2HR_fr.markdown %}#misuse-of-it-resources))

### Applying security measures to:

* [Email servers]({% link _publications/recommendationsecuring/Recommendations4securingEmailServer_fr.markdown %})
* [Computers connected to the Internet]({% link _publications/recommendationsecuring/SecuringFixedWorkstation_fr.markdown %})
* [Laptop computers]({% link _publications/recommendationsecuring/SecuringLaptops_fr.markdown %})

### Behavioural measures:

* [Best practice concerning email]({% link _knowhow/bestpractices/EMail-BestPractices_fr.markdown %})

### Directly associated organisational measures:

* [Classification and monitoring of resources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %})
  * [Classification of and responsibility for resources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %}#classification-and-responsibility-for-resources)
* [Human factors]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %})
  * [Training and information]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %}#training-and-information)
  * [Response to incidents and security malfunctions]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %}#response-to-incidents-and-malfunctions)
* [Operational and communications aspects]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %})
  * [Protection against malware]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#protection-against-malware)
* [Access control]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %})
  * [Use of external networks]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#use-of-external-networks)
  * [External connections]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#external-connections)
  * [Login procedure]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#connection-procedures)
* [Development and maintenance of systems]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %})
  * [Use of encryption]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}#encryption)
  * [Electronic signatures]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}#electronic-signatures)
* [Management of security incidents]({% link _knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents_fr.markdown %})
  * [Reporting information security events]({% link _knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents_fr.markdown %}#reporting-information-security-events)
* [Compliance]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %})
  * [Intellectual property]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %}#intellectual-property)
  * [Protection of operational data]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %}#protection-of-operational-data)
  * [Personal data protection]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %}#personal-data-protection)

### Technical measures:

* [Encryption]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}#encryption)
