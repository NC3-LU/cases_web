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
[Encryption]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}#encryption) consists of making data illegible to an unauthorised third party and preventing them from saving or transferring the data. The use of this method is recommended when transferring information classed as vital and confidential for the “organisation”, in particular during [email]({ % link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#email) communications. The choice of encryption method falls to the IT manager. If necessary they may consult with external specialists. (SMEs: see [Interception of communications]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure_fr.markdown %}#interception-of-communications)).

### Appliquer des mesures de sécurité pour:

* [File servers]({% link _publications/recommendationsecuring/Recommendations4securingWebServer_fr.markdown %})
* [Email servers]({% link _publications/recommendationsecuring/Recommendations4securingEmailServer_fr.markdown %})
* [Fixed network]({% link _publications/recommendationsecuring/SecuringFixedNetwork_fr.markdown %})
* [Internal WiFi network]({% link _publications/recommendationsecuring/SecuringWifiNetwork_fr.markdown %}#wifi-for-employees)
* [Customer WiFi network]({% link _publications/recommendationsecuring/SecuringWifiNetwork_fr.markdown %}#wifi-for-visitorsexternal-users)
* [Computers connected to the Internet]({% link _publications/recommendationsecuring/SecuringFixedWorkstation_fr.markdown %})
* [Laptop computers]({% link _publications/recommendationsecuring/SecuringLaptops_fr.markdown %})

### Mesures organisationnelles directement liées:

* [Classification and monitoring of resources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %})
  * [Classification of and responsibility for resources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %}#classification-and-responsibility-for-resources)
* [Physical and environmental security]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %})
  * [Off-site equipment security]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#off-site-equipment-security)
* [Operational and communications aspects]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %})
  * [Documented procedures]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#documentation-of-procedures)
  * [Data backups]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#data-backups)
  * [Device security during transport]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#device-security-during-transport)
  * [Courrier électronique]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#email)
* [Développement et maintenance des systèmes]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %})
  * [Electronic signatures]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}#electronic-signatures)
* [Conformité]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %})
  * [Intellectual property]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %}#intellectual-property)
  * [Protection des données opérationnelles]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %}#protection-of-operational-data)
  * [Protection des données à caractère personnel]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %}#personal-data-protection)

### Mesures techniques:

* [encryption]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}#encryption)

## Implementation
Some examples of free encryption tools:

### VeraCrypt
[VeraCrypt](https://veracrypt.codeplex.com/) is a free encryption software program with which you can encrypt a whole hard drive or create encrypted containers into which you can place sensitive files. These containers can be located on a hard drive, a file server or even on [removable devices]({% link _knowhow/glossary/RemovableDevices_fr.markdown %}). It is easy to use and reliable from a security point of view.

### 7Z
[7Z](https://www.7-zip.org/) is a free tool used to compress and archive files. This tool also has a AES 256-bit strong encryption option. It can therefore be used to transfer confidential encrypted files on removable devices or by email since the files are located in a compressed archive.

It is a symmetrical encryption tool like truecrypt, so you need to exchange the encryption key securely with the recipient. Use a channel that is safe but different to the one used for the transfer of data. You can, for example, send the key by post, fax or SMS, or hand it to them in person.

## Deposit of encryption keys

### Responsibility
The CSSI and the key administrator are responsible for the encryption process.

### Deposit creation
The CSSI defines a secure location (typically a safety-deposit box [classified]({% link _knowhow/cisoapproach/SecurityPolicy-Classification_fr.markdown %}) as SECRET) in which copies of the keys made available to users are kept. The deposit has no backup. In the event they are destroyed, the key administrators should deposit their cases again.

### “Paper” deposit of keys classified as SECRET in a safety-deposit box.

Applicable security measures:

* Two people are necessary (“four eyes” principle; separate [l'authentification]({% link _knowhow/glossary/Authentication_fr.markdown %}));
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
An electronic signature is a method used to guarantee the authenticity of the source of a message (sender), and the [integrity]({% link _knowhow/glossary/Integrity_fr.markdown %}) of its contents.

This technology should be implemented during dialogue via email with external entities which may represent a commitment for the “organisation”. It is the responsibility of the IT manager to implement this technology for users.

[LuxTrust](https://www.luxtrust.lu) provides electronic signature solutions. [OpenPGP](https://www.openpgp.org/) is a free alternative for signatures and encryption.

Electronic signatures can be affixed to documents and to emails. The signature guarantees the authenticity of the sender, as well as the [integrity]({% link _knowhow/glossary/Integrity_fr.markdown %}) of the contents of the file relating to the message.

### Appliquer des mesures de sécurité pour:

* guarantee integrity
* guarantee non-repudiation

### Organisational measures:

* [Operational and communications aspects]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %})
  * [Documented procedures]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#documentation-of-procedures)
* [Développement et maintenance des systèmes]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %})
  * [Utilisation du chiffrement]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}#encryption)
  * [Gestion des vulnérabilités techniques]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}#managing-technical-vulnerabilities)

### Mesures techniques:

* [encryption]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}#encryption)

## Managing technical vulnerabilities
All types of organisation need to monitor risks relating to the exploitation of [technical vulnerabilities]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}#managing-technical-vulnerabilities) which have been subject to publication.

To do this, they should introduce an effective and systematic management of technical vulnerabilities for all their operating systems and network equipment. This is done through the application of [corrective]({% link _knowhow/glossary/Patches_fr.markdown %}) or other tools designed to prevent the exploitation of technical vulnerabilities. Monitoring the measures undertaken will enable their actual effectiveness to be gauged.

### Appliquer des mesures de sécurité pour:

* [les serveurs fichier]({% link _publications/recommendationsecuring/Recommendations4securingWebServer_fr.markdown %})
* [les serveurs mail]({% link _publications/recommendationsecuring/Recommendations4securingEmailServer_fr.markdown %})
* [les ordinateurs connectés à l'Internet]({% link _publications/recommendationsecuring/SecuringFixedWorkstation_fr.markdown %})
* [les ordinateurs portables]({% link _publications/recommendationsecuring/SecuringLaptops_fr.markdown %})

### Behavioural measures:

* [les sites web malicieux]({% link _knowhow/glossary/MaliciousWebsites_fr.markdown %})
* [malicious code]({% link _knowhow/glossary/MaliciousCodes_fr.markdown %})

### Mesures organisationnelles directement liées:

* [Organisation de la sécurité]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity_fr.markdown %})
  *[ Attribution of responsibilities]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity_fr.markdown %}#attribution-of-responsibilities)
* [Aspects humains]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %})
  * [La réponse aux incidents et dysfonctionnements de sécurité]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %}#response-to-incidents-and-malfunctions)
* [Operational and communications aspects]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %})
  * [Documented procedures]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#documentation-of-procedures)
  * [Separation of development and production environments]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#separation-of-environments)
* [Gestion des incidents liés à la sécurité]({% link _knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents_fr.markdown %})
  * [Incident management and improvements information security]({% link _knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents_fr.markdown %}#incident-management-and-improvements-information-security)


### Mesures techniques:
* [corrections]({% link _knowhow/glossary/Patches_fr.markdown %})
* [le pare-feu]({% link _knowhow/glossary/Firewall_fr.markdown %})
* [network segmentation]({% link _knowhow/glossary/NetworkSegmentation_fr.markdown %})