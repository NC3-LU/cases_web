---
layout: knowhow
category: "Knowhow"
title:  "Risk management"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short: "How is a risk analysis conducted? What are the different criteria? Or how are the risks estimated"
categories: f-bestpract
toc: true
ref: riskmanagement
lang: fr
---
Les orientations générales de la gestion du risque telles qu'utilisées par CASES proviennent de la norme ISO/IEC 27005, appartenant à la famille des normes [ISO/IEC 27000]({% link _publications/ISO27000SF_fr.markdown %}). La normes [ISO/IEC 27001]({% link _publications/ISO27000SF/ISO27001-ISMS_fr.markdown %}) régit la mise en place d'un système de management de la sécurité de l'information qui doit nécessairement intégrer un processus de gestion du risque. La gestion du risque est l'approche préconisée dans l'ISO/IEC 27001 qui sert de ce fait de base à la [politique de sécurité]({% link _knowhow/CISOApproach_fr.markdown %}) de l'organisme concerné.

Le schéma ci-dessous décrit le processus de gestion du risque.

## Définition du contexte

Pour produire une analyse de risque, il importe en premier lieu de spécifier les critères de base (évaluation des risques, impact, acceptation des risques, disponibilité des ressources…), la cible et le périmètre de l'analyse. La définition du contexte décrit notamment l'environnement et l'objet du processus de gestion des risques.

Les **critères d'évaluation** des risques sont notamment :

* les valeurs stratégiques des processus
* la [criticité]({% link _knowhow/cisoapproach/SecurityPolicy-Classification_fr.markdown %}) des [actifs]({% link _knowhow/glossary/Assets_fr.markdown %})
* les exigences légales et contractuelles
* l'importance CID ([confidentialité]({% link _knowhow/glossary/Confidentiality_fr.markdown %}), [disponibilité]({% link _knowhow/glossary/Availability_fr.markdown %}), [intégrité]({% link _knowhow/glossary/Integrity_fr.markdown %}))
* les attentes des parties prenantes et la réputation

Ainsi, pour un service du cadastre par exemple, l'importance du critère de la confidentialité est moindre que celle de l'intégrité. Dans certains métiers, il y a des risques qu'il faut à tout prix écarter, dans d'autres, il existe des actifs qu'il faut à tout prix protéger. C'est lors de la phase d'évaluation que ces valeurs contextuelles sont définies. Elles doivent être appliquées tout au long de l'analyse des risques.

Il faut aussi définir les **[critères de base]({% link _knowhow/glossary/BasicCriteria_fr.markdown %})** :

* Critères d'[impact]({% link _knowhow/glossary/Impact_fr.markdown %}) :
  * comment exprimer le degré du dommage et les coûts y associés, comment exprimer les dommages en terme de réputation ou les dommages causés par des conséquences légales)
  * échelle qualitative ou quantitative
* Critères d'acceptation des risques :
  * définir les niveaux acceptables des risques (éventuellement différents pour la confidentialité, l'intégrité et la disponibilité)
* Définition de la cible et du périmètre de l'analyse des risques
  * quels actifs doivent être inclus
  * quel est le périmètre de l'analyse des risques
  * comment traiter les risques au périmètre
* Définition des valeurs de l'organisme
  * métier
  * missions
  * valeurs
  * structure
  * valeurs socioculturelles
  * contraintes...

Ensuite, il faut définir l'**organisation** de l'analyse des risques :

* processus de gestion
* intervenants et rôles respectifs
* méchanismes d'escalation
* relations entre intervenants et les parties prenantes
* enregistrements qui doivent être conservés et qui servent à documenter le processus de gestion des risques


## Identification du risque

L’objectif de l’identification du risque est de déterminer les causes d'impacts et de comprendre comment, où, et pourquoi ces dommages peuvent arriver. Cette phase prépare l’estimation du risque à proprement dite. Elle se déroule selon les étapes suivantes :

* Identification des [actifs]({% link _knowhow/glossary/Assets_fr.markdown %}):
  * actifs primaires tels que les processus métier et les informations
  * actifs secondaires ou actifs de support
* Identification des [menaces]({% link _knowhow/glossary/Threat_fr.markdown %})
* Identification des [mesures de sécurité]({% link _publications/ProtectingYourCompany_fr.markdown %}) existantes
* Identification des [vulnérabilités]({% link _knowhow/glossary/Vulnerabilities_fr.markdown %}) (inhérente à l’identification des spécificités des risques)
* Identification des [impacts]({% link _knowhow/glossary/Impact_fr.markdown %}) (prise en considération des critères d’impact ; voir aussi [classification]({% link _knowhow/cisoapproach/SecurityPolicy-Classification_fr.markdown %}))

Ainsi il est possible de définir la liste des actifs pour lesquels une gestion du risque s'impose.

## Estimation du risque

L’estimation du risque inclut plusieurs phases :

1. le choix de la méthodologie
2. l’estimation des [impacts]({% link _knowhow/glossary/Impact_fr.markdown %})
3. l’estimation des probabilités d’occurrence
4. l’estimation du niveau de risque

Il s'agit de calculer une valeur, respectivement un niveau approximatif pour des risques identifiés, sur base de la méthode employée (qui doit garantir la répétabilité), en estimant les impacts ainsi que les probabilités d'occurrence. (Par exemple : on multiplie un impact approximatif (échelle qualitative) avec une probabilité d'occurrence (échelle qualitative) pour obtenir une estimation du risque).


<table class="tg">
  <tr>
    <th class="tg-us36 color-table-grey">Numero actif</th>
    <th class="tg-us36 color-table-grey">Libelle actif</th>
    <th class="tg-us36 color-table-grey">Type d'actif</th>
    <th class="tg-us36 color-table-grey">Niv. Imp.</th>
    <th class="tg-us36 color-table-grey">Menace</th>
    <th class="tg-us36 color-table-grey">Libelle menace</th>
    <th class="tg-us36 color-table-grey">Niv men.</th>
    <th class="tg-us36 color-table-grey">Vulnerabilite</th>
    <th class="tg-us36 color-table-grey">Libelle vulnerabilite</th>
    <th class="tg-us36 color-table-grey">Niv vulne.</th>
    <th class="tg-us36 color-table-grey">Niv. risque</th>
    <td class="tg-us36 color-table-grey">Commentaire</td>
  </tr>
  <tr>
    <td class="tg-us36" rowspan="5">ASB01</td>
    <td class="tg-us36" rowspan="5">Locaux de l"admin.</td>
    <td class="tg-us36" rowspan="5">Locaux batiments</td>
    <td class="tg-us36" rowspan="5">2</td>
    <td class="tg-us36" rowspan="3">ME11</td>
    <td class="tg-us36" rowspan="3">Incendie</td>
    <td class="tg-us36" rowspan="3">1</td>
    <td class="tg-us36">V001</td>
    <td class="tg-us36">Absence de plan de secours (evacuation, possibilite DRP, etc.)</td>
    <td class="tg-us36">2</td>
    <td class="tg-us36 color-table-grey">4</td>
    <td class="tg-us36"></td>

  </tr>
  <tr>
    <td class="tg-us36">V002</td>
    <td class="tg-us36">Batiments vetustes (plancher, electricitem plomberie, etc.)</td>
    <td class="tg-us36">1</td>
    <td class="tg-us36 color-table-grey">2</td>
    <td class="tg-us36"></td>
  </tr>
  <tr>
    <td class="tg-us36">V003</td>
    <td class="tg-us36">Absence de moyens pour combattre le feu (extincteurs, sprinklers, gaz, etc.)</td>
    <td class="tg-us36">2</td>
    <td class="tg-us36 color-table-grey">4</td>
    <td class="tg-us36"></td>
  </tr>
  <tr>
    <td class="tg-us36" rowspan="2">ME12</td>
    <td class="tg-us36" rowspan="2">Dommage cree par l'eau ou zone inondable</td>
    <td class="tg-us36" rowspan="2">2</td>
    <td class="tg-us36">V002</td>
    <td class="tg-us36">Batiments vetustes (plancher, electricitem plomberie, etc.)</td>
    <td class="tg-us36">1</td>
    <td class="tg-us36 color-table-grey">4</td>
    <td class="tg-us36"></td>
  </tr>
  <tr>
    <td class="tg-us36">V007</td>
    <td class="tg-us36">Zone inondable (riviere, vallee, crue historique, etc.)</td>
    <td class="tg-us36">2</td>
    <td class="tg-us36 color-table-grey">8</td>
    <td class="tg-us36"></td>
  </tr>
</table>


## Évaluation du risque

Pour cette étape, il s'agit de se servir de la connaissance du risque obtenue grâce à l'analyse de risque et de prendre également en considération les obligations contractuelles, légales et réglementaires de l'entité.

Les risques estimés sont ordonnés selon leur "importance" en se basant sur les décisions prises lors de la définition du contexte de l'analyse des risques.

<table class="tg">
  <tr>
    <th class="tg-us36 color-table-grey">Numero actif</th>
    <th class="tg-us36 color-table-grey">Libelle actif</th>
    <th class="tg-us36 color-table-grey">Type d'actif</th>
    <th class="tg-us36 color-table-grey">Niv. Imp.</th>
    <th class="tg-us36 color-table-grey">Menace</th>
    <th class="tg-us36 color-table-grey">Libelle menace</th>
    <th class="tg-us36 color-table-grey">Niv men.</th>
    <th class="tg-us36 color-table-grey">Vulnerabilite</th>
    <th class="tg-us36 color-table-grey">Libelle vulnerabilite</th>
    <th class="tg-us36 color-table-grey">Niv vulne.</th>
    <th class="tg-us36 color-table-grey">Niv. risque</th>
    <td class="tg-us36 color-table-grey">Commentaire</td>
  </tr>
  <tr>
    <td class="tg-us36" rowspan="5">ASB01</td>
    <td class="tg-us36" rowspan="5">Locaux de l"admin.</td>
    <td class="tg-us36" rowspan="5">Locaux batiments</td>
    <td class="tg-us36" rowspan="5">2</td>
    <td class="tg-us36" rowspan="3">ME11</td>
    <td class="tg-us36" rowspan="3">Incendie</td>
    <td class="tg-us36" rowspan="3">1</td>
    <td class="tg-us36">V001</td>
    <td class="tg-us36">Absence de plan de secours (evacuation, possibilite DRP, etc.)</td>
    <td class="tg-us36">2</td>
    <td class="tg-us36 color-table-green">4</td>
    <td class="tg-us36"></td>

  </tr>
  <tr>
    <td class="tg-us36">V002</td>
    <td class="tg-us36">Batiments vetustes (plancher, electricitem plomberie, etc.)</td>
    <td class="tg-us36">1</td>
    <td class="tg-us36 color-table-green">2</td>
    <td class="tg-us36"></td>
  </tr>
  <tr>
    <td class="tg-us36">V003</td>
    <td class="tg-us36">Absence de moyens pour combattre le feu (extincteurs, sprinklers, gaz, etc.)</td>
    <td class="tg-us36">2</td>
    <td class="tg-us36 color-table-green">4</td>
    <td class="tg-us36"></td>
  </tr>
  <tr>
    <td class="tg-us36" rowspan="2">ME12</td>
    <td class="tg-us36" rowspan="2">Dommage cree par l'eau ou zone inondable</td>
    <td class="tg-us36" rowspan="2">2</td>
    <td class="tg-us36">V002</td>
    <td class="tg-us36">Batiments vetustes (plancher, electricitem plomberie, etc.)</td>
    <td class="tg-us36">1</td>
    <td class="tg-us36 color-table-green">4</td>
    <td class="tg-us36"></td>
  </tr>
  <tr>
    <td class="tg-us36">V007</td>
    <td class="tg-us36">Zone inondable (riviere, vallee, crue historique, etc.)</td>
    <td class="tg-us36">2</td>
    <td class="tg-us36 color-table-orange">8</td>
    <td class="tg-us36"></td>
  </tr>
</table>


## Traitement du risque

Cette dernière étape suggère les mesures à mettre en place. Pour cela, il faut organiser les mesures de sécurité selon :

* les mesures à considérer ;
* l’ordre d’importance et les priorités.


Tout le système se base sur le calcul des "Return On Security Investment" c'est-à-dire sur l’économie abtenue par la mise en place de solutions de réduction des risques. Les calculs sont basés sur les ALE ("Annualised Loss Expectancy") calculées au préalable et aussi sur le calcul des coûts de mise en place de la solution.

La méthode d'analyse de risques s'arrête au choix du traitement, il reste encore à mettre en place l'analyse et appliquer ces derniers. En revanche elle aide à la mise en place d’un plan d’action.

Le processus de traitement du risque comporte 4 options de traitement :

1. la « Réduction du risque » qui consiste à réduire le risque en sélectionnant des objectifs et mesures de sécurité adéquats (Voir : [Analyse sectorielle des risques - traitement du risque]({% link _services/diagnostic_fr.markdown %}));
2. la « Conservation du risque » qui consiste à accepter les risques actuels sans actions complémentaires ;
3. le « Refus du risque » qui consiste à abandonner l'activité ou le domaine d'origine du risque ;
4. le « Transfert du risque » vers un tiers, par le biais d'une assurance par exemple.

Le risque résiduel ainsi obtenu doit être validé par la direction de l’entité concernée.

<table class="tg">
  <tr>
    <th class="tg-us36 color-table-grey">Numero actif</th>
    <th class="tg-us36 color-table-grey">Libelle actif</th>
    <th class="tg-us36 color-table-grey">Type d'actif</th>
    <th class="tg-us36 color-table-grey">Niv. Imp.</th>
    <th class="tg-us36 color-table-grey">Menace</th>
    <th class="tg-us36 color-table-grey">Libelle menace</th>
    <th class="tg-us36 color-table-grey">Niv men.</th>
    <th class="tg-us36 color-table-grey">Vulnerabilite</th>
    <th class="tg-us36 color-table-grey">Libelle vulnerabilite</th>
    <th class="tg-us36 color-table-grey">Niv vulne.</th>
    <th class="tg-us36 color-table-grey">Niv. risque</th>
    <td class="tg-us36 color-table-grey">Commentaire</td>
    <td class="tg-us36 color-table-grey">Type de traitement</td>
    <td class="tg-us36 color-table-grey">Mesure 27002</td>
    <td class="tg-us36 color-table-grey">Risque vise</td>
  </tr>
  <tr>
    <td class="tg-us36" rowspan="5">ASB01</td>
    <td class="tg-us36" rowspan="5">Locaux de l"admin.</td>
    <td class="tg-us36" rowspan="5">Locaux batiments</td>
    <td class="tg-us36" rowspan="5">2</td>
    <td class="tg-us36" rowspan="3">ME11</td>
    <td class="tg-us36" rowspan="3">Incendie</td>
    <td class="tg-us36" rowspan="3">1</td>
    <td class="tg-us36">V001</td>
    <td class="tg-us36">Absence de plan de secours (evacuation, possibilite DRP, etc.)</td>
    <td class="tg-us36">2</td>
    <td class="tg-us36">4</td>
    <td class="tg-us36"></td>
    <td class="tg-us36"></td>
    <td class="tg-us36"></td>
    <td class="tg-us36"></td>

  </tr>
  <tr>
    <td class="tg-us36">V002</td>
    <td class="tg-us36">Batiments vetustes (plancher, electricitem plomberie, etc.)</td>
    <td class="tg-us36">1</td>
    <td class="tg-us36">2</td>
    <td class="tg-us36"></td>
    <td class="tg-us36"></td>
    <td class="tg-us36"></td>
    <td class="tg-us36"></td>
  </tr>
  <tr>
    <td class="tg-us36">V003</td>
    <td class="tg-us36">Absence de moyens pour combattre le feu (extincteurs, sprinklers, gaz, etc.)</td>
    <td class="tg-us36">2</td>
    <td class="tg-us36">4</td>
    <td class="tg-us36"></td>
    <td class="tg-us36"></td>
    <td class="tg-us36"></td>
    <td class="tg-us36"></td>
  </tr>
  <tr>
    <td class="tg-us36" rowspan="2">ME12</td>
    <td class="tg-us36" rowspan="2">Dommage cree par l'eau ou zone inondable</td>
    <td class="tg-us36" rowspan="2">2</td>
    <td class="tg-us36">V002</td>
    <td class="tg-us36">Batiments vetustes (plancher, electricitem plomberie, etc.)</td>
    <td class="tg-us36">1</td>
    <td class="tg-us36">4</td>
    <td class="tg-us36"></td>
    <td class="tg-us36"></td>
    <td class="tg-us36"></td>
    <td class="tg-us36"></td>
  </tr>
  <tr>
    <td class="tg-us36">V007</td>
    <td class="tg-us36">Zone inondable (riviere, vallee, crue historique, etc.)</td>
    <td class="tg-us36">2</td>
    <td class="tg-us36 color-table-orange">8</td>
    <td class="tg-us36"></td>
    <td class="tg-us36">T001</td>
    <td class="tg-us36">x.y.z</td>
    <td class="tg-us36 color-table-green">4</td>
  </tr>
</table>


## Acceptation du risque

L'acceptation du risque est l'approbation par la direction des choix effectués lors du traitement du risque. La direction accepte donc le plan de traitement ainsi que les risques résiduels.


## Partage des informations

C'est un processus continu qui permet d'échanger et de partager les informations sur les risques entre les décideurs et les autres parties prenantes. La communication du risque a pour objectif de :

* réduire les incompréhensions avec les décisionnaires
* améliorer la coordination pour répondre aux incidents
* partager les résultats de l'évaluation des risques et présenter le plan de traitement
* obtenir de nouvelles connaissances en matière de sécurité
* améliorer la sensibilisation à la sécurité



## Surveillance et réexamen

Ce processus consiste en la surveillance et le réexamen des éléments du risque :

* valeur et catégories des actifs
* impacts, [menaces]({% link _knowhow/glossary/Threat_fr.markdown %}), vulnérabilités, probabilités d'occurrence
* éléments externes (contexte légal, environnemental)
* modification de l'approche d'appréciation du risque (critères d'impact, d'évaluation, d'acceptation des risques)
* etc.
