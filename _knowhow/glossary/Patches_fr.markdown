---
layout: article
title:  "Correctifs - patch"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: knowhow
toc: true
ref: glossarypatches
lang: fr
---
## En quelques mots
Les failles peuvent dans certains cas servir de porte d'entrée à des codes malicieux ou des sites malveillants qui cherchent à obtenir un accès non-autorisé sur la machine. Il est donc important de les corriger en appliquant des correctifs, parfois appelés patchs.

Un patch ou correctif est une mise à jour, sous forme de fichier ou logiciel, visant à corriger les failles de sécurité d'un système d'exploitation ou logiciel.

Dans certains cas, le patch va non seulement corriger une faille, mais également ajouter de nouvelles fonctionnalités au logiciel informatique ou au système d'exploitation.

## Cycle de vie
Le cycle de vie d'un patch de sécurité commence dans la majorité des cas par la notification de la faille par le constructeur du logiciel, voire directement par une annonce publique. Dans des cas limités, et en fonction de certaines lois et réglementations nationales, l'annonce publique sans autorisation de la part du constructeur peut être considérée comme illicite.

A partir de cet instant et dans un laps de temps arbitraire, le constructeur de logiciel valide l'existence de la faille par une annonce ou la publication d'un bulletin de sécurité.

Dans la plupart des cas, cette annonce est accompagnée simultanément de la mise à disposition d'un correctif (patch) permettant de corriger la faille existante.

## Mesures comportementales
Les mises à jour sont importantes à faire. L'adage «Never touch a running system» n'est pas valable du point de vue de la sécurité.

Évidemment il faut néanmoins rester tout aussi prudent que lors de l'installation de nouveaux programmes.

## Mesures organisationnelles
L'organisme doit rédiger et faire respecter une politique sectorielle pour le développement et la gestion des systèmes – [gestion des vulnérabilités techniques]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}#managing-technical-vulnerabilities)

## Mesures techniques
* Avant de déployer des correctifs sur des systèmes vitaux, il est important de les tester. Posséder pour cela un ordinateur de test peut être pratique.
* Pour vérifier si des correctifs existent pour votre système d'exploitation ou les logiciels installés, vous pouvez utiliser [le service en ligne de Secunia]({% link _knowhow/glossary/SecuniaPSI_fr.markdown %}) ou télécharger un applicatif de Secunia (attention leur version PSI ne doit pas être utilisé dans un cadre professionnel). Ces services vont vous indiquer quels logiciels mettre à jour.
* Dans une infrastructure Microsoft il est conseillé de mettre en place un serveur de mise à jour WSUS, si possible avec des extensions permettant la mise à jour de tous les logiciels des postes de travail.
