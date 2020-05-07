---
layout: knowhow
category: "Knowhow"
title:  "Security Policy – Operational and Communication Aspects"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: f-ciso
toc: true
ref: cisooperationalcommunicationaspects
lang: en
---
## Documentation of Procedures
All operations concerning the processing of information must be documented. This applies to planned processing (batches), system shutdowns and restarts, and data backup procedures.

In addition to the everyday operations to be carried out, these procedures must specify:

* the instructions in case of error
* start-up conditions
* what to do with the output (listings, printouts, etc.)
* ...

The procedures are updated by the IT manager and saved in specific, easily accessible locations. The employees concerned must know about these procedures and follow them.

The attached section is optional but important for organisations that use servers. Nevertheless, documenting at least the backup procedure still applies in all other cases.

### Applying Security Measures To:

* [File Servers]({% link _publications/recommendationsecuring/Recommendations4securingWebServer.markdown %})
* [E-mail Servers]({% link _publications/recommendationsecuring/Recommendations4securingEmailServer.markdown %})
* potentially to describe the installation of new computers and laptops (‘Ghost’)

### Directly Associated Organisational Measures:

* [Organisation of Security]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity.markdown %})
  * [Attribution of Responsibilities]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity.markdown %}#attribution-of-responsibilities)

## Separation of Environments
It is preferable to separate devices that deal with software development activities or test activities from those on which products in relation to production are installed. This separation aims to limit the risk of modifications to actual data. The use of production data located in test environments (which tend to be less well protected) is not recommended.
In particular, if critical data ([Confidentiality]({% link _knowhow/glossary/Confidentiality.markdown %})), trade secrets or personal data is processed there.

### Applying Security Measures To:

* Servers that run applications (accounting, Customer Relationship Management, Stock Management, etc.) if the organisation is making or testing developments.

### Directly Associated Organisational Measures:

* [Classification and Monitoring of Resources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources.markdown %})
  * [Classification of and responsibility for resources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources.markdown %}#classification-and-responsibility-for-resources)
* [Compliance]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance.markdown %})
  * [Protection of operational data]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance.markdown %}#protection-of-operational-data)
  * [Personal data protection]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance.markdown %}#personal-data-protection)

## Outsourcing of Resource Management
Concerning resources managed by external companies, it is important to first assess the organisation’s critical security points and indicate the specific management measures in the service agreement. Here, we talk about 'outsourcing' or 'facilities management'.

### Applying Security Measures To:
* Computers and servers that are managed by external companies. In the case of remote management, it is very important to provide specific terms for access controls (see [External connections]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#external-connections)).

## Protection Against Malware
An attack by a virus or other [malicious software]({% link _knowhow/glossary/MaliciousCodes.markdown %}) is one of the most likely risks for any computer user. They can infiltrate the 'organisation' through [removable devices]({% link _knowhow/glossary/RemovableDevices.markdown %}), such as, in particular, USB flash drives and e-mails.

The organisation’s computers and servers must be equipped with [antivirus software]({% link _knowhow/glossary/AntiVirus.markdown %}). The IT manager is responsible for installing these tools on each device and ensuring they are always up to date. This concerns both the users’ workstations and the servers (see [security measures for file servers]({% link _publications/recommendationsecuring/Recommendations4securingWebServer.markdown %}) and [security measures for e-mail servers]({% link _publications/recommendationsecuring/Recommendations4securingEmailServer.markdown %})).

On the other hand, numerous measures must be respected by users to avoid compromising security. It is prohibited to:

* prevent the antivirus tools from running (deactivating them, reconfiguring them, turning off updates, etc.);
* install software that has not been approved by the IT manager (SMEs: see [Use of unapproved software]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Software.markdown %}#use-of-unapproved-software));
* launch programs or files received by e-mail sent unsolicited to the recipient, even if they know the sender (SMEs: see [Social engineering/Inadequate communication]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2HR.markdown %}#manipulation-of-people) and [Handling malicious codes]({% link _knowhow/glossary/MaliciousCodes.markdown %})). Such e-mails must be destroyed, and advice may be requested from the IT manager.

Incoming e-mail verification tools deal not only with viruses, but can also eliminate potentially dangerous attachments (executables, scripts, macros).

### Applying Security Measures To:

* [File servers]({% link _publications/recommendationsecuring/Recommendations4securingWebServer.markdown %})
* [E-mail servers]({% link _publications/recommendationsecuring/Recommendations4securingEmailServer.markdown %})
* [Computers connected to the Internet]({% link _publications/recommendationsecuring/SecuringFixedWorkstation.markdown %})
* [Laptop computers]({% link _publications/recommendationsecuring/SecuringLaptops.markdown %})

### Behavioural Measures:

* [Malicious software – best practice]({% link _knowhow/glossary/MaliciousCodes.markdown %})
* [E-mails]({% link _knowhow/bestpractices/EMail-BestPractices.markdown %})
* [Removable devices]({% link _knowhow/glossary/RemovableDevices.markdown %})
* [Malicious websites]({% link _knowhow/glossary/MaliciousWebsites.markdown %})

### Directly Associated Organisational Measures:

* [Classification and monitoring of resources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources.markdown %})
  * [Classification of and responsibility for resources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources.markdown %}#classification-and-responsibility-for-resources)
* [Human factors]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown %})
  * [Training and information]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown %}#training-and-information)
  * [Response to incidents and security malfunctions]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown %}#response-to-incidents-and-malfunctions)
* [Operational and communications aspects]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %})
  * [E-mail]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}#email)
* [Access control]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %})
  * [Access control policy]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#access-control-policy)
  * [Use of external networks]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#use-of-external-networks)
  * [Separation of networks]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#separation-of-networks)
* [Development and maintenance of systems]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.markdown %})
  * [Management of technical vulnerabilities]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.markdown %}#managing-technical-vulnerabilities)
* [Management of security incidents]({% link _knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents.markdown %})
  * [Reporting information security events]({% link _knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents.markdown %}#reporting-information-security-events)
  * [Incident management and improvements of information security]({% link _knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents.markdown %}#incident-management-and-improvements-information-security)
* [Managing business continuity]({% link _knowhow/cisoapproach/SecurityPolicy-ManagingBusinessContinuity.markdown %})
  * [Operational continuity]({% link _knowhow/cisoapproach/SecurityPolicy-ManagingBusinessContinuity.markdown %}#operational-continuity)


### Technical Measures:

* [Antivirus]({% link _knowhow/glossary/AntiVirus.markdown %})
* [Firewall]({% link _knowhow/glossary/Firewall.markdown %})
* [Network segmentation]({% link _knowhow/glossary/NetworkSegmentation.markdown %})
* [Patches]({% link _knowhow/glossary/Patches.markdown %})
* [Backups]({% link _publications/ProtectingYourCompany.markdown %}#data-backups)
* [Cryptography]({% link _knowhow/glossary/Cryptography.markdown %})

## Data Backups
It is essential for an organisation to back up their data and their specific, or specifically configured, software. A disaster (fire, flood) or, more commonly, a hard drive problem could easily destroy all information (SMEs: see [Fire]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}#fire) and [Failure of IT or communications equipment]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware.markdown %}#failure-of-it-or-communications-equipment) and [Hardware damaged during transport]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware.markdown %}#hardware-damaged-during-transport)).

In the event of a large disaster, equipment that has been destroyed can usually be replaced; however, it is often impossible to reproduce lost data, which may lead to a company’s closure.

Backing up important or crucial information ([classification]({% link _knowhow/cisoapproach/SecurityPolicy-Classification.markdown %})) should be done regularly with respect to the level of importance of the *organisation’s* activities.

The backup cycle can take place at three levels, depending on the type of information. A daily backup on a device that is reused weekly (Monday’s backup erases the backup from Monday of the previous week, for example). A weekly backup with a cycle of four to five weeks. A monthly backup with an annual cycle. The weekly backup can be turned into a monthly backup once a month (the last day of the month). The last annual backup is archived 'indefinitely' in case of legal requirements.

The weekly and monthly backups must be stored in a specific location that guarantees the same security conditions as those used in the security perimeter, if possible at a remote location.

Unused devices must be erased or destroyed. This applies to all media whether digital, paper or otherwise (SMEs: see [Disposal]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %}#disposal-and-reuse-of-equipment) and [Device recovery]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware.markdown %}#device-recovery) and [Aggravated theft]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware.markdown %}#aggravated-theft)).

Data backups can also be useful in the event of human error (SMEs: see [Human errors]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown %})), to restart the IT system from a previously reliable position. A data recovery procedure is necessary in this case and, additionally, it will allow you to test the procedure. The procedures should be tested annually.

### Applying Security Measures To:

* [File servers]({% link _publications/recommendationsecuring/Recommendations4securingWebServer.markdown %})
* [E-mail servers]({% link _publications/recommendationsecuring/Recommendations4securingEmailServer.markdown %})
* [Computers connected to the Internet]({% link _publications/recommendationsecuring/SecuringFixedWorkstation.markdown %})
* [Laptop computers]({% link _publications/recommendationsecuring/SecuringLaptops.markdown %})

### Directly Associated Organisational Measures:

* [Organisation of security]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity.markdown %})
  * [Attribution of responsibilities]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity.markdown %}#attribution-of-responsibilities)
* [Classification and monitoring of resources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources.markdown %})
  * [Classification of and responsibility for resources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources.markdown %}#classification-and-responsibility-for-resources)
* [Physical and environmental security]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %})
  * [Physical security perimeter]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %}#physical-security-perimeter)
  * [Off-site equipment security]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %}#off-site-equipment-security)
* [Operational and communications aspects]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %})
  * [Documented procedures]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}#documentation-of-procedures)
  * [Device security during transport]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}#device-security-during-transport)
* [Access control]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %})
  * [Access control policy]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#access-control-policy)
  * [Access rights management]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#access-rights-management)
* [Managing business continuity]({% link _knowhow/cisoapproach/SecurityPolicy-ManagingBusinessContinuity.markdown %})
  * [Operational continuity]({% link _knowhow/cisoapproach/SecurityPolicy-ManagingBusinessContinuity.markdown %}#operational-continuity)

### Technical Measures:

* [Data backups]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}#data-backups)

## Device Security During Transport
When transporting or sending devices containing the organisation’s data, it is important to take the following measures into account, depending on the level of importance of the data (SMEs: see [Hardware damaged during transport]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware.markdown %}#hardware-damaged-during-transport)):

* use specific packaging (which leaves traces of forced opening)
* use a briefcase with a combination lock
* have a member of the 'organisation' transport the delivery
* encrypt the data

### Applying Security Measures To:

* The transportation of backups
* Communication by e-mail
* Communication by Internet (FTP, etc.)

### Organisational Measures:

* [Classification and monitoring of resources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources.markdown %})
  * [Classification of and responsibility for resources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources.markdown %}#classification-and-responsibility-for-resources)
* [Development and maintenance of systems]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.markdown %})
  * [Use of encryption]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.markdown %}#encryption)

### Technical Measures:
* [encryption]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.markdown %}#encryption)

## E-mail
E-mails that are transmitted across the Internet can in no way be considered a secure means of communication. This is because the e-mail may be accidentally sent to a wrong recipient, or be edited or read by a third party. As a result, any operation for which the 'organisation' is responsible would be better confirmed by an additional means (telephone, letter, fax, etc.). This would prevent recipient error or changes to prices or quantities on orders, for example ([Good E-mail Practises]({% link _knowhow/bestpractices/EMail-BestPractices.markdown %})).

Avoid sending confidential information by e-mail. If applicable, use an approved encryption tool with your correspondents.

The organisation’s messaging system is intended for professional use. Moderate personal use may be tolerated. The user is held personally responsible in the case of the criminal use of tools. Please note that, in response to traceability restrictions, it is possible that part or all of the messages exchanged by members of the 'organisation' will be saved (SMEs: see [Misuse of the organisation’s resources]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2HR.markdown %}#misuse-of-it-resources)).

### Applying Security Measures To:

* [E-mail servers]({% link _publications/recommendationsecuring/Recommendations4securingEmailServer.markdown %})
* [Computers connected to the Internet]({% link _publications/recommendationsecuring/SecuringFixedWorkstation.markdown %})
* [Laptop computers]({% link _publications/recommendationsecuring/SecuringLaptops.markdown %})

### Behavioural Measures:

* [Best practice concerning e-mail]({% link _knowhow/bestpractices/EMail-BestPractices.markdown %})

### Directly Associated Organisational Measures:

* [Classification and monitoring of resources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources.markdown %})
  * [Classification of and responsibility for resources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources.markdown %}#classification-and-responsibility-for-resources)
* [Human factors]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown %})
  * [Training and information]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown %}#training-and-information)
  * [Response to incidents and security malfunctions]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown %}#response-to-incidents-and-malfunctions)
* [Operational and communications aspects]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %})
  * [Protection against malware]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}#protection-against-malware)
* [Access control]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %})
  * [Use of external networks]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#use-of-external-networks)
  * [External connections]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#external-connections)
  * [Login procedure]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#connection-procedures)
* [Development and maintenance of systems]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.markdown %})
  * [Use of encryption]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.markdown %}#encryption)
  * [Electronic signatures]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.markdown %}#electronic-signatures)
* [Management of security incidents]({% link _knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents.markdown %})
  * [Reporting information security events]({% link _knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents.markdown %}#reporting-information-security-events)
* [Compliance]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance.markdown %})
  * [Intellectual property]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance.markdown %}#intellectual-property)
  * [Protection of operational data]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance.markdown %}#protection-of-operational-data)
  * [Personal data protection]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance.markdown %}#personal-data-protection)

### Technical Measures:

* [Encryption]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.markdown %}#encryption)
