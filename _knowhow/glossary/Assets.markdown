---
layout: article
title:  "Assets"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short: "Security Measures"
categories: knowhow
toc: true
ref: glossaryassets
lang: en
hidden: true
---

## In brief
Par 'actif', l'on comprend un bien ou un service ayant une certaine valeur pour l'entreprise. Les actifs sont sujets à différentes [vulnérabilités]({% link _knowhow/glossary/Vulnerabilities.markdown %}), susceptibles d'être exploitées par des menaces qui auront des [impacts]({% link _knowhow/glossary/Impact.markdown %}) au niveau de l'entreprise. Pour protéger ses actifs, une entreprise mettra en place des mesures de sécurité. La sélection de ces mesures se fait lors de la phase de [gestion des risques]({% link _knowhow/bestpractices/RiskManagement.markdown %}).

On distingue entre:

* actifs primaires:  processus et informations

* actifs de support: tous les autres actifs comme notamment les personnes, machines, ...

## Les actifs primaires
Par actifs primaires, on entend les processus métiers ainsi que les informations de l'organisme. Chaque actif primaire présente une certaine [criticité]({% link _knowhow/cisoapproach/SecurityPolicy-Classification.markdown %}) pour l'organisme. Ainsi il y a des processus métier plus ou moins importants, il y a des processus métier ou l'[intégrité]({% link _knowhow/glossary/Integrity.markdown %}) joue un rôle plus important que la [confidentialité]({% link _knowhow/glossary/Confidentiality.markdown %}) (service du cadastre) et ainsi de suite. Il en est de même pour les informations. Il y a des informations très importantes et moins importantes. Il y a des informations ou la confidentialité est plus importante que la [disponibilité]({% link _knowhow/glossary/Availability.markdown %}).

L'[analyse de risques]({% link _knowhow/bestpractices/RiskManagement.markdown %}#risk-estimation) est en faite calculée sur base de la criticité des actifs primaires. Les actifs de support nécessaires à la réalisation ou des processus métier héritent de la criticité des actifs primaires.

## Les actifs de support
EBIOSv2 propose une catégorisation des entités et des actifs de support autour de 7 types:

1. MAT : Matériel

2. LOG : Logiciel

3. RES : Réseau

4. PER : Personne

5. PHY : Site

6. ORG : Organisation

7. SYS : Système

## Matériel
Le type 'matériel' est constitué de l’ensemble des éléments physiques d'un système informatique. (PME: [Voir le matériel face aux menaces]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware.markdown %}))

* MAT_ACT : Support de traitement de données (actif)
Équipement informatique de traitement automatique de données comprenant les éléments nécessaires à son fonctionnement autonome.

  * MAT_ACT.1 : Matériel transportable
Matériels informatiques conçus pour être déplacés manuellement et utilisés en des lieux différents.

  * MAT_ACT.2 : Matériel fixe
Matériels informatiques appartenant à l’organisme ou utilisés dans les locaux de l’organisme.

  * MAT_ACT.3 : Périphérique de traitement
Matériel connecté à un ordinateur par un port de communication (série, parallèle, USB ...) pour la saisie, le transport ou l´émission de données.

* MAT_PAS : Support de données (passif)
Il s’agit de supports de stockage d'informations ou de fonctions.

  * MAT_PAS.1 : Support électronique
Supports électroniques connectables à un ordinateur ou à un réseau informatique pour le stockage de données. De petite taille, ils sont susceptibles de contenir de grand volume de données. Ils sont utilisables à partir d’équipement informatique standard.

  * MAT_PAS.2 : Autres supports
Support statique non électronique contenant des données.

## Logiciel
Le type 'logiciel' est constitué de l'ensemble des programmes participant au fonctionnement d'un ensemble de traitements de l'information. (PME: [Voir le logiciel face aux menaces]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Software.markdown %}))

* LOG_OS : Système d’exploitation
Ce libellé comprend l'ensemble des logiciels d’un ordinateur constituant le socle opérationnel sur lequel vont s’exécuter l’ensemble des autres logiciels (services ou applications). Il comprend un noyau et des fonctions ou services de base. Selon les architectures, un système d’exploitation peut être monolithique ou constitué d’un micro-noyau et d’un ensemble de services systèmes. Le système d’exploitation contient principalement tous les services de gestion du matériel (CPU, mémoire, disques, périphériques et interfaces réseaux), ceux de gestion des tâches ou processus, et ceux de gestion des utilisateurs et de leurs droits.

* LOG_SRV : Logiciel de service, maintenance ou administration
Logiciel qui se caractérise par le fait qu’il complète les services du système d’exploitation et qu’il n'est pas au service direct des utilisateurs ou des applications (même s’il est le plus souvent essentiel ou même indispensable au fonctionnement global du SI).

* LOG_STD : Progiciel ou logiciel standard
Les logiciels standards ou progiciels sont de véritables produits commercialisés comme tels (et non des développements uniques ou spécifiques) avec support, version et maintenance. Ils rendent des services « génériques » aux utilisateurs et applications, mais ne sont pas personnalisés ou spécifiques comme des applications métier.

* LOG_APP : Application métier

  * LOG_APP .1 : Application métier standard
Il s’agit de logiciels du marché dont la finalité est de fournir directement aux utilisateurs les services et fonctions qu’ils attendent de leur système d’information dans le cadre de leur métier. Les domaines sont multiples et par définition sans limite.

  * LOG_APP .2 : Application métier spécifique
Il s’agit de développements spécifiques (ce qui impacte notablement les aspects de support, maintenance, évolution…) dont la finalité est de fournir directement aux utilisateurs les services et fonctions qu’ils attendent de leur système d’information dans le cadre de leur métier. Les domaines sont multiples et par définition sans limite.

## Réseau
Le type 'réseau' est constitué de l'ensemble des dispositifs de télécommunication permettant l’interconnexion de plusieurs ordinateurs ou composants d’un système d'information physiquement éloignés.

* RES_INF : Médium et supports
Les médiums ou supports de communication et de télécommunication comprennent principalement les caractéristiques physiques et techniques du support (point à point, diffusion) et les protocoles de communication (lien ou réseau – niveau 2 et 3 du modèle OSI à 7 couches).

* RES_REL : Relais passif ou actif
Ce sous-type comprend tous les dispositifs qui ne sont pas des terminaisons logiques des communications (vision SI), mais des intermédiaires ou relais. Ces relais comportent du matériel mais souvent des logiciels ad-hoc. Ils se caractérisent par les protocoles de communication –réseau– supportés. Ils comportent souvent, en plus du simple relais, des fonctions et services de routage (aiguillage des communications) et/ou de filtrage (filtres dans les routeurs). Ils sont souvent administrables à distance et parfois capables de générer des traces (journaux).

* RES_INT : Interface de communication
Il s'agit des interfaces de communication des unités de traitement. Elles y sont rattachées, mais se caractérisent par les média et protocoles supportés, par les éventuelles fonctions et capacités de filtrage, de génération de journaux ou d'alerte et par la possibilité et le besoin d’administration à distance.

## Personnel
Le type 'personnel' est constitué de l’ensemble des groupes d’individus en relation avec le système d'information. (PME: [Voir le personnel face aux menaces]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2HR.markdown %}))

* PER_DEC : Décisionnel
Il s'agit des propriétaires des éléments essentiels (informations et fonctions) ainsi que des responsables hiérarchiques au sein de l'organisation ou d'un projet spécifique.

* PER_UTI : Utilisateurs
Il s'agit des personnes qui manipulent des éléments sensibles dans le cadre de leur activité et qui ont une responsabilité particulière à cet égard. Elles peuvent disposer de privilèges particuliers d’accès au système d’information pour assurer leurs tâches quotidiennes.

* PER_EXP : Exploitant / Maintenance
Il s'agit des personnes en charge de l’exploitation et de la maintenance du système d’information. Elles disposent de privilèges particuliers d’accès au système d’information pour assurer leurs tâches quotidiennes.

* PER_DEV : Développeur
Il s'agit des personnes en charge du développement des applications au sein de l’organisme. Ils accèdent à une partie du système d’information avec des privilèges avancés mais n’agissent pas sur les données de production.

## Organisation
Le type 'organisation' décrit le cadre organisationnel, constitué de l’ensemble des structures de personnel affecté à une tâche et des procédures régissant ces structures.

* ORG_DEP : Organisation dont dépend l’organisme
Il s’agit d’organisations dont dépend l’organisme étudié, qu’il y soit juridiquement rattaché ou externe. L’organisme étudié est alors contraint en termes de réglementation, de décisions, d’actions voir de remontée d’informations.

* ORG_GEN : Organisation de l’organisme
Il s’agit des différentes branches de l’organisme rattachées à sa direction, y inclue les activités transversales.

* ORG_PRO : Organisation d'un projet ou d’un système
Il s’agit de l’organisation de la mise en place d'un projet ou d'un service particulier.

* ORG_EXT : Sous-traitant/Fournisseurs/Industriels
Il 'sagit de l'organisation autour de fournisseurs de services, ou de ressources humaines liées par contrat à l'organisme

## Site
Le type 'site' est constitué de l’ensemble des lieux contenant tout ou une partie du système et les moyens physiques nécessaires à son fonctionnement. (PME: [Voir l'infrastructure face aux menaces]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}))

* PHY_LIE : Lieu
Périmètre, enceinte physique.

  * PHY_LIE.1 : Externe
Il s’agit de tous les lieux dans lesquels les moyens de sécurité de l’organisme ne peuvent être appliqués

  * PHY_LIE.2 : Locaux
Ce lieu est délimité par le périmètre de l’organisme directement en contact avec l’extérieur. Il peut s’agir d’un périmètre de protection physique obtenu en installant des barrières physiques, ou en utilisant des moyens de surveillance autour du/des bâtiment(s).

  * PHY_LIE.3 : Zone
Il s’agit d’un périmètre de protection physique offrant un cloisonnement des locaux dans l’organisme. Il est obtenu en créant des barrières physiques autour des infrastructures de traitement de l’information de l’organisme.

* PHY_SRV : Service essentiel
Ensemble de services nécessaires au fonctionnement des matériels dans l’organisme.

  * PHY_SRV.1 : Communication
Services et équipement de télécommunication fournis par un opérateur.

  * PHY_SRV.2 : Énergie
Services et moyens (sources et câblage) nécessaires à l’alimentation du matériel informatique et périphérique.

  * PHY_SRV.3 : Refroidissement /pollution
Services et moyens (matériel, conduite) de refroidissement et de purification de l’air.

## Système
Le type 'système' est constitué de l’ensemble des installations spécifiques liées aux technologies de l’information, dans un environnement opérationnel, et avec un objectif particulier. Il est composé de diverses entités appartenant aux autres types décrits ci-avant.

* SYS_INT : Dispositif d’accès Internet
Dispositif composé de l’interconnexion entre le réseau de l’organisme et le réseau Internet et offrant les services d’accès depuis ou vers l’Internet.

* SYS_MES : Messagerie
Dispositif permettant aux utilisateurs habilités la saisie, la consultation différée et la transmission, sur des ordinateurs connectés en réseau, de documents informatisés ou messages électroniques.

* SYS_ITR : Intranet
Données et services informatiques partagés et privés, qui utilisent les protocoles de communication et les technologies fédératrices (technologie d'Internet par exemple).

* Dispositif de gestion et d’accès à une base de données décrivant le personnel de l’entreprise et leurs caractéristiques.

* SYS_WEB : Portail externe
Un portail externe est un point d’accès dont un utilisateur se servira pour trouver de l’information ou un service concernant un organisme. Les portails fournissent un grand éventail de ressources et de services.
