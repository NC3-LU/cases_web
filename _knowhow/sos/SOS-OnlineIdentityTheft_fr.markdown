---
layout: knowhow
category: "Knowhow"
title:  "SOS – Usurpation d'identité en ligne"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: f-sos
toc: true
ref: sosidtheft
lang: fr
---

## En quelques mots
Le vol d'identité en ligne peut résulter dans le [vol ou la perte de données]({% link _knowhow/glossary/DataLoss_fr.markdown %}), l'utilisation de l'identité pour des arnaques sur des connaissances, envoi de [spam]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2HR_fr.markdown %}#spam--phishing), distribution de [logiciels malveillants]({% link _knowhow/glossary/MaliciousWebsites_fr.markdown %}) ou avoir d'autres conséquences néfastes. Il est donc important de contrecarrer cette usurpation au plus vite pour limiter les dégâts.

En général le vol d'identité passe par le vol des données d'authentification de la victime.

## Comment le vol a-t-il eu lieu ?
Pour se défendre d'une usurpation d'identité il est important de savoir comment l'on a pu perdre ses données d'authentification :

* un ordinateur utilisé était infecté par un logiciel malveillant qui a envoyé vos données d'identification à l'attaquant ;
  * [votre ordinateur est infecté]({% link _knowhow/sos/SOS-IThinkMyComputerInfected_fr.markdown %});
  * vous avez utilisé votre mot de passe sur un ordinateur publique ou de peu de confiance;
* vous avez été la victime de phishing;
* votre mot de passe a été deviné;
* l'application en ligne que vous utilisiez a été compromise;
* vous vous êtes authentifié sur un réseau potentiellement hostile (wifi ouvert p. ex.) sans utiliser une  [communication chiffrée]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}#encryption).

Il existe néanmoins aussi des méthodes d'usurper des identités provisoirement sans voler les données d'authentification :

* vous vous êtes authentifié sur un ordinateur public et avez oublié de vous déconnecter;
* votre session a été volée sur un réseau  potentiellement hostile (vous n'avez pas utilisé de chiffrement);

## Mesures à prendre

* Si vous avez encore accès à votre compte procédez immédiatement à un changement de [mot de passe]({% link _knowhow/glossary/Password_fr.markdown %}), en observant les [bonnes pratiques]({% link _knowhow/bestpractices/MaliciousSoftwareBP_fr.markdown %}), sur un ordinateur de confiance (qui ne serait pas infecté).
* Si vous n'avez plus accès à votre compte, vous devez contacter les gestionnaires de l'application utilisé. La plupart des applications en ligne proposent en service de récupération de compte volé.
* N'utilisez plus d'ordinateurs qui ne vous appartiennent pas et suivez les bonnes pratiques en ce qui concerne les [Logiciels malveillants]({% link _knowhow/glossary/MaliciousWebsites_fr.markdown %}).
* Veillez à vérifier que le site sur lequel vous vous authentifiez est bien en [“https”]({% link _knowhow/glossary/SSLTLS-EncryptionTechnologiesOnWeb_fr.markdown %}).
