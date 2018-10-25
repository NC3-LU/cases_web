---
layout: knowhow
title:  "Security Policy – System development and maintenance"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: f-ciso
toc: true
ref: cisosystemdeploymentmaintenance
lang: fr
---
## Encryption
[Encryption]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.markdown %}#encryption) consists of making data illegible to an unauthorised third party and preventing them from saving or transferring the data. The use of this method is recommended when transferring information classed as vital and confidential for the “organisation”, in particular during [email]({ % link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}#email) communications. The choice of encryption method falls to the IT manager. If necessary they may consult with external specialists. (SMEs: see [Interception of communications]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}#interception-of-communications)).

### Applying security measures to:

* [File servers]({% link _publications/recommendationsecuring/Recommendations4securingWebServer.markdown %})
* [Email servers]({% link _publications/recommendationsecuring/Recommendations4securingEmailServer.markdown %})
* [Fixed network]({% link _publications/recommendationsecuring/SecuringFixedNetwork.markdown %})
* [Internal WiFi network]({% link _publications/recommendationsecuring/SecuringWifiNetwork.markdown %}#wifi-for-employees)
* [Customer WiFi network]({% link _publications/recommendationsecuring/SecuringWifiNetwork.markdown %}#wifi-for-visitorsexternal-users)
* [Computers connected to the Internet]({% link _publications/recommendationsecuring/SecuringFixedWorkstation.markdown %})
* [Laptop computers]({% link _publications/recommendationsecuring/SecuringLaptops.markdown %})

### Directly associated organisational measures:

* [Classification and monitoring of resources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources.markdown %})
  * [Classification of and responsibility for resources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources.markdown %}#classification-and-responsibility-for-resources)
* [Physical and environmental security]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %})
  * [Off-site equipment security]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %}#off-site-equipment-security)
* [Operational and communications aspects]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %})
  * [Documented procedures]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}#documentation-of-procedures)
  * [Data backups]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}#data-backups)
  * [Device security during transport]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}#device-security-during-transport)
  * [Email]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}#email)
* [Development and maintenance of systems]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.markdown %})
  * [Electronic signatures]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.markdown %}#electronic-signatures)
* [Compliance]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance.markdown %})
  * [Intellectual property]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance.markdown %}#intellectual-property)
  * [Protection of operational data]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance.markdown %}#protection-of-operational-data)
  * [Personal data protection]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance.markdown %}#personal-data-protection)

### Technical measures:

* [encryption]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.markdown %}#encryption)

## Implementation
Some examples of free encryption tools:

### VeraCrypt
[VeraCrypt](https://veracrypt.codeplex.com/) is a free encryption software program with which you can encrypt a whole hard drive or create encrypted containers into which you can place sensitive files. These containers can be located on a hard drive, a file server or even on [removable devices]({% link _knowhow/glossary/RemovableDevices.markdown %}). It is easy to use and reliable from a security point of view.

### 7Z
[7Z](https://www.7-zip.org/) is a free tool used to compress and archive files. This tool also has a AES 256-bit strong encryption option. It can therefore be used to transfer confidential encrypted files on removable devices or by email since the files are located in a compressed archive.

It is a symmetrical encryption tool like truecrypt, so you need to exchange the encryption key securely with the recipient. Use a channel that is safe but different to the one used for the transfer of data. You can, for example, send the key by post, fax or SMS, or hand it to them in person.

## Deposit of encryption keys

### Responsibility
The CSSI and the key administrator are responsible for the encryption process.

### Deposit creation
The CSSI defines a secure location (typically a safety-deposit box [classified]({% link _knowhow/cisoapproach/SecurityPolicy-Classification.markdown %}) as SECRET) in which copies of the keys made available to users are kept. The deposit has no backup. In the event they are destroyed, the key administrators should deposit their cases again.

### “Paper” deposit of keys classified as SECRET in a safety-deposit box.

Applicable security measures:

* Two people are necessary (“four eyes” principle; separate [authentication]({% link _knowhow/glossary/Authentication.markdown %}));
* Protocol for opening and access to keys;
* Keys in sealed envelopes;
* Contents inventory stating:
  * the name of the key creator; the name of persons authorised to access it;
  * the name of the environment and of the software for use with the key;
  * the type of data being protected;
  * the identifier of the envelope containing the value of the key.

### “Electronic” deposit (for CO keys)
This is the same procedure as detailed above, except for the four-eyes principle, as only the CSSI may access the safety-deposit box. This is why they may keep keys in electronic form (in a sufficiently protected container). They can replace the key identifier with the key itself. The CSSI does, however, have to ensure that their safeguards can also enable access to the key file.

### Importing into the physical deposit
The author of the key drafts a form, noting down the key, and encloses it in the presence of the person responsible for the safety-deposit box, after having shown this person the form, solely for sufficient time for this person to see that the form has been fully completed and that the quality of the key is sufficiently good.

The person responsible for the deposit updates the deposit inventory and has it signed by the author of the added key.

### Exporting a key from deposit
No key can be removed from deposit. In the case of usage, authorised persons may come and consult it:

The following are authorised:

1. author of the key;
2. any person explicitly mandated by the administrator of the information protected by the key, on condition that there is a legitimate purpose validated by the Security manager.

Any export of the safety-deposit box inventory shall be signed by the person who examined the key, as well as the safety-deposit box managers.

### Destruction of a key from deposit
On written request by the author and validated by the manager of the information protected, the safety-deposit box managers proceed with the destruction of a key. To this end, they destroy the envelope with the key inside in a document destroyer, after having verified the destruction request.

The inventory is updated, keeping the destruction request as proof of legitimisation.

## Electronic signatures
An electronic signature is a method used to guarantee the authenticity of the source of a message (sender), and the [integrity]({% link _knowhow/glossary/Integrity.markdown %}) of its contents.

This technology should be implemented during dialogue via email with external entities which may represent a commitment for the “organisation”. It is the responsibility of the IT manager to implement this technology for users.

[LuxTrust](https://www.luxtrust.lu) provides electronic signature solutions. [OpenPGP](https://www.openpgp.org/) is a free alternative for signatures and encryption.

Electronic signatures can be affixed to documents and to emails. The signature guarantees the authenticity of the sender, as well as the [integrity]({% link _knowhow/glossary/Integrity.markdown %}) of the contents of the file relating to the message.

### Applying security measures to:

* guarantee integrity
* guarantee non-repudiation

### Organisational measures:

* [Operational and communications aspects]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %})
  * [Documented procedures]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}#documentation-of-procedures)
* [Development and maintenance of systems]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.markdown %})
  * [Use of encryption]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.markdown %}#encryption)
  * [Management of technical vulnerabilities]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.markdown %}#managing-technical-vulnerabilities)

### Technical measures:

* [encryption]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.markdown %}#encryption)

## Managing technical vulnerabilities
All types of organisation need to monitor risks relating to the exploitation of [technical vulnerabilities]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.markdown %}#managing-technical-vulnerabilities) which have been subject to publication.

To do this, they should introduce an effective and systematic management of technical vulnerabilities for all their operating systems and network equipment. This is done through the application of [corrective]({% link _knowhow/glossary/Patches.markdown %}) or other tools designed to prevent the exploitation of technical vulnerabilities. Monitoring the measures undertaken will enable their actual effectiveness to be gauged.

### Applying security measures to:

* [file servers]({% link _publications/recommendationsecuring/Recommendations4securingWebServer.markdown %})
* [email servers]({% link _publications/recommendationsecuring/Recommendations4securingEmailServer.markdown %})
* [computers connected to the Internet]({% link _publications/recommendationsecuring/SecuringFixedWorkstation.markdown %})
* [laptop computers]({% link _publications/recommendationsecuring/SecuringLaptops.markdown %})

### Behavioural measures:

* [malicious websites]({% link _knowhow/glossary/MaliciousWebsites.markdown %})
* [malicious code]({% link _knowhow/glossary/MaliciousCodes.markdown %})

### Directly associated organisational measures:

* [Organisation of security]({% link _knowhow/cisoapproach/SecurityPolicy-OrganisationOfSecurity.markdown %})
  *[ Attribution of responsibilities]({% link _knowhow/cisoapproach/SecurityPolicy-OrganisationOfSecurity.markdown %}#attribution-of-responsibilities)
* [Human factors]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown %})
  * [Response to incidents and security malfunctions]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown %}#response-to-incidents-and-malfunctions)
* [Operational and communications aspects]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %})
  * [Documented procedures]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}#documentation-of-procedures)
  * [Separation of development and production environments]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}#separation-of-environments)
* [Management of security incidents]({% link _knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents.markdown %})
  * [Incident management and improvements information security]({% link _knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents.markdown %}#incident-management-and-improvements-information-security)


### Technical measures:
* [corrections]({% link _knowhow/glossary/Patches.markdown %})
* [firewall]({% link _knowhow/glossary/Firewall.markdown %})
* [network segmentation]({% link _knowhow/glossary/NetworkSegmentation.markdown %})
