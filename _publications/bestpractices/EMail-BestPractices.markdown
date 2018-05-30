---
layout: publication-list
title:  "Email: good practices"
menutitle: "Email: good practices"
logo:
date:  2017-11-06 00:00:00 +0100
short: "Behavioural and technical measures to prevent risks related to sending emails"
categories: bestpractice
toc: true
---
<h3 class="titre-page" id="in-brief">In brief</h3>
Email is one of the primary forms of private and professional communication. It’s a user-friendly, fast and inexpensive tool. Despite its advantages, there are still some precautions to be taken into consideration when both sending and receiving messages.

While it is true that sending company emails internally does not carry the same risk of interception when the company has its own internal mail server, it is nevertheless important to remember that the information sent is not just saved on the company’s secure server. It can also be found in the sender and recipient’s mailboxes. Most of the time, these computers are both physically and logically significantly less well protected than the servers – and are therefore more vulnerable to attack – while containing, in some cases, the exact same information, with the same classification levels, as the servers.

Therefore, emails sent within the company are often the source of the inappropriate broadcasting or distribution of confidential or secret information. This information would be more secure if it were stored in a single, protected environment, with information that could be accessed according to classification level.

The problem with loss of information is also made worse by the use of laptop computers within the company.

For the company’s security, it is also important to set up, amongst other things, specific disposal procedures for [IT equipment]({% link _knowhow/sos/SOS-WhatBeforeGettingRidOldHardware.markdown %}).

<h3 class="titre-page" id="risks">Risks</h3>
Risks related to sending emails

* Loss of [confidentiality]({% link _knowhow/glossary/Confidentiality.markdown %}) as a result of:
  * sending [confidential]({% link _knowhow/glossary/Confidentiality.markdown %}) information by email (interception or [social engineering]({% link _knowhow/glossary/SocialEngineering.markdown %}));
  * sending confidential information to the wrong recipient;
  * adding new recipients during a discussion that previously contained confidential information;
  * due to a recipient in the same company forwarding their emails to an external mailbox to receive ‘push’ notifications on their smartphones;
  * logging in to their mailbox without [SSL]({% link _knowhow/glossary/SSLTLS-EncryptionTechnologiesOnWeb.markdown %});
  * the email server being compromised externally or internally (bad protection, bad configuration, weak administrator password, etc.);
  * the malicious extraction of confidential data by an employee;
  * the malicious extraction of confidential data from a badly protected workstation (physical security, access security, weak password or password that is visible on or near the workstation);
  * the theft of a computer with an email account;
  * the theft of an email server;
  * not following the data classification instructions;
* Loss of integrity due to multiple versions of a document distributed through multiple company mailboxes.

<h3 class="titre-page" id="risks-related-to-receiving-emails">Risks related to receiving emails</h3>

* Risk of loss of [confidentiality]({% link _knowhow/glossary/Confidentiality.markdown %}), [integrity]({% link _knowhow/glossary/Integrity.markdown %}) or [availability]({% link _knowhow/glossary/Availability.markdown %}) as a result of:
  * infection by [malicious software]({% link _knowhow/glossary/MaliciousCodes.markdown %}) through linked files;
  * infection by [malicious software]({% link _knowhow/glossary/MaliciousCodes.markdown %}) through links provided in emails;
* risk of loss of confidentiality due to being tricked into disclosing confidential information by [social engineering]({% link _knowhow/glossary/SocialEngineering.markdown %}) techniques;
* risk of loss of availability:
  * due to the presence of [spam]({% link _knowhow/glossary/SPAM-UnwantedEmails.markdown %});
  * due to hoaxes.

<h3 class="titre-page" id="behavioural-measures">Behavioural measures</h3>

* Make sure you don’t reveal any confidential information when replying to emails. Check the legitimacy of the request and be careful not to divulge too much information when you respond;
* the majority of [emails]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}]\#email) containing attachments are follow-ups to previous discussions, meaning that they fall within a special context in which the addition of attachments is to be expected. If this isn’t the case, be very careful when you receive an email with an attachment, as this attachment may contain [malicious codes]({% link _knowhow/glossary/MaliciousCodes.markdown %});
* ill-intentioned people often try to exploit human [vulnerability]({% link _knowhow/glossary/Vulnerabilities.markdown %}), such as curiosity, pity, fear, the lure of rewards, or even libido. If you receive an email that makes allusion to any of these things, it is highly likely it is a malicious email;
  * there are many types of malicious emails, including hoaxes, [phishing]({% link _knowhow/glossary/Phishing.markdown %}) emails, spear phishing emails (a highly targeted type of phishing), Nigerian scams, [malicious codes]({% link _publications/bestpractices/MaliciousSoftwareBP.markdown %}), and [spam]({% link _knowhow/glossary/SPAM-UnwantedEmails.markdown %});
* check if the email resembles those you have previously received from the supposed sender. The language used, way of writing, spelling, style, etc. may all be clues. If something seems odd, it’s probably a malicious email;
* never click on links in emails where you don’t know the sender, or in particular, if there are signs the email may be malicious, as it could be a phishing email or a link towards a fake website;
* never answer suspicious emails. By answering, you are confirming to the sender that the email address is active.

<h3 class="titre-page" id="organisational-practices">Organisational practices</h3>

* staff training in the [classification of data]({% link _knowhow/cisoapproach/SecurityPolicy-Classification.markdown %}) and associated rules;
* staff training in risks related to [social engineering]({% link _knowhow/glossary/SocialEngineering.markdown %});
* try to eliminate any procedures involving attachments;
* if opening attachments is necessary:
  * wait 4 days before opening attachments. Waiting this long gives the [antivirus]({% link _knowhow/glossary/AntiVirus.markdown %}) a chance to detect [malicious codes]({% link _publications/bestpractices/MaliciousSoftwareBP.markdown %}). A minimum of 3 to 4 days is necessary to detect a new virus when it first appears and add it to the signature database for the corresponding [antiviruses]({% link _knowhow/glossary/AntiVirus.markdown %}).
* equip PCs used to open attachments with a less common operating system that is therefore subject to fewer attacks, e.g. ‘Linux’;
* call the person who sent you a suspicious email and ask them if they did indeed send it. Tell them why you thought the email was suspicious;
* avoid opening emails on critical [assets]({% link _knowhow/glossary/Assets.markdown %}) or those which have access to critical assets, such as [confidential]({% link _knowhow/glossary/Confidentiality.markdown %}) information or indispensable assets.

<h3 class="titre-page" id="applicable-sectoral-policies">Applicable sectoral policies</h3>
Draw up and enforce the following sectoral policies:

* [Classification and monitoring of resources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources.markdown %})
  * [Classification of and responsibility for resources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources.markdown %}\#classification-and-responsibility-for-resource)
* [Human factors]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown %})
  * [Training and information]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown %}\#training-and-information)
* [Operational and communications aspects]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %})
  * [Protection against malware]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}\#protection-against-malware)
  * [Email]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}\#email)
* [Access control]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %})
  * [Use of external networks]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}\#use-of-external-networks)
  * [External connections]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}\#external-connections)
  * [Separation of networks]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}\#separation-of-networks)
  * [Login procedure]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}\#connection-procedures)
* [Development and maintenance of systems]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.markdown %})
  * [Use of encryption]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.markdown %}\#encryption)
  * [Electronic signatures]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.markdown %}\#electronic-signatures)
* [Management of security incidents]({% link _knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents.markdown %})
  * [Reporting information security events]({% link _knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents.markdown %}\#reporting-information-security-events)
* [Compliance]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance.markdown %})
  * [Intellectual property]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance.markdown %}\#intellectual-property)
  * [Protection of operational data]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance.markdown %}\#protection-of-operational-data)
  * [Personal data protection]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance.markdown %}\#personal-data-protection)

<h3 class="titre-page" id="technical-measures">Technical measures</h3>

* Make sure your [antivirus]({% link _knowhow/glossary/AntiVirus.markdown %}) software is always up to date. Normally, updates are downloaded automatically;
* Do not use the same antivirus software on both the email server and on the workstations. This increases the likelihood of discovering malicious software. No antivirus detects more than 80% of existing [malicious codes]({% link _publications/bestpractices/MaliciousSoftwareBP.markdown %});
* do not work at a workstation when logged on in administrator mode. Malicious codes run on these workstations will inherit your rights and will therefore be able to access and install programs on all of the computer’s accounts;
* activate the [spam]({% link _knowhow/glossary/SPAM-UnwantedEmails.markdown %}) filter in your email software;
* [encrypt]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.markdown %}\#encryption) the content of your laptop computers;
* dutifully adhere to the equipment disposal instructions, both for servers and for computers and GSM;
* use strong [authentication]({% link _knowhow/glossary/Authentication.markdown %}) tools for your webmail solutions (OTP, LuxTrust);
* only use secure [SSL]({% link _knowhow/glossary/SSLTLS-EncryptionTechnologiesOnWeb.markdown %}) log-ins for your webmail solutions.
