---
layout: knowhow
category: "Knowhow"
title:  "Mesures de sécurité pour PME - Le logiciel face aux menaces"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: f-bestpract
toc: true
ref: bestpractthreeatstosoftware
lang: fr
---
Le logiciel représente l'interface utilisateur la plus couramment utilisée par des pirates informatiques pour manipuler des informations. Il est soumis à de multiples contraintes et [menaces]({% link _knowhow/glossary/Threat_fr.markdown %}) pouvant mettre en péril le fonctionnement d'une organisation. Cette section est spécifiquement consacrée aux logiciens malveillants ('malware' en anglais).

## Environnement logiciel inapproprié

Pour pouvoir fonctionner de façon appropriée et remplir leurs fonctions, les équipements informatiques doivent être munis de logiciels adéquats. Pour ce faire, il s'agit :

* de recenser les logiciels nécessaires au fonctionnement de l’entreprise ainsi que toute dépendance logicielles possible (bibliothèques de fonctions). (Rédigez et faites respecter une Politique sectorielle pour la [Classification et maîtrise des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %})).
* d'établir des configurations types pour les équipements logiciels.
* de sauvegarder les logiciels nécessaires (et mis à jour) dans une bibliothèque numérique disponible à l’installation.
* de gérer les licences des logiciels. (Rédigez et faites respecter une Politique sectorielle liée à la Conformité - [Propriété intellectuelle]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %}#intellectual-property)).

## Utilisation de logiciels non approuvés

L’utilisation de logiciels non approuvés peut aboutir à la violation de droits liés à ces logiciels ou à l’introduction de traitements informatiques préjudiciables à l’entreprise. Il faut donc s’assurer que l’environnement IT de l’entreprise ne soit pas perturbé par des logiciels inutiles, respectivement non autorisés à la réalisation des objectifs de l’organisation. Il faut donc veiller à ce que :

* les utilisateurs respectent la charte d’utilisation des ressources informatiques.
* a politique d’utilisation des logiciels soit restrictive et définie au niveau du système d’exploitation, c’est-à-dire qu'il faut définir une liste blanche d’applications exécutables. (Rédigez et faites appliquer une politique sectorielle sur l'organisation de la sécurité - [procédure d'autorisation pour l'ajout d'outils]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity_fr.markdown %}#authorising-the-addition-of-tools)).
* les comptes utilisateurs ne donnent pas automatiquement accès aux droits d'administrateur. (Rédigez et faites respecter une Politique sectorielle pour le contrôle d'accès - [Politique de contrôle d'accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-control-policy) et [Gestion des droits d'accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-rights-management)).

## Indisponibilité des administrateurs

L’administration d’une ressource informatique (le matériel et/ou les logiciels) permet de réagir aux événements liés à l’environnement et d’adapter le système en conséquence. Il faut donc s’assurer que la ressource soit opérable, notamment pour des solutions fournies par des tierces parties, respectivement pour celles où un fournisseur unique connaît à lui seul la procédure d’administration. Veillez à :

* assurer qu’un administrateur soit toujours accessible et disponible. (Rédigez et faites appliquer une politique sectorielle sur l'organisation de la sécurité - [attribution des responsabilités]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity_fr.markdown %}#attribution-of-responsibilities)).
* une mise à disposition, par le fournisseur de service, d'une procédure d’administration. (Rédigez et faites respecter une Politique sectorielle Sécurité physique et environnementale – [Maintenance]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#maintenance)).
* recruter des administrateurs de confiance. (Rédigez et faites respecter une Politique sectorielle liée aux aspects humains - [La sécurité comme mission]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %}#security-as-a-mission)).
* former les administrateurs. (Rédigez et faites respecter une Politique sectorielle liée aux aspects humains - [Formation et information]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %}#training-and-information)).
