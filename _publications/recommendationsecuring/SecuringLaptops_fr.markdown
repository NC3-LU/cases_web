---
layout: publication-list
category: "In depth articles"
title:  "Sécuriser les laptops"
menutitle: "Sécuriser les laptops"
logo:
date:  2017-11-06 00:00:00 +0100
short: "Recommendations"
categories: securing
toc: true
ref: securinglaptops
lang: fr
---
## En quelques mots
Les laptops sont des ordinateurs spéciaux dans le sens qu'ils peuvent non-seulement être transportés hors de l'entreprise mais aussi se brancher sur d'autres réseaux, parfois peu protégés comme des réseaux dans les hôtels.

Vu qu'ils peuvent en plus être transportés hors du périmètre de sécurité de l'entreprise ils sont soumis à des risques de perte, [vol]({% link _knowhow/glossary/PhysicalTheft_fr.markdown %}) ou [destruction]({% link _knowhow/glossary/PhysicalFaults_fr.markdown %}).

En général il faudrait considérer les laptops comme des ordnateurs externes à l'entreprise.

Les recommandations ci-dessous sont des recommandations prévues uniquement pour les ordinateurs portables, il est fortement conseillé de suivre aussi les recommandations générales pour [postes fixes]({% link _publications/recommendationsecuring/SecuringLaptops_fr.markdown %}) are also followed.

## Recommendations

1. Il est fortement recommandé de chiffrer le disque dur de l'ordinateur portable contenant des informations sensibles pour empêcher la fuite d'informations en cas de vol ou de perte. Dans ce contexte il est recommandé d'utiliser une méthode d'authentification forte (mot de passe très long, stick contenant la clé de chiffrement,...) pour le déchiffrement du disque.
2. Il est fortement recommandé de ne mettre sur l’ordinateur portable **que les données absolument nécessaires** à réaliser la mission à laquelle il doit servir. Ces données doivent nécessairement être chiffrées pour prévenir la perte de confidentialité en cas de vol (p.ex. avec un chiffrement à l’aide de truecrypt).
3. Il est fortement recommandé de doter l’ordinateur d’un **câble antivol** . Ce câble doit être utilisé dès que l’ordinateur portable est utilisé à l’extérieur de l’organisme.
4. Il est fortement recommandé de **personnaliser l'aspect** de votre ordinateur portable pour pouvoir l'identifier rapidement en cas d'un échange malicieux. Rédigez et faites respecter au sein de votre organisme une politique sectorielle pour la Sécurité physique et environnementale - [Sécurité des équipements hors locaux]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#off-site-equipment-security).
5. Il est fortement déconseillé d’utiliser des **réseaux WiFi**non chiffrés. Sur ces réseaux, tout traffic peut être enregistré et analysé. Rédigez et faites respecter au sein de votre organisme une politique sectorielle sur le Contrôle d'accès - [Utilisation de réseaux externes]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#use-of-external-networks).
6. Il est fortement déconseillé de connecter les ordinateurs portables directement au réseau interne de l'entreprise. Mettez en place un sous [réseau dédié]({% link _knowhow/glossary/NetworkSegmentation_fr.markdown %}) qui filtrera des attaques potentielles venues de laptops infectés.
7. Il est fortement déconseillé d’utiliser des **réseaux WiFi chiffrés respectivement des réseaux fixes** dans lesquels on n’a pas une confiance absolue. Mieux vaut utiliser dans ces cas-là son téléphone portable comme Mobile Hot Spot (tethering). Rédigez et faites respecter au sein de votre organisme une politique sectorielle sur le Contrôle d'accès - [Utilisation de réseaux externes]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#use-of-external-networks).
8. Il est fortement conseillé d’utiliser un **filtre de confidentialité** si l’ordinateur portable est utilisé pour travailler dans des lieux publics comme notamment les gares, trains ou aéroports et avions. Il s'agit d'un film plastique à mettre devant l'écran et qui empêche la lecture sur l'écran depuis un angle trop grand.
