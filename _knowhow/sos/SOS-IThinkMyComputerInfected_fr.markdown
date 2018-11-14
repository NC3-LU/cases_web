---
layout: knowhow
title:  "SOS – I think my computer is infected"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: f-sos
toc: true
ref: sosmycomputerinfected
lang: fr
---

## In brief
These days, it is very difficult to tell if a machine is infected. [Cybercriminals]({% link _knowhow/glossary/Cybercriminals_fr.markdown %}) try to use [Trojan horses]({% link _knowhow/glossary/MaliciousCodes_fr.markdown %}#cheval-de-troie) to extract data (spying), or use the computer for larger scale attacks (distributed denial of service), to send [spam]({% link _knowhow/glossary/SPAM-UnwantedEmails_fr.markdown %}) or other illicit reasons.

Some infections have no real aim, and many initial infections only load installation software. In this case, access to the infected computers is sold to the highest bidder, who then uses the installer (Trojan loader) to install the final Trojan horse.

The most common vectors for infection are:

* [malicious websites]({% link _knowhow/glossary/MaliciousWebsites_fr.markdown %}) (popular websites that have been infected, or malicious websites on which victims are tricked by advertising displayed on the sites or in emails, or links included in [emails]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#email));
* infected attachments;
* [removable storage media]({% link _knowhow/glossary/RemovableDevices_fr.markdown %}).

Use [best practices]({% link _knowhow/bestpractices/MaliciousSoftwareBP_fr.markdown %}) to avoid malware.

## Risk analysis
Try to perform a risk analysis to check whether you have fallen victim to a targeted or opportunistic attack. These questions might help you:

* What is the probability that someone wants to spy on you?
* Do you have any data that may interest other companies?
* Do you work in the military sector?
* Do you work for a government department?
* Do you have access, as a sub-contractor, to highly confidential data?
* Are you in the process of responding to an important call for tenders?
* Are you part of an international consortium responding to a call for tenders?

If you answered yes to any of these questions, a cybercriminal may well be interested in you and launch a targeted attack. In other cases, you have probably fallen victim to an opportunistic attack. Your machine will be sold on to the highest bidder.

Another way to determine whether this is a targeted or opportunistic attack is to look at the methods used by the criminal to infect your device. An impersonal email indicates an opportunistic attack, while an email that refers to you by name looks more like a targeted attack.

## Victim of an opportunistic attack
Some cybercriminals try to infect as many machines as possible through opportunistic attacks. These criminals specialise in the “acquisition” of machines and only install software enabling remote access. They often try to distribute their victims by country, categorising individuals and companies, and they sometimes even try to identify the infected victim. (The profiling quality of the infected machines increases their sale price). They go on to sell access to these machines to the highest bidder. This person will then install specialist malware using the remote access software, based on their objectives:

* stealing log-in data or other confidential data (e-banking, e-commerce, social networking, emails, etc);
* using the infected machine to send [spam]({% link _knowhow/glossary/SPAM-UnwantedEmails_fr.markdown %});
* using the infected machine to host [malicious web servers]({% link _knowhow/glossary/MaliciousWebsites_fr.markdown %}), or servers with illegal content;
* using machines to carry out denial of service attacks, as a proxy, to click on links;
* targeted attacks.

opportunistic attacks are usually quite large scale, with malicious code used to provide remote access – in the best case scenario, this code will only be detected days later by the supplier's [anti-virus]({% link _knowhow/glossary/AntiVirus_fr.markdown %}) software. Generally speaking, the resident anti-virus never detects malware after detection and you need to use a live CD anti-virus for better detection.

## Victim of a targeted attack
As opposed to large-scale, opportunistic attacks, targeted attacks usually focus on a specific victim, often a single person within a targeted organisation. [Malicious code]({% link _knowhow/bestpractices/MaliciousSoftwareBP_fr.markdown %}) is specially designed for this type of attack, and in most cases slips through [anti-virus]({% link _knowhow/glossary/AntiVirus_fr.markdown %}) checks. Targeted attacks can be used as a vector for infection:

* buying access to a machine belonging to a specific organisation from a criminal carrying out opportunistic attacks;
* [social engineering]({% link _knowhow/glossary/SocialEngineering_fr.markdown %}) by email, with infected files (SMEs: see [Spam / Phishing]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2HR_fr.markdown %}#spam--phishing), [Social engineering / Inadequate communication]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2HR_fr.markdown %}#manipulation-of-people));
* social engineering by physical access and infection of targeted machines (SMEs: see [Infiltrating the premises]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure_fr.markdown %}#infiltrating-the-premises), [Insertion or removal of hardware]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware_fr.markdown %}#addition-or-removal-of-hardware), [Use of unapproved software]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Software_fr.markdown %}#use-of-unapproved-software), [Third-party use of access reserved for a single user]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2HR_fr.markdown %}#use-of-limited-access-by-a-third-party));
* social engineering  by physical access and deposit of infected [removable storage media]({% link _knowhow/glossary/RemovableDevices_fr.markdown %}) (SMEs: see [Infiltrating the premises]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure_fr.markdown %}#infiltrating-the-premises), [Insertion or removal of hardware]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware_fr.markdown %}#addition-or-removal-of-hardware));
* social engineering by sending physical post containing infected removable storage media;
* social engineering by offering an infected gift (during a conference, a trade fair, etc.);
* social engineering by attracting the victim to a [malicious website]({% link _knowhow/glossary/MaliciousWebsites_fr.markdown %});
* infection of digital hardware left unattended (airports, hotels, conference halls, etc.) (SMEs: see [Infiltrating the premises]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure_fr.markdown %}#infiltrating-the-premises), [Insertion or removal of hardware]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware_fr.markdown %}#addition-or-removal-of-hardware), [Use of unapproved software]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Software_fr.markdown %}#use-of-unapproved-software), [Use of access reserved for a user by a third party]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2HR_fr.markdown %}#use-of-limited-access-by-a-third-party), [Spam / Phishing]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2HR_fr.markdown %}#spam--phishing), [social engineering / inadequate communication]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2HR_fr.markdown %}#manipulation-of-people)).

It is very difficult to recognise an attack of this type. These codes make no “noise”, because they do not spread, or they only spread very slowly. They do everything to remain unnoticed so as to extract confidential information for as long as possible.

Malware activity may eventually be identified in firewall or proxy logs.

## Cleaning an infected machine
It is often difficult to tell whether a machine is infected, and it is even more difficult to clean it. The effort made and the method chosen need to be sufficient to match the criticality of the machine concerned.

* If it was an opportunistic attack and the machine does not hold any confidential data and is not used for critical operations, such as e-banking, you can try to clean the machine:
  * your anti-virus probably won’t detect the infection, because if it knew the malicious code used, it would have prevented infection in the first place. Remove the machine from the network and try to [disinfect the machine using a live CD from another anti-virus retailer]({% link _knowhow/glossary/DisinfectWithLiveCD_fr.markdown %}). Even better, wait four or five days before cleaning – recent malicious code slips through the anti-virus net for the first few days, until anti-virus manufacturers catch up and enter it into their anti-virus signature. Please note: disinfection by anti-virus may delete infected system files. The machine therefore risks not working properly after disinfection. The system should then be repaired using an installation disk, or the operating system may need a full reinstall.
* If you know exactly when your machine was infected and you have backups of your hard disk made from an earlier time, you can try to restore the backup. Don’t forget to reinstall all the necessary updates after the system restore.
* In other cases, we recommend a full reinstallation:
  * backup your data on an external hard drive;
  * format the disk and reinstall from your preferred installation disk (there is a small chance that the partition reset is also infected).
