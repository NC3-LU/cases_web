---
layout: articlesmall
title:  "Sécuriser le réseau WiFi"
menutitle:  
logo:
date:   2017-11-06 00:00:00 +0100
short: "Renforcez vos défenses. Organisez votre protection."
categories: knowhow
toc: false
---
## En quelques mots

Au sein d’une entité, un réseau WiFi peut être mis en place pour permettre :

* aux employés de se connecter avec leurs appareils portables (GSM, Smart phones, tablettes) ;
* aux visiteurs d'accéder à Internet avec leur laptop sans pour autant accéder au réseau local.

Voir aussi l'article sur la segmentation de réseau pour plus d'informations.

## Wifi pour employés

De plus en plus d'employés apportent leur appareil mobile ou portable au travail. Fournir un accès à l'Internet à ces appareils peut réduire maints problèmes de sécurité comme par exemple les essais de connexion au réseau de l'entreprise ou les connexions aux ordinateurs de travail. Cet accès doit être réservé aux employés et être protégé contre toute tentative d'intrusion à l'aide de méthodes adéquates.

La méthode de chiffrement conseillée pour ce genre d'application est le protocole WPA2-Enterprise qui permet de donner à chaque employé son propre mot de passe ou certificat et qui permet ainsi une bonne gestion des droits d'accès.

Faites aussi signer aux employés une charte d'utilisation du Wifi.

>Conseil :  mettre en place une politique sectorielle de Développement et maintenance des systèmes - Utilisation de l'encryption. et une politique sectorielle liée à la conformité - protection des données à caractère personnel.

## Mesures de sécurité

Les recommandations suivantes sont à suivre :

1. ne pas connecter le réseau WiFi au réseau fixe de l’entité. Rédigez et faites respecter une Politique sectorielle relative au Contrôle d'accès - Séparation de réseaux
2. activer un serveur DHCP pour l’attribution d’adresses IP
3. installer un filtre web (proxy) au sein du réseau WiFi pour empêcher tout accès à des sites web malicieux ou à des sites web offrant des contenus inappropriés (jeux, gambling, pornographie,…). Rédigez et faites respecter une Politique sectorielle relative au Contrôle d'accès - Utilisation de réseaux externes
4. ajouter un antivirus au filtre web proposé
5. bloquer tous les accès non-web vers l'Internet, sauf quelques exceptions comme les accès VPN (les clients pourraient vouloir se connecter au réseau de leur entreprise) ou e-mail
6. chiffrer le réseau. Il existe pour cela différentes stratégies possibles. Elles sont détaillées ci-dessous
7. rendre l’accès physique aux antennes, respectivement au routeur WiFi difficile. Rédigez et faites respecter une politique sectorielle Sécurité physique et environnementale - Périmètre de sécurité physique et Règles dans le périmètre.

## Wifi pour visiteurs/externes
Les visiteurs qui aimeraient utiliser l'Internet au sein de votre organisation devraient avoir un accès spécifique qui leur est dédié. Vu que, contrairement aux employés, ils n'ont pas signé de charte d'utilisation du Wifi il faut leur présenter lors du premier accès.
Configuration type :

* un hotspot avec portail captif qui restreint les accès des visiteurs tant que ceux-ci n'ont pas accepté les conditions générales d'utilisation et introduit un mot de passe provisoire qui leur aura été fourni;
  * une méthode de chiffrement pour éviter que certains utilisateurs n'écoutent les communications des autres ; il vaut mieux mettre en place un réseau sécurisé avec un mot de passe trivial dans ce cas là, même si le mot de passe est connu de tous. là, même si le mot de passe est connu de tous.
