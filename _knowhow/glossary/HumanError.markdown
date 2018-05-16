---
layout: article
title:  "Human error"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: knowhow
toc: true
---
<h3 class="titre-page" id="in-brief">In brief</h3>
Considering human errors as [threats]({% link _knowhow/glossary/Threat.markdown %}) may seem a little insensitive, yet as statistics from various organisations show, they are still a very common cause of IT incidents. 

“Human error” is defined as any human behaviour that does not fall under correct usage and may involuntarily result in various damages.

<h3 class="titre-page" id="types-of-error">Types of error</h3>
“Human error” is defined as any human behaviour that does not fall under correct usage and may involuntarily result in various [damages]({% link _knowhow/glossary/Impact.markdown %}). Voluntary acts committed with malicious intent are not considered errors.

Drawing up an exhaustive list of human errors would be impossible. It might not be possible to list all possibilities for human error, but it is, however, possible to identify some distinctive criteria that we can use to categorise human error.

### Errors through negligence
Actions carried out by people who understand the rules, but fail to apply them fall under this heading. Negligence can therefore be considered a voluntary act. However, negligence is rarely intended to be fraudulent.

Examples:

* not following procedures set out for saving data (SMEs: see [Unusable backups]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware.markdown %}\#unusable-backups)),
* deactivating the antivirus update when starting up the computer,
* sharing their password with a colleague (SMEs: see [Third-party use of access reserved for a single user]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2HR.markdown %}\#use-of-limited-access-by-a-third-party)),
* using the company’s IT architecture for personal use (SMEs: see [Misuse of organisation’s resources]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2HR.markdown %}\#misuse-of-it-resources))
* installing “non-standard” software on a machine, notably a computer or server (SMEs: see [Use of unapproved software]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Software.markdown %}\#use-of-unapproved-software) and [Malicious administrator]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2HR.markdown %}\#the-administrator)).

### Errors through incompetence
This category includes all errors committed unknowingly. A number of errors may be committed “in good faith”, without the user having realised they were acting irresponsibly or breaking a rule, and without them realising the consequences of their actions.

Examples:

* “social engineering” (see [point on this topic]({% link _knowhow/glossary/SocialEngineering.markdown %})),
* incorrect use of an IT tool,
* deletion of data.

<h3 class="titre-page" id="how-does-it-work">How does it work?</h3>
Human errors are unintentional threats that exploit different vulnerabilities, such as:

### Idleness and lack of conscientiousness
This category includes all acts committed through negligence and that are very difficult to combat, except by making employees accountable and using sanctions.

### Lack of training or security awareness
A person’s lack of awareness is a huge vulnerability, of which the result is a lack of awareness of the error committed and therefore the inability for the error to be detected and corrected by the person themself.

A person’s lack of training and security awareness is a vulnerability that can easily be exploited through the highly dangerous threat of [social engineering]({% link _knowhow/glossary/SocialEngineering.markdown %}).

<h3 class="titre-page" id="how-can-we-protect-ourselves">How can we protect ourselves?</h3>
The American mathematician Gilb’s Law of “unreliability” states that “Any system which depends on human reliability is unreliable.”.

There are multiple ways to combat human error. However, it is recommended that you focus on limiting the impact of human error and not get caught up in the idea that we will ever be able to avoid human error entirely. The primary countermeasures are as follows:

### Awareness
Increased awareness is an easy way to noticeably reduce risk.

Most people mean well and if they are aware of the importance of their daily actions, as well as the value of the data processed, they will make sure they treat it with due diligence.

### Training
The best way to avoid the incorrect handling of data and software is to train the users on how to use the software and devices.

### Implementation and control of procedures
It is vital to introduce procedures covering all important security-related aspects (access, backups, etc.). These procedures must be cyclically controlled and non-compliance should result in sanctions. These procedures are generally part of the [security policy]({% link _knowhow/CISOApproach.markdown %}).

### Double validation
In order to avoid data entry errors in critical software (e.g. electronic payment), it is a good idea to set up a duplicate data entry or double validation system.

### Error management and follow-up
As errors can’t be avoided entirely, it is important to learn from the consequences so they don’t happen again. Only a targeted analysis of the mistakes made and what caused them can prevent them being repeated in the future.

### Centralised administration
To minimise human error, it is advisable to limit access to software and data only to those persons who really need it: access management and [authentication]({% link _knowhow/glossary/Authentication.markdown %}).
