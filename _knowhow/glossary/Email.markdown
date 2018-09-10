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

## In brief
Le courrier électronique est une forme très populaire de communication sur Internet. À la base il consiste dans le transfert de texte en clair entre différents ordinateurs sur Internet. Le courrier électronique ou e-mail n'est donc pas adapté à l'envoi de données confidentielles. Néanmoins, certaines techniques de [chiffrement]({% link _knowhow/glossary/Cryptography.markdown %}), comme [OpenPGP](https://www.openpgp.org/), permettent d'assurer un haut degré de [confidentialité]({% link _knowhow/glossary/Confidentiality.markdown %}).

## Les risques associés
Beaucoup de [risques sont associés à l'utilisation de courriers électroniques]({% link _publications/bestpractices/EMail-BestPractices.markdown %}#risks-related-to-receiving-emails).

### Infrastructure
Il existe différents logiciels couvrant différents rôles dans la transmission d'e-mails sur Internet.

### MUA - MAIL USER AGENT
Le MUA (Mail User Agent) est le logiciel sur l'ordinateur qui permet d'envoyer des mails. En général il s'agit d'un logiciel installé comme Outlook ou Thunderbird mais peut aussi être une application web. Le MUA transfère un courrier électronique rédigé au MTA.

### MTA - MAIL TRANSFER AGENT
Le MTA (Mail Transfer Agent), parfois appelé serveur SMTP, s'occupe de recevoir et de renvoyer les courriers électroniques selon certaines règles définies par les administrateurs de ces services. Il peut y avoir un nombre arbitraire de MTA dans le chemin d'un mail; les MTA intermédiaires sont appelés «relays» et deviennent de plus en plus rares de nos jours car traditionnellement souvent utilisés pour du [SPAM]({% link _knowhow/glossary/SPAM-UnwantedEmails.markdown %}).

Le MTA de destination transfère le courrier au MDA en vue d'une distribution à l'utilisateur final.

### MDA - MAIL DELIVERY AGENT
Il s'agit ici de services (souvent pop3 ou imap) qui reçoivent le courrier, le stockent et attendent la connexion d'un MUA en vue de la transmission finale du courrier.

## Comment se protéger?
En fonction du besoin de confidentialité de vos communications (voire [classification]({% link _knowhow/cisoapproach/SecurityPolicy-Classification.markdown %}) des données), il convient de suivre certains conseils [comportementaux]({% link _publications/bestpractices/EMail-BestPractices.markdown %}#behavioural-measures), [organisationnels]({% link _publications/bestpractices/EMail-BestPractices.markdown %}#organisational-practices) et [techniques]({% link _publications/bestpractices/EMail-BestPractices.markdown %}#technical-measures) spécifiques à la manipulation des courriers électroniques. Suivez les [recommandations de sécurité pour les serveurs mail]({% link _publications/recommendationsecuring/Recommendations4securingEmailServer.markdown %}).
