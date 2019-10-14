---
layout: knowhow
category: "Knowhow"
title:  "SOS – Quelqu'un me demande des informations confidentielles"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: f-sos
toc: true
ref: sosaskedforconfidentialinfo
lang: fr
---

## En quelques mots
Vérifier le niveau de [classification]({% link _knowhow/cisoapproach/SecurityPolicy-Classification_fr.markdown %}) des informations demandées. Ensuite, assurez-vous que :

* le demandeur puisse être identifié de manière satisfaisante, correspondant au niveau requis pour la criticité de l'information (si une information secrète ou confidentielle est demandée, l'identité du demandeur doit être déterminée avec certitude) ;
* le demandeur soit habilité à détenir cette information ([politique de contrôle d'accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-control-policy));
* la criticité de l'information autorise l'utilisation du canal de communication proposé ([politique sectorielle sur la classification et la maîtrise des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %})).

Si ces trois conditions sont remplies, la transmission peut avoir lieu. En cas de doute, refusez de communiquer les informations demandées.

## Vérifier l'identité d'une personne
Il est très difficile de s'assurer de l'identité d'une personne :

* L'identité de l'expéditeur d'un [email]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#email) ne peut être vérifiée que si le courrier est signé électroniquement et que le moyen utilisé donne lieu au niveau de confiance nécessaire.
* L'identité d'une personne au téléphone est très difficile à vérifier. Le numéro de téléphone affiché peut être falsifié ('caller id spoofing'). Il existe aussi des moyens pour falsifier le timbre de la voix. Une certain niveau d'assurance peut être établi lorsqu'on propose de rappeler le numéro affiché, tout en vérifiant qu'il appartient bel et bien à l'interlocuteur prétendu.

## Vérifiez la légitimité de la demande
Avant de transmettre des informations à une personne identifiée, vérifiez si cette personne est habilitée à recevoir les informations souhaitées. Cela dépend évidemment du contexte dans lequel on se trouve est dépend en partie du bon sens, de la politique de sécurité mise en place ou de différentes autres règles définies au sein de l'organisation.

## Choisir le canal de communication
Avant de transmettre une information, veillez à choisir le canal de communication adéquat, correspondant au niveau de criticité des données à transmettre. Rappelez-vous que :

* Le courrier électronique n'assure aucun niveau de confidentialité. En utilisant des moyens de [cryptographie]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}#encryption) forts, l'utilisation de courriers électroniques est envisageable.  La clé de chiffrement doit cependant encore être transférée de façon sécurisée, sans passer par le courrier électronique; il faut donc utiliser des moyens sécurises d'échange de clés ou de la [cryptographie asymétrique]({% link _knowhow/glossary/Cryptography_fr.markdown %}). Voir aussi [Email: bonnes pratiquess]({% link _knowhow/bestpractices/EMail-BestPractices_fr.markdown %}) et [OpenPGP](https://www.openpgp.org).
* Les réseaux de téléphonie fixe ainsi que les réseaux GSM sont nettement plus sûrs (même si dans certains cas leur écoute est possible) et peuvent être utilisés pour échanger des mots de passe.
