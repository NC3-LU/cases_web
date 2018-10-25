---
layout: publication-list
title:  "Malicious software: best practice"
menutitle: "Malicious software: best practice"
logo:
date:  2017-11-06 00:00:00 +0100
short: "Behavioural measures to prevent from infection"
categories: f-bestpract
toc: true
ref: malicioussoftwarebp
lang: en
---
## In brief
Malicious software represents one of the greatest [threats]({% link _knowhow/glossary/Threat.markdown %}) to the whole IT system, regardless of its size. All types of operating systems are at risk, and all administrations, municipalities and companies can succumb to it.

Since they first came into existence, [cybercriminals]({% link _knowhow/glossary/Cybercriminals.markdown %}) have become significantly more sophisticated in the way they work and target their victims; malicious software or malware, one of their main tools, has naturally benefited from this. Nowadays, you’ll no longer find malicious software written for purely entertainment purposes. Currently, the most widely used malicious codes on the market are variations on the [Trojan horse]({% link _knowhow/glossary/MaliciousCodes.markdown %}#cheval-de-troie), which grant access to devices so they can be used either for illicit purposes or to steal confidential information.

Today, these malicious codes are primarily used to:

* steal confidential information (data extraction),
* attack online banking systems,
* send [spam]({% link _knowhow/glossary/SPAM-UnwantedEmails.markdown %})/[phishing]({% link _knowhow/glossary/Phishing.markdown %}) emails (SMEs: see [Spam]({% link _knowhow/glossary/SPAM-UnwantedEmails.markdown %})/[Phishing]({% link _knowhow/glossary/Phishing.markdown %}) and [Social engineering/Inadequate communication]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2HR.markdown %}#manipulation-of-people))
* carry out denial of service type attacks (SMEs: see [Denial of service attacks and distributed denial of service attacks]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}#denial-of-servicedistributed-service)),
* host illicit content

They present a large and omnipresent [threat]({% link _knowhow/glossary/Threat.markdown %}). Without preventative measures, protective measures and curative measures, an entity risks being considerably [impacted]({% link _knowhow/glossary/Impact.markdown %}).

## Infection vectors
There are a number of ways to infect a computer. The most commonly used include:

* infecting genuine websites (preferably those with high visitor counts). These suffer from opportunistic or targeted attacks. The attacker will take advantage of the website’s [technical vulnerabilities]({% link _knowhow/glossary/Vulnerabilities.markdown %}#technical-vulnerabilities), often the result of bad management, by trying to access the website management system either by exploiting default passwords or as a result of weak security. They then install tools so they can exploit technical vulnerabilities in the visitors’ browsers, or incite users to install the malicious codes themselves (e.g. fake [antiviruses]({% link _knowhow/glossary/AntiVirus.markdown %}) or fake video players).
* [malicious websites]({% link _knowhow/glossary/MaliciousWebsites.markdown %}) specifically designed to exploit the technical vulnerabilities of their visitors’ web browsers. As the visitors aren’t familiar with these websites, the attacker has to draw them in. To do so, he can:
  * lure victims by sending them [Spam]({% link _knowhow/glossary/SPAM-UnwantedEmails.markdown %}) containing links;
  * lure victims through [phishing]({% link _knowhow/glossary/Phishing.markdown %})-type attacks;
  * lure victims through adverts posted on frequently visited websites.
* [emails]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}#email) with infected attachments. This technique is used for both targeted and opportunistic attacks. Social engineering methods are used to manipulate the victims into opening the infected files.
* [removable devices]({% link _knowhow/glossary/RemovableDevices.markdown %}) containing infected files. Malicious codes exploit the technical vulnerabilities of the targeted computers. This method is primarily used for targeted attacks, using social engineering techniques.

## Impacts
As there are malicious codes all over the Internet, the chances of encountering one are extremely high (EBIOS [threats]({% link _knowhow/glossary/Threat.markdown %}), remote listening, software trap).

The [impacts]({% link _knowhow/glossary/Impact.markdown %}) caused are usually:

* Financial
  * Access to online banking may result in a loss of money. Pay particular attention to multi-line applications, as transactions are frequently made from company accounts and procedures often aren’t noticed until days, or even weeks, afterwards.
  * Loss of confidential information (intellectual property theft, theft of trade secrets, theft of strategic company data, theft of customer information) often results in a loss of money.
* Legal
  * If the infected computers are used for illicit purposes, the victim may face complaints (denial of service attacks, infection of visitor devices, hosting of illegal content, etc.).
  * The loss of confidential information, notably including data of a personal nature, may result in complaints received from the victims or from the CNPD.
* Impact on reputation
  * The use of an organisation’s website to infect visitors’ devices may result in serious problems for its brand image. Just like any type of trade, e-commence thrives on its consumers’ trust. A security incident may negatively impact this trust.
* Impact on “knowledge”
  * The theft or destruction of data relating to customer data or to trade secrets may result in a lack of knowledge.
* Impact on “time”
  * Analysing the compromised system, as well as getting the infected machines up and running again, may result in a significant loss of time.

## Behavioural measures
Whether the attack is targeted or opportunistic, a large number of malicious codes infiltrate their victims’ devices via infection vectors that play on human [vulnerabilities]({% link _knowhow/glossary/Vulnerabilities.markdown %}#human-vulnerabilities).

Before publishing malicious software, its authors check to see if it can be detected via websites such as [www.virtest.com](https://www.virtest.com).

The codes then often remain invisible to antivirus software for at least the first few days of the attack, which is enough time for the antivirus to collect the updated signatures. 

It is therefore vital for any organisation to train their employees and make them aware of the risks incurred by malicious codes and of commonly used infection vectors.

## Preventing infection
Infection with malicious codes can be prevented through responsible and careful behaviour when using [email]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}#email), [removable devices]({% link _knowhow/glossary/RemovableDevices.markdown %}) and when surfing the Internet.

Make sure you::

* observe [best practice relating to the use of email]({% link _knowhow/bestpractices/EMail-BestPractices.markdown %})
* avoid the use of unknown removable devices.
  * If you find any such devices, send them to your IT department for analysis. 
  * If you are given removable devices at conferences, have them analysed by experts before you use them.
  * Be very careful if anyone sends you a removable device. If you do not know the person who sent it to you, don’t use it. If it is someone you know, check with them to make sure they were the ones who sent it and remember to get the devices analysed by experts before you use them.

When surfing the Internet: 

* only open links on websites you trust entirely. Otherwise, you might be taken to a [malicious website]({% link _knowhow/glossary/MaliciousWebsites.markdown %}).
* pay attention to warnings from your web browser (“safe browsing” on [IE](https://www.microsoft.com/en-us/security/default.aspx), [Firefox](https://support.mozilla.org/en/US/kb/use-master-password-protect-stored-logins), [Chrome](https://support.google.com/chrome/answer/114836?hl=en&ref_topic=7437824)), or add-ons such as WOT.
* be wary of adverts that appear on websites that are not completely trustworthy. They may contain malicious codes or take you to [malicious websites]({% link _knowhow/glossary/MaliciousWebsites.markdown %}).

When travelling or on business trips, make sure you: 

* keep an eye on your IT equipment. Ill-intentioned persons could try to ambush it or install malicious codes. ([Threats]({% link _knowhow/glossary/Threat.markdown %}): see equipment traps, software traps). 

You should also remember that even equipment located within the organisation can be easily infected if ill-intentioned people gain access to it. (SMEs see: [Infiltrating the premises]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}#infiltrating-the-premises) and [Insertion or removal of hardware]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware.markdown %}#addition-or-removal-of-hardware) and [Use of unapproved software]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Software.markdown %}#use-of-unapproved-software)).

## Minimise the impacts
Each employee should know how to act in case of infection:  

* the infected device must be isolated and removed from the network;
* it must not be used again until the virus has been removed;
* it must be reported to the managers responsible for this type of incident immediately.

## Organisational practices
To prevent infection by malicious codes, organisational measures must be implemented. Draft and enforce the following sectoral policies:

* [Classification and monitoring of resources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources.markdown %})
  * [Classification of and responsibility for resources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources.markdown %}#classification-and-responsibility-for-resource)
* [Human factors]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown %})
  * [Security as a mission]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown %}#security-as-a-mission)
  * [Training and information]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown %}#training-and-information)
  * [Response to incidents and security malfunctions]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown %}#response-to-incidents-and-malfunctions)
* [Operational and communications aspects]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %})
  * [Email]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}#email)
  * [Protection against malware]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}#protection-against-malware)
* [Access control]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %})
  * [Access control policy]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#access-control-policy)
  * [Access rights management]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#access-rights-management)
  * [Use of external networks]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#use-of-external-networks)
  * [External connections]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#external-connections)
  * [Separation of networks]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#separation-of-networks)
* [Development and maintenance of systems]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.markdown %})
  * [Management of technical vulnerabilities]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.markdown %}#managing-technical-vulnerabilities)
* [Management of security incidents]({% link _knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents.markdown %})
  * [Reporting information security events]({% link _knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents.markdown %}#reporting-information-security-events)
  * [Incident management and improvements information security]({% link _knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents.markdown %}#incident-management-and-improvements-information-security)
  * [Analysis of non-fulfilment of obligations]({% link _knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents.markdown %}#analysis-of-non-fulfilment-of-obligations)
* [Managing business continuity]({% link _knowhow/cisoapproach/SecurityPolicy-ManagingBusinessContinuity.markdown %})
  * [Operational continuity]({% link _knowhow/cisoapproach/SecurityPolicy-ManagingBusinessContinuity.markdown %}#operational-continuity)
 
## Technical measures
In addition to behavioural and organisational measures, it is important to put in place technical measures to help prevent infections and reduce the impact of a potential infection.

The installation of the following technical measures is recommended:

* [antivirus]({% link _knowhow/glossary/AntiVirus.markdown %})<br />
  Antiviruses can detect a large number of malicious codes and prevent infection. Each computer within your organisation, as well as the file servers and email servers should have an antivirus installed. If possible, use a different antivirus for computers and for servers to increase the likelihood of malicious codes being detected. Update these antiviruses on a regular basis. Make sure users cannot deactivate the antivirus.
* [firewall]({% link _knowhow/glossary/Firewall.markdown %})<br />
  A firewall set up on a device can both prevent the device being infected as a result of [technical vulnerabilities]({% link _knowhow/glossary/Vulnerabilities.markdown %}#technical-vulnerabilities) and help detect a possible infection.
* [network segmentation]({% link _knowhow/glossary/NetworkSegmentation.markdown %}) firewall<br />
  A ‘company firewall’ may help prevent a virus from spreading throughout the whole company network. It can also prevent the exploitation of certain technical vulnerabilities thanks to the filtering of connection attempts via specific ports.
* [Web filter]({% link _knowhow/glossary/WebFilterProxy.markdown %})<br />
  Web filters can prevent computer infections by blocking malicious websites or those with a bad reputation.
* [patches<]({% link _knowhow/glossary/Patches.markdown %})br />
  Some malicious software tries to exploit technical vulnerabilities. These vulnerabilities can be corrected by patches. However, no system is ever really safe from technical vulnerabilities.
* [backups]({% link _knowhow/glossary/DataBackups.markdown %})<br />
  Backups are an effective way of preventing loss of availability and integrity. Unfortunately, they cannot prevent loss of confidentiality. Backups can also help to reduce the impact caused by the system being compromised by a destructive malicious code.
* [encryption]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.markdown %}#encryption)<br />
  Encryption can help reduce the likelihood of loss of confidentiality for highly confidential information in the event of infection.

## Virus removal
See: [SOS – I think my computer is infected]({% link _knowhow/sos/SOS-IThinkMyComputerInfected.markdown %})
