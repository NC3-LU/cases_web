---
layout: knowhow
category: "Knowhow"
title:  "Security Measures for Small and Medium-Sized Enterprises – Threats to Human Resources"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: f-bestpract
toc: true
ref: bestpractthreatstohr
lang: en
---
## Manipulation of People
Social engineering is one of the most frightening techniques used to attack users of an IT system.  [Social engineering]({% link _knowhow/glossary/SocialEngineering.markdown %}) is based on subtle psychological techniques that get people to share the desired information.  By exploiting human vulnerabilities, e.g. the desire to help a peer or the need to impress a superior, an ill-intentioned person can obtain access to data and confidential systems from an individual.

To avoid the involuntary disclosure of information, it is important to make staff aware of the general principles of 'social engineering' and teach them the appropriate ways to react and communicate. This means, amongst other things:

* training employees in communication and the protection of the organisation’s image (in particular during email communication, participation in discussion forums, contact with the media, etc.) (Draft and enforce a Sectoral policy on Human factors – [Training and information]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown %}#training-and-information));
* making employees aware of good security practises outside the organisation’s perimeter;
* attributing a unique code to each employee who calls the help desk;
* establishing better identity checks for information requests (Draft and enforce a Sectoral policy on [the Classification and control of resources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources.markdown %}));
* checking and tracing long-distance calls – or securing telephone servers (PBX).

## Human Error: Prevention Measures
There is a large range of human errors, going from inadvertently sending an email to the wrong person right up to the accidental deletion of vital company data.

The best chance to avoid such errors is to provide:

* adequate staff training (Draft and enforce a Sectoral policy on Human factors – [Training and information]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown %}#training-and-information));
* a reminder of the backup measures for sensitive files (Draft and enforce a Sectoral policy on Operational and communication aspects – [Data backups]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}#data-backups));
* a double validation system for critical operations;
* a log of operations carried out on sensitive information (paper register, audit logs).

## Misuse of IT Resources
IT resources available to users may be misappropriated for personal use.  An organisation must respect the privacy of its employees just as the employees should not exploit the IT infrastructure for personal use during their working day, in particular regarding the use of the Internet and electronic messaging. You could, for example, include:

* a paragraph in the charter that clearly indicates what would be considered misuse, within the confines of respect of privacy at the workplace;
* a restrictive usage policy regarding software set out at operating system level (Draft and enforce a Sectoral policy on the [Classification and control of resources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources.markdown %}) and a Sectoral policy on Access control – [Access control policy]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#access-control-policy) and [Access rights management]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#access-rights-management));
* website filtering (Draft and enforce a Sectoral policy on Access control – [Use of external networks]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#use-of-external-networks));
* blocking external incoming and outgoing emails (Draft and enforce a Sectoral policy on Operational and communication aspects – [Emails]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}#email)).

## Staff Absences
The availability of the information system is linked to the availability of staff in general. Ideally, you should ensure that all information is accessible at all times. This can be organised through the use of authorisations, the implementation of a staff rota and on-call service, which is all the more important where system administrators are concerned. It may be useful to introduce the following elements:

* provisional calendar of absences;
* task delegation system (who does what when a particular person is absent) (Draft and enforce a Sectoral policy on Access control – [Access control policy]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#access-control-policy) and [Access rights management]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#access-rights-management));
* keep a record of the employees’ personal telephone number to establish an alert network (Draft and enforce a Sectoral policy on Human aspects – [Responding to incidents and malfunctions]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown %}#response-to-incidents-and-malfunctions)).

## The Administrator
Information system administrators, as part of their role as a supervisor, have specific access permissions. They can, therefore, have access to all information stored in the IT system and, in the event of a cyberattack, block access to the information system. As a security measure, it is useful to ensure:

* a log of administration operations on sensitive data and the configuration of authorisations;
* that administrators are made aware of their legal responsibilities (Draft and enforce a Sectoral policy on Human factors – [Training and information]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown %}#training-and-information));
* the implementation of measures linked to the “[administration impossible]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Software.markdown %}#unavailability-of-administrators)” security problem.

## Spam / Phishing
[Spam]({% link _knowhow/glossary/SPAM-UnwantedEmails.markdown %}) is unsolicited email. This type of advertising email is sent to the owner of the mailbox in the aim of getting them to view a service/product or a website. In the best-case scenario, the time wasted and electronic space taken up by this type of email may unnecessarily overload an information system and must, as a result, be fought against. Furthermore, the spam could also contain malicious software and so become a concrete threat to the organisation’s assets.

[Phishing]({% link _knowhow/glossary/Phishing.markdown %}) is a special social engineering technique that primarily uses emails and aims to obtain personal information (bank account details, in particular) by claiming to be a trusted organisation (e.g. a bank) via a fraudulent website. This type of attack is primarily aimed at individuals, but the company’s vital information may also be targeted.

Both of these threats currently plague email inboxes. You can guard against them by doing the following:

* setting up an anti-spam filter (client or server) (Draft and enforce a Sectoral policy on Operational and communication aspects – [Emails]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}#email));
* making employees aware of best practice in this area, for example:
  * ignoring all spam or phishing emails;
  * ensuring that email addresses are only shared with your express permission. Some service providers may automatically register you in a web directory. (Draft and enforce a Sectoral policy on Human aspects – [Training and information]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown %}#training-and-information));
* as far as possible, avoid publishing your email address on forums or websites;
* keeping confidential information secret (e.g. credit card) (Draft and enforce a Sectoral policy on the [Classification and control of resources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources.markdown %}));
* restricting who can view the organisation’s electronic directory.

## Use of Limited Access by a Third Party
To be able to access an information system, users are given access rights according to their IT system user profile. The  simplest case is physical access to a device. When a third party uses a resource without having been authorised to do so, we call that intrusion. When a third party uses a user’s rights to access a resource, we call that identity fraud. It is important to ensure that authentication always entails identification and that physical intrusion is avoided. It is useful:

* to lock all electronic equipment after use or, failing this, after a set amount of time (Draft and enforce a Sectoral policy on Access control – [Access control policy]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#access-control-policy) and [Connection procedures]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#connection-procedures));
* prohibit the lending of keys, badges, passwords (Draft and enforce a Sectoral Policy on Access control – [Password management]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#password-management));
* track events regarding sensitive locations and data.
