---
layout: article
title:  "Antivirus"
menutitle:
logo:
date:   2017-11-06 00:00:00 +0100
short: 
categories: knowhow
toc: true
---
<h3 class="titre-page" id="in-brief">In brief</h3>

Antivirus is software for the identification and blocking of [malware]({% link _publications/bestpractices/MaliciousSoftwareBP.markdown %}).

It does this using two key resources:

* Based on the "signatures" of malicious code: as soon as a new malicious code is discovered, it is analysed by antivirus companies. They establish an identification and eradication protocol for the code in question. They then pass this information on to the software of their customers. Completely new malicious codes are constantly changing or are only used for highly targeted attacks and to escape detection. Accordingly, antiviruses are like safety belts: they protect but they can't guarantee 100% safety.
* Based on the "behaviour" of malicious codes: antiviruses identify malicious codes based on the operations that they try to perform (heuristic approach)

Antivirus programs are essential for the protection of computers, smartphones, tablets and servers against malicious codes that are more and more numerous and widespread.

No system is invulnerable to malicious code attacks, particularly because machines cannot tell the difference between malicious and legitimate code.

<h3 class="titre-page" id="additional-measures">Additional measures</h3>

### Behavioural measures

* Users who detect suspicious files should not open them, whether they arrive by [email]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}\#email) or on [removable media]({% link _knowhow/glossary/RemovableDevices.markdown %}).
* If a file needs to be opened and it is believed to contain non-confidential data, the user can upload it to the [virustotal](https://virustotal.com/#/home/upload) site, which will analyse the file for free using a wide range of software.
* It is also sensible to wait 3 or 4 days before opening it. In fact, if it is new [malware]({% link _publications/bestpractices/MaliciousSoftwareBP.markdown %}), this wait will be needed to enable the production of the antivirus software to detect the code, analyse it and update the antivirus signature databases.

### Organisational practices

Within an organisation, the following are required:

* user training in the recognition of suspicious or doubtful files and awareness-raising on [social engineering]({% link _knowhow/glossary/SocialEngineering.markdown %}) techniques;
* clear and efficient procedures for handling suspicious or doubtful files;
* a contact person for the odd case where a user opens a file or clicks a link;
* drafting and compliance with [security policies]({% link _knowhow/glossary/AntiVirus.markdown %}]#security-policy);

### Technical measures

* Antivirus software must be updated several times a day to ensure that signature databases remain up to date.
* Antivirus programs installed on user workstations and different servers should be different to increase the chances of detection of a malicious code.
* When new malicious code is detected by a security expert, antivirus software publishers require a certain amount of time (1 to 4 days) to analyse the code and update their signature databases.
* You should set up a specialised service to analyse suspicious or doubtful files. The IT department or an external expert can open the files in a specialised environment.
* If infection is suspected, scan your computer with an antivirus program on a live CD
* Since some malicious code (worms) exploits technical vulnerabilities, you should always apply [patches]({% link _knowhow/glossary/Patches.markdown %}) and updates to your operating system and any applications used on the system in question.
* Since some malicious code (worms) uses automated mechanisms to spread itself, [the network should be partitioned] ({% link _knowhow/glossary/NetworkSegmentation.markdown %})using a firewall and computers should be protected with firewalls. These systems can also help prevent data exfiltration by Trojan horses.

<h3 class="titre-page" id="security-policy">Security policy</h3>
Write and apply the following sectoral policies:

* [Organisation of security]({% link _knowhow/cisoapproach/SecurityPolicy-OrganisationOfSecurity.markdown %})
  * [Authorisation procedure for adding information processing tools]({% link _knowhow/cisoapproach/SecurityPolicy-OrganisationOfSecurity.markdown %}\#authorising-the-addition-of-tools)
  * [Third party access and outsourcing]({% link _knowhow/cisoapproach/SecurityPolicy-OrganisationOfSecurity.markdown %}\#third-party-access-and-outsourcing)
* [Human factors]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown %})
  * [Security as a mission]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown %}\#security-as-a-mission)
  * [Training and information]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown %}\#training-and-information)
  * [Response to incidents and security malfunctions]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown %}\#response-to-incidents-and-malfunctions)
*[ Physical and environmental security]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %})
  * [Physical security perimeter]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %}\#physical-security-perimeter)
  * [Rules within the perimeter]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %}\#rules-within-the-perimeter)
  * [Off-site equipment security]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %}\#off-site-equipment-security)
* [Operational and communications aspects]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %})
  * [Protection against malware]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}\#protection-against-malware)
  * [Data backups]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}\#data-backups)
  * [Email]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}\#email)
* [Access control]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %})
  * [Access control policy]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}\#access-control-policy)
  * [Access rights management]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}\#access-rights-management)
  * [Use of external networks]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}\#use-of-external-networks)
  * [External connections]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}\#external-connections)
  * [Separation of networks]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}\#separation-of-networks)
*[ Management of security incidents]({% link _knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents.markdown %})
  * [Reporting information security events]({% link _knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents.markdown %}\#reporting-information-security-events)
  * [Incident management and improvements information security]({% link _knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents.markdown %}\#incident-management-and-improvements-information-security)
  * [Analysis of non-fulfilment of obligations]({% link _knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents.markdown %}\#analysis-of-non-fulfilment-of-obligations)
* [Managing business continuity]({% link _knowhow/cisoapproach/SecurityPolicy-ManagingBusinessContinuity.markdown %})
  * [Operational continuity]({% link _knowhow/cisoapproach/SecurityPolicy-ManagingBusinessContinuity.markdown %}\#operational-continuity)
* [Compliance]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance.markdown %})
  * [Intellectual property]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance.markdown %}\#intellectual-property)
  * [Protection of operational data]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance.markdown %}\#protection-of-operational-data)
  * [Personal data protection]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance.markdown %}\#personal-data-protection)


<h3 class="titre-page" id="different-types-of-antivirus">Different types of antivirus</h3>

### Solutions for computers

Antivirus is important software protection that should be installed on each machine, regardless of operating system. There are many antivirus solutions available, but note that none is able to detect every form of malware. It is, therefore, essential to implement **good behavioural practice for email and for the use of removable media**.

### Solutions offered by your Internet Service Provider (ISP)
The solutions offered by your Internet Service Provider (ISP) can be used to scan emails and traffic between your computer and the website you are browsing.

Although these solutions have undeniable advantages, they also have significant limitations:

* inability to scan encrypted content, such as when you visit a website in [SSL]({% link _knowhow/glossary/SSLTLS-EncryptionTechnologiesOnWeb.markdown %}) mode or if you receive encrypted email;
* inability to scan files you transfer from removable media such as DVDs, CDs, external hard drives, or USB drives;
* inability to scan your system to find malicious code that would have infected your computer before it was listed by the antivirus;
* you cannot choose the antivirus program and do not know if the solution is constantly updated.

Subscribing to your ISP's solutions is certainly useful, but does not replace local solutions installed directly on computers or servers.

### Server solutions
Antivirus solutions for servers are more or less the same as for desktops. The difference is that the server antivirus programs have certain specialisations. For example, it is standard to monitor all email traffic through a mail server or to check client downloads through a proxy server.

<h3 class="titre-page" id="operating-modes">Operating modes</h3>
Most antivirus software operates in two ways:

* 'Realtime protection' – intercepting malicious codes as soon as they try to infect a machine.
* Ad hoc scans of the machine to discover any malicious codes that have already managed to infect the system. The scan will be more effective if the malicious code is inactive, for example when using a 'live' operating system (antivirus on live CD).

Antivirus software is therefore constantly inspecting all files processed by the computer, i.e. on entry, during processing
 