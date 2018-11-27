---
layout: knowhow
title:  "Security policy – Access control"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: f-ciso
toc: true
ref: cisoaccesscontrol
lang: fr
---
## Politique de contrôle d'accès
L’accès aux applications et aux données (fichiers, base de données) qui ont été [classifiées]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}) comme importantes ou vitales, est réservé aux personnes autorisées et est interdit à toute autre personne, qu’elle soit interne ou externe à "l’organisation".

e droit d’accès à chacune des ressources est accordé par le responsable des données, tel que défini dans la section 2 “[Attributions des responsabilités]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity_fr.markdown %}#third-party-access-and-outsourcing)”. Il définit également le type d’accès aux informations: lecture seule, modification ou droit de suppression.

C’est lui qui peut accorder, faire modifier ou supprimer tout droit d’accès à ces données.

La création du droit d’accès est techniquement mise en œuvre par le responsable de l’informatique.

### Appliquer des mesures de sécurité pour:

* [les serveurs fichier]({% link _publications/recommendationsecuring/Recommendations4securingFileServer_fr.markdown %})
* [les serveurs mail]({% link _publications/recommendationsecuring/Recommendations4securingEmailServer_fr.markdown %})
* [le réseau fixe]({% link _publications/recommendationsecuring/SecuringWifiNetwork_fr.markdown %})
* [le réseau wifi interne]({% link _publications/recommendationsecuring/SecuringWifiNetwork_fr.markdown %}#wifi-for-employees)
* [le réseau wifi pour clients]({% link _publications/recommendationsecuring/SecuringWifiNetwork_fr.markdown %}#wifi-for-visitorsexternal-users)
* [les ordinateurs connectés à l'Internet]({% link _publications/recommendationsecuring/SecuringFixedWorkstation_fr.markdown %})
* [les ordinateurs portables]({% link _publications/recommendationsecuring/SecuringLaptops_fr.markdown %})

### Mesures organisationnelles directement liées:

* [Classification et maîtrise des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %})
* [Classification et responsabilité des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %}#classification-and-responsibility-for-resources)
* [Sécurité physique et environnementale]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %})
* [Périmètre de sécurité physique]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#physical-security-perimeter)
* [Aspects opérationnels et communications]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %})
* [Procédures documentées]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#documentation-of-procedures)
* [Contrôle d’accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %})
* [Gestion des droits d’accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-rights-management)
* [Séparation de réseaux]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#separation-of-networks)
* [Procédure de connexion]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#connection-procedures)
* [Conformité]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %})
* [Protection des données opérationnelles]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %}#protection-of-operational-data)
* [Protection des données à caractère personnel]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %}#personal-data-protection)

### Mesures techniques:

* [l'authentification]({% link _knowhow/glossary/Authentication_fr.markdown %})

## Gestion des droits d'accès
Avant de créer un compte personnel pour un utilisateur, le responsable informatique s’assure que les [gestionnaires des données]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity_fr.markdown %}#the-data-manager) ont donné leur accord pour l’accès aux différents groupes d’utilisateurs, disques, répertoires et applications. Il en profite pour passer en revue les membres des groupes et leurs droits.

### Appliquer des mesures de sécurité pour:

* [les serveurs fichier]({% link _publications/recommendationsecuring/Recommendations4securingFileServer_fr.markdown %})
* [les serveurs mail]({% link _publications/recommendationsecuring/Recommendations4securingEmailServer_fr.markdown %})
* [le réseau fixe]({% link _publications/recommendationsecuring/SecuringWifiNetwork_fr.markdown %})
* [le réseau wifi interne]({% link _publications/recommendationsecuring/SecuringWifiNetwork_fr.markdown %}#wifi-for-employees)
* [le réseau wifi pour clients]({% link _publications/recommendationsecuring/SecuringWifiNetwork_fr.markdown %}#wifi-for-visitorsexternal-users)
* [les ordinateurs connectés à l'Internet]({% link _publications/recommendationsecuring/SecuringFixedWorkstation_fr.markdown %})
* [les ordinateurs portables]({% link _publications/recommendationsecuring/SecuringLaptops_fr.markdown %})

### Mesures organisationnelles directement liées:

* [Classification et maîtrise des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %})
* [Classification et responsabilité des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %}#classification-and-responsibility-for-resources)
* [Aspects opérationnels et communications]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %})
* [Procédures documentées]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#documentation-of-procedures)
* [Protection contre les logiciels malveillants]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#protection-against-malware)
* [Contrôle d’accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %})
* [Politique de contrôle d’accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-control-policy)
* [Gestion des mots de passe]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#password-management)
* [Séparation de réseaux]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#separation-of-networks)
* [Procédure de connexion]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#separation-of-networks)

### Mesures techniques:

* [l'authentification]({% link _knowhow/glossary/Authentication_fr.markdown %})

## Gestion des mots de passe

### Appliquer des mesures de sécurité pour:

* [les serveurs fichier]({% link _publications/recommendationsecuring/Recommendations4securingFileServer_fr.markdown %})
* [les serveurs mail]({% link _publications/recommendationsecuring/Recommendations4securingEmailServer_fr.markdown %})
* [le réseau fixe]({% link _publications/recommendationsecuring/SecuringWifiNetwork_fr.markdown %})
* [le réseau wifi interne]({% link _publications/recommendationsecuring/SecuringWifiNetwork_fr.markdown %}#wifi-for-employees)
* [le réseau wifi pour clients]({% link _publications/recommendationsecuring/SecuringWifiNetwork_fr.markdown %}#wifi-for-visitorsexternal-users)
* [les ordinateurs connectés à l'Internet]({% link _publications/recommendationsecuring/SecuringFixedWorkstation_fr.markdown %})
* [les ordinateurs portables]({% link _publications/recommendationsecuring/SecuringLaptops_fr.markdown %})


### Mesures organisationnelles directement liées:

* [Aspects humains]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %})
* [La formation et l’information]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %}#training-and-information)
* [Contrôle d’accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %})
* [Politique de contrôle d’accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-control-policy)
* [Gestion des droits d’accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-rights-management)
* [Procédure de connexion]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#connection-procedures)

### Mesures techniques:

* [l'authentification]({% link _knowhow/glossary/Authentication_fr.markdown %})
* [les mots de passe]({% link _knowhow/glossary/Password_fr.markdown %})

## Utilisation de réseaux externes

La connexion à des réseaux externes, et en particulier à l'Internet, doit se faire dans des conditions appropriées.

Voici quelques scénarios possibles:

### Appliquer dans mesures de sécurité pour:

* [les serveurs fichier]({% link _publications/recommendationsecuring/Recommendations4securingFileServer_fr.markdown %})
* [les serveurs mail]({% link _publications/recommendationsecuring/Recommendations4securingEmailServer_fr.markdown %})
* [le réseau fixe]({% link _publications/recommendationsecuring/SecuringWifiNetwork_fr.markdown %})
* [le réseau wifi interne]({% link _publications/recommendationsecuring/SecuringWifiNetwork_fr.markdown %}#wifi-for-employees)
* [le réseau wifi pour clients]({% link _publications/recommendationsecuring/SecuringWifiNetwork_fr.markdown %}#wifi-for-visitorsexternal-users)
* [les ordinateurs connectés à l'Internet]({% link _publications/recommendationsecuring/SecuringFixedWorkstation_fr.markdown %})
* [les ordinateurs portables]({% link _publications/recommendationsecuring/SecuringLaptops_fr.markdown %})


### Mesures organisationnelles directement liées:

* [les sites web malicieux]({% link _knowhow/glossary/MaliciousWebsites_fr.markdown %})

### Mesures organisationnelles directement liées:

* [Aspects humains]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %})
* [La formation et l’information]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %}#training-and-information)
* [La réponse aux incidents et dysfonctionnements de sécurité]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %}#response-to-incidents-and-malfunctions)
* [Aspects opérationnels et communications]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %})
* [Procédures documentées]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#documentation-of-procedures)
* [Protection contre les logiciels malveillants]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#protection-against-malware)
* [Courrier électronique]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#email)
* [Contrôle d’accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %})
* [Politique de contrôle d’accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-control-policy)
* [Gestion des droits d’accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-rights-management)
* [Séparation de réseaux]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#separation-of-networks)
* [Développement et maintenance des systèmes]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %})
* [Utilisation du chiffrement]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}#encryption)
* [Gestion des vulnérabilités techniques]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}#managing-technical-vulnerabilities)
* [Gestion des incidents liés à la sécurité]({% link _knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents_fr.markdown %})
* [Signalement des événements liés à la sécurité de l’information]({% link _knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents_fr.markdown %}#reporting-information-security-events)

### Mesures techniques:

* [l'anti-virus]({% link _knowhow/glossary/AntiVirus_fr.markdown %})
* [le pare-feu]({% link _knowhow/glossary/Firewall_fr.markdown %})
* [le firewall entreprise]({% link _knowhow/glossary/Firewall_fr.markdown %})
* [le filtre web]({% link _knowhow/glossary/WebFilterProxy_fr.markdown %})

## Connexion de l'extérieur
La connexion depuis un réseau extérieur vers les systèmes de "l’organisation" doit être restreinte aux cas indispensables. A ces occasions, la connexion se fait de façon préférentielle via [VPN]({% link _knowhow/glossary/VPN_fr.markdown %}).

### Appliquer des mesures de sécurité pour:

* [les serveurs fichier]({% link _publications/recommendationsecuring/Recommendations4securingFileServer_fr.markdown %})
* [les serveurs mail]({% link _publications/recommendationsecuring/Recommendations4securingEmailServer_fr.markdown %})
* [le réseau fixe]({% link _publications/recommendationsecuring/SecuringFixedNetwork_fr.markdown %})
* [les ordinateurs connectés à l'Internet]({% link _publications/recommendationsecuring/SecuringFixedWorkstation_fr.markdown %})
* [les ordinateurs portables]({% link _publications/recommendationsecuring/SecuringLaptops_fr.markdown %})

### Mesures organisationnelles directement liées:

* [Organisation de la sécurité]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity_fr.markdown %})
* [Accès par des tiers et sous-traitance]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity_fr.markdown %}#third-party-access-and-outsourcing)
* [Aspects humains]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %})
* [La formation et l’information]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %}#training-and-information)
* [La réponse aux incidents et dysfonctionnements de sécurité]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %}#response-to-incidents-and-malfunctions)
* [Aspects opérationnels et communications]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %})
* [Procédures documentées]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#documentation-of-procedures)
* [Contrôle d’accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %})
* [Politique de contrôle d’accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-control-policy)
* [Gestion des droits d’accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-rights-management)
* [Séparation de réseaux]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#separation-of-networks)
* [Procédure de connexion]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#connection-procedures)
* [Développement et maintenance des systèmes]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %})
* [Utilisation du chiffrement]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}#encryption)
* [Gestion des vulnérabilités techniques]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}#managing-technical-vulnerabilities)
* [Gestion des incidents liés à la sécurité]({% link _knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents_fr.markdown %})
* [Signalement des événements liés à la sécurité de l’information]({% link _knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents_fr.markdown %}#reporting-information-security-events)
* [Conformité]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %})
* [Protection des données opérationnelles]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %}#protection-of-operational-data)
* [Protection des données à caractère personnel]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %}#personal-data-protection)

### Mesures techniques:

* [le firewall entreprise]({% link _knowhow/glossary/Firewall_fr.markdown %})
* [VPN]({% link _knowhow/glossary/VPN_fr.markdown %})

## Séparation de réseaux

Dans le cadre de réseaux plus complexes comprenant différentes zones de sécurité, [le pare-feu]({% link _knowhow/glossary/Firewall_fr.markdown %}) est utilisé pour séparer ces différents réseaux.

Le pare-feu est configuré de façon à laisser uniquement passer les flux et les utilisateurs autorisés.

Si une machine est trop sensible, elle est isolée du reste des systèmes, physiquement et/ou logiquement.

Voir aussi: [La segmentation de réseau]({% link _knowhow/glossary/NetworkSegmentation_fr.markdown %})


### Appliquer des mesures de sécurité pour:

* [les serveurs fichier]({% link _publications/recommendationsecuring/Recommendations4securingWebServer_fr.markdown %})
* [les serveurs mail]({% link _publications/recommendationsecuring/Recommendations4securingEmailServer_fr.markdown %})
* [le réseau fixe]({% link _publications/recommendationsecuring/SecuringFixedNetwork_fr.markdown %})
* [le réseau wifi interne]({% link _publications/recommendationsecuring/SecuringWifiNetwork_fr.markdown %}#wifi-for-employees)
* [le réseau wifi pour clients]({% link _publications/recommendationsecuring/SecuringWifiNetwork_fr.markdown %}#wifi-for-visitorsexternal-users)
* [les ordinateurs connectés à l'Internet]({% link _publications/recommendationsecuring/SecuringFixedWorkstation_fr.markdown %})
* [les ordinateurs portables]({% link _publications/recommendationsecuring/SecuringLaptops_fr.markdown %})

## Procédures de connexion
Les écrans d’accueil sur les différents systèmes sont configurés de manière à:

* donner le minimum d’informations, et de préférence aucune sur le système, l’application et "l’organisation", tant que l’utilisateur ne s’est pas correctement identifié;
* afficher un message du type "Accès interdit à toute personne non autorisée";
* limiter le nombre de tentatives à 3 essais avant de refuser l’utilisateur;
* afficher, si possible, la date et l’heure de la dernière connexion, ainsi que les tentatives de connexion. Ces informations sont à vérifier par l’utilisateur pour s'assurer qu’il n’y a pas eu de connexion frauduleuse à son insu.
