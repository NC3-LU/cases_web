---
layout: knowhow
title:  "Security Policy – System development and maintenance"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: f-ciso
toc: true
---
## Encryption
Encryption consists of making data illegible to an unauthorised third party and preventing them from saving or transferring the data. The use of this method is recommended when transferring information classed as vital and confidential for the “organisation”, in particular during email communications. The choice of encryption method falls to the IT manager. If necessary they may consult with external specialists. (SMEs: see Interception of communications).

### Applying security measures to:

* file servers
* email servers
* fixed network
* internal WiFi network
* customer WiFi network
* computers connected to the Internet
* laptop computers

### Directly associated organisational measures:

* Classification and monitoring of resources
  * Classification of and responsibility for resources
* Physical and environmental security
  * Off-site equipment security
* Operational and communications aspects
  * Documented procedures
  * Data backups
  * Device security during transport
  * Email
* Development and maintenance of systems
  * Electronic signatures
* Compliance
  * Intellectual property
  * Protection of operational data
  * Personal data protection

### Technical measures:

* encryption

## Implementation
Some examples of free encryption tools:

### VeraCrypt
[VeraCrypt](https://veracrypt.codeplex.com/) is a free encryption software program with which you can encrypt a whole hard drive or create encrypted containers into which you can place sensitive files. These containers can be located on a hard drive, a file server or even on removable devices. It is easy to use and reliable from a security point of view.

### 7Z
[7Z](www.7-zip.org) is a free tool used to compress and archive files. This tool also has a AES 256-bit strong encryption option. It can therefore be used to transfer confidential encrypted files on removable devices or by email since the files are located in a compressed archive.

It is a symmetrical encryption tool like truecrypt, so you need to exchange the encryption key securely with the recipient. Use a channel that is safe but different to the one used for the transfer of data. You can, for example, send the key by post, fax or SMS, or hand it to them in person.

## Deposit of encryption keys

### Responsibility
The CSSI and the key administrator are responsible for the encryption process.

### Deposit creation
The CSSI defines a secure location (typically a safety-deposit box classified as SECRET) in which copies of the keys made available to users are kept. The deposit has no backup. In the event they are destroyed, the key administrators should deposit their cases again.

### “Paper” deposit of keys classified as SECRET in a safety-deposit box.

Applicable security measures:

* Two people are necessary (“four eyes” principle; separate authentication);
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
An electronic signature is a method used to guarantee the authenticity of the source of a message (sender), and the integrity of its contents.

This technology should be implemented during dialogue via email with external entities which may represent a commitment for the “organisation”. It is the responsibility of the IT manager to implement this technology for users.

[LuxTrust](www.luxtrust.lu) provides electronic signature solutions. OpenPGP is a free alternative for signatures and encryption.

Electronic signatures can be affixed to documents and to emails. The signature guarantees the authenticity of the sender, as well as the integrity of the contents of the file relating to the message.

### Applying security measures to:

* guarantee integrity
* guarantee non-repudiation

### Organisational measures:

* Operational and communications aspects
  * Documented procedures
* Development and maintenance of systems
  * Use of encryption
  * Management of technical vulnerabilities

### Technical measures:

* encryption

## Managing technical vulnerabilities
All types of organisation need to monitor risks relating to the exploitation of technical vulnerabilities which have been subject to publication.

To do this, they should introduce an effective and systematic management of technical vulnerabilities for all their operating systems and network equipment. This is done through the application of corrective or other tools designed to prevent the exploitation of technical vulnerabilities. Monitoring the measures undertaken will enable their actual effectiveness to be gauged.

### Applying security measures to:

* file servers
* email servers
* computers connected to the Internet
* laptop computers

### Behavioural measures:

* malicious websites
* malicious code

### Directly associated organisational measures:

* Organisation of security
  * Attribution of responsibilities
* Human factors
  * Response to incidents and security malfunctions
* Operational and communications aspects
  * Documented procedures
  * Separation of development and production environments
* Management of security incidents
  * Incident management and improvements information security

### Technical measures:
* corrections
* firewall
* network segmentation
