---
layout: knowhow
title:  "Security Policy – Operational and communication aspects"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: f-ciso
toc: true
ref: cisooperationalcommunicationaspects
lang: fr
---
## Documentation des procédures

Toutes les opérations concernant le traitement des informations doivent être documentées. Ceci s’applique aux traitements planifiés ('batch'), aux arrêts et redémarrages de systèmes et aux procédures de sauvegarde de données.

Outre les opérations courantes à réaliser, ces procédures doivent préciser:

* les instructions en cas d’erreur
* les conditions de démarrage
* que faire des sorties (listings, impressions, etc.)
*  ...

Les procédures sont mises à jour par le responsable de l’informatique et sauvegardées dans des locaux spécifiques, facilement accessibles. Il va de soi que les employés concernés doivent connaître ces procédures et les suivre.

La section ci-jointe est facultative, mais importante pour des organisations qui utilisent des serveurs. Documenter un minimum les procédures de sauvegarde reste néanmoins applicable dans tous les autres cas de figure.

### Appliquer des mesures de sécurité pour:

* [les serveurs de fichiers]({% link _publications/recommendationsecuring/Recommendations4securingWebServer_fr.markdown %})
* [les serveurs mail]({% link _publications/recommendationsecuring/Recommendations4securingEmailServer_fr.markdown %})
* éventuellement pour décrire l'installation de nouveaux ordinateurs et ordinateurs portables ('Ghost')

### Mesures organisationnelles directement liées:

* [Organisation de la sécurité]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity_fr.markdown %})
  * [Attribution des responsabilités]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity_fr.markdown %}#attribution-of-responsibilities)

## Séparation des environnements

Il est préférable de séparer les machines traitant des activités de développement de logiciel, ou des activités de test, de celles où sont installés les produits en cours de production.

Cette séparation vise à limiter les risques de modifications sur des données réelles.
L'utilisation de données de production situés dans des environnements de test (généralement moins bien protégés) est en effet déconseillée.

Notamment si l'on y traite des données critiques (du point de vue [confidentialité]({% link _knowhow/glossary/Confidentiality_fr.markdown %})), des secrets de fabrication, ou des données à caractère personnel.

### Appliquer des mesures de sécurité pour:

* Les serveurs faisant tourner des applications (comptabilité, Customer Relationship Management, Gestion de stocks, ...) si l'organisme fait ou teste des développements.

### Mesures organisationnelles directement liées:

* [Classification et maîtrise des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %})
  * [Classification et responsabilité des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %}#classification-and-responsibility-for-resources)
* [Conformité]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %})
  * [Protection des données opérationnelles]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %}#protection-of-operational-data)
  * [Protection des données à caractère personnel]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %}#personal-data-protection)

## Externalisation de la gestion des ressources

Concernant les ressources gérées par des sociétés externes, il faut au préalable faire analyser les points de sécurité critiques de l'organisation et indiquer les mesures de gestion particulières dans le contrat de services.

On parle ici "d’outsourcing" ou de "facilities management", ou plus simplement d’externalisation.

### Appliquer des mesures de sécurité pour:

* Les ordinateurs et serveurs qui sont gérés par des sociétés externes. En cas de gestion à distance, il est très important de prévoir des modalités spécifiques pour les  contrôles d'accès (voir [Connexions de l'extérieur]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#external-connections)).

## Protection contre les logiciels malveillants

Une attaque par des virus ou autres [logiciels malveillants]({% link _knowhow/glossary/MaliciousCodes_fr.markdown %}) est l’un des risques les plus probables pour tout utilisateur d'informatique. Ceux-ci peuvent s'infiltrer dans "l’organisation" par le biais de  [supports amovibles]({% link _knowhow/glossary/RemovableDevices_fr.markdown %}),comme notamment les CD-Rom, disquettes, stick USB ou via e-mail ou la visite de sites malicieux.

Les ordinateurs et serveurs de "l’organisation" doivent être munis de [logiciels anti-virus]({% link _knowhow/glossary/AntiVirus_fr.markdown %}). Le responsable informatique est chargé d’installer ces outils sur chaque machine et de s’assurer qu'ils soient constamment à jour. Sont concernés aussi bien les postes de travail des utilisateurs, que les serveurs (voir [mesures de sécurité pour serveurs de fichiers]({% link _publications/recommendationsecuring/Recommendations4securingWebServer_fr.markdown %}) et [mesures de sécurité pour serveurs de messagerie électronique]({% link _publications/recommendationsecuring/Recommendations4securingEmailServer_fr.markdown %})).

D’autre part, un certain nombre de mesures doivent être respectées par les utilisateurs pour éviter de compromettre la sécurité. Il est défendu:

   d'empêcher le fonctionnement des outils d’antivirus (de les désactiver, de les reconfigurer, d'empêcher les mises à jour, etc.);

   d'installer des logiciels qui n’ont pas été approuvés par le responsable informatique (PME: voir [Utilisation de logiciels non approuvés]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Software_fr.markdown %}#use-of-unapproved-software));
* de lancer des programmes ou fichiers reçus par e-mail, qui auraient été envoyés à l'utilisateur sans une demande de sa part, même s'il en connaît l'émetteur (PME: voir [Social engineering / Communication inadéquate]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2HR_fr.markdown %}#manipulation-of-people) et [Le traitement des codes malicieux]({% link _knowhow/glossary/MaliciousCodes_fr.markdown %})).     Ces e-mails doivent être détruits et des conseils peuvent être demandés au responsable informatique.

Les outils de vérification d' e-mails entrants traitent non seulement les virus, mais peuvent aussi éliminer des fichiers joints, potentiellement dangereux (exécutables, scripts, macros).

### Appliquer des mesures de sécurité pour:

* [les serveurs de fichiers]({% link _publications/recommendationsecuring/Recommendations4securingWebServer_fr.markdown %})
* [les serveurs mail]({% link _publications/recommendationsecuring/Recommendations4securingEmailServer_fr.markdown %})
* [Les ordinateurs connectés à l'Internet]({% link _publications/recommendationsecuring/SecuringFixedWorkstation_fr.markdown %})
* [Les ordinateurs portables]({% link _publications/recommendationsecuring/SecuringLaptops_fr.markdown %})

### Mesures comportementales:

* [Logiciels malveillants- bonnes pratiques]({% link _knowhow/glossary/MaliciousCodes_fr.markdown %})
* [Courriers électroniques]({% link _knowhow/bestpractices/EMail-BestPractices_fr.markdown %})
* [Supports amovibles]({% link _knowhow/glossary/RemovableDevices_fr.markdown %})
* [Sites web malicieux]({% link _knowhow/glossary/MaliciousWebsites_fr.markdown %})

### Mesures organisationnelles directement liées:

* [Classification et maîtrise des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %})
  * [Classification et responsabilité des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %}#classification-and-responsibility-for-resources)
* [Aspects humains]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %})
  * [La formation et l’information]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %}#training-and-information)
  * [La réponse aux incidents et dysfonctionnements de sécurité]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %}#response-to-incidents-and-malfunctions)
* [Aspects opérationnels et communications]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %})
  * [Courrier électronique]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#email)
* [Contrôle d’accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %})
  * [Politique de contrôle d’accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-control-policy)
  * [Utilisation de réseaux externes]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#use-of-external-networks)
  * [Séparation de réseaux]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#separation-of-networks)
* [Développement et maintenance des systèmes]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %})
  * [Gestion des vulnérabilités techniques]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}#managing-technical-vulnerabilities)
* [Gestion des incidents liés à la sécurité]({% link _knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents_fr.markdown %})
  * [Signalement des événements liés à la sécurité de l’information]({% link _knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents_fr.markdown %}#reporting-information-security-events)
  * [Gestion des incidents et des améliorations de la sécurité de l’information]({% link _knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents_fr.markdown %}#incident-management-and-improvements-information-security)
* [Gestion de la continuité de l’entreprise]({% link _knowhow/cisoapproach/SecurityPolicy-ManagingBusinessContinuity_fr.markdown %})
  * [La continuité de fonctionnement]({% link _knowhow/cisoapproach/SecurityPolicy-ManagingBusinessContinuity_fr.markdown %}#operational-continuity)


### Mesures techniques:

* [Antivirus]({% link _knowhow/glossary/AntiVirus_fr.markdown %})
* [Firewall]({% link _knowhow/glossary/Firewall_fr.markdown %})
* [Segmentation de réseau]({% link _knowhow/glossary/NetworkSegmentation_fr.markdown %})
* [Correctifs (patch)]({% link _knowhow/glossary/Patches_fr.markdown %})
* [Sauvegardes]({% link _publications/ProtectingYourCompany_fr.markdown %}#data-backups)
* [Cryptographie]({% link _knowhow/glossary/Cryptography_fr.markdown %})

## Sauvegarde des données

Il est essentiel pour une organisation de faire une  sauvegarde de leurs données et de leurs logiciels spécifiques ou configurés spécifiquement. En effet, un sinistre (incendie, inondation) ou, de façon plus courante, un problème sur un disque peut facilement détruire ces informations. (PME: voir [Incendie]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure_fr.markdown %}#fire) et [Équipement informatique ou de communication en panne]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware_fr.markdown %}#failure-of-it-or-communications-equipment) et [Endommagement du matériel pendant le transport]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware_fr.markdown %}#hardware-damaged-during-transport)).

En cas de sinistre important, le matériel détruit peut en général être remplacé; par contre, il est souvent impossible de reproduire les données perdues, ce qui peut causer la fermeture d'une entreprise.

La sauvegarde des informations importantes ou vitales ([classification]({% link _knowhow/cisoapproach/SecurityPolicy-Classification_fr.markdown %})) devrait se faire selon une périodicité compatible avec le niveau d'importance des activités de "l’organisation".

Selon le type d’informations, le cycle de sauvegarde doit être effectué à 3 niveaux. Une sauvegarde journalière sur un support réutilisé chaque semaine (la sauvegarde du lundi écrase la sauvegarde du lundi précédent par exemple). Une sauvegarde hebdomadaire avec un cycle de 4 à 5 semaines. Une sauvegarde mensuelle avec un cycle annuel. La sauvegarde hebdomadaire est en fait transformée en sauvegarde mensuelle une fois par mois (la dernière du mois). La dernière sauvegarde annuelle est archivée "définitivement" en cas de besoin légal.

Les sauvegardes hebdomadaires et mensuelles doivent être stockées dans un local spécifique qui garantit les mêmes conditions de sécurité que celles utilisées dans le périmètre de sécurité, si possible sur un site distant.

Les supports inutilisés doivent être effacés ou détruits. Ceci s’applique à tous les supports, qu’ils soient informatiques, papiers ou autres (PME: voir  [Mise en rebut]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#disposal-and-reuse-of-equipment) et [Récupération de supports]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware_fr.markdown %}#device-recovery) et [Vol caractérisé]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware_fr.markdown %}#aggravated-theft)).

La sauvegarde de données peut également rendre service en cas d’erreur humaine (PME: voir [erreurs humaines]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %})), afin de démarrer le système informatique d’une situation antérieure fiable. Une procédure de récupération des données est nécessaire dans ce cas et  ce sera par ailleurs l’occasion de tester la procédure. En effet il faut procéder annuellement à un test des procédures.

### Appliquer des mesures de sécurité pour:

* [les serveurs de fichiers]({% link _publications/recommendationsecuring/Recommendations4securingWebServer_fr.markdown %})
* [les serveurs mail]({% link _publications/recommendationsecuring/Recommendations4securingEmailServer_fr.markdown %})
* [Les ordinateurs connectés à l'Internet]({% link _publications/recommendationsecuring/SecuringFixedWorkstation_fr.markdown %})
* [Les ordinateurs portables]({% link _publications/recommendationsecuring/SecuringLaptops_fr.markdown %})

### Mesures organisationnelles directement liées:

* [Organisation de la sécurité]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity_fr.markdown %})
  * [Attribution des responsabilités]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity_fr.markdown %}#attribution-of-responsibilities)
* [Classification et maîtrise des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %})
  * [Classification et responsabilité des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %}#classification-and-responsibility-for-resources)
* [Sécurité physique et environnementale]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %})
  * [Périmètre de sécurité physique]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#physical-security-perimeter)
  * [Sécurité des équipements hors des locaux]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#off-site-equipment-security)
* [Aspects opérationnels et communications]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %})
  * [Procédures documentées]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#documentation-of-procedures)
  * [Sécurité des médias pendant les transports]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#device-security-during-transport)
* [Contrôle d’accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %})
  * [Politique de contrôle d’accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-control-policy)
  * [Gestion des droits d’accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-rights-management)
* [Gestion de la continuité de l’entreprise]({% link _knowhow/cisoapproach/SecurityPolicy-ManagingBusinessContinuity_fr.markdown %})
  * [La continuité de fonctionnement]({% link _knowhow/cisoapproach/SecurityPolicy-ManagingBusinessContinuity_fr.markdown %}#operational-continuity)

### Mesures techniques:

* [sauvegarde des données]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#data-backups)

## Sécurité des médias pendant le transport

Lors du transport ou de l'expédition de médias contenant des données de "l’organisation" il est important de prendre en compte  en fonction du niveau d'importance des données, les mesures suivantes (PME: voir [Endommagement du matériel pendant le transport]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware_fr.markdown %}#hardware-damaged-during-transport)):

* utiliser un emballage spécifique (dont l'ouverture forcée garde les traces)
* utiliser une mallette à ouverture à code
* exécuter la livraison par un membre de "l’organisation"
* chiffrer les données

### Appliquer des mesures de sécurité pour:

* Le Transport de sauvegardes
* La communication via courrier électronique
* La communication via Internet (FTP,...)


### Mesures organisationnelles:

* [Classification et maîtrise des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %})
  * [Classification et responsabilité des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %}#classification-and-responsibility-for-resources)
* [Développement et maintenance des systèmes]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %})
  * [Utilisation du chiffrement]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}#encryption)

### Mesures techniques:

* La [cryptographie]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}#encryption)

## Courrier électronique

Le courrier électronique transitant par l'Internet ne peut en aucun cas être considéré comme un moyen de communication sécurisé. En effet, le courrier peut être envoyé par mégarde au mauvais destinataire, être modifié ou être lu par un tiers. En conséquence,  toute opération qui engage la responsabilité de "l’organisation" ferait mieux d'être confirmée par  un support supplémentaire (téléphone, courrier, fax, etc.). Ceci pourrait éviter une erreur de destinataire, ou une modification de prix ou de quantité lors d'une commande par exemple. ([bonnes pratiques e-mail]({% link _knowhow/bestpractices/EMail-BestPractices_fr.markdown %}))

Évitez d'envoyer des informations confidentielles par e-mail. Le cas échéant utilisez un mécanisme de chiffrement agréé avec vos correspondants.

Le système de messagerie de "l’organisation" est destiné à un usage professionnel. Un usage personnel modéré peut être toléré. La responsabilité de l’utilisateur est personnellement engagée en cas d’utilisation délictueuse des outils. Notez que dans un souci de réponse aux contraintes de traçabilité, il est possible qu’une partie ou l’ensemble des messages échangés par les membres de "l’organisation" soient conservés. (PME: voir [Utilisation abusive des ressources de l’organisation]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2HR_fr.markdown %}#misuse-of-it-resources))

### Appliquer des mesures de sécurité pour:

* [les serveurs mail]({% link _publications/recommendationsecuring/Recommendations4securingEmailServer_fr.markdown %})
* [Les ordinateurs connectés à l'Internet]({% link _publications/recommendationsecuring/SecuringFixedWorkstation_fr.markdown %})
* [Les ordinateurs portables]({% link _publications/recommendationsecuring/SecuringLaptops_fr.markdown %})

### Mesures comportementales:

* [Bonnes pratiques concernant le courrier électronique]({% link _knowhow/bestpractices/EMail-BestPractices_fr.markdown %})

### Mesures organisationnelles directement liées:

* [Classification et maîtrise des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %})
  * [Classification et responsabilité des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %}#classification-and-responsibility-for-resources)
* [Aspects humains]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %})
  * [La formation et l’information]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %}#training-and-information)
  * [La réponse aux incidents et dysfonctionnements de sécurité]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %}#response-to-incidents-and-malfunctions)
* [Aspects opérationnels et communications]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %})
  * [Protection contre les logiciels malveillants]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#protection-against-malware)
* [Contrôle d’accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %})
  * [Utilisation de réseaux externes]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#use-of-external-networks)
  * [Connexions de l'extérieur]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#external-connections)
  * [Procédure de connexion]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#connection-procedures)
* [Développement et maintenance des systèmes]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %})
  * [Utilisation du chiffrement]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}#encryption)
  * [La signature électronique]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}#electronic-signatures)
* [Gestion des incidents liés à la sécurité]({% link _knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents_fr.markdown %})
  * [Signalement des événements liés à la sécurité de l’information]({% link _knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents_fr.markdown %}#reporting-information-security-events)
* [Conformité]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %})
  * [Propriété intellectuelle]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %}#intellectual-property)
  * [Protection des données opérationnelles]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %}#protection-of-operational-data)
  * [Protection des données à caractère personnel]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %}#personal-data-protection)

### Mesures techniques:

* La [cryptographie]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}#encryption)
