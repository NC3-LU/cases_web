---
layout: article
title:  "Firewall"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short: "Security Measures"
categories: knowhow
toc: true
ref: glossaryfirewall
lang: en
hidden: true
---

## In brief
Un firewall ou pare-feu est un dispositif physique (matériel) ou logique (logiciel) servant de système de protection pour les ordinateurs. Il peut également servir d'interface entre un ou plusieurs réseaux d’entreprise afin de contrôler et éventuellement bloquer la circulation des données en analysant les informations contenues dans les flux de données (cloisonnement réseau).

Le firewall fonctionne comme filtre et analyseur de trames réseau. Une entreprise qui aurait un serveur de fichiers pour son réseau interne et qui voudrait que celui-ci ne soit pas accessible depuis l'Internet pourrait effectivement utiliser un firewall pour bloquer les communications vers celui-ci.

Il permet donc d'une part de bloquer des attaques ou connexions suspectes pouvant provenir de [codes malicieux]({% link _knowhow/glossary/MaliciousCodes.markdown %}) comme notamment les virus, vers ou chevaux de Troie. D’un autre côté, un firewall sert dans de nombreux cas également à éviter la fuite non contrôlée d’informations vers l’extérieur.

Souvent le produit firewall contient aussi d'autres outils de sécurité comme un [antivirus]({% link _knowhow/glossary/AntiVirus.markdown %}) ou un proxy et permet ainsi non seulement de bloquer les connexions non désirées mais aussi de vérifier de manière automatique le contenu des communications et de bloquer les contenus indésirables.

Certains firewall offrent aussi une possibilité [VPN]({% link _knowhow/glossary/VPN.markdown %}).

Il existe principalement 2 catégories de firewalls :

* les firewalls personnels protégeant uniquement les stations de travail ou ordinateurs personnels. Ils sont installés directement sur l’ordinateur de l’utilisateur.

* les firewalls d’entreprise installés sur des machines dédiées. Ce type de firewall est souvent placé entre Internet et un réseau d’entreprise afin de protéger ce dernier des différentes menaces d’Internet. Il est également utilisé pour la création de zones démilitarisées (DMZ) pour l’hébergement de serveurs publics. Dans certains cas, il sert même à séparer différentes parties du réseau d’entreprise en périmètres de sécurité différents ([segmentation ou cloisonnement réseau]({% link _knowhow/glossary/NetworkSegmentation.markdown %})).

## Mesures comportementales

* Le firewall n'est pas une protection absolue contre des attaques depuis Internet respectivement des exfiltration des données et dépend en grosse partie de la configuration faite. Les utilisateurs doivent rester vigilants à de telles attaques.

## Mesures organisationnelles

* La gestion du firewall doit suivre des règles strictes. Tout changement de règle doit être documenté.

* L'organisme doit rédiger et faire respecter une politique sectorielle pour le contrôle d'accès

* Rédigez et faites appliquer une politique sectorielle contrôle d'accès - [séparation des réseaux]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#separation-of-networks)

## Mesures techniques

* Il faut de façon récurrente tester les règles firewall

* Il faut conserver et analyser les logs (fichier journal) des firewall. Ils sont souvent la seule aide pour identifier des codes malicieux exfiltrant des informations vers certaines destinations.
