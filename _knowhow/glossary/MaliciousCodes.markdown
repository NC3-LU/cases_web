---
layout: article
title:  "Malicious Codes"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short: "Security Measures"
categories: knowhow
toc: true
ref: glossarymaliciouscode
lang: en
---

## In Brief

Malware or malicious code is software that infects a user’s machine without their knowledge. The [impact]({% link _knowhow/glossary/Impact.markdown %}) of infection can be multiple, such as the loss of [confidentiality]({% link _knowhow/glossary/Confidentiality.markdown %}), [integrity]({% link _knowhow/glossary/Integrity.markdown %}) or [availability]({% link _knowhow/glossary/Availability.markdown %}) of an entity’s assets. A malicious code infection is not always noticeable, sometimes it is even very difficult to detect.

The infection can take place by inciting the victim by methods of [social engineering]({% link _knowhow/glossary/SocialEngineering.markdown %}) for example, to open a file annexed to an [electronic mail]({% link _knowhow/bestpractices/EMail-BestPractices.markdown %}), to open a file being on a [removable media]({% link _knowhow/glossary/RemovableDevices.markdown %}), or simply to motivate the victim to visit a [malicious web page]({% link _knowhow/glossary/MaliciousWebsites.markdown %}).

Malicious codes can have different [impacts]({% link _knowhow/glossary/Impact.markdown %}). They present a considerable [threat]({% link _knowhow/glossary/Threat.markdown %}) and can, depending on the type, either exploit [human]({% link _knowhow/glossary/Vulnerabilities.markdown %}#human-vulnerabilities) or [technical vulnerabilities]({% link _knowhow/glossary/Vulnerabilities.markdown %}#technical-vulnerabilities).

## Viruses
A virus is a software, or a part of software which, in order to be able to spread, attaches itself to any type of file or other software with the aim of infecting the machine concerned, as well as others, without the knowledge of users.

A virus is generally activated as soon as a person opens the file (attached to an [e-mail]({% link _knowhow/bestpractices/EMail-BestPractices.markdown %}) or located on a [removable medium]({% link _knowhow/glossary/RemovableDevices.markdown %})) or runs the software hosting the virus. As a result, the virus creator will try to trick the potential victim into opening the infected file by exploiting [human vulnerabilities]({% link _knowhow/glossary/Vulnerabilities.markdown %}#human-vulnerabilities).

As soon as a virus has been launched, it will try two things:

1.	launch its payload, that is to say, its malicious functionality;

2.	try to spread using distribution channels such as the corporate network, e-mail or removable media.

It is, therefore, strongly advised to ignore attached files from people who are unknown to us or content in emails or on computer media that cause our distrust.

## Worms
Unlike the virus, a worm does not need human intervention to infect a machine. It has an ‘engine’ (automation) which initially allows it to automatically deliver and execute its malicious code.

The Morris Worm named after its creator (Robert Morris) was one of the first worms (1988) to spread quickly on the Internet and to infect a large number of machines.

## Trojan Horse
The term ‘Trojan horse’ appears in Greek mythology, especially in Homer’s Iliad which tells the story of the Greeks who decided to invade the city of Troy. Using a ruse to assault this well-protected city, they built a large wooden horse and sent it to Troy as a gift and a sign of peace. The people of Troy appreciated this gesture and took the horse into the city. During the night some Greek soldiers, sheltered inside the wooden horse, emerged from their hiding place and opened the gates of the city to the rest of the army, which seized it.

By analogy, a Trojan horse is spyware installed on a machine to open a back door to the [attacker]({% link _knowhow/glossary/Cybercriminals.markdown %}). Unlike a virus or a worm, a Trojan horse is not intended to reproduce or spread. But like viruses, Trojans hide in harmless files and often exploit [human vulnerabilities]({% link _knowhow/glossary/Vulnerabilities.markdown %}#human-vulnerabilities) to get launched.

In general, the Trojan is used to create and maintain permanent unauthorised access to a machine, when the latter is connected to the Internet. The number of ‘trojans’ is as impressive as the variety of actions they allow attackers on target computers.

Some simply open access to machine files, others allow real interaction with the infected machine from the Internet or a local network.

## Spyware
Spyware is a program designed to collect personal data on users without authorisation, and sending them to its designer, or a third party, via the Internet or any other computer network. The primary objective of spyware is to spy on the behaviour of the Internet user and to transmit the information collected to the creators and software editors to feed a gigantic database. 

Spyware is usually ‘caught’ by browsing the Internet, as well as by downloading software. 

There are different types of spyware:

### **COMMERCIAL SPYWARES**
Commercial spyware collects data and interacts visibly with their users, by managing the display of targeted advertising banners, by triggering the appearance of pop-ups, or even by modifying the content of the websites visited to add commercial links, for example. These are the most common spyware. Their existence is generally mentioned in the licence to use the software concerned, but often in an ambiguous manner and/or in a foreign language, which means that the user is not clearly informed.

### **COOKIES**
Cookies also collect data about their users but do so with the utmost discretion. The monitoring and possible reuse of the data collected are done without the knowledge of the users, generally, for the purpose of collecting statistics, marketing information, debugging or technical maintenance, or even cyber-surveillance. The existence of these cookies is deliberately hidden from users.

### **THE INTEGRATED SPYWARE**
Integrated (or internal) spyware is an executable program included in the source code of the software with its own function, to give it the possibility of collecting and transmitting information over the Internet. This spyware can be downloaded separately or are offered for installation at the same time as other free programs, themselves usually spyware, thanks to agreements between software publishers.

### **THE OUTSOURCED SPYWARE**
Outsourced spyware is a standalone application that dialogues with the main software associated with it, and whose sole function is to take care of the ‘customer relationship’: collection and transmission of information, display of advertising banners, etc. This spyware is designed by advertising agencies or specialised companies.

## How to Protect Yourself?

### **BEHAVIOURAL MEASURES**
* It is essential to follow behavioural advice related to e-mail, advice on handling removable media and those concerning malicious websites. Follow good practices concerning malware.

### **ORGANISATIONAL MEASURES**
The organisation must draft and enforce several sectoral policies:
* [Classification and control of resources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources.markdown %})
  * [Resource classification and responsibility]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources.markdown %}#classification-and-responsibility-for-resources)
* [Human aspects]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown %})
  * [Security as a mission]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown %}#security-as-a-mission)
  * [Training and information]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown %}#training-and-information)
  * [Response to security incidents and malfunctions]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown %}#response-to-incidents-and-malfunctions)
* [Operational aspects and communications]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %})
  * [Protection against malicious code]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}#protection-against-malware)
  * [E-mail]({% link _knowhow/bestpractices/EMail-BestPractices.markdown %})
* [Access control]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %})
  * [Use of external networks]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#use-of-external-networks)
  * [Connection from the outside]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#external-connections)
  * [Network separation]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#separation-of-networks)
* [Business continuity management]({% link _knowhow/cisoapproach/SecurityPolicy-ManagingBusinessContinuity.markdown %})
  * [Continuity of operation]({% link _knowhow/cisoapproach/SecurityPolicy-ManagingBusinessContinuity.markdown %}#operational-continuity)

### **TECHNICAL MEASURES**
The use of [antivirus]({% link _knowhow/glossary/AntiVirus.markdown %}) can help against infection by malicious codes. 

[Network segmentation]({% link _knowhow/glossary/NetworkSegmentation.markdown %}) using a [firewall]({% link _knowhow/glossary/Firewall.markdown %}) can protect against infection by malicious code type ‘worms’ and against data extraction by Trojans. 

Updating the [patches]({% link _knowhow/glossary/Patches.markdown %}) of all applications, as well as the operating system, can help fight against infection by malicious ‘worm’ codes.
