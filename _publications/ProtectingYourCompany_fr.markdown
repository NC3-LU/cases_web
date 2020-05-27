---
layout: publication-list
category: "In depth articles"
title:  "Protéger son entreprise"
menutitle: "Protéger son entreprise"
logo:
date:  2017-11-06 00:00:00 +0100
short: "Anticiper les risques, protéger vos données, quelles sont les bonnes astuces pour protéger votre entreprise"
categories: securing
toc: true
ref: protectingyourcompany
lang: fr
---
## Prévenir les risques
La meilleure façon de sécuriser son entreprise est d'installer un [processus de gestion des risques]({% link _knowhow/bestpractices/RiskManagement_fr.markdown %}). Il permet d'identifier des mesures de protection adaptées à la situation et aux valeurs de l'entreprise, tout en protégeant les actifs les plus importants. Voir: “[pourquoi gérer les risques ?]({% link _publications/WhyManageRisks_fr.markdown %})” et “[pourquoi mutualiser l'analyse des risques ?]({% link _publications/WhyPoolRisksAnalysis_fr.markdown %})”

Le risque peut se définir par le calcul suivant : risque = [vulnérabilité]({% link _knowhow/glossary/Vulnerabilities_fr.markdown %}) * [menace]({% link _knowhow/glossary/Threat_fr.markdown %}) * [impact]({% link _knowhow/glossary/Impact_fr.markdown %}). Il est composé d'un facteur ‘probabilité’ (provenant de la menace) et d'un facteur ‘dégât’ (provenant de la valeur de l'actif compromis, respectivement de la valeur du dommage indirect subit). La vulnérabilité utilisée dans cette fonction prend compte des mesures de sécurité mise en place.

Il est pratiquement impossible de prévenir un risque en voulant agir sur les menaces existantes. Par contre, on peut agir sur le risque en réduisant les facteurs ‘vulnérabilité’ et ‘impact’ :

* Réduire le facteur ‘vulnérabilité’, par la mise en place de mesures de sécurité ciblées
* Réduire l’impact potentiel, par la mise en place de systèmes de redondances des données (n’a cependant aucun effet sur la confidentialité des données)

Un organisme qui s'initie au domaine de la sécurité de l’information peut choisir de mettre en place des bonnes pratiques, sans nécessairement déployer des processus spécifiques à la gestion des risques.

Les “menaces”  désignent l'ensemble des éléments pouvant compromettre les ressources informatiques d'une organisation.

Les “vulnérabilités” expriment toutes les faiblesses humaines et techniques qui pourraient être exploitées par des menaces, dans le but de les compromettre.

L'“impact” est le résultat de l'exploitation d'une vulnérabilité par une menace, donc le dommage causé.

La combinaison des ces trois facteurs fonde le “**risque**”.

## Protéger les données
Les processus métier tout comme les données sont appelés des actifs primaires ([Classification]({% link _knowhow/cisoapproach/SecurityPolicy-Classification_fr.markdown %}) des [actifs]({% link _knowhow/glossary/Assets_fr.markdown %}); [gestion des risques]({% link _knowhow/bestpractices/RiskManagement_fr.markdown %})). La première priorité pour une mise en sécurité au niveau informatique concerne la protection de ces actifs primaires.

Toute entité a un intérêt particulier à protéger ses données d'entreprise, notamment lorsqu'il s'agit d'informations relatives à la réalisation du plan économique de celle-ci. Par ailleurs, les exigences légales ou encore les attentes clients représentent également des raisons qui amènent une entreprise à protéger des données spécifiques.

Différents types de données qui doivent être protégées :

* [la propriété intellectuelle]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %}#intellectual-property)
* les secrets de production
* les données clients
* les données des processus, comme notamment les données logistiques, comptables, fournisseurs,…

La [perte de données]({% link _knowhow/glossary/DataLoss_fr.markdown %}) a généralement des conséquences néfastes pour toute entité.

## Classification des données
Avant de mettre en place des mesures de protection l’entité doit procéder à une classification , au moins sommaire, des données qu’elle traite. Cette classification est importante pour prendre conscience de la juste valeur ([confidentialité]({% link _knowhow/glossary/Confidentiality_fr.markdown %}), [intégrité]({% link _knowhow/glossary/Integrity_fr.markdown %}) et [disponibilité]({% link _knowhow/glossary/Availability_fr.markdown %})) des données. Dépendant de la valeur des données, respectivement de l'[impact]({% link _knowhow/glossary/Impact_fr.markdown %}) attendu en cas de compromission des données, l’entité va pouvoir décider de l'investissement à consacrer à la sécurité des données.

> Remarque : le schéma de classification appliqué aux informations doit aussi être appliqué aux contenants, c’est-à-dire aux conteneurs, aux emplacements physiques et aux supports contenant des informations. Le terme contenant est considéré au sens large.

[Politique de sécurité PME]({% link _knowhow/cisoapproach/SecurityPolicy-SecurityPolicy_fr.markdown %}):

* [Classification et maîtrise des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %})
* [Contrôle d'accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}) -- [Politique de contrôle d'accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-control-policy) and [Gestion des droits d'accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-rights-management)

## La sauvegarde des données
Toutes les données qui ont été identifiées au sein d'une entreprise comme ayant un besoin de disponibilité doivent être sauvegardées. Par la création d'une copie de sauvegarde, la perte ou destruction des données primaires peut plus facilement être compensée. La sauvegarde devient cependant plus difficile, lorsque les données à sauvegarder revêtent un caractère confidentiel ou d’intégrité.

Les données ayant un besoin de confidentialité doivent être protégées contre tout accès illicite, indépendamment du support sur lequel ils se trouvent et indépendamment de l’endroit où ils sont stockés.

Les données ayant un grand besoin d’intégrité doivent être protégées contre toute modification par des personnes non autorisées. Ceci vaut aussi pour les sauvegardes. De plus, en ce qui concerne les originaux papier digitalisés, il faut nécessairement respecter les conditions d’archivage électronique.

[Politique de sécurité PME :]({% link _knowhow/cisoapproach/SecurityPolicy-SecurityPolicy_fr.markdown %}):

* [Aspects opérationnels et communications]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}) --- [Sauvegarde des données]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#data-backups)
* [Sécurité physique et environnementale]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}) --- [Périmètre de sécurité physique]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#physical-security-perimeter) et [Règles dans le périmètre]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#rules-within-the-perimeter)
* [Contrôle d'accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}) -- [Politique de contrôle d'accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-control-policy) and [Gestion des droits d'accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-rights-management)

## La destruction des données
Les données dont l’entreprise n’a plus besoin, respectivement celles qui doivent être supprimées, doivent être détruites de façon à ce que leur critère de confidentialité ne soit pas violé.

Une destruction définitive et sécurisée des données doit respecter certains critères de sécurité. Il existe des méthodes qui permettent la réutilisation des disques, ou même de l’ordinateur.

Pour des données strictement confidentielles, ils est fortement conseillé de détruire les supports de données, y inclus les disques durs, par broyeur ou démagnétiseur.

[Politique de sécurité PME]({% link _knowhow/cisoapproach/SecurityPolicy-SecurityPolicy_fr.markdown %}):

* [Sécurité physique et environnementale]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}) --- [Mise au rebut et réutilisation des équipements]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#disposal-and-reuse-of-equipment)

## La transmission de données
La technologie utilisée pour transmettre des données doit notamment respecter les critères de confidentialité et d’intégrité des données (plus rarement ceux relatifs à la disponibilité).

Il est fortement recommandé d’utiliser des moyens cryptographiques pour protéger les données à transmettre contre la perte de confidentialité et d’intégrité.

Toute communication via l'Internet (téléchargement, FTP) doit donc être chiffrée, au moins via SSL respectivement via un réseau  respectivement via un réseau VPN. L’envoi en clair (càd non chiffré) d’informations confidentielles via courrier électronique est strictement à éviter.

[Politique de sécurité PME :]({% link _knowhow/cisoapproach/SecurityPolicy-SecurityPolicy_fr.markdown %}):

* [Aspects opérationnels et communications]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}) --- [Courrier électronique]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#email)
* [Développement et maintenance des systèmes]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}) --- [Utilisation du chiffrement]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}#encryption)
* [Contrôle d'accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}) --- [Utilisation de réseaux externes]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#use-of-external-networks)

SOS:

* [On me demande des informations confidentielles]({% link _knowhow/sos/SOS-IamAskedForConfidentialInformation_fr.markdown %})

## Le transport de données
La technologie utilisée pour transporter des données doit respecter les besoins de confidentialité, d’intégrité et de disponibilité des données (surtout pour des originaux).

Il est fortement recommandé d’utiliser des moyens cryptographies, et de sécurité physique pour protéger les données transportées contre la perte de confidentialité, d’intégrité et de disponibilité.

[Politique de sécurité PME :]({% link _knowhow/cisoapproach/SecurityPolicy-SecurityPolicy_fr.markdown %}):

* [Aspects opérationnels et communications]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}) --- [Sécurité des medias pendant les transports]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#device-security-during-transport)
* [Sécurité physique et environnementale]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}) --- [Sécurité des équipements hors locaux]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#off-site-equipment-security)
* [Développement et maintenance des systèmes]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}) --- [Utilisation de l'encryption]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}#encryption)

## Protéger une machine
Les machines utilisées pour réaliser les processus métiers et pour traiter les informations de l'organisme sont appelés actifs secondaires ou encore actifs de support ( voir : classification des actifs ; analyse des risques). Afin de pouvoir protéger les processus métiers, respectivement les informations, il faut protéger les actifs de supports qui sont utilisés pour les traiter.

En effet, la compromission au niveau d'un ordinateur ou d'un serveur peut évidemment entraîner la perte de confidentialité, de disponibilité et de l'intégrité des processus ou informations qui y sont traités.

Il faut donc mettre en place, au niveau des actifs secondaires, des mesures de traitement des risques afin de prévenir des impacts néfastes.

## Les ordinateurs
La plupart des organisations dédient au moins un ordinateur de bureau à la gestion de l'organisme. Cet ordinateur doit être protégé contre les menaces les plus répandues. Il est fortement conseillé de mettre en place les mesures de sécurité de base

Suivant la criticité des données traitées, respectivement des processus métiers supportés, il faudra bien entendu élargir le niveau des mesures de protections.

[Politique de sécurité pour PME :]({% link _knowhow/cisoapproach/SecurityPolicy-SecurityPolicy_fr.markdown %}):

* [Aspects opérationnels et communications]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}) – [protection contre les logiciels malicieux]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#protection-against-malware) et [Sauvegarde des données]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#data-backups)
* [contrôle d'accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %})

## Les ordinateurs portables

Certaines organismes utilisent aussi des ordinateurs portables comme actifs de support pour les processus métier ou pour traiter certains types de données. Ces ordinateurs portables sont souvent sortis de l'enceinte sécurisée d'un bureau et emmenés en des moyens de transports privés ou publics ou encore utilisés dans des lieux privés ou publics. Souvent ils sont connectés à des réseaux étrangers à l'organisme.
Les menaces mettant en cause les ordinateurs portables sont nombreuses et toute organisme voulant utiliser des ordinateurs portables doit au moins respecter les mesures de sécurité basiques.

[Politique de sécurité pour PME :]({% link _knowhow/cisoapproach/SecurityPolicy-SecurityPolicy_fr.markdown %}):

* [Aspects opérationnels et communications]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}) – [protection contre les logiciels malicieux]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#protection-against-malware) et [Sauvegarde des données]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#data-backups)
* [contrôle d'accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}) – [Gestion des droits d'accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-rights-management), et [Gestion des mots de passe]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#password-management) et [Procédures de connexion]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#connection-procedures) et [Connextions de l'extérieur]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#external-connections) and [Utilisation de réseaux externes]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#use-of-external-networks)
* [aspects humains]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %}) – [La formation et l'information]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %}#training-and-information)
* [Classification et maîtrise des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %})
* [Développement et maintenance des systèmes]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}) – [Utilisation du chiffrement]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}#encryption)

## Les serveurs de fichiers
Certains organismes utilisent des serveurs de fichiers pour faciliter la coopération entre les différents agents respectivement pour augmenter le niveau de résilience des données stockées. Tout comme les autres machines de l'organisme, les serveurs de fichiers sont des actifs de support pour les processus métier. Mais ils représentent souvent le point de défaillance unique d' une organisation à petite ou moyenne taille.

Les besoins en terme de confidentialité, de disponibilité et d'intégrité des serveurs de fichiers sont de ce fait plus grands que pour les autres actifs de support de l'organisme. Il est donc essentiel d'appliquer des mesures de sécurité basiques sur ce type de machines.

[Politique de sécurité pour PME :]({% link _knowhow/cisoapproach/SecurityPolicy-SecurityPolicy_fr.markdown %}):

* [Aspects opérationnels et communications]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}) – [protection contre les logiciels malicieux]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#protection-against-malware) et [Sauvegarde des données]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#data-backups)
* [contrôle d'accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}) – [Politique de contrôle d'accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-control-policy) and [Gestion des droits d'accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-rights-management), and [Password management]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#password-management) and [Gestion des mots de passe]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#connection-procedures) and [Procédures de connexion]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#external-connections) and [Connexions de l'extérieur]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#separation-of-networks)
* [aspects humains]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %}) – [La formation et l'information]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %}#training-and-information)
* [Classification et maîtrise des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %})
* [Sécurité physique et environnementale]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}) – [Périmètre de sécurité physique]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#physical-security-perimeter); [Règles dans le périmètre]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#rules-within-the-perimeter); [Maintenance]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#maintenance) et [Mise en rebut et réutilisation des équipements]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#disposal-and-reuse-of-equipment); [Sécurité électrique des équipements]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#electrical-equipment-safety)

## Les serveurs mail
Les services d'un serveur mail sont connectés en permanence à l'Internet. La probabilité d'être exposé à une menace est grande et l'exploitation de nouvelles vulnérabilités souvent aisée. Sécuriser le serveur mail requiert une certaine attention, parfois même un effort de veille de la part de l'organisme. En effet, l'e-mail est souvent le premier moyen de communication au sein d'une entreprise (intégrité) et contient bien souvent des fichiers au contenu sensible (confidentialité).

Les organismes de petite taille disposent rarement de serveurs mail. Leur gestion, notamment leur protection, est trop complexe pour leur utilisation au sein de petites structures.

[Politique de sécurité pour PME :]({% link _knowhow/cisoapproach/SecurityPolicy-SecurityPolicy_fr.markdown %}):

* [Aspects opérationnels et communications]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}) – [protection contre les logiciels malicieux]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#protection-against-malware) et [Sauvegarde des données]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#data-backups)
* [Contrôle d'accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}) – [Politique de contrôle d'accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-control-policy);[ Gestion des droits d'accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-rights-management), and [Gestion des mots de passe]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#password-management); [Procédures de connexion]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#connection-procedures); [Séparation de réseaux]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#separation-of-networks); [Utilisation de réseaux externes]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#use-of-external-networks)
* [Aspects humains]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %}) – [La formation et l'information]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %}#training-and-information)
* [Classification et maîtrise des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %})
* [Développement et maintenance des systèmes]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}) – [Utilisation du chiffrement]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}#encryption)

## Le serveur web
Les serveurs web ne contiennent pas toujours des données confidentielles, de ce fait il sont moins touchés par les problèmes de confidentialité. En revanche ils sont supposés fonctionner en permanence (disponibilité) et doivent être résistants aux attaques potentielles de défiguration ou d'infection. Il est pour cela recommandé de suivre les recommandations pour la sécurisation des serveurs web.

## Protéger le réseau
Le réseau est un actif secondaire supportant les processus métiers de l'organisme, et transmettant les informations traitées au sein de cet organisme. Son rôle est essentiel, car sa compromission entraîne souvent celle des machines connectées.

## Le réseau local (fixe)
La plupart des organismes connectent leur réseau, respectivement une partie du réseau, à Internet. Ce qui l'expose à une multitude de menaces potentielles. Mais le réseau peut également être mis en péril par des menaces venant de l'intérieur de l'organisme.

L'installation d'un pare-feu (firewall) constitue le cas échéant une protection essentielle pour le réseau car il permet de cloisonner certaines parties du réseau.

Respectez des mesures de sécurité de base pour sécuriser votre réseau local.

[Politique de sécurité pour PME :]({% link _knowhow/cisoapproach/SecurityPolicy-SecurityPolicy_fr.markdown %}):

* [Contrôle d'accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}) – [Procédures de connexion]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#connection-procedures) et [Gestion des droits d'accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-rights-management); [Utilisation de réseaux externes]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#use-of-external-networks) et [Connexions de l'extérieur]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#external-connections); [Séparation de réseaux]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#separation-of-networks)
* [Sécurité physique et environnementale]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}) – [Périmètre de sécurité physique]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#physical-security-perimeter) et [Règles dans le périmètre]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#rules-within-the-perimeter)

## Le réseau wifi
De nombreux organismes mettent en place un réseau wifi : il offre certains avantages mais a comme inconvénient majeur que les ondes wifi se propagent à travers l'air et sont généralement aussi accessibles à l'extérieur de l'organisme.

Il est donc important de mettre en place des mesures de sécurité basiques pour réseaux wifi.

[Politique de sécurité pour PME :]({% link _knowhow/cisoapproach/SecurityPolicy-SecurityPolicy_fr.markdown %}):

* [Contrôle d'accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}) – [Procédures de connexion]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#connection-procedures) et [Gestion des droits d'accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-rights-management); [Utilisation de réseaux externes]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#use-of-external-networks)
; [Séparation de réseaux]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#separation-of-networks)
* [Gestion des systèmes d'information]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}) – [Utilisation du chiffrement]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}#encryption)
* [Sécurité physique et environnementale]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}) – [Périmètre de sécurité physique]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#physical-security-perimeter) et [Règles dans le périmètre]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#rules-within-the-perimeter)

## Télétravail
Permettre un accès sûr depuis l'extérieur de l'organisation peut se faire de différentes manières en fonction des besoins des employés.

Un accès au serveur de mails est souvent suffisant et peut être facile à mettre en place.

Pour des accès plus importants, il est fortement recommandé de mettre en place un accès par VPN.

[Politique de sécurité pour PME :]({% link _knowhow/cisoapproach/SecurityPolicy-SecurityPolicy_fr.markdown %}):

* [Contrôle d'accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}) – [Procédures de connexion]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#connection-procedures) and [Gestion des droits d'accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-rights-management); [Utilisation de réseaux externes]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#use-of-external-networks)
; [Séparation de réseaux<]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#separation-of-networks)
* [Gestion des systèmes d'information]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}) – [Utilisation du chiffrement]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}#encryption)

## Formation et sensibilisation
La formation et la sensibilisation à la sécurité des systèmes d'information et de communication constitue un élément essentiel pour que celle-ci devienne une réalité concrète au sein de notre société.

[Politique de sécurité pour PME :]({% link _knowhow/cisoapproach/SecurityPolicy-SecurityPolicy_fr.markdown %}):

* [Aspects humains]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %}) – [Formation et information]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %}#training-and-information);

Mesures :

* [La sensibilisation et la formation]({% link _publications/ProtectingYourCompany_fr.markdown %}#training-and-awareness)

## S´organiser
La sécurité d'une entreprise dépend en grande partie des processus métier de celle-ci. Souvent il sera très difficile d'appliquer des règles de sécurité à un processus, qui n'aura pas été pensé pour être sûr. De ce fait il est plus facile, et donc moins cher, de prendre en compte la sécurité depuis la création de l'organisation de la société.

Analysez les processus et essayez de changer ou éliminer ceux qui ne sont pas optimaux, comme par exemple ceux qui nécessiteraient un partage de mot de passe.

L'attribution de rôles spécifiques est ici primordial; l'octroi de responsabilités sur certains actifs, la désignation des personnes responsables de gérer les incidents et la mise en place d'une bonne communication en interne.

[Politique de sécurité pour PME :]({% link _knowhow/cisoapproach/SecurityPolicy-SecurityPolicy_fr.markdown %}):

* [Organisation de la securité]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity_fr.markdown %}) – [Attribution des responsabilités]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity_fr.markdown %}#attribution-of-responsibilities) et [Conseils d'un spécialiste]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity_fr.markdown %}#specialist-advice); [Accès par des tiers et sous-traitance]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity_fr.markdown %}#third-party-access-and-outsourcing); [Revue indépendante de la sécurité des informations]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity_fr.markdown %}#independent-review-of-information-security); [Procédure d'autorisation pour l'ajout d'outils]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity_fr.markdown %}#authorising-the-addition-of-tools)

## Protection des locaux
La plupart des organismes disposent de leur propre local ou établissement pour héberger leurs bureaux, dépôts, archives et locaux informatiques. Ils  peuvent ainsi restreindre certains risques dus à des menaces d'origine environnementale, délibérée et accidentelle compromettant les besoins en confidentialité, intégrité ou disponibilité des actifs  importants ou vitaux.

La mise en place de zones sécurisées, ainsi que la restriction d'accès à ces zones, et donc aux actifs s'y trouvant, réduit nettement le risque provenant de menaces délibérées ou accidentelles.

Les locaux hébergeant des actifs importants ou vitaux doivent également être protégés contre des menaces environnementales, comme notamment les incendies (PME : voir [Incendie]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure_fr.markdown %}#fire)), les dégâts des eaux, la pollution, la poussière, la corrosion, le gel, les dégâts liés à l'électricité ou des sinistres majeurs.

Voir le chapitre consacré à la sécurité physique de l'organisme.

### Accès physique
Plus un actif est important, plus l'accès physique à celui-ci doit être contrôlé. L'organisme disposera donc d'une zone "publique", accessible aux clients, d'une zone interne, accessible uniquement aux employés ainsi que d'une ou de plusieurs zones sécurisées uniquement accessibles à des personnes autorisées. Les actifs, selon leur importance, seront déployés uniquement dans les zones correspondant à leur degré de protection. Les mesures de sécurité mises en place doivent prévenir des intrusions physiques.

Ainsi un serveur de fichiers, contenant des documents critiques de l'organisme, ne doit pas se trouver dans un local ouvert d'accès. La probabilité d'une manipulation malintentionnée ou accidentelle serait bien trop grande. (PME : voir [Vol caractérisé]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware_fr.markdown %}#aggravated-theft) et [Pénétration dans les locaux]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure_fr.markdown %}#infiltrating-the-premises)).

## Communications and social networks
Les **réseaux sociaux** font désormais partie de notre vie quotidienne. Pour les entreprises et les organisations, ils présentent des opportunités inédites. Beaucoup en ont déjà fait un levier de **communication et de marketing** efficace.

Si les **avantages** sont nombreux, il ne faut pas pour autant perdre de vue les **risques** , et notamment :

* risque de perte de réputation
* risque d'infection par des virus ou code malveillant circulant sur les réseaux sociaux
* risque de perte ou de divulgation de données
* risque de phishing, scam ou forme d'ingénierie sociale au travers des réseaux sociaux.

Pour prévenir des mesures simples peuvent être mises en place.

## Les voyages de service
Les données de l'entreprise (données commerciaux ou stratégiques, résultats de recherche, savoir-faire…) doivent aussi être protégés lors des éventuels déplacements ou voyages de service.

Lors que les ordinateurs portables, les supports amovibles ou supports papiers contenant ces types de données quittent l'enceinte sécurisée de l'entreprise, des précautions spécifiques doivent être prises.
