---
layout: article
title:  "Politique de Sécurité"
menutitle:  
logo:
date:   2017-11-06 00:00:00 +0100
short: "Renforcez vos défenses. Organisez votre protection."
categories: knowhow
toc: true
---
## Classification et responsabilités des ressources
Il convient de tenir à jour un inventaire des ressources importantes et vitales de « l’organisation ». Il prend la forme d’un tableau décrivant la ressource et désignant la ou les personnes responsables. La classification des actifs est une tâche ultimement importante.

Le niveau d’importance de la ressource pour l’entreprise est également précisé :

* vital
* important

Sont considérés comme ressources les éléments suivants :

* ordinateurs (PC, portables, serveurs, mini) et imprimantes ;
* équipements de communication (modem, switch, routeur, Pabx, fax, etc.) ;
* fichiers et bases de données (quels que soient leurs supports : disques, CD Rom, bandes, etc.) ;
* applications (logiciels) ;
* documents (contrats, procédures, plans, archives, etc.).

### Remarque

Les éléments désignés comme « vitaux » sont ceux qui pourraient compromettre l’existence de « l’organisation » s’ils venaient à disparaître, à être divulgués à l’extérieur ou à être défectueux.

Les éléments considérés comme « importants » sont ceux qui pourraient causer des conséquences non négligeables à l’entreprise dans les mêmes conditions.


### Mesures de sécurité

* [les serveurs fichier]({% link _knowhow/cisoapproach/polsec-class/polsec-class-fileserver.markdown %})
* [les serveurs mail]({% link _knowhow/cisoapproach/polsec-class/polsec-class-email.markdown %})
* [le réseau fixe]({% link _knowhow/cisoapproach/polsec-class/polsec-class-netfix.markdown %})
* [le réseau wifi interne]({% link _knowhow/cisoapproach/polsec-class/polsec-class-netwifi.markdown %})
* [le réseau wifi pour clients]({% link _knowhow/cisoapproach/polsec-class/polsec-class-netwifi.markdown %})
* [les ordinateurs connectés à l'Internet]({% link _knowhow/cisoapproach/polsec-class/polsec-class-fixpost.markdown %})
* [les ordinateurs portables]({% link _knowhow/cisoapproach/polsec-class/polsec-class-mobile.markdown %})

### Mesures organisationnelles directement liées

* Organisation de la sécurité
  * Attribution des responsabilités
* Aspects opérationnels et communications
  * Procédures documentées
* Contrôle d’accès
  * Politique de contrôle d’accès
  * Gestion des droits d’accès
* Conformité
  * Identification de la législation applicable
  * Propriété intellectuelle
  * Protection des données opérationnelles
  * Protection des données à caractère personnel

### Mesures techniques

* [la classification]({% link _knowhow/cisoapproach/polsec-class/polsec-class-class.markdown %})


## Inventaire des actifs

Il convient de tenir à jour un inventaire des ressources (actifs) majeures de « l’organisation ». Il prend la forme d’un tableau décrivant la ressource et désignant la ou les personnes responsables. Pour chaque chaque actif, il convient de procéder à une classification selon les besoins de confidentialité, d'intégrité et de disponibilité.

Les éléments désignés comme « vitaux » sont ceux qui pourraient compromettre l’existence de « l’organisation » s’ils venaient à disparaître, à être divulgués à l’extérieur ou à être défectueux. Les éléments considérés comme « importants » sont ceux qui pourraient causer des conséquences non négligeables à l’entreprise dans les mêmes conditions.

La gestion et la classification des biens se basent sur les principes suivants :

1. Application à tout actif, c’est-à-dire à tout ce qui a de la valeur, y compris les informations, telles que reprises dans un inventaire.
2. Définition d’un gestionnaire pour chaque type d'actif.
3. Garantir l’utilisation correcte des actifs en accordant des règles de sécurité aux différentes classes.
4. Révision régulière par le gestionnaire.
5. Classification en 3 axes : confidentialité, intégrité et disponibilité.
6. Classification en fonction de l’impact.
7. Héritage de la classification de confidentialité.
8. Qualification des contenants afin de simplifier les règles de gestion.
9. Classification par défaut.
10. Marquage pour assurer la prise en compte des règles de sécurité dans le traitement des actifs.
11. Utilisation de la cryptographie afin de pouvoir véhiculer une information sensible dans un contenant suffisamment protégé.

D’où découlent les règles et responsabilités suivantes :

1. Chaque bien doit être inventorié et attribué à un gestionnaire qui est chargé de définir la classification et les mesures de sécurité à appliquer.
2. Un bien contenant d’autres biens a au minimum la même classification que le bien le plus sensible qui y est intégré.
3. Une information a toujours la même classification, indépendamment de la forme sous laquelle elle se trouve.
4. Le responsable de la sécurité est chargé de qualifier les contenants.
5. La politique de sécurité et tout document y intégré seront inspirés des bonnes pratiques reconnues sur le plan international en matière de gestion de la sécurité. Ces bonnes pratiques sont documentées dans les normes ISO/IEC 27001 et 27002.
6. Le gestionnaire d’un bien doit être au rang d’un chargé de la direction d’une division ou de son remplaçant.
7. Le responsable de la sécurité est chargé de qualifier les contenants.
8. La politique de classification est mise en œuvre à travers des procédures.
9. Ces procédures et documents sont mis à disposition de tout le personnel.
