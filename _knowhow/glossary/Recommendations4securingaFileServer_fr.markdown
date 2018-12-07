---
layout: article
title:  "Recommandations pour sécuriser un serveur de fichiers"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: knowhow
ref: glossaryrecomm4securingfileserver
lang: fr
---
## En quelques mots
Un serveur de fichiers est un serveur spécial dans le sens que celui-ci n'est que rarement connecté à l'Internet mais est en général directement ou au travers d'un [pare-feu]({% link _knowhow/glossary/Firewall_fr.markdown %})connecté au réseau interne. Il sert de lieu de stockage commun à tous les fichiers de l'entreprise et fait de ce fait office de lien entre tous les ordinateurs, facilitant la communication en interne mais aussi la propagation de [logiciels malveillant]({% link _knowhow/glossary/MaliciousCodes_fr.markdown %}).

Malgré le fait que ce serveur ne soit pas connecté à l'Internet en général il est important de suivre les mêmes [recommandations que pour un serveur connecté à l'Internet]({% link _publications/recommendationsecuring/Recommendations4securingWebServer_fr.markdown %}).

## Mesures de sécurité

1. Il est fortement recommandé de protéger le serveur de fichiers contre les [logiciels malveillant]({% link _knowhow/glossary/MaliciousCodes_fr.markdown %}) (malware). Le logiciel d'analyse antivirus doit être régulièrement mis à jour pour pouvoir reconnaître les derniers codes malicieux et les supprimer. Rédigez et faites respecter une Politique sectorielle sur Aspects opérationnels et communications - [protection contre les logiciels malicieux]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#protection-against-malware).
2. Il est fortement recommandé d’utiliser **un logiciel antivirus différent** pour le serveur de fichiers que pour les postes des agents. Ainsi la chance de détection d’un virus est plus grande.
3. Il est fortement recommandé de **restreindre la fonctionnalité** du serveur de fichiers à cette seule tâche et de n’héberger aucune autre application sur ce même serveur virtuel, respectivement physique.
4. Il est fortement recommandé de mettre **le serveur de fichiers à l’intérieur du réseau** de l’entité et de n’autoriser aucun accès depuis l’extérieur de ce réseau. Rédigez et faites respecter une Politique sectorielle pour le contrôle d'accès – [Connection de l'extérieur]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#external-connections) et [Séparation de réseaux]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#separation-of-networks).
5. Il est fortement recommandé d’appliquer une procédure de **création et désactivation des comptes utilisateurs**. Les comptes utilisateurs sont créés à l'arrivée de chaque nouvel agent. Au départ ou lors de la mutation d'un agent, son compte d'accès est désactivé afin qu'il ne puisse continuer à accéder aux fichiers. Rédigez et faites respecter une politique sectorielle liée aux [aspects humains]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %}) ainsi qu’une politique sectorielle de [contrôle d’accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}).
6. Il est fortement conseillé de mettre en place une **procédure formelle d’attribution et de reprise des droits d’accès** (lecture, écriture). L’accès aux données est attribué par le gestionnaire des données en question. Rédigez et faites respecter une Politique sectorielle pour la [Classification et maîtrise des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %}) et une Politique sectorielle pour le contrôle d'accès – [Politique de contrôle d'accès ]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-control-policy) et [Gestion des droits d'accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-rights-management)
7. Il est recommandé de mettre en place des fonctionnalités de chiffrement si des contenus strictement confidentiels doivent être sauvegardés sur le serveur. Rédigez et faites respecter une Politique sectorielle Développement et maintenance des systèmes – [Utilisation du chiffrement]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}#encryption).
