---
layout: publication-list
category: "In depth articles"
title:  "Pourquoi gérer les risques ?"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short: "Pourquoi gérer les risques ?"
categories: securing
toc: true
ref: whymanagerisks
lang: fr
---
[Impact]({% link _knowhow/glossary/Impact_fr.markdown %}) : conséquence négative qui survient lorsqu’une [menace]({% link _knowhow/glossary/Threat_fr.markdown %}) exploite une [vulnérabilité]({% link _knowhow/glossary/Vulnerabilities_fr.markdown %})d’un **actif**.

[**Asset**]({% link _knowhow/glossary/Assets_fr.markdown %}) : tout élément représentant de la valeur pour l’organisation / l’entreprise.

De façon générale, la sécurité vise à réduire le nombre ainsi que l’envergure des impacts :

* financiers
* juridiques
* sur la réputation
* sur le temps (perdu)
* sur le savoir-faire
* sur la santé

La plupart des impacts, à l’exception des impacts financiers, ne peuvent être couverts par aucune assurance. Il faut donc nécessairement les empêcher de survenir, respectivement **atténuer leurs conséquences** en réduisant les vulnérabilités des différents actifs. Cette réduction des vulnérabilités reste souvent difficile et peut engendrer des coûts substantiels, surtout si l’on doit créer des redondances. Par contre, il est impossible d’agir sur les menaces car elles ne sont pas sous le contrôle de l’organisme.

Puisqu’il ne sera **pas possible**, en tout cas pas tout de suite possible, **d’adresser toutes les vulnérabilités**, il est préférable d’adresser les vulnérabilités dont l’exploitation peut mener vers des impacts importants ou même critiques. Une notion de **priorité** et de «road map» doit être introduite.

La norme ISO/IEC 27005 ([gestion des risques]({% link _publications/WhyManageRisks_fr.markdown %})) propose une approche méthodologique visant à identifier les risques existants, à les estimer, à les évaluer et finalement à proposer des traitements. La norme propose quatre types de traitement :

* la **réduction**, en implémentant des mesures identifiées dans l’ISO/IEC 27002,
* le **transfert** du risque vers un spécialiste (sous-traitance),
* l’**acceptation** du risque
* le **refus** qui bien sûr engendre l’arrêt de l’activité en question.

Avec cette méthode il est possible d’identifier les différents risques auxquels une organisation est confrontée. Pour chaque processus métier et information, les actifs de support nécessaires à leur traitement sont analysés d’un point de vue menaces, vulnérabilités et impacts. **Pour chaque actif** on énumère donc les différentes menaces et vulnérabilités existantes. On retient les couples menaces-vulnérabilités réalistes aussi appelés «**attack scenarios**» et on calcule le risque en fonction de l’importance de l’actif (importance pour le processus primaire respectivement valeur de l’actif).

L’évaluation du risque est un calcul basé sur :

* la probabilité de la menace,
* l’aisance d’exploitation de la vulnérabilité (en tenant compte des mesures de sécurité existantes)
* l’envergure de l’impact (estimation du risque).

Lors de l’évaluation du risque, on trie les différents risques selon leur importance.

Finalement on propose **des traitements** pour chaque élément sortant de l’évaluation des risques ayant un **niveau de risque inacceptable**.

Cette approche peut sembler ardue, mais elle représente &nbsp;le seul moyen de prioriser les investissements en sécurité. Ceux-ci seront efficaces car adaptés aux scénarios d’attaque les plus «prometteurs».

En effet pourquoi investir des millions dans le combat du feu si la menace principale est l’eau ?
