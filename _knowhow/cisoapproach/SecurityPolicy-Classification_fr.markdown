---
layout: knowhow
title:  "Classification"
menutitle:  
logo:
date:   2017-11-06 00:00:00 +0100
short: "Renforcez vos défenses. Organisez votre protection."
categories: f-ciso
toc: true
ref: cisoclassification
lang: fr
---
L'identification et la classification des actifs font partie intégrante de la gestion des risques et représentent des composantes importantes pour la gestion de la sécurité de l'information (encore appelé: système de management de la sécurité de l'information - SMSI, voir [ISO/IEC 27001]({% link _publications/ISO27000SF/ISO27001-ISMS_fr.markdown %})). Elles définissent les besoins de sécurité en termes de confidentialité, disponibilité et intégrité.

Rédigez et faites appliquer une politique sectorielle sur la classification et maîtrise des ressources

## Principes de classification

* Plus l’impact d’une divulgation est important, plus la classification de confidentialité devra être élevée.
* Plus l’impact d’une perte en cas de compromission d’un actif est important, plus la classification d’intégrité devra être élevée.
* Plus l’impact en cas d’entrave prolongée à l’accès légitime à l'actif est critique, plus la classification de disponibilité devra être élevée.

## Importance de la classification

La classification des actifs sert avant tout à établir une analyse des risques. En effet pour effectuer celle-ci, il est nécessaire de mettre en relation la criticité d'un actif (= niveau de classification - impact potentiel) avec les menaces et les vulnérabilités y associées.

La classification permettra de manière la plus objective possible d'évaluer les risques et d'établir un plan de traitement face à ceux-ci. Ainsi le bénéficiaire pourra s'assurer de la réduction des risques majeurs,  tout en considérant le niveau d'investissement disponible.

## Schéma de classification

Chaque entreprise dispose d'actifs plus ou moins critiques pour assurer son bon fonctionnement. Parmi ces actifs, on compte des processus métier, des personnes, des informations et bien-sûr des machines. Afin de pouvoir mettre en place des mesures de sécurité efficaces et performantes, il est nécessaire de définir un niveau de protection à apporter à chacun des actifs.

Pour cette raison, il importe de procéder à une classification des actifs et de déterminer leur criticité quant au degré de confidentialité, d'intégrité et de disponibilité.

## Confidentialité

Le schéma suivant indique l’abréviation officielle, le nom et une description des classes de confidentialité. Il fait aussi référence aux classes du schéma "Trafic Light protocol" défini par l’administration anglaise NISCC. Ces classes définissent des règles de distribution pour des informations utilisées au niveau de la protection des infrastructures critiques.

<table class="classification">
  <tr>
    <th style="width: 15%;">Catégorie</th>
    <th>1) Impact, 2) Gestion, 3) Exemple, 4) Outils</th>
    <th style="width: 20%;">Correspondance TLP</th>
  </tr>
  <tr>
    <td style="background-color:#DD0000; color:white; font-weight:bold;">SE, Secret</td>
    <td>
      <ol>
        <li>La divulgation pourrait nuire gravement aux intérêts de l’organisation.</li>
        <li>Gestion selon des procédures bien établies, stockée uniquement dans des emplacements chiffrés sous le contrôle exclusif du détenteur.</li>
        <li>Information classifiée par la loi (EU, OTAN, National, etc.), les mots de passe, l’information sensible.</li>
        <li>Utilisation de la cryptographie, coffre-fort, mémoire uniquement.</li>
      </ol>
    </td>
    <td>
      <strong>Rouge</strong><br /><br />
      Personal for named recipients only, mostly passed verbally or in person <!-- FR traduction missing -->
    </td>
  </tr>
  <tr>
    <td style="background-color:orange; font-weight:bold;">
    CO, Confidentiel
    </td>
    <td>
      <ol>
        <li>La divulgation pourrait nuire aux intérêts de l’organisation.</li>
        <li>Gestion selon des procédures bien établies, accès restreint à des personnes ayant un motif approuvé.</li>
        <li>Secret bancaire, données à caractères personnelles sensibles (santé), incidents de sécurité.</li>
        <li>Utilisation de la cryptographie, stockage local non partagé, gestion des autorisations d’accès formellement gérés.</li>
      </ol>
    </td>
    <td>
    <strong>Orange</strong><br /><br />
      Limited distribution, within organization, but only on a ‘need-to-know’ basis. <!-- FR traduction missing -->
    </td>
  </tr>
  <tr>
    <td style="background-color:#00CC00; font-weight:bold;">
      RE, Restreint
    </td>
    <td>
      <ol>
        <li>La divulgation pourrait être défavorable aux intérêts de l’organisation ou du groupe autorisé.</li>
        <li>Gestion sur base d’un contrat de travail ou d’un NDA, données à caractères personnelles (salaire), motivation partagée par un responsable de dossier.</li>
        <li>Documentation ou schéma de réseau interne, programme source.</li>
        <li>Utilisation de la cryptographie, gestion des autorisations d’accès strictement gérés.</li>
      </ol>
    </td>
    <td>
    <strong>Vert</strong><br /><br />
    Community wide. Circulation, may not be published or posted on the Internet, nor released outside of the community. <!-- FR traduction missing -->
    </td>
  </tr>
  <tr>
    <td style="background-color: #00CC00; font-weight:bold;">
    IN, Interne
    </td>
    <td>
      <ol>
        <li>La divulgation pourrait être parfois défavorable aux intérêts de l’organisation ou du groupe autorisé.</li>
        <li>Peut-être transmis à d’autres organisations de la même communauté.</li>
        <li>Guide utilisateur, certains numéros directs de téléphone, procédure de fonctionnement.</li>
        <li>Utilisation et transmission libre en interne, la protection doit être assurée en cas de transmission externe.</li>
      </ol>
    </td>
    <td>
      <strong>Vert</strong><br /><br />
      Community wide. Circulation, may not be published or posted on the Internet, nor released outside of the community. <!-- FR traduction missing -->
    </td>
  </tr>
  <tr>
    <td style="background-color: white; font-weight:bold;">
      PU, Public
    </td>
    <td>
      <ol>
        <li>Information dont la divulgation n’est généralement pas préjudiciable.</li>
        <li>Peut circuler librement, car accessible en dehors de l’organisation.</li>
        <li>Publications diverses, contenu informatif d’un site internet..</li>
        <li>Pas de contraintes sur l’utilisation ou la transmission.</li>
      </ol>
    </td>
    <td>
      <strong>Blanc</strong><br /><br />
      Unlimited, subject to standard copyright rules, WHITE information may be distributed freely, without restriction. <!-- FR traduction missing -->
    </td>
  </tr>
</table>

## Intégrité

Le schéma suivant indique l’abréviation officielle, le nom et une description des classes d'intégrité.

<table class="classification">
  <tr>
    <th style="width: 15%;">
      Catégorie
    </th>
    <th>
      1) Impact, 2) Gestion, 3) Exemple, 4) Outils
    </th>
  </tr>
  <tr>
    <td style="background-color:#DD0000; color:white; font-weight:bold;">
      VIT, Vital
    </td>
    <td>
      <ol>
        <li> La modification pourrait engendrer des pertes importantes pour l’organisme ou permettrait à l’auteur de la modification de s’enrichir considérablement.</li>
        <li>Des procédures formelles de contrôle périodique sont mises en œuvre très souvent (environ une semaine à un mois maximum).</li>
        <li>Courrier "DHL", système de GED, configuration des serveurs ou éléments de stockage, lignes téléphoniques.</li>
        <li>Utilisation de la signature, coffre fort.</li>
      </ol>
    </td>
  </tr>
  <tr>
    <td style="background-color: orange; font-weight:bold;">
      IMP, Important
    </td>
    <td>
      <ol>
        <li>La modification pourrait engendrer des pertes d’efficacité ou des coûts de redressements notables.</li>
        <li>Des procédures formelles de contrôle périodique sont mises en œuvre souvent. (environ 3 mois).</li>
        <li>Courrier recommandé, email chiffré, configuration des  postes clients (PC, laptop, PDA, etc.).</li>
        <li>Limitation des droits d’accès.</li>
      </ol>
    </td>
  </tr>
  <tr>
    <td style="background-color:white; font-weight:bold;">
      NOR, Normal
    </td>
    <td>
      <ol>
        <li>Il n’y a pas de contraintes supplémentaires de sécurité en plus de la protection de confidentialité.</li>
        <li>Des procédures de contrôle périodique sont mises en œuvre régulièrement. (environ 6 mois à 1 an).</li>
        <li>Courrier interne, email, consultation Internet, etc.).</li>
        <li>Pas de contraintes sur l’utilisation ou la transmission.</li>
      </ol>
    </td>
  </tr>
</table>

## Disponibilité

La disponibilité est exprimée en fonction du temps de réparation estimé en cas de panne.

<table class="classification classification--small">
  <tr>
    <th>Catégorie</th>
    <th>Code catégorie</th>
    <th>Temps calendaire d’arrêt par an</th>
    <th>Temps ouvré d’arrêt par an</th>
  </tr>
  <tr>
    <td>1</td>
    <td>20J</td>
    <td>1 mois</td>
    <td>+/- 20 jours</td>
  </tr>
  <tr>
    <td>2</td>
    <td>10J</td>
    <td>½ mois</td>
    <td>2 semaines</td>
  </tr>
  <tr>
    <td>3</td>
    <td>5J</td>
    <td>1 semaine</td>
    <td>5 jours</td>
  </tr>
  <tr>
    <td>4</td>
    <td>2.5J</td>
    <td>½ semaine</td>
    <td>2½ jours</td>
  </tr>
  <tr>
    <td>5</td>
    <td>1J</td>
    <td>1 day</td>
    <td>8 heures</td>
  </tr>
  <tr>
    <td>6</td>
    <td>0.5J</td>
    <td>½ day</td>
    <td>4 heures</td>
  </tr>
  <tr>
    <td>7</td>
    <td>0.1J</td>
    <td>1 hour</td>
    <td>1 heures</td>
  </tr>
</table>
