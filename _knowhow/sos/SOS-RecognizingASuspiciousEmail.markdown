---
layout: knowhow
category: "Knowhow"
title:  "SOS – Recognising a Suspicious E-mail"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: f-sos
toc: true
ref: sosrecognizeweirdemail
lang: en
---

## In Brief
[E-mail]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}#email) is one of the most favourite means of communication of cybercriminals. It is cheap to use, it does not require any identification on the part of the sender and the service is very quick.

E-mails can be used as a tool for many forms of attacks. This chapter will deal with analysing e-mails to find out how to recognise a suspicious e-mail without opening the links it contains or its attachments.

## E-mail From a Bank
Be aware that Luxembourg retail banks do not send e-mails. To communicate with their customers, instead, they send letters by post and communicate via their ‘e-banking’ platforms, or call their customers using an account manager known to them.

## Spam
[Spam]({% link _knowhow/glossary/SPAM-UnwantedEmails.markdown %}) is another name for an unsolicited e-mail. These can be advertising, hoaxes (fake messages) or [phishing]({% link _knowhow/glossary/Phishing.markdown %})-type attacks. Your service provider or your e-mail client should have the ability to recognise and flag spam.

Do not open spam unless you are certain that an e-mail flagged as spam is legitimate. Under no circumstances respond to spam. That will confirm to the sender that your e-mail address is valid.

## Impersonal E-mail
If you receive an [e-mail]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}#email) that does not mention you by name, be careful – it is probably a [spam]({% link _knowhow/glossary/SPAM-UnwantedEmails.markdown %}) mail.

A legitimate correspondent who knew your e-mail address would have your identifying information and use it to address you as appropriate.

Handle this type of e-mail with great care. If the e-mail contains any of the elements (detailed in the sections below), do not respond.

## E-mail Implying Urgency
If the e-mail does not address you by name and it implies urgency, it is very probably a hoax or [phishing]({% link _knowhow/glossary/Phishing.markdown %}). Do not respond to the request. Ignore this e-mail (See: [E-mail – best practices]({% link _knowhow/bestpractices/EMail-BestPractices.markdown %})).

## E-mail Containing a Link
If the e-mail does not address you by name and it contains a link, it is very probably trying to lure you to a [malicious website]({% link _knowhow/glossary/MaliciousWebsites.markdown %}) ([phishing]({% link _knowhow/glossary/Phishing.markdown %}) or infection by [malicious code]({% link _knowhow/bestpractices/MaliciousSoftwareBP.markdown %}) exploiting [technical vulnerabilities]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.markdown %}#managing-technical-vulnerabilities)). Whatever you do, do not click on that link (See: [E-mail – best practices]({% link _knowhow/bestpractices/EMail-BestPractices.markdown %})).

## E-mail With Attachment
If the e-mail does not address you by name and it includes an attachment, it is very probably an attempt to infect your machine with malware. Any type of file could include malicious code. Whatever you do, do not open the file. A lot of social engineering type of attacks operate based on infected files attached to e-mails exploiting human vulnerabilities ([See: E-mail – best practices](-)).

## Personal E-mail
Even if the e-mail is properly addressed to you, still take care and check the following elements:

### Known Sender
You know and trust the sender. The e-mail was expected and was announced during earlier communication – you can trust the e-mail and its contents. You should, however, remain wary of opening attachments which, despite everything else, could contain [malicious code]({% link _knowhow/bestpractices/MaliciousSoftwareBP.markdown %}) or links leading to [malicious websites]({% link _knowhow/glossary/MaliciousWebsites.markdown %}).

If the sender is known, but addresses you in an unfamiliar fashion, be very careful. The use of another language, a different style of writing or the unusual inclusion of spelling mistakes are very significant clues which may point to this e-mail being criminal. Handle with care and call up the sender (if you know the sender) to make sure the e-mail genuinely was sent by them.

([See: E-mail – best practices]({% link _knowhow/bestpractices/EMail-BestPractices.markdown %}))

### Unknown sender
You receive an e-mail from an unknown sender and the e-mail does not fall within a known and strictly professional context. Be careful when handling the content, including any attachments.

The e-mail could include attachments infected by [malicious code]({% link _knowhow/bestpractices/MaliciousSoftwareBP.markdown %}), or it could try to lure you into visiting [malicious websites]({% link _knowhow/glossary/MaliciousWebsites.markdown %}) by following a link posted in the message.

([See: E-mail – best practices]({% link _knowhow/bestpractices/EMail-BestPractices.markdown %}))
