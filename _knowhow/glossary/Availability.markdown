---
layout: article
title:  "Availability"
menutitle: 
logo:
date:  2017-11-06 00:00:00 +0100
short: "Security Measures"
categories: knowhow
toc: true
---

<h3 class="titre-page" id="in-brief">In brief</h3>
La 'disponibilité' d'un actif au sein d'une entité,  c'est l'assurance que celui-ci est utilisable en terme de temps et de performance prévue. [Les mesures de sécurité]({% link _publications/ProtectingYourCompany.markdown %}) voulant garantir la disponibilité des actifs doivent donc veiller à ce qu'une ressource reste utilisable en termes de capacités et temps prévus. (Voir aussi [classification]({% link _knowhow/cisoapproach/SecurityPolicy-Classification.markdown %})).

<h3 class="titre-page" id="menaces-mettant-en-peril-la-disponibilite">Menaces mettant en péril la disponibilité</h3>

Voici une liste, non exhaustive, des menaces EBIOS qui peuvent mettre en péril la disponibilité d'un actif :

### **Dommages physiques**

* Incendie (PME: voir [Incendie]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}\#fire))

* Dégât des eaux

* Pollution

* Sinistre majeur

* Destruction de matériel ou de supports (PME: voir [Équipement informatique ou de communication en panne]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware.markdown %}\#failure-of-it-or-communications-equipment) )

* Poussière, corrosion, gel

### **Evenements naturels**

* Phénomène climatique

* Phénomène sismique

* Phénomène volcanique

* Phénomène météorologique

* Crue

### **Perte de services essentiels**

* Défaillance de la climatisation

* Perte d'alimentation énergétique (PME: voir [Panne de courant]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}\#power-cut))

* Perte des moyens de télécommunication (PME: voir [Accès au réseau indisponible]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}\#network-unavailability) et [Interruption des communications]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}\#network-unavailability) et [Discontinuité des fournisseurs de service]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}\#discontinuity-of-service-providers))

### **Distribution dues aux radiations**

* Rayonnements électromagnétiques

* Rayonnements thermiques

* Impulsions électromagnétiques (IEM)

### **Compromission d'informations**

* Vol de supports ou de documents (PME: voir [Vol caractérisé]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware.markdown %}\#aggravated-theft) et [Pénétration dans les locaux]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}\#infiltrating-the-premises))

* Vol de matériels (PME: voir [Vol caractérisé]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware.markdown %}\#aggravated-theft) et [Pénétration dans les locaux]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}\#infiltrating-the-premises))

### **Defaillances techniques**

* Panne matérielle (PME: voir [Équipement informatique ou de communication en panne]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware.markdown %}\#failure-of-it-or-communications-equipment) et [Endommagement du matériel pendant le transport]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware.markdown %}\#hardware-damaged-during-transport))

* Dysfonctionnement du matériel (PME: [Insertion ou suppression de matériels]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware.markdown %}\#addition-or-removal-of-hardwar}))

* Saturation du système d'information

* Dysfonctionnement logiciel

* Atteinte à la maintenabilité du système d'information (PME: voir [Sauvegardes inutilisables]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware.markdown %}\#unusable-backups) et [Administration impossible]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Software.markdown %}\#unavailability-of-administrators) et [Environnement logiciel inapproprié]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Software.markdown %}\#unsuitable-software-environment))

### **Actions non autorisees**

* Utilisation illicite des matériels (PME: voir [Utilisation abusive des ressources de l’organisation]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2HR.markdown %}\#misuse-of-it-resources))

* Utilisation de logiciels contrefaits ou copiés (PME: voir : [Licence non valide ou inexistante]({% link _knowhow/bestpractices/SecurityMeasures4SME-LegalAspects.markdown %}\#invalid-or-non-existent-licence))

* Traitement illicite des données (PME: voir [Traitement non autorisé de données personnelles - Surveillance des employés]({% link _knowhow/bestpractices/SecurityMeasures4SME-LegalAspects.markdown %}\#unauthorised-processing-of-personal-data--employee-monitoring) et [Exigences réglementaires]({% link _knowhow/bestpractices/SecurityMeasures4SME-LegalAspects.markdown %}\#regulatory-requirements))

### **Compromission de fonctions**

* Erreur d'utilisation (PME: voir [Erreur humaine]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2HR.markdown %}\#human-error-prevention-measures))

* Abus de droits (PME: voir [Utilisation abusive des ressources de l’organisation]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2HR.markdown %}\#misuse-of-it-resources))

* Usurpation de droit (PME: voir [Administrateur malveillant]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2HR.markdown %}\#the-administrator) et [Utilisation d’un accès réservé à un utilisateur par un tiers]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2HR.markdown %}\#use-of-limited-access-by-a-third-party))

* Déni de service (PME: voir [Attaques par déni de service et déni de service distribués]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}\#denial-of-servicedistributed-service))

* Atteinte à la disponibilité du personnel (PME: voir [Personnel absent]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2HR.markdown %}\#staff-absences))