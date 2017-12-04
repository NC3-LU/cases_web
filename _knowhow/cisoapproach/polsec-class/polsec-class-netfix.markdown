---
layout: articlesmall
title:  "Sécuriser le réseau fixe"
menutitle:  
logo:
date:   2017-11-06 00:00:00 +0100
short: "Renforcez vos défenses. Organisez votre protection."
categories: knowhow
toc: false
---
## En quelques mots

Les mesures de sécurité sont des mesures comportementales, organisationnelles ou techniques qui cherchent à garantir la confidentialité, l'intégrité et la disponibilité d'un actif. Les mesures de sécurité cherchent à réduire les vulnérabilités exploitées par les menaces pour ainsi réduire les impacts. Elles sont définies lors de la phase de traitement du risque du processus gestion des risques. Au sein d’une entité, le réseau fixe relie les différentes machines (donc des "actifs") entre elles. Ce réseau, pour être sécurisé doit répondre à certaines mesures de sécurité, décrites ci-après.

## Mesures de sécurité

Afin de garantir la sécurité informatique au niveau du réseau fixe :

1. Il est fortement recommandé d’activer un serveur DHCP pour le contrôle de l’attribution d’adresses IP. Les serveurs doivent se voir attribuer des adresses IP fixes ou en static DHCP.
2. Il est fortement recommandé d’attribuer des adresses IP fixes (à l'aide du serveur DHCP) aux ordinateurs qui jouissent de règles spécifiques  au niveau du firewall entreprise ou du filtre web. Rédigez et faites respecter une Politique sectorielle relative au Contrôle d'accès - Procédures de connexion et Gestion des droits d'accès.
3. Il est fortement conseillé de mettre en place un système de contrôle d'accès au réseau (NAC - Network access control), pour empêcher les machines non prévues sur le réseau.
4. Il est fortement recommandé d’installer un filtre web (proxy) au sein du réseau pour interdire tout accès à des sites web malicieux ou à des sites web offrant des contenus inappropriés (jeux, pornographie,…). Rédigez et faites respecter une Politique sectorielle relative au Contrôle d'accès - Utilisation de réseaux externes.
5. Il est recommandé, pour des structures plus grandes, de cloisonner le réseau par des firewall. Rédigez et faites respecter une Politique sectorielle relative au Contrôle d'accès - Connextions de l'extérieur et Séparation de réseaux.
6. Il est fortement recommandé de créer un réseau spécifique, pour les ordinateurs portables utilisés aussi à l’extérieur de l’entreprise. Pour ce faire, des switchs spécifiques peuvent être nécessaires. Rédigez et faites respecter une Politique sectorielle relative au Contrôle d'accès - Séparation de réseaux
7. En cas de mise en place d'un réseau sans fil, il est fortement recommandé de mettre en place un réseau dédié aux nomades ou appareils personnels.
8. Dans un environnement WINDOWS, il est fortement recommandé de mettre en place un serveur de domaine ainsi qu’un Active Directory. Rédigez et faites respecter une politique sectorielle Classification et maîtrise des ressources -  ainsi qu’une politique sectorielle de contrôle d’accès - Gestion des droits d'accès.
9. Il est fortement recommandé de limiter l’accès au réseau aux zones non accessibles au grand public. Rédigez et faites respecter une politique sectorielle Sécurité physique et environnementale - Périmètre de sécurité physique et Règles dans le périmètre.
