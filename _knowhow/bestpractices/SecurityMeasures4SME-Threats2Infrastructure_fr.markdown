---
layout: knowhow
category: "Knowhow"
title:  "Mesures de sécurité pour PME - L'infrastructure face aux menaces"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: f-bestpract
toc: true
ref: bestpractthreatstoinfrastructure
lang: fr
---
Par infrastructure l'on comprend ici tous les actifs et services essentiels sur lesquels repose le système d’information, comme notamment la fourniture de services d’énergie, de communication ou de traitement. Ces services sont donc critiques pour le fonctionnement du système d’information et soumis à certaines [menaces]({% link _knowhow/glossary/Threat_fr.markdown %}). La section ci-après décrit les menaces les plus communes dans ce domaine et livre les mesures de protections adéquates pour une PME.

## Incendie

Un incendie peut être une [menace]({% link _knowhow/glossary/Threat_fr.markdown %})absolument destructrice autant pour les supports physiques (dossiers papier) que pour les informations sur supports électroniques (perte de [disponibilité]({% link _knowhow/glossary/Availability_fr.markdown %})). La source de cette menace peut être interne ou externe, délibérée ou accidentelle. Pour la prévenir, respectez les consignes suivantes :

* [Réservez un local dédié]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#physical-security-perimeter) aux équipements informatiques et aux supports physiques les plus sensibles (Rédigez et appliquez une Politique sectorielle pour la sécurité physique et environnementale – [Périmètre de sécurité physique]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#physical-security-perimeter) et [Règles dans le périmètre]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#rules-within-the-perimeter))
  * sans douche incendie
  * protégé avec une porte coupe-feu
  * avec des extincteurs type CO2 à disposition ou un système d'extinction par gaz inerte
  * sans matériels et surfaces inflammables à l’intérieur
* Rangez les supports (dossiers papier par ex.) de préférence dans des armoires fermées. (Rédigez et appliquez une Politique sectorielle pour la classification et la maîtrise des ressources - [Classification et responsabilités des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %}), ainsi qu'une Politique sectorielle pour la sécurité physique et environnementale - [Bureaux en ordre]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#tidy-office-policy))
* Sauvegarder les documents uniques dans des armoires ou trésors résistant au feu. (Rédigez et appliquez une Politique sectorielle pour la sécurité physique et environnementale - [Bureaux en ordre]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#tidy-office-policy))
* Élaborez une procédure de signalement (déclenchement d’une alarme et ouverture des issues de secours) et d’évacuation. (Rédigez et appliquez une Politique sectorielle liée aux aspects humains).
* Mettez en place une politique de sauvegarde, avec décentralisation. (Rédigez et appliquez une Politique sectorielle Aspects opérationnels et communications - [Sauvegardes]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#data-backups))
* éventuellement, l’organisation peut faire appel à un site de reprise en mode dégradé reposant sur une [procédure de continuité opérationnelle]({% link _knowhow/cisoapproach/SecurityPolicy-ManagingBusinessContinuity_fr.markdown %}#operational-continuity) (BCP)

## Interruption de service

L’interruption de service se traduit par l’impossibilité du système d’information de fournir le service souhaité et/ou les données demandées et correspond donc à une perte, du moins momentanée, de [disponibilité]({% link _knowhow/glossary/Availability_fr.markdown %}). Des mesures particulières permettent de se protéger :

* dimensionnement approprié des équipements informatiques (processeur, réseau, stockage), particulièrement pour les systèmes temps réel, et donc une étude préalable des besoins (Rédigez et appliquez une Politique sectorielle pour la classification et la maîtrise des ressources - [Classification et responsabilités des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %}))
* identification des périodes de pointe
* hiérarchisation de certaines activités pendant ces périodes
* installation d’équipements de régulation de trafic tels que load balancer, ou cluster pour les cas extrêmes
* surveillance des équipements et connexions réseau
* surveillance des performances des systèmes
* installation de système redondants

## Déni de service /de service distribué

Les attaques par DoS (Denial of Service, déni de service) ou DDos (Distributed Dos) provoquent la saturation du système informatique, bloquant notamment les services web ou réseaux. Ils ont généralement une origine délibérée et malveillante. Que faut-il faire pour s’en protéger ?

* Mettez en place des règles de filtrage avancées pour les routeurs et les [firewalls]({% link _knowhow/glossary/Firewall_fr.markdown %}), [segmentez le réseau]({% link _knowhow/glossary/NetworkSegmentation_fr.markdown %}) (Rédigez et faites respectez une Politique sectorielle pour le contrôle d'accès - [Connection de l'extérieurExternal connections]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#external-connections) et [Séparation de réseaux]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#separation-of-networks)).
* Configurez des équipements de système à forte [disponibilité]({% link _knowhow/glossary/Availability_fr.markdown %}), reconnaissant ces tentatives, pouvant les repousser et/ou s’adapter en conséquence.

Veuillez aussi consulter le dossier de CIRCL en cas d'attaques DDOS: [https://www.circl.lu/pub/dfak/DDoSMitigation/](https://www.circl.lu/pub/dfak/DDoSMitigation/)

## Perturbation de la transmission des communications sans fil
La perturbation de la transmission des communications sans fil [WiFi]({% link _publications/recommendationsecuring/SecuringWifiNetwork_fr.markdown %})) peut être le résultat d’une attaque par DoS (parasitage par exemple), ou d’un problème de propagation des ondes (perte de disponibilité). Pour évitez ces problèmes, vérifiez que :

* le milieu physique n'empêche pas les communications (ex : béton armé, plomb)
* les points d’accès sans fil soient situés dans les espaces à forte fréquentation tout en étant inaccessibles (par exemple : situés en hauteur). (Rédigez et faites respecter une Politique sectorielle pour la Sécurité physique et environnementale - [Périmètre de sécurité physique]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#physical-security-perimeter) et [Règles dans le périmètre]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#rules-within-the-perimeter))
* le rayonnement des points d’accès ne soit pas perturbé par le rayonnement d’autres sources électromagnétiques aux alentours (antenne radio, GSM, TV)

## Écoute des réseaux sans fil

Les réseaux sans fil [WiFi]({% link _publications/recommendationsecuring/SecuringWifiNetwork_fr.markdown %})) ne reposent sur aucun support physique, ils transitent par la voie aérienne, rendant possible l’écoute au simple moyen d’un capteur passif. Il peut donc en résulter une perte de [confidentialité]({% link _knowhow/glossary/Confidentiality_fr.markdown %}) de vos informations. Vous pouvez éviter ce risque en respectant les mesures de sécurité suivantes :

* les communications doivent être cryptées par un protocole sécurisé (ex : WPA2 pour le Wifi) (Rédigez et faites respecter une Politique sectorielle pour le développement et maintenance des systèmes - [Utilisation de l'encryption]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}#encryption))
* le rayonnement des points d’accès du WiFi doit être circonscrit aux limites physiques de l’organisation
* l’accès à ces réseaux doit être limité aux ayant droits (filtrage par adresse MAC par ex)
* le réseau Wifi ne doit pas être directement connecté au réseau interne de l'organisme, mais être séparé par un [firewall]({% link _knowhow/glossary/Firewall_fr.markdown %}) voire avoir une connection dédiée (Rédigez et faites appliquer une Politique sectorielle de contrôle d'accès - [Séparation de réseaux]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#separation-of-networks))

Voir aussi [Sécuriser le réseau WiFi interne]({% link _publications/recommendationsecuring/SecuringWifiNetwork_fr.markdown %}#wifi-for-employees) et [Sécuriser le réseau WiFi clients]({% link _publications/recommendationsecuring/SecuringWifiNetwork_fr.markdown %}#wifi-for-visitorsexternal-users).

## Interception des communications

Un tiers peut intercepter, altérer ou effacer les données transmises (attaques dites man-in-the-middle) et compromettre de fait la [confidentialité]({% link _knowhow/glossary/Confidentiality_fr.markdown %}), l’[intégrité]({% link _knowhow/glossary/Integrity_fr.markdown %}) et la [disponibilité des données]({% link _knowhow/glossary/Availability_fr.markdown %}). Vous pouvez protéger la transmission de vos communications et :

* mettre en place les mesures de protection décrites dans « l’écoute des réseaux sans fil »
* utiliser des moyens cryptographiques pour prévenir l'accès et l'altération de données transmises. (Rédigez et faites respecter une Politique sectorielle Développement et maintenance des systèmes - [Utilisation du chiffrement]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}#encryption)).
* cloisonner les réseaux (Rédigez et faites respecter une Politique sectorielle pour le contrôle d'accès - [Connection de l'extérieur]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#external-connections) et [Séparation de réseaux]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#separation-of-networks)).
* prévenir que le câblage ne soit pas accessible à des personnes malveillantes. (Rédigez et faites respecter une politique sectorielle pour la Sécurité physique et environnementale - [Périmètre de sécurité physique]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#physical-security-perimeter) et [Règles dans le périmètre]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#rules-within-the-perimeter)).
* mettre en place une politique de contrôle d'accès (Rédigez et faites respecter une politique sectorielle pour le contrôle d'accès - [Politique de contrôle d'accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-control-policy) et [Gestion des droits d'accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-rights-management) et [Procédures de connection]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#connection-procedures) et [Connection de l'extérieur]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#external-connections)).

Veuillez aussi consulter le dossier de CIRCL sur la communication sécurisée: [https://www.circl.lu/pub/dfak/SecureCommunication/](https://www.circl.lu/pub/dfak/SecureCommunication/)

## Indisponibilité du réseau

La perte des moyens de télécommunications (perte de [disponibilité]({% link _knowhow/glossary/Availability_fr.markdown %})) paralyse les systèmes d’information. Il est recommandé  d'avoir accès à un point source redondant, si possible auprès d'un deuxième opérateur de télécommunications utilisant un autre équipement de raccordement, et qui soit testé régulièrement.

## Panne de courant

Une panne de courant peut engendrer une perte de [disponibilité]({% link _knowhow/glossary/Availability_fr.markdown %}) de tout le système d'information. La fourniture d’énergie est essentielle notamment pour les organismes opérant au niveaux d'une activité « temps réel ». Prévenez cette [menace]({% link _knowhow/glossary/Threat_fr.markdown %}) en vous munissant :

* d'une alarme signalant les défaillances d'un système électrique
* d'onduleurs sur les dispositifs sensibles
* d'un générateur de secours pour les systèmes vitaux
* de disjoncteurs protégeant les équipements contre les surtensions
* d'une procédure d’arrêt des équipements informatiques (Rédigez et faites respecter une Politique sectorielle liée à la sécurité physique et environnementale - [sécurité électrique des équipements]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#electrical-equipment-safety).

## Discontinuité des fournisseurs de service

Une entité dépend de ses fournisseurs. Une indisponibilité au niveau des fournisseurs de services peut donc avoir des répercussions graves sur le fonctionnement de celle-ci. Il est donc préférable de prévoir :

* la [disponibilité]({% link _knowhow/glossary/Availability_fr.markdown %}) (niveau de service d’un SLA) dans le contrat de services. (Rédigez et faites respecter une Politique sectorielle Sécurité physique et environnementale - [Maintenance]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#maintenance))
* une redondance des fournisseurs de service pour des modes dégradés
* une mise à disposition, par le fournisseur de service, des informations (procédures, code source, documentation technique) permettant de maintenir l’activité

## Pénétration des locaux

Une enfreinte aux périmètres sécurisés peut avoir des conséquences graves de [confidentialité]({% link _knowhow/glossary/Confidentiality_fr.markdown %}), d'[intégrité]({% link _knowhow/glossary/Integrity_fr.markdown %}) et de [disponibilité]({% link _knowhow/glossary/Availability_fr.markdown %}) pour tout organisme. Une personne malintentionnée, ayant accès à des [actifs]({% link _knowhow/glossary/Assets_fr.markdown %}) au sein de l'entreprise, peut voler, saboter ou copier ces actifs et donc causer de grands [dégâts]({% link _knowhow/glossary/Impact_fr.markdown %}). Vérifiez que :

* les identités des personnes puissent être surveillées dans les sas d’entrées et sorties du bâtiment. (Rédigez et faites respecter une politique sectorielle pour la Sécurité physique et environnementale - [Périmètre de sécurité physique]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#physical-security-perimeter) et [Règles dans le périmètre]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#rules-within-the-perimeter))
* les visiteurs et fournisseurs soient toujours accompagnés
* les issues de secours ne puissent s'ouvrir que de l'intérieur
* les salles réservées aux serveurs soient verrouillées, et équipées de systèmes d’alarme, si besoin de caméras
* une politique « clean desk » soit respectée (c.à-d. rangement des dossiers papier sensibles (classification) et verrouillage des stations de travail). (Rédigez et faites respecter une Politique sectorielle pour la Classification et maîtrise des ressources - [Classification et responsabilités des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %}#classification-and-responsibility-for-resources), ainsi qu'une Politique sectorielle pour la sécurité physique et environnementale - [Bureaux en ordre]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#tidy-office-policy))
* lorsque les locaux sont fermés, un système d’alarme ou une société de gardiennage assure la surveillance du site
* le respect de la politique du port de badge, et que le badge soit aisément visible
* des zones de quarantaine pour les livraisons soit disponibles
