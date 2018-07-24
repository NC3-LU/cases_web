---
layout: article
title:  "Threat"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short: "Security Measures"
categories: knowhow
toc: true
---

Les menaces exploitent des vulnérabilités d'actifs et créent ainsi un impact. Les interactions entre actifs, menaces et vulnérabilités sont analysées lors de la gestion des risques.

Il est impossible pour un organisme d'exclure totalement l'existence de menaces. En matière de sécurité on s'applique donc généralement à

## EBIOSv2
[EBIOS : Expression des Besoins et Identification des Objectifs de Sécurité](-)

## Les menaces par groupes
EBIOSv2[1] propose une liste d'Agents Menaçants (e.g. menaces) génériques :

### **DOMMAGES PHYSIQUES**

* Incendie (PME : voir [Incendie]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}#fire))
* Dégât des eaux
* Pollution
* Sinistre majeur
* Destruction de matériel ou de supports (PME : voir [Équipement informatique ou de communication en panne]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware.markdown %}#failure-of-it-or-communications-equipment))
* Poussière, corrosion, gel

### **ÉVÉNEMENTS NATURELS**

* Phénomène climatique
* Phénomène sismique
* Phénomène volcanique
* Phénomène météorologique
* Crue

### **PERTE DE SERVICES ESSENTIELS**

* Défaillance de la climatisation
* Perte d'alimentation énergétique (PME : voir [Panne de courant]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}#power-cut))
* Perte des moyens de télécommunication (PME : voir [Accès au réseau indisponible]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}#network-unavailability) et [Interruption des communications]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}#interception-of-communications) et [Discontinuité des fournisseurs de service]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}#discontinuity-of-service-providers))

### **DISTRIBUTION DUES AUX RADIATIONS**

* Rayonnements électromagnétiques
* Rayonnements thermiques
* Impulsions électromagnétiques (IEM)

### **COMPROMISSION D'INFORMATIONS**

* Interceptions de signaux parasites compromettant
* Espionnage à distance (PME : voir [Interception des communications]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}#interception-of-communications) et [Spam / Phishing]({% link _knowhow/glossary/Phishing.markdown %}) et [Mesures contre les codes malicieux]({% link _publications/bestpractices/MaliciousSoftwareBP.markdown %}))
* Écoute passive (PME voir : [Écoute des réseaux sans fil]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}#wireless-network-tapping) )
* Vol de supports ou de documents (PME : voir [Vol caractérisé]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware.markdown %}#aggravated-theft) et [Pénétration dans les locaux]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}#infiltrating-the-premises))
* Vol de matériels (PME : voir [Vol caractérisé]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware.markdown %}#aggravated-theft) et [Pénétration dans les locaux]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}#infiltrating-the-premises))
* Récupération de supports recyclés ou mis au rebut (PME : voir [Récupération de supports]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware.markdown %}#device-recovery))
* Divulgation (PME : voir [Social engineering / Communication inadéquate]({% link _knowhow/glossary/SocialEngineering.markdown %}))
* Information sans garantie de l'origine
* Piégeage du matériel
* Piégeage du logiciel (PME voir : [Mesures contre les codes malicieux]({% link _knowhow/glossary/MaliciousCodes.markdown %}))
* Géolocalisation

### **DÉFAILLANCES TECHNIQUES**

* Panne matérielle (PME : voir [Équipement informatique ou de communication en panne]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware.markdown %}#failure-of-it-or-communications-equipment) et [Endommagement du matériel pendant le transport]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware.markdown %}#hardware-damaged-during-transport))
* Dysfonctionnement du matériel (PME : [Insertion ou suppression de matériels]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware.markdown %}#addition-or-removal-of-hardware))
* Saturation du système d'information
* Dysfonctionnement logiciel
* Atteinte à la maintenabilité du système d'information (PME : voir [Sauvegardes inutilisables]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware.markdown %}#unusable-backups) et [Administration impossible]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2HR.markdown %}#the-administrator) et [Environnement logiciel inapproprié]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Software.markdown %}#unsuitable-software-environment))

### **ACTIONS NON AUTORISÉES**

* Utilisation illicite du matériel (PME : voir [Utilisation abusive des ressources de l’organisation]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2HR.markdown %}#misuse-of-it-resources))
* Copie frauduleuse de logiciels (PME : voir [Utilisation d'un logiciel non autorise]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Software.markdown %}#use-of-unapproved-software)

## Qualification des menaces
Les menaces EBIOSv2 peuvent être qualifiées selon :

### **LEUR ORIGINE**

* E : Environnementale - tous les incidents qui ne sont pas causés par des actions humaines
* D : Délibérée - pour toutes les actions délibérées visant les actifs
* A : Accidentelle - utilisé pour toutes les actions humaines qui peuvent accidentellement endommager des actifs

### **LEUR ATTEINTE À LA**

* D: Disponibilité
* I: Intégrité
* C: Confidentialité

### **LEUR TYPE**

* N: Naturel
* H: Humain
* E: Environnemental

## Lien Vulnérabilités / Menaces / Actifs
Cette section fait référence aux vulnérabilités génériques du document EBIOS v2 – Section 4 – Outillage (Appréciation)

On peut identifier :

## Objectifs de sécurité
La section 2 Objectifs de sécurité génériques du document EBIOS v2 – Section 5 – Outillage (Traitement) [4] propose pour chacun des 7 types d'entités / [actifs]({% link _knowhow/glossary/Assets.markdown %}) haut niveau une liste d'objectifs de sécurité génériques adressant de fait les [vulnérabilités]({% link _knowhow/glossary/Vulnerabilities.markdown %}) génériques identifiées précédemment.

La section 3.2 Exigences issues de l'ISO 17799 du même document EBIOS v2 – Section 5 – Outillage (Traitement)[5] propose des exigences de sécurité en lien avec chacune des clauses de la norme ISO/IEC 17799 : 2000 (et non la version de la norme publiée en 2005 [[ISO/IEC 27002:2005]({% link _publications/ISO27000SF.markdown %})).

## EBIOS 2010
EBIOS 2010[6] propose une présentation différente de la version 2, tant sur le plan de la présentation des menaces que de l'approche globale.

EBIOS 2010 se divise selon les axes suivants :

### **TYPES DE BIENS SUPPORT**

* SYS - Systèmes informatiques et de téléphonie
* ORG - Organisations
* LOC - Locaux

## IMPACTS

* Impacts sur le fonctionnement
* Impacts humains
* Impacts sur les biens
* Autres impacts

### **SOURCES DE MENACES**

* Sources humaines
  * Délibéré malveillant
  * Source (humaine) interne
		* Capacités faibles
		* Capacités importantes
		* Capacités illimitées
	* Source (humaine) externe
		* Capacités faibles
		* Capacités importantes
		* Capacités illimitées
  * Accidentel sans intention de nuire
	* Source (humaine) interne
		* Capacités faibles
		* Capacités importantes
		* Capacités illimitées
	* Source (humaine) externe
		* Capacités faibles
		* Capacités importantes
		* Capacités illimitées
	* Sources non humaines

## Les menaces MEHARI par groupe de menace
* Désastres naturels
  * Feu
  * Dommages provoqués par l'eau
  * Catastrophes naturelles
* Désastres d’origine industrielle
  * Feu
  * Dommages provoqués par l'eau
  * Désastres industriels
  * Pollution mécanique
  * Pollution électromagnétique
  * Panne d'origine physique ou logique
  * Coupure de l'alimentation en électricité
  * Conditions inadéquates de température et/ou humidité
  * Défaillance des services de communications
  * Interruption des autres services et des approvisionnements essentiels
  * Dégradation des supports de stockage de l'information
  * Émanations électromagnétiques
* Erreurs et défaillances non intentionnées
  * Erreurs des utilisateurs
  * Erreurs de l'administrateur
  * Erreurs de contrôle (log)
  * Erreurs de configuration
  * Déficiences au niveau de l'organisation
  * Diffusion de software nuisible
  * Erreurs de ré-acheminement
  * Erreurs de séquence
  * Fuites d'information
  * Altération de l'information
* Introduction de fausses informations
  * Dégradation de l'information
  * Destruction de l'information
  * Divulgation de l'information
  * Vulnérabilités des programmes (software)
  * Erreurs de maintenance / actualisation des programmes (software)
  * Erreurs de maintenance / actualisation des équipements (hardware)
  * Effondrement du système provoqué par l'épuisement des ressources
  * Perte d'équipements
  * Indisponibilité du personnel
* Attaques délibérées
  * Manipulation de la configuration
  * Supplantation de l'identité de l'utilisateur
  * Abus de privilèges d'accès
  * Utilisation non prévue
  * Diffusion de software nuisible
  * Ré-acheminement des messages
  * Altération de séquence
  * Accès non autorisé
  * Analyse du trafic
  * Répudiation
  * Interception d'information (écoute)
  * Modification de l'information
  * Introduction de fausses informations
  * Corruption de l'information
  * Divulgation de l'information
  * Manipulation des programmes
  * Refus de service
  * Vol d'équipements
  * Attaque destructive
  * Occupation ennemie
  * Indisponibilité du personnel
  * Extorsion
  * Ingénierie sociale
