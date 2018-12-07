---
layout: article
title:  "IDS/IPS"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: knowhow
toc: true
ref: glossaryidsips
lang: fr
---
## The Intrusion Detection System (IDS)
Le système de détection d’intrusion, ou IDS ("Intrusion Detection System"),
joue un rôle particulier dans le domaine de la sécurité informatique. En effet,
plutôt que de protéger activement les équipements, il fonctionne passivement et
enregistre l’activité réseau pour déclencher une alarme au moment de remarquer
un mouvement suspect. Cette détection peut se faire selon les approches
présentées ci-dessus. Cependant, la complexité des flux réseaux peut mener l’IDS
à déclencher de nombreuses fausses alarmes, également appelées faux-positifs.
Il y a donc tout un travail de post-traitement des logs d’alerte à effectuer
pour déceler les véritables attaques des fausses, ce qui peut s’avérer
fastidieux. Néanmoins, l’IDS peut être un outil très utile pour repérer les
risques (menaces et vulnérabilités) auxquels les systèmes d'information sont
assujettis. La disposition de l’IDS est un élément crucial pour  le critère
d’efficacité des données collectées. L'idéal étant de le placer à des points
d’interconnexions entre réseaux, à la manière des firewalls.

## The Intrusion Prevention System (IPS)
Le système de protection d'intrusion, ou IPS ("Intrusion prevention system"), a
été développé pour pallier les deux désavantages majeurs des IDS, à savoir la
passivité et la création de faux-positifs. En effet, l’IPS a pour fonction non
seulement de détecter les comportements suspects, mais également de les stopper.
La détection se fait de la même façon que pour les IDS et génère donc des
faux-positifs. Cependant, l’IPS est doté de filtres de détection d’un ensemble
de règles qui vont lui indiquer la façon adéquate à réagir : bloquer le flux
réseau, le laisser passer ou demander l’intervention humaine ; un peu à la
manière d’un firewall. Là encore, pour être efficace, l’IPS doit être placé à
des points d’interconnexion entre les réseaux.
