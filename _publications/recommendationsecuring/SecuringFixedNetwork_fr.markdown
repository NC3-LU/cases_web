---
layout: publication-list
category: "In depth articles"
title:  "Sécuriser le réseau fixe"
menutitle: "Sécuriser le réseau fixe"
logo:
date:  2017-11-06 00:00:00 +0100
short: "How to guarantee IT security in a fixed network"
categories: securing
toc: true
ref: securingfixednetwork
lang: fr
---
## En quelques mots
Les mesures de sécurité sont des mesures comportementales, organisationnelles ou techniques qui cherchent à garantir la [confidentialité]({% link _knowhow/glossary/Confidentiality_fr.markdown %}), l'[intégrité]({% link _knowhow/glossary/Integrity_fr.markdown %}) and [disponibilité ]({% link _knowhow/glossary/Availability_fr.markdown %}) d'un [actif]({% link _knowhow/glossary/Assets_fr.markdown %}). Les mesures de sécurité cherchent à réduire les [vulnérabilités]({% link _knowhow/glossary/Vulnerabilities_fr.markdown %}) exploitées par les [menaces]({% link _knowhow/glossary/Threat_fr.markdown %}) pour ainsi réduire les [impacts]({% link _knowhow/glossary/Impact_fr.markdown %}). Elles sont définies lors de la phase de [traitement du risque]({% link _knowhow/bestpractices/RiskManagement_fr.markdown %}#risk-treatment) du processus gestion des risques. Au sein d’une entité, le réseau fixe relie les différentes machines (donc des “actifs”) entre elles. Ce réseau, pour être sécurisé doit répondre à certaines mesures de sécurité, décrites ci-après.

## Mesures de sécurité
Afin de garantir la sécurité informatique au niveau du réseau fixe :

1. Il est fortement recommandé d’activer un serveur **DHCP** pour le contrôle de l’attribution d’adresses IP. Les serveurs doivent se voir attribuer des adresses IP fixes ou en static DHCP.
2. Il est fortement recommandé d’attribuer des **adresses IP fixes** (à l'aide du serveur DHCP) aux ordinateurs qui jouissent de règles spécifiques ; au niveau du firewall entreprise ou du filtre web. Rédigez et faites respecter une Politique sectorielle relative au Contrôle d'accès - [Procédures de connexion]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#connection-procedures) et [Gestion des droits d'accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-rights-management).
3. Il est fortement conseillé de mettre en place un système de contrôle d'accès au réseau (NAC - Network access control), pour empêcher les machines non prévues sur le réseau.
4. Il est fortement recommandé d’installer un [filtre web]({% link _knowhow/glossary/WebFilterProxy_fr.markdown %}) (proxy) au sein du réseau pour interdire tout accès à des sites web malicieux ou à des sites web offrant des contenus inappropriés (jeux, pornographie,…). Rédigez et faites respecter une Politique sectorielle relative au Contrôle d'accès - [Use of external networks]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#use-of-external-networks).
5. Il est recommandé, pour des structures plus grandes, de [cloisonner le réseau]({% link _knowhow/glossary/NetworkSegmentation_fr.markdown %}) par des firewalls. Rédigez et faites respecter une Politique sectorielle relative au Contrôle d'accès - [Connextions de l'extérieur]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#external-connections) et [Séparation de réseaux]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#separation-of-networks).
6. Il est fortement recommandé de créer **un réseau spécifique**, pour les ordinateurs portables utilisés aussi à l’extérieur de l’entreprise. Pour ce faire, des switchs spécifiques peuvent être nécessaires. Rédigez et faites respecter une Politique sectorielle relative au Contrôle d'accès - [Séparation de réseaux]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#separation-of-networks)
7. En cas de mise en place d'un réseau sans fil, il est fortement recommandé de mettre en place un réseau dédié aux nomades ou appareils personnels.
8. Dans un environnement WINDOWS, il est fortement recommandé de mettre en place un  **serveur de domaine**  ainsi qu’un Active Directory. Rédigez et faites respecter une politique sectorielle [Classification et maîtrise des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %}) ainsi qu’une politique sectorielle de contrôle d’accès - [Gestion des droits d'accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-rights-management).
9. Il est fortement recommandé de limiter l’accès au réseau aux zones non accessibles au grand public. Rédigez et faites respecter une politique sectorielle Sécurité physique et environnementale - [Périmètre de sécurité physique]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#physical-security-perimeter) et [Règles dans le périmètre]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#rules-within-the-perimeter).
