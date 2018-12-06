---
layout: article
title:  "Phishing"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: knowhow
toc: true
ref: glossaryphishing
lang: fr
---
## En quelques mots
Le phishing, ou hameçonnage, ou, plus rarement filoutage, est une technique utilisée par des pirates informatiques pour obtenir des renseignements personnels dans le but de perpétrer une usurpation d'identité. La technique consiste à faire croire à la victime qu'elle s'adresse à un tiers de confiance — banque, administration, etc. — afin de lui soutirer des renseignements personnels : mot de passe, numéro de carte de crédit, date de naissance, etc. C'est une forme d'attaque informatique reposant sur [l'ingénierie sociale]({% link _knowhow/glossary/Phishing_fr.markdown %}). Elle peut se faire par courrier électronique, par des sites webs falsifiés ou par d'autres moyens électroniques.

Les criminels informatiques utilisent généralement le phishing pour voler de l'argent. Les cibles les plus courantes sont les services bancaires en ligne, les fournisseurs d'accès à Internet et les sites de ventes aux enchères tels qu'eBay et PayPal. Les adeptes du phishing envoient habituellement des courriels à un grand nombre de victimes potentielles.

## Comment reconnaître le phishing

Un phish (courrier électronique utilisé dans une attaque phishing) peut généralement être reconnu via les indices suivants :

* le courrier électronique s'adresse à vous de manière impersonnelle
* le courrier électronique suggère de réagir rapidement
* le courrier électronique contient un lien qu'il faut suivre

Si un de ces indices s'applique au courrier électronique reçu, il convient de l'ignorer. Refuser de suivre le lien proposé. Si vous avez des doutes sur la véracité du message, vous pouvez également ouvrir vous-même votre navigateur et entrer l'adresse du site que vous voulez visiter.
Mesures comportementales

La mesure comportementale la plus importante consiste à ignorer les liens proposés dans des [courriers électroniques]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#email), ou se trouvant sur des sites que vous ne connaissez pas.

## Mesures organisationnelles

En France, les internautes sont invités à communiquer avec la cellule de veille de la police nationale pour témoigner de leurs propres (mauvaises) expériences ou de leur envoyer des liens conduisant à des sites qu'ils jugent contraires aux lois.
Il existe des associations à but non lucratif qui aident les internautes à se protéger contre ce genre de fraudes :

* [PhishTank](https://www.phishtank.com)
* [Phishing Initiative](https://phishing-initiative.fr/contrib)
* [APWG](https://apwg.org)

## Mesures techniques
Les mesures techniques suivantes peuvent être mises en place :

* Filtre SPAM dans votre client courrier électronique
  * Les attaques de type phishing sont généralement des attaques de grande envergure. Il est donc probable que votre client courrier électronique reconnaisse qu'il s'agit d'un spam et le marque en fonction.
* Filtre Phishing dans votre navigateur
  * Les navigateurs modernes peuvent identifier des sites de phishing. Activez ce filtre pour que votre navigateur vous mette en garde contre de telles attaques :
  * [Google Chrome et sécurité du navigateur](https://support.google.com/chrome/answer/114836?hl=fr&ref_topic=7437824)
  * [Phishing filtre de mozilla firefox](https://support.mozilla.org/en-US/kb/how-does-phishing-and-malware-protection-work)
  * [Smart screen de Microsoft](https://www.microsoft.com/en-us/security/default.aspx)
* Utilisez l'ajout ([Web of Trust - WOT]({% link _knowhow/glossary/WOT_fr.markdown %}))
* Utilisez un [filtre web]({% link _knowhow/glossary/WebFilterProxy_fr.markdown %}) (proxy)
