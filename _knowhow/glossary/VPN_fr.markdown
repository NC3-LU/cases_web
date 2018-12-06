---
layout: article
title:  "VPN : Les réseaux privés virtuels"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: knowhow
toc: true
ref: glossaryvpn
lang: fr
---

## En quelques mots
La croissance de l’utilisation d’Internet donne lieu à de nouveaux modes de travail tels que le télétravail, l’échange d’informations privilégiées entre différentes filiales d’une entreprise, ou encore la consultation de sites Web et des systèmes informatiques de ses fournisseurs ou clients. En conséquence, une réelle problématique de sécurité liée à ces nouveaux modes de travail est en train d’émerger.

Les « Virtual Private Networks » (VPN) peuvent répondre à certains de ces problèmes et sont de plus en plus utilisés. L’objet de cette fiche est de présenter les différents types de VPN existant, mais aussi d’en proposer quelques scénarios d’utilisation.

## Explications
Un Réseau Privé Virtuel (anglais : Virtual Private Network, VPN) est un moyen de communication assurant la sécurité des transferts de données sur des réseaux publics ou partagés (comme la télédistribution ou encore l’ADSL). Un VPN est, en fait, un réseau de communication avec les mêmes paramètres de sécurité qu’un réseau privé. Ses principales caractéristiques sont :

* confidentialité des données : le chiffrement assure que le contenu des données transmises n’est connu que des parties qui échangent l’information. De ce fait, un tiers interceptant le trafic du VPN n’aura pas la possibilité d’en déterminer la teneur;
* intégrité des données : les méthodes cryptographiques employées assurent que les données reçues au travers du VPN par le destinataire sont identiques à celles envoyées par l’expéditeur ;
* authentification des utilisateurs du VPN : il est important de savoir quels sont ceux qui participent au processus afin d’éviter les problèmes de sécurité liés à l’usurpation d’identité et par la même à l’accès illicite aux réseaux privés.

Le VPN est une technologie permettant l'extension logique du réseau, ou d'un sous-réseau, de l'organisation par l'ajout de postes ou sous-réseaux se trouvant à l'extérieur des limites physiques de celle-ci. Concrètement les employés travaillant de chez eux seront virtuellement dans le réseau interne de l'organisme ou deux sites distants, voire aux antipodes l'un de l'autre, pourront partager le même réseau.


## Menaces contrées
L’Internet ne donne aucune garantie sur la confidentialité ou l’intégrité des données qui y circulent. Par exemple, si vous envoyez un e-mail, il est tout à fait possible qu’une tierce personne l’intercepte, le regarde et change même son contenu.

Ceci n’est en aucun cas acceptable et encore moins en ce qui concerne les connexions d’ordre sensible comme des transactions avec des clients ou partenaires ou dans le cas d’accès à distance aux informations internes d’une entreprise (sur un serveur de fichiers par exemple).

A l’heure actuelle, le meilleur moyen pour contrer ces menaces est bien l’utilisation d’un VPN.

## Recommandations
Il existe un grand nombre de protocoles VPN différents et le choix de ceux-ci n'est pas trivial. Il est important de se renseigner sur la robustesse des algorithmes de cryptographie employés. Par exemple le protocole PPTP, le protocole utilisé traditionnellement dans les infrastructures Windows, est connu pour ne plus être fiable car les données d'authentification peuvent être volées par des tiers.
En général le plus facile sera d'utiliser le type de VPN proposé dans la solution firewall de votre organisme.

## Politique de sécurité
Rédigez et faites respecter les politiques sectorielles suivantes:

* [Organisation de la sécurité]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity_fr.markdown %})
  * [Accès par des tiers et sous-traitance]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity_fr.markdown %}#third-party-access-and-outsourcing)
* [Classification et maîtrise des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %})
  * [Classification et responsabilité des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %}#classification-and-responsibility-for-resources)
* [Sécurité physique et environnementale]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %})
  * [Périmètre de sécurité physique]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#physical-security-perimeter )
  * [Règles dans le périmètre]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#rules-within-the-perimeter)
  * [Sécurité des équipements hors des locaux]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#off-site-equipment-security)
* [Aspects opérationnels et communications]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %})
  * [Procédures documentées]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#documentation-of-procedures)
  * [Séparation des environnements de développement et de production]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#separation-of-environments)
  * [Gestion de ressources par des externes]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#outsourcing-of-resource-management)
  * [Protection contre les logiciels malveillants]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#protection-against-malware)
* [Contrôle d’accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %})
  * [Politique de contrôle d’accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-control-policy %})
  * [Gestion des droits d’accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-rights-management)
  * [Utilisation de réseaux externes]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#use-of-external-networks)
  * [Connexion de l’extérieur]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#external-connections)
  * [Séparation de réseaux]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#separation-of-networks)
  * [Procédure de connexion]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#connection-procedures)
* [Développement et maintenance des systèmes]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %})
  * [Utilisation de l’encryption]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}#encryption)
* [Gestion des incidents liés à la sécurité](% link _knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents_fr.markdown %})
  * [Signalement des événements liés à la sécurité de l’information]({% link _knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents_fr.markdown %}#reporting-information-security-events)
  * [Gestion des incidents et des améliorations de la sécurité de l’information]({% link _knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents_fr.markdown %}#incident-management-and-improvements-information-security)
  * [Analyse des manquements avec obligations]({% link _knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents_fr.markdown %}#analysis-of-non-fulfilment-of-obligations)
* [Conformité]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %})
  * [Propriété intellectuelle]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %}#intellectual-property})
  * [Protection des données opérationnelles]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %}#protection-of-operational-data)
  * [Protection des données à caractère personnel]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %}#personal-data-protection)  
