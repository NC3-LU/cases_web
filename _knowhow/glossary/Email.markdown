---
layout: article
title:  "Email"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: knowhow
toc: true
ref: glossaryemail
lang: en
---

## In Brief
E-mail is a very popular form of communication. It involves the transfer of plain text between different computers on the Internet. Electronic mail or e-mail is not suitable for sending confidential data. However, certain [encryption]({% link _knowhow/glossary/Cryptography.markdown %}) techniques, such as [OpenPGP](https://www.openpgp.org/), ensure a high degree of [confidentiality]({% link _knowhow/glossary/Confidentiality.markdown %}).

## Associated Risks
There are many [risks associated with the use of e-mail]({% link _knowhow/bestpractices/EMail-BestPractices.markdown %}#risks-related-to-receiving-emails).

### INFRASTRUCTURE
Different software programs cover different roles in transmitting e-mail over the Internet.

### MUA - MAIL USER AGENT
The MUA (Mail User Agent) is the software on the computer that allows you to send e-mails. In general, it is an installed software like Outlook or Thunderbird, but it can also be a web application. The MUA forwards an e-mail written to the MTA.

### MTA - MAIL TRANSFER AGENT
The MTA (Mail Transfer Agent), sometimes called the SMTP server, takes care of receiving and resending e-mails according to certain rules defined by the administrators of these services. There can be an arbitrary number of MTAs in the path of an e-mail; intermediate MTAs are called ‘relays’ and are becoming rarer these days because traditionally often used for [SPAM]({% link _knowhow/glossary/SPAM-UnwantedEmails.markdown %}). 

The destination MTA forwards mail to the MDA for delivery to the end-user.

### MDA - MAIL DELIVERY AGENT
These are services (often POP3 or IMAP) which receive the mail, store it, and wait for the connection of an MUA for the final transmission of the mail.

## How to Protect Yourself?
Depending on the need for confidentiality of your communications (or even [classification]({% link _knowhow/cisoapproach/SecurityPolicy-Classification.markdown %}) of data), certain [behavioural]({% link _knowhow/bestpractices/EMail-BestPractices.markdown %}#behavioural-measures), [organisational]({% link _knowhow/bestpractices/EMail-BestPractices.markdown %}#organisational-practices) and [technical]({% link _knowhow/bestpractices/EMail-BestPractices.markdown %}#technical-measures) advice specific to the handling of e-mails should be followed. Follow the [security recommendations for mail servers]({% link _publications/recommendationsecuring/Recommendations4securingEmailServer.markdown %}).
