---
layout: knowhow
title:  "Security Policy – Physical and environmental security"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: f-ciso
toc: true
ref: cisophysiscalenvironmentalsecurity
lang: fr
---
## Périmètre de sécurité physique

La [sécurité physique]({% link _knowhow/glossary/PhysicalSecurity_fr.markdown %}) concernant l'organisation est le premier aspect de sécurité à mettre en œuvre. En effet, quel intérêt y a t'il à se protéger avec des mots de passe ou des logiciels compliqués si une personne peut accéder physiquement à une ressource essentielle pour la voler, la modifier ou la détruire ? (PME voir: [Pénétration dans les locaux]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure_fr.markdown %}#infiltrating-the-premises) et [Insertion ou suppression de matériels]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware_fr.markdown %}#addition-or-removal-of-hardware) et [Récupération de supports]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware_fr.markdown %}#device-recovery) et [Vol caractérisé]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware_fr.markdown %}#aggravated-theft)).

Ayez toujours conscience de la valeur réelle d’une ressource (voir [classification]({% link _knowhow/cisoapproach/SecurityPolicy-Classification_fr.markdown %}))  afin de pouvoir planifier une protection adéquate.

Tous les éléments répertoriés comme importants ou vitaux pour "l’organisation" doivent être installés dans des locaux sécurisés. Ces locaux constituent le périmètre de sécurité.

### Appliquer des mesures de sécurité pour:

* [les ordinateurs]({% link _publications/recommendationsecuring/SecuringFixedWorkstation_fr.markdown %})
* [les ordinateurs portables]({% link _publications/recommendationsecuring/SecuringLaptops_fr.markdown %})
* [les serveurs fichier]({% link _publications/recommendationsecuring/Recommendations4securingFileServer_fr.markdown %})
* [les serveurs mail]({% link _publications/recommendationsecuring/Recommendations4securingEmailServer_fr.markdown %})
* [le réseau fixe]({% link _publications/recommendationsecuring/SecuringFixedNetwork_fr.markdown %})
* [le réseau wifi interne]({% link _publications/recommendationsecuring/SecuringWifiNetwork_fr.markdown %}#wifi-for-employees)
* [le réseau wifi pour clients]({% link _publications/recommendationsecuring/SecuringWifiNetwork_fr.markdown %}#wifi-for-visitorsexternal-users)
* [protéger les locaux]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure_fr.markdown %}#infiltrating-the-premises)

### Mesures organisationnelles directement liées:

* [Sécurité physique et environnementale]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %})
  * [Règles dans le périmètre]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#rules-within-the-perimeter)
  * [Bureaux en ordre]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#tidy-office-policy)
* [Contrôle d’accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %})
  * [Politique de contrôle d’accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-control-policy)
  * [Gestion des droits d’accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-rights-management)
* [Gestion des incidents liés à la sécurité]({% link _knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents_fr.markdown %})
  * [Signalement des événements liés à la sécurité de l’information]({% link _knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents_fr.markdown %}#reporting-information-security-events)
* [Gestion de la continuité de l’entreprise]({% link _knowhow/cisoapproach/SecurityPolicy-ManagingBusinessContinuity_fr.markdown %})
  * [La continuité de fonctionnement]({% link _knowhow/cisoapproach/SecurityPolicy-ManagingBusinessContinuity_fr.markdown %}#operational-continuity)


### Mesures techniques:

[sécurité physique]({% link _knowhow/glossary/PhysicalSecurity_fr.markdown %})

## Règles dans le périmètre

Les locaux du périmètre de sécurité doivent être:

* protégés contre l’accès de personnes non autorisées et donc a fortiori aux personnes étrangères à "l’organisation". (PME voir:  [Pénétration dans les locaux]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure_fr.markdown %}#infiltrating-the-premises) et [Insertion ou suppression de matériels]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware_fr.markdown %}) et [Récupération de supports]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware_fr.markdown %}#device-recovery) et [Vol caractérisé]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware_fr.markdown %}#aggravated-theft)). Une seule porte permet d’y accéder et l’autorisation est donnée par le responsable informatique,
* protégés contre l’incendie. Les portes doivent être coupe-feu et des alarmes incendie doivent être installés. (PME: voir [Incendie]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure_fr.markdown %}#fire))

D’autre part, les règles suivantes doivent être respectées:

* les clés ne doivent en aucun cas être accessibles au public.
* les équipements de bureaux de type fax ou photocopieurs doivent être situés dans un périmètre sûr, mais pas à proximité des éléments les plus essentiels, de façon à ne pas multiplier les demandes d’accès dans cette zone,
* les portes et les fenêtres doivent être fermées à clé, en particulier en dehors des heures de bureau,
* les accès, en particulier au rez-de-chaussée, doivent être protégés contre l’intrusion, soit par des grilles ou par un système de détection électronique couplé à une alarme sonore,
* les matériaux dangereux ou facilement inflammables (ceci inclut les cartons, papiers, poubelles et produits de nettoyage) ne doivent pas être stockés à proximité des éléments vitaux ou importants.


### Appliquer des mesures de sécurité pour:

* [les serveurs fichier]({% link _publications/recommendationsecuring/Recommendations4securingFileServer_fr.markdown %})
* [les serveurs mail]({% link _publications/recommendationsecuring/Recommendations4securingEmailServer_fr.markdown %})
* [le réseau fixe]({% link _publications/recommendationsecuring/SecuringWifiNetwork_fr.markdown %})
* [le réseau wifi interne]({% link _publications/recommendationsecuring/SecuringWifiNetwork_fr.markdown %}#wifi-for-employees)
* [le réseau wifi pour clients]({% link _publications/recommendationsecuring/SecuringWifiNetwork_fr.markdown %}#wifi-for-visitorsexternal-users)
* [les ordinateurs connectés à l'Internet]({% link _publications/recommendationsecuring/SecuringFixedWorkstation_fr.markdown %})
* [les ordinateurs portables]({% link _publications/recommendationsecuring/SecuringLaptops_fr.markdown %})


### Mesures organisationnelles directement liées:

* [Classification et maîtrise des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %})
  * [Classification et responsabilité des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %}#classification-and-responsibility-for-resources)
* [Aspects humains]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %})
  * [La formation et l’information]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %}#training-and-information)
  * [La réponse aux incidents et dysfonctionnements de sécurité]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %}#response-to-incidents-and-malfunctions)
* [Sécurité physique et environnementale]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %})
  * [Périmètre de sécurité physique]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#physical-security-perimeter)
  * [Bureaux en ordre]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#tidy-office-policy)
* [Aspects opérationnels et communications]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %})
  * [Procédures documentées]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#documentation-of-procedures)
* [Gestion des incidents liés à la sécurité]({% link _knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents_fr.markdown %})
  * [Signalement des événements liés à la sécurité de l’information]({% link _knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents_fr.markdown %}#reporting-information-security-events)


### Mesures techniques

La [sécurité physique]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %})

## Sécurité électrique des équipements

Les alimentations électriques des équipements vitaux doivent être sécurisées:

* par une alimentation de 2 sources différentes (2 fusibles sur 2 circuits) quand les équipements disposent de 2 alimentations (PME: voir [Service interruption]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure_fr.markdown %}#service-interruption) et [Panne de courant]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure_fr.markdown %}#power-cut) et [Discontinuité des fournisseurs de service]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure_fr.markdown %}#discontinuity-of-service-providers));
* par une unité non interruptible qui garantit l’alimentation pendant les petites coupures et suffisamment longtemps pour éteindre les équipements proprement;
* par un générateur de secours.


### Appliquer dans mesures de sécurité pour:

* [les serveurs fichier]({% link _publications/recommendationsecuring/Recommendations4securingFileServer_fr.markdown %})
* [les serveurs mail]({% link _publications/recommendationsecuring/Recommendations4securingEmailServer_fr.markdown %})

### Mesures organisationnelles directement liées:

* [Classification et maîtrise des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %})
  * [Classification et responsabilité des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %}#classification-and-responsibility-for-resources)
* [Sécurité physique et environnementale]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %})
  * [Périmètre de sécurité physique]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#physical-security-perimeter)
  * [Maintenance]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#maintenance)
* [Aspects opérationnels et communications]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %})
  * [Procédures documentées]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#documentation-of-procedures)
* [Gestion de la continuité de l’entreprise]({% link _knowhow/cisoapproach/SecurityPolicy-ManagingBusinessContinuity_fr.markdown %})
  * [La continuité de fonctionnement]({% link _knowhow/cisoapproach/SecurityPolicy-ManagingBusinessContinuity_fr.markdown %}#operational-continuity)

### Mesures techniques

La [sécurité physique]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %})

## Maintenance

Pour les ressources classifiées comme importantes ou vitales, un contrat de maintenance doit être conclu avec un délai d’intervention ou de remplacement garanti, compatible avec les besoins de disponibilité de la ressource. (PME: voir [Licence non valide ou inexistante]({% link _knowhow/bestpractices/SecurityMeasures4SME-LegalAspects_fr.markdown %}#invalid-or-non-existent-licence) et [Administration impossible]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Software_fr.markdown %}#unavailability-of-administrators)). La maintenance est un critère important pour optimiser la [disponibilité]({% link _knowhow/glossary/Availability_fr.markdown %}) des [ressources]({% link _knowhow/glossary/Assets_fr.markdown %})

Lorsqu’un équipement quitte "l’organisation" pour maintenance, ou est [mise en rebut]({% link _knowhow/glossary/Discarded_fr.markdown %}), il ne doit pas contenir de données confidentielles. Si tel est le cas, et selon la sensibilité des données, une procédure spécifique doit être décidée (traitement sur place, accompagnement du matériel, destruction du matériel, etc.). (PME: voir [Endommagement du matériel pendant le transport]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware_fr.markdown %}#hardware-damaged-during-transport) et [Récupération de supports]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware_fr.markdown %}#device-recovery))

Voir aussi: [SOS - donner en réparation]({% link _knowhow/sos/SOS-HandoverToRepairs_fr.markdown %})

### Appliquer dans mesures de sécurité pour:

* [les serveurs fichier]({% link _publications/recommendationsecuring/Recommendations4securingFileServer_fr.markdown %})
* [les serveurs mail]({% link _publications/recommendationsecuring/Recommendations4securingEmailServer_fr.markdown %})

### Mesures organisationnelles directement liées:

* [Organisation de la sécurité]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity_fr.markdown %})
  * [Attribution des responsabilités]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity_fr.markdown %}#attribution-of-responsibilities)
  * [Accès par des tiers et sous-traitance]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity_fr.markdown %}#third-party-access-and-outsourcing)
* [Classification et maîtrise des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %})
  * [Classification et responsabilité des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %}#classification-and-responsibility-for-resources)
* [Sécurité physique et environnementale]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %})
  * [Sécurité électrique des équipements]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#electrical-equipment-safety)
* [Aspects opérationnels et communications]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %})
  * [Procédures documentées]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#documentation-of-procedures)
* [Développement et maintenance des systèmes]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %})
  * [Gestion des vulnérabilités techniques]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}#managing-technical-vulnerabilities)
* [Gestion de la continuité de l’entreprise]({% link _knowhow/cisoapproach/SecurityPolicy-ManagingBusinessContinuity_fr.markdown %})
  * [La continuité de fonctionnement]({% link _knowhow/cisoapproach/SecurityPolicy-ManagingBusinessContinuity_fr.markdown %})


### Mesures techniques:

La [sécurité physique]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %})

## Sécurité des équipements hors locaux

Les équipements utilisés pour le traitement des informations à l'extérieur des locaux de "l’organisation" (à la maison, dans un hôtel, chez un client), comme les laptops ou téléphones, sont soumis à des procédures de sécurité semblables. Toutefois, les utilisateurs doivent être particulièrement vigilants aux risques de vols et garder le matériel sous surveillance à tout instant. Une assurance spécifique doit être contractée pour ce type d’équipement. Le matériel peut être marqué pour prévenir tout échange. Une autorisation doit être accordée par le responsable de l’équipement dans "l’organisation" avant toute sortie de matériel. Celui-ci peut envisager l’utilisation ou non d’outils de chiffrement des données présentes sur le disque dur. (PME: voir [Endommagement du matériel pendant le transport]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware_fr.markdown %}#hardware-damaged-during-transport); [Vol caractérisé]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware_fr.markdown %}#aggravated-theft); [Mesures de sécurité basiques pour les ordinateurs portables]({% link _publications/recommendationsecuring/SecuringLaptops_fr.markdown %}#recommendations))

### Appliquer des mesures de sécurité pour:

* [les ordinateurs portables]({% link _publications/recommendationsecuring/SecuringLaptops_fr.markdown %})

### Mesures organisationnelles directement liées:

* [Classification et maîtrise des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %})
  * [Classification et responsabilité des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %}#classification-and-responsibility-for-resources)
* [Contrôle d’accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %})
  * [Politique de contrôle d’accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-control-policy)
  * [Gestion des droits d’accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-rights-management)
* [Développement et maintenance des systèmes]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %})
  * [Utilisation du chiffrement]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}#encryption)
  * [Gestion des vulnérabilités techniques]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}#managing-technical-vulnerabilities)
* [Gestion des incidents liés à la sécurité]({% link _knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents_fr.markdown %})
  * [Signalement des événements liés à la sécurité de l’information]({% link _knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents_fr.markdown %}#reporting-information-security-events)
* [Conformité]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %})
  * [Protection des données opérationnelles]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %}#protection-of-operational-data)
  * [Protection des données à caractère personnel]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %}#personal-data-protection)

### Mesures techniques:

* [sécurité physique]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %})
* [Prévenir le vol physique]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#tidy-office-policy)

## Mise en rebut et réutilisation des équipements

Tout équipement qui est [mise au rebut]({% link _knowhow/glossary/Discarded_fr.markdown %}) ou réutilisé dans un autre contexte doit être vidé de toutes ses données;  les disques doivent être effacés. Le système pourra être réinstallé, le cas échéant. Selon la sensibilité des données sauvegardées, la destruction physique des disques (par broyeur ou démagnétiseur) doit être envisagée. (PME: voir [Récupération de supports]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware_fr.markdown %}#device-recovery)).

L’effacement classique des fichiers est insuffisant car les données resteront présentes sur le disque. Si les compétences internes manquent de connaissances pour le faire, un fournisseur externe peut s'en charger sous la surveillance d’un membre de l’organisation.

Quoi qu'il arrive, soyez respectueux de l'environnement.

### Appliquer des mesures de sécurité pour:

* [les ordinateurs]({% link _publications/recommendationsecuring/SecuringFixedWorkstation_fr.markdown %})
* [les ordinateurs portables]({% link _publications/recommendationsecuring/SecuringLaptops_fr.markdown %})
* [les serveurs fichier]({% link _publications/recommendationsecuring/Recommendations4securingFileServer_fr.markdown %})
* [les serveurs mail]({% link _publications/recommendationsecuring/Recommendations4securingEmailServer_fr.markdown %})

### Mesures organisationnelles directement liées:

* [Classification et maîtrise des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %})
  * [Classification et responsabilité des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %}#classification-and-responsibility-for-resources)
* [Aspects humains]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %})
  * [La formation et l’information]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %}#training-and-information)
* [Sécurité physique et environnementale]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %})
  * [Maintenance]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#maintenance)
* [Aspects opérationnels et communications]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %})
  * [Procédures documentées]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#documentation-of-procedures)
* [Conformité]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %})
  * [Propriété intellectuelle]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %}#intellectual-property)
  * [Protection des données opérationnelles]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %}#protection-of-operational-data)
  * [Protection des données à caractère personnel]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %}#personal-data-protection)

### Mesures techniques:

* [Mise en rebut]({% link _knowhow/glossary/Discarded_fr.markdown %})
* [sécurité physique]({% link _knowhow/glossary/PhysicalSecurity_fr.markdown %})

## Politique du bureau propre

Respectez une politique du rangement de bureau, à savoir:

* rangez les papiers et [supports informatiques amovibles]({% link _knowhow/glossary/RemovableDevices_fr.markdown %}) (Clés USB, disques,etc) sans les laisser à la vue de tout le monde. Enlever vos documents de l'imprimante, fax ou photocopieurs;
* sauvegardez sous clés les supports les plus importants ou même dans des coffres ignifuges;
* lorsqu’une personne laisse son PC inutilisé pendant quelques minutes, le logiciel économiseur d’écran (screensaver) devrait s'activer. Le mot de passe permettra de quitter l’économiseur et de reprendre le travail. Il est fortement déconseillé de contourner ce mécanisme;
* utilisez une poubelle spéciale ou des broyeurs pour la destruction des documents papiers sensibles.


### Mesures organisationnelles directement liées:

* [Organisation de la sécurité]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity_fr.markdown %})
  * [Attribution des responsabilités]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity_fr.markdown %}#attribution-of-responsibilities)
  * [Accès par des tiers et sous-traitance]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity_fr.markdown %}#third-party-access-and-outsourcing)
* [Classification et maîtrise des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %})
  * [Classification et responsabilité des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %}#classification-and-responsibility-for-resources)
* [Sécurité physique et environnementale]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %})
  * [Périmètre de sécurité physique]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#physical-security-perimeter)
  * [Règles dans le périmètre]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#rules-within-the-perimeter)
* [Aspects opérationnels et communications]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %})
  * [Procédures documentées]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#documentation-of-procedures)
* [Conformité]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %})
  * [Propriété intellectuelle]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %}#intellectual-property)
  * [Protection des données opérationnelles]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %}#protection-of-operational-data)
  * [Protection des données à caractère personnel]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %}#personal-data-protection)

### Mesures techniques:

La [sécurité physique]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %})
