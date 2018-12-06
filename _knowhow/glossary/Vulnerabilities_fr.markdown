---
layout: article
title:  "Vulnérabilités"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: knowhow
toc: true
ref: glossaryvulnerabilities
lang: fr
---
Par vulnérabilités on entend toutes les failles des [actifs]({% link _knowhow/glossary/Assets_fr.markdown %}) de l'entreprise qui peuvent être exploitées par des [menaces]({% link _knowhow/glossary/Threat_fr.markdown %}), dans le but de les compromettre. Une telle exploitation peut causer des [impacts]({% link _knowhow/glossary/Impact_fr.markdown %}). importants. De nouvelles vulnérabilités sont découvertes régulièrement.

Il est possible de les regrouper en plusieurs familles.

## Vulnérabilités humaines
Les vulnérabilités humaines sont à la base des sentiments, comportements et instincts qui ont depuis la nuit des temps aidé l'humanité à survivre. Malheureusement ces comportements sont si intrinsèquement liés à la nature humaine qu'ils sont très souvent exploités dans différentes arnaques ou attaques type [social engineering]({% link _knowhow/glossary/SocialEngineering_fr.markdown %}) De ce fait nous parlons de vulnérabilités dans le contexte de la sécurité de l'information. (PME: Voir [les humains faces aux menaces]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2HR_fr.markdown %}))

Parmi ces vulnérabilités on compte notamment:
* la peur (souvent exploitée par des menaces comme notamment le scareware)
* la pitié
* la curiosité
* la libido
* la cupidité (souvent exploité par des menaces comme les fausses loteries ou encore les nigériens)
* ...

## Vulnérabilités au niveau technique
Cette famille de vulnérabilités est de loin la plus mouvante, en effet, elle comprend toutes les vulnérabilités liées à l'utilisation de technologies ou solutions (hardware, software). Beaucoup de personnes sont actives dans la recherche des vulnérabilités et ainsi de nouvelles failles apparaissent quotidiennement. (PME voir [le matériel faces aux menaces]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware_fr.markdown %}) et [le logiciel face aux menaces]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Software_fr.markdown %}))

On peut nommer:

* présence de vulnérabilités au niveau des logiciels ou du système d'exploitation pouvant être exploités par des [logiciels malveillants]({% link _knowhow/bestpractices/MaliciousSoftwareBP_fr.markdown %}), par exemple simplement en visitant des [sites web malicieux]({% link _knowhow/glossary/MaliciousWebsites_fr.markdown %});
* interopérabilité des systèmes d'information et de communication : afin de permettre une communication aisée entre différents systèmes, des couches de communication supplémentaires sont souvent mises en place, qui peuvent entraîner l'apparition de nouvelles vulnérabilités;
* complexité des règles sur les [pare-feux]({% link _knowhow/glossary/Firewall_fr.markdown %})     et routeurs : la mise en place de filtrages et règles d'accès, à la demande, rend la vue d'ensemble difficile.

## Vulnérabilités au niveau physique
Cette famille comprend toutes les vulnérabilités liées aux événements imprévisibles comme les pannes, les accidents ou encore les atteintes intentionnelles aux matériels.

C'est en réponse à cette famille de vulnérabilités que l'on analysera toutes les caractéristiques physiques de l'entreprise comme notamment les accès au bâtiment, les salles et équipements informatiques et que l'on parlera également de «Plan de Continuité». (PME: voir [l'infrastructure face aux menaces]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure_fr.markdown %}))

On peut nommer:
* non-redondance : que ce soit pour des raisons liées aux systèmes d'informations, logiciels ou conditions physiques (température, courant,...) l'indisponibilité d'un serveur ou d'une base de données peut entraîner la rupture de services;
* manque de contrôle d'accès aux éléments physiques : l'accès au bâtiment, aux salles informatiques, connectiques ou autres doit être limité de manière à éviter des manipulations (in)volontaires, mais pouvant causer la perte globale de la salle informatique ou de la connectique;
* mauvaise conservation de supports de sauvegarde : les supports de sauvegarde sont souvent stockés dans la salle informatique ce qui les rend inopérants en cas de sinistre;
* mauvaise gestion des ressources : les ressources doivent être dimensionnées de façon correcte et doivent être surveillées de près;
* absence de gestion du câblage : l'absence de documentation du câblage peut entraîner des déconnexions intempestives voire la mise à disposition de ressources sur des réseaux publics.
