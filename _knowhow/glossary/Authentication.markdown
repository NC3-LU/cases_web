---
layout: article
title:  "Authentication"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: knowhow
toc: true
ref: glossaryauthentication
lang: en
---

## In Brief
Our society is largely based on the innate ability of humans to recognise their fellow humans. Humans have a highly evolved identification system with multiple factors such as appearance, voice, manner of speech, posture, etc.

This human skill is something that is sorely lacking in computers. Although automated facial recognition systems do exist, they are far from perfect. The 'shared secret' – the password – remains the predominant authentication factor for a computer. However, machine authentication factors are still far from our natural ability to recognise people and they are often, therefore, the weak link in information security. Indeed, people still do not take authentication seriously. Rather, most of us consider it to be a necessary evil. But this is often the only protection that users have against the fraudulent use of their online identity.

###Authentication Factors
Authentication on a computer is performed in different ways, classified here according to four factors:

### Authentication Using Something You Know
This is usually a password or a PIN code. The advantage of this identification method is its simplicity and familiarity for most people. However, it has many disadvantages:

* A [password]({% link _knowhow/glossary/Password.markdown %}) can easily be copied without the knowledge of the legitimate user. A user's password can be stolen, for example, in '[malicious codes]({% link _knowhow/bestpractices/MaliciousSoftwareBP.markdown %})' or '[phishing' attack]({% link _knowhow/glossary/Phishing.markdown %}); saving them on a website without [SSL]({% link _knowhow/glossary/SSLTLS-EncryptionTechnologiesOnWeb.markdown %}) security, or by the mere fact that someone looks over your shoulder and notes your password when you log in ('shoulder surfing').
* Many people use passwords that can easily be guessed by others, as shown by a [study conducted following the exfiltration of passwords from rockyou.com](https://www.imperva.com/docs/gated/WP_Consumer_Password_Worst_Practices.pdf).
* Many people use the same password for different applications. If a hacker manages to compromise one of these applications using your password, he will probably try the same password to infiltrate other applications.

### Authentication by Something You Own
This authentication method generally uses a key providing physical access to the computer, a cryptographic card kept in a wallet or a 'TAN' type card.

The level of security used for this identification method depends on how easy it is to make copies of the tool in question.

It is for example very easy to copy a TAN card (by photo, by photocopier); it is also easy to duplicate a key.

However, it is impossible to make a copy of a '[LuxTrust](https://www.luxtrust.lu/en/product_page/61)' card. The advantages of this authentication system are as follows:

* the certainty that the card cannot be reproduced
* three incorrect authentication attempts to block the card
* if it is lost, the card can be cancelled and will not work anymore, even if the thief has the PIN code.

### Authentication by Something That You Are
This involves fingerprint authentication or recognition by the layout of the veins of your hand or the image of your retina.

### Authentication by Something You Know How to Do
This most often involves the user copying a distorted word (the well-known "captcha" fields, where you are asked to copy a word for example). This identification method makes it possible to differentiate humans from computers, but not human beings from one another, because most human skills are shared by large groups of the population and identification would not be unambiguous.

## Multi-Factor Authentication
Multi-factor [authentication]({% link _knowhow/glossary/Authentication.markdown %}) means the use of at least two of the first three authentication factors. The more forms of authentication used, the greater the level of information access security.

It should not be forgotten that the more an online asset or service attracts the interest of [hackers]({% link _knowhow/glossary/Cybercriminals.markdown %}), the more effort they will put into getting it. This is why online services are secured at different levels. The ideal access security would be to always use multi-factor authentication. Unfortunately, the cost of implementation, the accessibility of technology and the constant developments in security solutions mean that this behaviour is not yet a reality for users. Few people have a fingerprint reader and even fewer are willing to carry it when they travel. Hence, the most common form of authentication is the password, i.e. where the user shares secret information with the computer that the computer can identify.

## Security Policy
Draft and enforce the following sectoral policies:

* [Classification and monitoring of resources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources.markdown %})
  * [Classification of and responsibility for resources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources.markdown %}#classification-and-responsibility-for-resources)
* [Access control]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %})
  * [Access control policy]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#access-control-policy)
  * [Access rights management]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#access-rights-management)
  * [Password management]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#password-management)
  * [Login procedure]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#connection-procedures)
