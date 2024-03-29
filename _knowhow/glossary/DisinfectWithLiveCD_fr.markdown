---
layout: article
title:  "Désinfectez la machine avec un live CD"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: knowhow
toc: true
ref: glossarydisinfectthemachinelivecd
lang: fr
---

## En quelques mots
Un système d'exploitation live est un système d'exploitation qui peut être démarré depuis un CD et qui se charge complètement en mémoire, sans modifier de manière permanente l'ordinateur.

Ce systèmes permet de faire des analyses de l'ordinateur, sans que le système principal ne soit démarré. Il se prête donc parfaitement aux analyses d'antivirus ou autre opérations d'analyse criminalistique.

## Pourquoi l'utiliser?
Il est biensûr très important de posséder un [antivirus]({% link _knowhow/glossary/AntiVirus_fr.markdown %}) fonctionnel et mis à jour, qui puisse agir comme une première ligne de défense contre les [logiciels malveillants]({% link _knowhow/glossary/MaliciousCodes_fr.markdown %}). Malheureusement, l’installation d’un tel antivirus n’est pas une garantie absolue de sécurité. En effet, pour distinguer les programmes malveillants des programmes inoffensifs, les antivirus dépendent de signatures (empreintes des virus) que les créateurs d’antivirus mettent à disposition régulièrement sous forme de mises à jour. Parfois les virus peuvent être plus rapides et se nicher dans les systèmes d’exploitation avant que l’antivirus ne puisse les détecter. Comme certains possèdent des systèmes d’évasion, ils peuvent rester indétectés, même après le téléchargement de la signature adéquate. C'est pour cette raison qu'il est important de pouvoir analyser un système à un moment où tous ses éléments sont en veille (hors fonctionnement du système d'exploitation), et particulièrement les programmes malveillants éventuels.

Certains systèmes d'exploitation existent sous une forme spéciale dite « Live », avec un disque compact permettant le démarrage d’un ordinateur sans installation préalable et n’effectuant aucun changement sur l’ordinateur utilisé.

Des fabricants d’antivirus ont profité de ces systèmes d’exploitation éphémères pour créer des systèmes de détections de logiciels malveillants. Le système se charge sur votre ordinateur, charge l’antivirus et analyse vos disques durs tout en gardant votre système d’exploitation installé dormant, rendant ainsi la détection de [virus]({% link _knowhow/glossary/MaliciousCodes_fr.markdown %}#virus), [vers]({% link _knowhow/glossary/MaliciousCodes_fr.markdown %}#vers), [chevaux de Troie]({% link _knowhow/glossary/MaliciousCodes_fr.markdown %}#cheval-de-troie) et plus particulièrement de rootkits plus aisée.

## Où le trouver?
Dans les références de cet article vous trouverez quelques exemples de systèmes d'analyse de [code malicieux]({% link _knowhow/glossary/MaliciousCodes_fr.markdown %}). En général il s'agit de fichiers "image" à télécharger. Ces fichiers "image" doivent être gravés de manière spéciale sur CD ou DVD ; cherchez l'option "graver une image" dans votre logiciel de gravure.

## Comment s'en servir?
La plupart des ordinateurs sont configurés pour démarrer depuis le lecteur CD ou les sticks USB. Il suffira donc d'introduire le CD gravé (voire le stick) dans l'ordinateur et de le redémarrer. Si vous ne voyez pas l'écran de démarrage du live CD, mais que votre système d’exploitation habituel démarre, votre BIOS (système d'exploitation basique de l'ordinateur) n’est pas configuré pour démarrer sur CD. Ce réglage dépend de votre ordinateur et nous ne pouvons malheureusement que vous donner des pistes pour faire les réglages nécessaires :

Au début du démarrage appuyez sur la touche « Del », « F12 » ou « Esc » (si cette action ne marche pas, renseignez-vous auprès de votre fabriquant d'ordinateur). Cela ouvrira soit un menu de sélection du média de démarrage, soit le menu de configuration du BIOS de votre machine.

Si le menu de configuration du BIOS de votre machine est ouvert par cette action, sélectionnez l’option qui définit le lecteur CD comme média de démarrage prioritaire avant le disque dur.

Pendant le démarrage, une mise à jour des signatures des virus sera tentée. Pour cela il faut que l’ordinateur ait un accès direct à internet. Sachez que le wifi ne marchera pas la plupart du temps, pensez donc à utiliser un câble réseau pour la durée de la procédure.

Après un temps d’attente plus ou moins long (sachez être patient, en effet le lecteur CD est beaucoup plus lent qu’un disque dur), l’analyse du système sera lancée automatiquement.

Dans le cas d’une détection de logiciels malveillants, l’antivirus vous proposera certains modes d’action. Nous vous conseillons alors d’effacer les virus éventuels. Quand vous aurez fini, faites un clic droit sur le fond d’écran et cliquez sur l’option « Exit », comme illustré ci-dessus. Le système s’éteindra et éjectera le disque compact. N’oubliez pas de l’enlever pour redémarrer normalement votre système d’exploitation habituel.

## Précautions à prendre
Vu que les antivirus sur live CD n'utilisent pas le système d'exploitation de base de l'ordinateur, il est possible que celui-ci devienne inutilisable après détection et effaçage d'un logiciel malveillant profondément ancré. Gardez donc votre disque d'installation de votre système d'exploitation à portée de main et faites régulièrement des [sauvegardes]({% link _knowhow/glossary/DataBackups_fr.markdown %}).
