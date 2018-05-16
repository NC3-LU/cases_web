---
layout: knowhow
title:  "Security Policy – Operational and communication aspects"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: f-ciso
toc: true
---
<h3 class="titre-page">Documentation of procedures</h3>
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

* Organisation of security
  * Attribution of responsibilities

<h3 class="titre-page">Separation of environments</h3>
It is preferable to separate devices that deal with software development activities or test activities from those on which products in production are installed.

This separation aims to limit the risk of modifications to actual data.

The use of production data located in test environments (which tend to be less well protected) is, in fact, not recommended.

In particular if critical data (from the point of view of [confidentiality]({{site.url}})), trade secrets or personal data is processed there.

### Applying security measures to:

* Servers that run applications (accounting, Customer Relationship Management, Stock Management, etc.) if the organisation is making or testing developments.

### Directly associated organisational measures:

* Classification and monitoring of resources
  * Classification of and responsibility for resources
* Compliance
  * Protection of operational data
  * Personal data protection

<h3 class="titre-page">Outsourcing of resource management</h3>
With regard to resources managed by external companies, it is important to first assess the organisation’s critical security points and indicate the specific management measures in the service agreement.

Here, we talk about “outsourcing” or “facilities management”.

### Applying security measures to:
* Computers and servers that are managed by external companies. In the case of remote management, it is very important to provide specific terms for access controls (see External connections).

<h3 class="titre-page">Protection against malware</h3>
An attack by a virus or other [malicious software]({{site.url}}) is one of the most likely risks for any computer user. They can infiltrate the “organisation” through [removable devices]({{site.url}}/knowhow/glossary/RemovableDevices.html), such as, in particular, CD-ROMs,

The “organisation’s” computers and servers must be equipped with [antivirus software]({{site.url}}/knowhow/glossary/AntiVirus.html). The IT manager is responsible for installing these tools on each device and ensuring they are always up to date. This concerns both the users’ workstations and the servers (see [security measures for file servers]({{site.url}}/publications/recommendationsecuring/Recommendations4securingWebServer.html) and [security measures for email servers]({{site.url}}/publications/recommendationsecuring/Recommendations4securingEmailServer.html)).

On the other hand, a large number of measures must be respected by the users to avoid compromising security. It is prohibited to:

* prevent the antivirus tools from running (deactivating them, reconfiguring them, turning off updates, etc.);
* install software that has not been approved by the IT manager (SMEs: see [Use of unapproved software]({{site.url}}/knowhow/bestpractices/SecurityMeasures4SME-Threats2Software.html#use-of-unapproved-software));
* launch programs or files received by email sent unsolicited to the recipient, even if they know the sender (SMEs: [see Social engineering/Inadequate communication]({{site.url}}/knowhow/bestpractices/SecurityMeasures4SME-Threats2HR.html#manipulation-of-people) and [Handling malicious codes]({{site.url}}/knowhow/glossary/MaliciousWebsites.html)). Such emails must be destroyed and advice may be requested from the IT manager.

Incoming email verification tools deal not only with viruses, but can also eliminate potentially dangerous attachments (executables, scripts, macros).

### Applying security measures to:

* [File servers]({{site.url}}/publications/recommendationsecuring/Recommendations4securingWebServer.html)
* [Email servers]({{site.url}}/publications/recommendationsecuring/Recommendations4securingEmailServer.html)
* [Computers connected to the Internet]({{site.url}}/publications/recommendationsecuring/SecuringFixedWorkstation.html)
* [Laptop computers]({{site.url}}/publications/recommendationsecuring/SecuringLaptops.html)

### Behavioural measures:

* [Malicious software – best practice]({{site.url}}/publications/bestpractices/MaliciousSoftwareBP.html)
* [Emails]({{site.url}}/publications/bestpractices/EMail-BestPractices.html)
* [Removable devices]({{site.url}}/knowhow/glossary/RemovableDevices.html)
* [Malicious websites]({{site.url}}/knowhow/glossary/MaliciousWebsite.html)

### Directly associated organisational measures:

* [Classification and monitoring of resources]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources.html)
  * [Classification of and responsibility for resources]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources.html#classification-and-responsibility-for-resources)
* [Human factors]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-HumanFactors.html)
  * [Training and information]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-HumanFactors.html#training-and-information)
  *[ Response to incidents and security malfunctions]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-HumanFactors.html#response-to-incidents-and-malfunctions)
* [Operational and communications aspects]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.html)
  * [Email]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.html#email)
* [Access control]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-AccessControl.html)
  * [Access control policy]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-AccessControl.html#access-control-policy)
  * [Use of external networks]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-AccessControl.html#use-of-external-networks)
  * [Separation of networks]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-AccessControl.html#separation-of-networks)
* [Development and maintenance of systems]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.html)
  * [Management of technical vulnerabilities]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.html#managing-technical-vulnerabilities)
* [Management of security incidents]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents.html)
  * [Reporting information security events]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents.html#reporting-information-security-events)
  * [Incident management and improvements information security]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents.html#incident-management-and-improvements-information-security)
*[Managing business continuity]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-ManagingBusinessContinuity.html)
  * [Operational continuity]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-ManagingBusinessContinuity.html#operational-continuity)


### Technical measures:

* [Antivirus]({{site.url}}/knowhow/glossary/AntiVirus.html)
* [Firewall]({{site.url}})
* [Network segmentation]({{site.url}}/knowhow/glossary/NetworkSegmentation.html)
* [Patches]({{site.url}}/knowhow/glossary/Patches.html)
* [Backups]({{site.url}}/publications/ProtectingYourCompany.html#data-backups)
* [Cryptography]({{site.url}}/knowhow/glossary/Cryptography.html)

<h3 class="titre-page">Data backups</h3>
It is essential for an organisation to back up their data and their specific, or specifically configured, software. A disaster (fire, flood) or, more commonly, a hard drive problem could easily destroy all of this information. (SMEs: see [Fire]({{site.url}}/knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.html#fire) and [Failure of IT or communications equipment]({{site.url}}/knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware.html#failure-of-it-or-communications-equipment) and [Hardware damaged during transport]({{site.url}}/knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware.html#hardware-damaged-during-transport)).

In the event of a large disaster, equipment that has been destroyed can usually be replaced; however, it is often impossible to reproduce lost data, which may lead to a company’s closure.

Backing up important or crucial information ([classification]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-Classification.html)) should be done at a regularity compatible with the level of importance of the *organisation’s* activities.

The backup cycle can take place at 3 levels, depending on the type of information. A daily backup on a device that is reused weekly (Monday’s backup erases the backup from Monday of the previous week, for example). A weekly backup with a cycle of 4 to 5 weeks. A monthly backup with an annual cycle. The weekly backup can in fact be turned into a monthly backup once a month (the last day of the month). The last annual backup is archived “indefinitely” in case of legal requirements.

The weekly and monthly backups must be stored in a specific location that guarantees the same security conditions as those used in the security perimeter, if possible at a remote location.

Unused devices must be erased or destroyed. This applies to all media, whether digital, paper or otherwise (SMEs: see [Disposal]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.html#disposal-and-reuse-of-equipment) and [Device recovery]({{site.url}}/knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware.html#device-recovery) and [Aggravated theft]({{site.url}}/knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware.html#aggravated-theft)).

Data backups can also be useful in the event of human error (SMEs: see [Human errors]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-HumanFactors.html)), in order to restart the IT system from a previously reliable position. A data recovery procedure is necessary in this case and, additionally, it will give you an opportunity to test the procedure. In fact, the procedures should be tested annually.

### Applying security measures to:

* [File servers]({{site.url}}/publications/recommendationsecuring/Recommendations4securingWebServer.html)
* [Email servers]({{site.url}}/publications/recommendationsecuring/Recommendations4securingEmailServer.html)
* [Computers connected to the Internet]({{site.url}}/publications/recommendationsecuring/SecuringFixedWorkstation.html)
* [Laptop computers]({{site.url}}/publications/recommendationsecuring/SecuringLaptops.html)

### Directly associated organisational measures:

* [Organisation of security]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-OrganisationOfSecurity.html)
  * [Attribution of responsibilities]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-OrganisationOfSecurity.html#attribution-of-responsibilities)
* [Classification and monitoring of resources]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources.html)
  * [Classification of and responsibility for resources]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources.html#classification-and-responsibility-for-resources)
* [Physical and environmental security]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.html)
  * [Physical security perimeter]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.html#physical-security-perimeter)
  * [Off-site equipment security]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.html#off-site-equipment-security)
* [Operational and communications aspects]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.html)
  * [Documented procedures]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.html#documentation-of-procedures)
  * [Device security during transport]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.html#device-security-during-transport)
* [Access control]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-AccessControl.html)
  * [Access control policy]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-AccessControl.html#access-control-policy)
  * [Access rights management]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-AccessControl.html#access-rights-management)
* [Managing business continuity]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-ManagingBusinessContinuity.html)
  * [Operational continuity]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-ManagingBusinessContinuity.html#operational-continuity)

### Technical measures:

* [Data backups]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.html#data-backups)

<h3 class="titre-page">Device security during transport</h3>
When transporting or sending devices containing the “organisation’s” data, it is important to take the following measures into account, depending on the level of importance of the data (SMEs: see [Hardware damaged during transport]({{site.url}}/knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware.html#hardware-damaged-during-transport)):

* use specific packaging (which leaves traces of forced opening)
* use a briefcase with a combination lock
* have a member of the “organisation” transport the delivery
* encrypt the data

### Applying security measures to:

* The transportation of backups
* Communication by email
* Communication by Internet (FTP, etc.)[

### Organisational measures:

* [Classification and monitoring of resources]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources.html)
  * [Classification of and responsibility for resources]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources.html#classification-and-responsibility-for-resources)
* [Development and maintenance of systems]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.html)
  * [Use of encryption]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.html#encryption)

### Technical measures:
* [encryption]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.html#encryption)

<h3 class="titre-page">Email</h3>
Email that is transmitted across the Internet can in no way be considered a secure means of communication. This is because the email may be accidentally sent to the wrong recipients, or be edited or read by a third party. As a result, any operation for which the “organisation” is responsible would be better confirmed by an additional means (telephone, letter, fax, etc.). This would prevent recipient error or changes to prices or quantities on orders, for example. (good email practices)

Avoid sending confidential information by email. If applicable, use an approved encryption tool with your correspondents.

The “organisation’s” messaging system is intended for professional use. Moderate personal use may be tolerated. The user is held personally responsible in the case of the criminal use of tools. Please note that, in response to traceability restrictions, it is possible that part or all of the messages exchanged by members of the “organisation” will be saved. (SMEs: see [Misuse of organisation’s resources]({{site.url}}/knowhow/bestpractices/SecurityMeasures4SME-Threats2HR.html#misuse-of-it-resources))

### Applying security measures to:

* [Email servers]({{site.url}}/publications/recommendationsecuring/Recommendations4securingEmailServer.html)
* [Computers connected to the Internet]({{site.url}}/publications/recommendationsecuring/SecuringFixedWorkstation.html)
* [Laptop computers]({{site.url}}/publications/recommendationsecuring/SecuringLaptops.html)

### Behavioural measures:

* [Best practice concerning email]({{site.url}}/publications/bestpractices/EMail-BestPractices.html)

### Directly associated organisational measures:

* [Classification and monitoring of resources]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources.html)
  * [Classification of and responsibility for resources]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources.html#classification-and-responsibility-for-resources)
* [Human factors]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-HumanFactors.html)
  * [Training and information]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-HumanFactors.html#training-and-information)
  * [Response to incidents and security malfunctions]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-HumanFactors.html#response-to-incidents-and-malfunctions)
* [Operational and communications aspects]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.html)
  * [Protection against malware]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.html#protection-against-malware)
* [Access control]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-AccessControl.html)
  * [Use of external networks]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-AccessControl.html#use-of-external-networks)
  * [External connections]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-AccessControl.html#external-connections)
  * [Login procedure]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-AccessControl.html#connection-procedures)
* [Development and maintenance of systems]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.html)
  * [Use of encryption]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.html#encryption)
  * [Electronic signatures]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.html#electronic-signatures)
* [Management of security incidents]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents.html)
  * [Reporting information security events]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents.html#reporting-information-security-events)
* [Compliance]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-Compliance.html)
  * [Intellectual property]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-Compliance.html#intellectual-property)
  * [Protection of operational data]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-Compliance.html#protection-of-operational-data)
  * [Personal data protection]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-Compliance.html#personal-data-protection)

### Technical measures:

* [Encryption]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.html#encryption)
