---
layout: knowhow
title:  "Mesures de sécurité pour PME - Le matériel face aux menaces"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: f-bestpract
toc: true
ref: bestpractthreatstohardware
lang: fr
---
## Endommagement du matériel pendant le transport

Le transport des informations peut représenter un problème de sécurité majeur, surtout si les données sont essentielles d'un point de vue de leur.

## Équipement informatique ou de communication en panne

Pour prévenir des dommages dues aux pannes de matériel, pensez à organiser un :

* plan d’investissement et de renouvellement des équipements IT en adéquation avec la durée de vie du matériel (Rédigez et faites respecter une politique sectorielle de sécurité physique et environnementale - [maintenance]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#maintenance));
* un stock d’équipements IT, notamment réseaux (câbles, switchs, disque durs…);
* augmenter les redondances pour réduire l’indisponibilité (RAID, load balancer).


## Sauvegardes inutilisables

La disponibilité des sauvegardes ainsi que la possibilité de pouvoir les restaurer sont des éléments critiques en cas de besoin après un incident. Pour prévenir les mauvaises surprises, veillez à :

* tester la procédure de restauration des sauvegardes (Rédigez et faites respecter une politique sectorielle liée aux Aspects opérationnels et communications - [Sauvegarde des données]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#data-backups));
* protéger les sauvegardes contre toute destruction accidentelle, délibérée ou environnementale (Rédigez et faites respecter une politique sectorielle pour la Sécurité physique et environnementale - [Périmètre de sécurité physique]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#physical-security-perimeter) et [Règles dans le périmètre]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#rules-within-the-perimeter));
* bien conserver les logiciels et le matériel permettant la restauration.

## Ajout ou suppression de matériels

L'introduction ou la suppression de matériel peut amener de nombreux risques. Veillez à ce que :

* l’accès au réseau informatique soit filtré et fasse l’objet d’une procédure d’autorisation (Rédigez et faites respecter une politique sectorielle pour le contrôle d'accès - [Politique de contrôle d'accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-control-policy) et [Gestion des droits d'accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-rights-management) et [Procédures de connexion]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}) et [Connexions de l'extérieur]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}) et [Séparation de réseaux]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#separation-of-networks));
* le réseau informatique doit être segmenté en fonction des besoins de sécurité. (Rédigez et faites respecter une Politique sectorielle pour le contrôle d'accès - [Séparation de réseaux]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#separation-of-networks));
* l’insertion de supports amovibles (USB notamment) soit conditionnée voire prohibée;
* les utilisateurs respectent la charte d’utilisation des ressources informatiques. (Rédigez et faites respecter une Politique sectorielle liée aux Ressources humaines - [Formation et information]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %}#training-and-information)).

## Device recovery
Une information n’est intégralement éliminée que lorsque son support est entièrement détruit. Afin d'éviter une récupération des supports mis au rebut et comportant des informations sensibles, ceux-ci doivent faire l’objet de mesures particulières pour les rendre inexploitables. (Rédigez et faites respecter une Politique sectorielle Sécurité physique et environnementale - [Mise au rebut et réutilisation des équipements]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#disposal-and-reuse-of-equipment)).  Veillez à :

* détruire les supports de données optiques et magnétiques (broyeur ou démagnétiseur);
* mettez à disposition du personnel traitant des données sensibles, des déchiqueteuses pour les dossiers papiers;
* sensibiliser le personnel à cette pratique (Rédigez et faites respecter une Politique sectorielle liée aux Aspects humains - [Formation et information]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %}#training-and-information)).

## Vol caractérisé

La forte valeur marchande des équipements informatiques, appareillage mobile en tête, ou des informations motive les personnes malveillantes à s’emparer de ces biens. Le vol n’est pas nouveau pour les équipements, mais le vol d’informations dans le cadre de l’intelligence économique peut être très rentable et des mesures de sécurité doivent être déployées, comme par exemple :  

* chiffrement des ordinateurs portables et tablets (Rédigez et faites respecter une Politique sectorielle Développement et maintenance des systèmes - [Utilisation du chiffrement]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}#encryption));
* une sensibilisation à la sécurité destinée aux utilisateurs d’équipements mobiles (Rédigez et faites respecter une Politique sectorielle liée aux Aspects humains - [Formation et information]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %}#training-and-information));
* une sauvegarde et une protection ad-hoc des données présentes sur les appareils mobiles, ou leur centralisation au sein de l’organisation (Rédigez et faites respecter une politique sectorielle liée aux Aspects opérationnels et communications - [Sauvegarde des données]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#data-backups));
* les mesures présentées pour se protéger contre la pénétration physique dans les locaux doivent être appliquées (Rédigez et faites appliquer une politique sectorielle de sécurité physique et environnementale - [périmètre de sécurité physique]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#physical-security-perimeter) et [règles dans le périmètre]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#rules-within-the-perimeter) et [bureaux en ordre]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#tidy-office-policy)).
