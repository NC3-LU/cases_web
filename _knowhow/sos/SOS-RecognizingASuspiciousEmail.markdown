---
layout: knowhow
category: "Knowhow"
title:  "SOS – Recognising a suspicious email"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: f-sos
toc: true
ref: sosrecognizeweirdemail
lang: en
---

## In brief
[Email]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}#email) is one of the most favourite means of communication of cybercriminals. It is cheap to use, it does not require any identification on the part of the sender and the service is very quick.

Emails can be used as a tool for many forms of attacks. This chapter will deal with analysing emails to find out how to recognise a suspicious email without opening the links it contains or its attachments.

## Email from a bank
Be aware that Luxembourg retail banks do not send emails. To communicate with their customers, instead, they send letters by post and communicate via their ‘e-banking’ platforms, or call their customers using an account manager known to them.

## Spam
[Spam]({% link _knowhow/glossary/SPAM-UnwantedEmails.markdown %}) is another name for an unsolicited email. These can be advertising, hoaxes (fake messages) or [phishing]({% link _knowhow/glossary/Phishing.markdown %})-type attacks. Your service provider or your email client should have the ability to recognise and flag spam.

Do not open spam unless you are sure an email flagged as spam is legitimate. Under no circumstances respond to spam. That will confirm to the sender that your email address is valid.

## Impersonal email
If you receive an [email]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}#email) that does not mention you by name, be careful – it is probably a [spam]({% link _knowhow/glossary/SPAM-UnwantedEmails.markdown %}) mail.

A legitimate correspondent who knew your email address would have your identifying information and use it to address you as appropriate.

Handle this type of email with great care. If the email contains any of the elements (detailed in the sections below), do not respond.

## Email implying urgency
If the email does not address you by name and it implies urgency, it is very probably a hoax or [phishing]({% link _knowhow/glossary/Phishing.markdown %}). Do not respond to the request. Ignore this email. (See: [Email – best practices]({% link _knowhow/bestpractices/EMail-BestPractices.markdown %})).

## Email containing a link
If the email does not address you by name and it contains a link, it is very probably trying to lure you to a [malicious website]({% link _knowhow/glossary/MaliciousWebsites.markdown %}) ([phishing]({% link _knowhow/glossary/Phishing.markdown %}) or infection by [malicious code]({% link _knowhow/bestpractices/MaliciousSoftwareBP.markdown %}) exploiting [technical vulnerabilities]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.markdown %}#managing-technical-vulnerabilities)). Whatever you do, do not click on that link. (See: [Email – best practices]({% link _knowhow/bestpractices/EMail-BestPractices.markdown %})).

## Email with attachment
If the email does not address you by name and it includes an attachment, it is very probably an attempt to infect your machine with malware. Any type of file could include malicious code. Whatever you do, do not open the file. A lot of social engineering type of attacks operate based on infected files attached to emails exploiting human vulnerabilities. ([See: Email – best practices](-))

## Personal email
Even if the email is properly addressed to you, still take care and check the following elements:

### Known sender
You know and trust the sender. The email was expected and was announced during earlier communication – you can trust the email and its contents. You should, however, remain wary of opening attachments which, despite everything else, could contain [malicious code]({% link _knowhow/bestpractices/MaliciousSoftwareBP.markdown %}) or links leading to [malicious websites]({% link _knowhow/glossary/MaliciousWebsites.markdown %}).

If the sender is known, but addresses you in an unfamiliar fashion, be very careful. The use of another language, a different style of writing or the unusual inclusion of spelling mistakes are very significant clues which may point to this email being criminal. Handle with care and call up the sender (if you know the sender) to make sure the email genuinely was sent by them.

([See: Email – best practices]({% link _knowhow/bestpractices/EMail-BestPractices.markdown %}))

### Unknown sender
You receive an email from an unknown sender and the email does not fall within a known and strictly professional context. Be careful when handling the content, including any attachments.

The email could include attachments infected by [malicious code]({% link _knowhow/bestpractices/MaliciousSoftwareBP.markdown %}), or it could try to lure you into visiting [malicious websites]({% link _knowhow/glossary/MaliciousWebsites.markdown %}) by following a link posted in the message.

([See: Email – best practices]({% link _knowhow/bestpractices/EMail-BestPractices.markdown %}))
