---
layout: knowhow
category: "Knowhow"
title:  "Security Policy – Classification and control of resources"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: f-ciso
toc: true
ref: cisoclassificationcontrolresources
lang: fr
---
## Classification et responsabilités des ressources

Il convient de tenir à jour un [inventaire des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %}#inventory-of-assets) importantes et vitales de "l’organisation". Il prend la forme d’un tableau décrivant la ressource et désignant la ou les personnes responsables. La [classification]({% link _knowhow/cisoapproach/SecurityPolicy-Classification_fr.markdown %}) des [actifs]({% link _knowhow/glossary/Assets_fr.markdown %}) est une tâche ultimement importante.

Le niveau d’importance de la ressource pour l’entreprise est également précisé:

* vital
* important

Sont considérés comme [ressources]({% link _knowhow/glossary/Assets_fr.markdown %}) les éléments suivants:

* ordinateurs (PC, portables, serveurs, mini) et imprimantes;
* équipements de communication (modem, switch, routeur, Pabx, fax, etc.);
* fichiers et bases de données (quels que soient leurs supports: disques, CD Rom, bandes, etc.);
* applications (logiciels);
* documents (contrats, procédures, plans, archives, etc.).

#### Remarque

Les éléments désignés comme "**vitaux**" sont ceux qui pourraient compromettre l’existence de "l’organisation" s’ils venaient à disparaître, à être divulgués à l’extérieur ou à être défectueux.

Les éléments considérés comme "**importants**" sont ceux qui pourraient causer des conséquences non négligeables à l’entreprise dans les mêmes conditions.

#### Mesures de sécurité:

* [les serveurs fichier]({% link _publications/recommendationsecuring/Recommendations4securingFileServer_fr.markdown %})
* [les serveurs mail]({% link _publications/recommendationsecuring/Recommendations4securingEmailServer_fr.markdown %})
* [le réseau fixe]({% link _publications/recommendationsecuring/SecuringFixedNetwork_fr.markdown %})
* [le réseau wifi interne]({% link _publications/recommendationsecuring/SecuringWifiNetwork_fr.markdown %}#wifi-for-employees)
* [le réseau wifi pour clients]({% link _publications/recommendationsecuring/SecuringWifiNetwork_fr.markdown %}#wifi-for-visitorsexternal-users)
* [les ordinateurs connectés à l'Internet]({% link _publications/recommendationsecuring/SecuringFixedWorkstation_fr.markdown %})
* [les ordinateurs portables]({% link _publications/recommendationsecuring/SecuringLaptops_fr.markdown %})

#### Mesures organisationnelles directement liées:

* [Organisation de la sécurité]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity_fr.markdown %})
  * [Attribution des responsabilités]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity_fr.markdown %}#attribution-of-responsibilities)
* [Aspects opérationnels et communications]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %})
  * [Procédures documentées]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#documentation-of-procedures)
* [Contrôle d’accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %})
  * [Politique de contrôle d’accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-control-policy)
  * [Gestion des droits d’accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-rights-management)
* [Conformité]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %})
  * [Identification de la législation applicable]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %}#comply-with-legislation)
  * [Propriété intellectuelle]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %}#intellectual-property)
  * [Protection des données opérationnelles]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %}#protection-of-operational-data)
  * [Protection des données à caractère personnel]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %}#personal-data-protection)

#### Mesures techniques:

* [classification]({% link _knowhow/cisoapproach/SecurityPolicy-Classification_fr.markdown %})

## Inventaire des actifs

Il convient de tenir à jour un inventaire des ressources ([actifs]({% link _knowhow/glossary/Assets_fr.markdown %})) majeures de "l’organisation". Il prend la forme d’un tableau décrivant la ressource et désignant la ou les personnes responsables. Pour chaque chaque actif, il convient de procéder à une [classification]({% link _knowhow/cisoapproach/SecurityPolicy-Classification_fr.markdown %})) selon les besoins de [confidentialité]({% link _knowhow/bestpractices/SecurityMeasures4SME-CheckList_fr.markdown %})), d'[intégrité]({% link _knowhow/glossary/Integrity_fr.markdown %})) et de [disponibilité]({% link _knowhow/glossary/Availability_fr.markdown %})).

Les éléments désignés comme "vitaux" sont ceux qui pourraient compromettre l’existence de "l’organisation" s’ils venaient à disparaître, à être divulgués à l’extérieur ou à être défectueux. Les éléments considérés comme "importants" sont ceux qui pourraient causer des conséquences non négligeables à l’entreprise dans les mêmes conditions.

La gestion et la classification des biens se basent sur les principes suivants:

1. Application à tout actif, c’est-à-dire à tout ce qui a de la valeur, y compris les informations, telles que reprises dans un inventaire.
2. Définition d’un gestionnaire pour chaque type d'actif.
3. Garantir l’utilisation correcte des actifs en accordant des règles de sécurité aux différentes classes.
4. Révision régulière par le gestionnaire.
5. Classification en 3 axes: confidentialité, intégrité et disponibilité.
6. Classification en fonction de l’[impact]({% link _knowhow/glossary/Impact_fr.markdown %})).
7. Héritage de la classification de confidentialité.
8. Qualification des contenants afin de simplifier les règles de gestion.
9. Classification par défaut.
10.Marquage pour assurer la prise en compte des règles de sécurité dans le traitement des actifs.
11. Utilisation de la [cryptographie]({% link _knowhow/glossary/Cryptography_fr.markdown %})) afin de pouvoir véhiculer une information sensible dans un contenant suffisamment protégé.

D’où découlent les règles et responsabilités suivantes:

1. Chaque bien doit être inventorié et attribué à un gestionnaire qui est chargé de définir la classification et les [mesures de sécurité]({% link _publications/ProtectingYourCompany_fr.markdown %})) à appliquer.
2. Un bien contenant d’autres biens a au minimum la même classification que le bien le plus sensible qui y est intégré.
3. Une information a toujours la même classification, indépendamment de la forme sous laquelle elle se trouve.
4. Le responsable de la sécurité est chargé de qualifier les contenants.
5. La politique de sécurité et tout document y intégré seront inspirés des bonnes pratiques reconnues sur le plan international en matière de gestion de la sécurité. Ces bonnes pratiques sont documentées dans les normes [ISO/IEC 27001]({% link _publications/ISO27000SF/ISO27001-ISMS_fr.markdown %})) et [27002]({% link _publications/ISO27000SF/ISO27002-CodeBestPractices4ISM_fr.markdown %})).
6. Le gestionnaire d’un bien doit être au rang d’un chargé de la direction d’une division ou de son remplaçant.
7. Le responsable de la sécurité est chargé de qualifier les contenants.
8. La politique de classification est mise en œuvre à travers des procédures.
9. Ces procédures et documents sont mis à disposition de tout le personnel.
