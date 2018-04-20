---
layout: article
title:  "Security Policy – Operational and communication aspects"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: f-ciso
toc: true
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

* Organisation of security
  * Attribution of responsibilities

## Separation of environments
It is preferable to separate devices that deal with software development activities or test activities from those on which products in production are installed.

This separation aims to limit the risk of modifications to actual data.

The use of production data located in test environments (which tend to be less well protected) is, in fact, not recommended.

In particular if critical data (from the point of view of confidentiality), trade secrets or personal data is processed there.

### Applying security measures to:

* Servers that run applications (accounting, Customer Relationship Management, Stock Management, etc.) if the organisation is making or testing developments.

### Directly associated organisational measures:

* Classification and monitoring of resources
  * Classification of and responsibility for resources
* Compliance
  * Protection of operational data
  * Personal data protection

## Outsourcing of resource management
With regard to resources managed by external companies, it is important to first assess the organisation’s critical security points and indicate the specific management measures in the service agreement.

Here, we talk about “outsourcing” or “facilities management”.

### Applying security measures to:
* Computers and servers that are managed by external companies. In the case of remote management, it is very important to provide specific terms for access controls (see External connections).

## Protection against malware
An attack by a virus or other malicious software is one of the most likely risks for any computer user. They can infiltrate the “organisation” through removable devices, such as, in particular, CD-ROMs,

The “organisation’s” computers and servers must be equipped with antivirus software. The IT manager is responsible for installing these tools on each device and ensuring they are always up to date. This concerns both the users’ workstations and the servers (see security measures for file servers and security measures for email servers).

On the other hand, a large number of measures must be respected by the users to avoid compromising security. It is prohibited to:

* prevent the antivirus tools from running (deactivating them, reconfiguring them, turning off updates, etc.);
* install software that has not been approved by the IT manager (SMEs: see Use of unapproved software);
* launch programs or files received by email sent unsolicited to the recipient, even if they know the sender (SMEs: see Social engineering/Inadequate communication and Handling malicious codes). Such emails must be destroyed and advice may be requested from the IT manager.

Incoming email verification tools deal not only with viruses, but can also eliminate potentially dangerous attachments (executables, scripts, macros).

### Applying security measures to:

* File servers
* Email servers
* Computers connected to the Internet
* Laptop computers

### Behavioural measures:

* Malicious software – best practice
* Emails
* Removable devices
* Malicious websites

### Directly associated organisational measures:

* Classification and monitoring of resources
  * Classification of and responsibility for resources
* Human factors
  * Training and information
  * Response to incidents and security malfunctions
* Operational and communications aspects
  * Email
* Access control
  * Access control policy
  * Use of external networks
  * Separation of networks
* Development and maintenance of systems
  * Management of technical vulnerabilities
* Management of security incidents
  * Reporting information security events
  * Incident management and improvements information security
* Managing business continuity
  * Operational continuity

### Technical measures:

* Antivirus
* Firewall
* Network segmentation
* Patches
* Backups
* Cryptography

## Data backups
It is essential for an organisation to back up their data and their specific, or specifically configured, software. A disaster (fire, flood) or, more commonly, a hard drive problem could easily destroy all of this information. (SMEs: see Fire and Failure of IT or communications equipment and Hardware damaged during transport).

In the event of a large disaster, equipment that has been destroyed can usually be replaced; however, it is often impossible to reproduce lost data, which may lead to a company’s closure.

Backing up important or crucial information (classification) should be done at a regularity compatible with the level of importance of the *organisation’s* activities.

The backup cycle can take place at 3 levels, depending on the type of information. A daily backup on a device that is reused weekly (Monday’s backup erases the backup from Monday of the previous week, for example). A weekly backup with a cycle of 4 to 5 weeks. A monthly backup with an annual cycle. The weekly backup can in fact be turned into a monthly backup once a month (the last day of the month). The last annual backup is archived “indefinitely” in case of legal requirements.

The weekly and monthly backups must be stored in a specific location that guarantees the same security conditions as those used in the security perimeter, if possible at a remote location.

Unused devices must be erased or destroyed. This applies to all media, whether digital, paper or otherwise (SMEs: see Disposal and Device recovery and Aggravated theft).

Data backups can also be useful in the event of human error (SMEs: see Human errors), in order to restart the IT system from a previously reliable position. A data recovery procedure is necessary in this case and, additionally, it will give you an opportunity to test the procedure. In fact, the procedures should be tested annually.

### Applying security measures to:

* File servers
* Email servers
* Computers connected to the Internet
* Laptop computers

### Directly associated organisational measures:

* Organisation of security
  * Attribution of responsibilities
* Classification and monitoring of resources
  * Classification of and responsibility for resources
* Physical and environmental security
  * Physical security perimeter
  * Off-site equipment security
* Operational and communications aspects
  * Documented procedures
  * Device security during transport
* Access control
  * Access control policy
  * Access rights management
* Managing business continuity
  * Operational continuity

### Technical measures:

* Data backups

## Device security during transport
When transporting or sending devices containing the “organisation’s” data, it is important to take the following measures into account, depending on the level of importance of the data (SMEs: see Hardware damaged during transport):

* use specific packaging (which leaves traces of forced opening)
* use a briefcase with a combination lock
* have a member of the “organisation” transport the delivery
* encrypt the data

### Applying security measures to:

* The transportation of backups
* Communication by email
* Communication by Internet (FTP, etc.)

### Organisational measures:

* Classification and monitoring of resources
  * Classification of and responsibility for resources
* Development and maintenance of systems
  * Use of encryption

### Technical measures:
* encryption

## Email
Email that is transmitted across the Internet can in no way be considered a secure means of communication. This is because the email may be accidentally sent to the wrong recipients, or be edited or read by a third party. As a result, any operation for which the “organisation” is responsible would be better confirmed by an additional means (telephone, letter, fax, etc.). This would prevent recipient error or changes to prices or quantities on orders, for example. (good email practices)

Avoid sending confidential information by email. If applicable, use an approved encryption tool with your correspondents.

The “organisation’s” messaging system is intended for professional use. Moderate personal use may be tolerated. The user is held personally responsible in the case of the criminal use of tools. Please note that, in response to traceability restrictions, it is possible that part or all of the messages exchanged by members of the “organisation” will be saved. (SMEs: see Misuse of organisation’s resources)

### Applying security measures to:

* Email servers
* Computers connected to the Internet
* Laptop computers

### Behavioural measures:

* Best practice concerning email

### Directly associated organisational measures:

* Classification and monitoring of resources
  * Classification of and responsibility for resources
* Human factors
  * Training and information
  * Response to incidents and security malfunctions
* Operational and communications aspects
  * Protection against malware
* Access control
  * Use of external networks
  * External connections
  * Login procedure
* Development and maintenance of systems
  * Use of encryption
  * Electronic signatures
* Management of security incidents
  * Reporting information security events
* Compliance
  * Intellectual property
  * Protection of operational data
  * Personal data protection

### Technical measures:

* Encryption
