---
layout: article
title:  "Sécurité physique"
menutitle:
logo:
date:   2017-11-06 00:00:00 +0100
short:
categories: knowhow
toc: true
ref: glossaryphysicalsecurity
lang: fr
---
## En quelques mots

La sécurité physique vise à favoriser l'exploitation des équipements informatiques dans des conditions fonctionnelles optimales, de manière à bénéficier d'un maximum de performances durant un maximum de temps.

Quand on parle de mesures ou parades, il faut faire la différence entre les actions préventives et les actions protectrices de celles-ci.

* Les mesures de prévention ont pour but d'éviter un sinistre.
* Les mesures de protection ont pour but de protéger le patrimoine en cas de sinistre.

Il serait illusoire de penser que les mesures préventives empêchent tout sinistre. Même dans le cas de mise en place de ce type de parade, il est conseillé de déployer également des mesures de protection.

L'ampleur des moyens de protection nécessaires est inversement proportionnelle aux moyens de prévention mis en place.

## Le local informatique
Pour différentes raisons liées à la nature des équipements, à leurs conditions de fonctionnement, à leur criticité, au bruit ou à la chaleur dégagée, etc., il est judicieux de mettre en place des locaux informatiques dédiés, séparés des surfaces de travail utilisées par les employés.

On peut distinguer différents types de locaux informatiques, tels que :

#### La salle informatique de type "data center"
Cette salle héberge généralement tous les équipements spécialisés, nécessaires à la fourniture des ressources informatiques. On y trouve les serveurs, gros calculateurs, solutions de [sauvegarde]({% link _knowhow/glossary/DataBackups_fr.markdown %}) et de restauration des données, baies de stockage, etc..

Dans la plupart des sociétés de taille moyenne, cette salle contient également les éléments critiques du réseau(commutateurs, routeurs,...) ainsi que les points d'accès et équipements servant à connecter la société vers le monde extérieur (central téléphonique, accès à l'Internet,...).

Dans de plus grandes infrastructures, on trouve différentes salles spécialisées, appelées salle réseau, salle téléphonie et salle connectique.

Au niveau des très gros centres de calcul, on fait même la distinction entre la salle «morte» où se trouvent les équipements n'exigeant que très peu d'interventions humaines (processeurs, stockage,...) et la salle «vive» où se trouvent les équipements nécessitant des interventions humaines fréquentes (robot de sauvegarde,...).

#### La salle connectique d'étage
Au niveau des étages, on trouve habituellement des locaux servant à connecter les équipements de l'étage sur le tronc commun de câblage menant à la salle informatique. Ces salles contiennent ordinairement des panneaux de brassage ainsi que des commutateurs d'étage.

Ces locaux et la connectique sont normalement conçus avec une redondance maximale, de manière à prévenir au maximum des ruptures éventuelles.

Etant donné la criticité de ces équipements, ces locaux sont considérés comme des locaux informatiques et sont donc soumis aux mêmes exigences de conception et de surveillance.

## Protection contre les incidents
Les mesures de prévention et de protection décrites dans ce document n'ont pas l'ambition d'être exhaustives, ni d'être obligatoires dans tous les cas de figure. Le choix d'application des mesures de prévention et de protection doivent résulter d'une étude incluant une analyse de risques, confrontée à une évaluation budgétaire des parades adaptées.

Pour assurer l'efficacité de toutes les mesures de prévention et de protection proposées, il est indispensable de les inclure dans le cadre d'une approche organisationnelle et procédurale.

Les aspects suivants font l'objet de ce chapitre :

* Dégâts des eaux,
* Dégâts du feu (PME : voir [Incendie]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure_fr.markdown %}#fire))
* dégâts liés à l'électricité (PME : voir [Interruption de service]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure_fr.markdown %}#service-interruption), [Panne de courant]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure_fr.markdown %}#power-cut)),
* Défauts de climatisation,
* Incidents de télécommunication (PME : voir [Attaques par déni de service et déni de service distribués]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure_fr.markdown %}#denial-of-servicedistributed-service), [Interruption de service]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure_fr.markdown %}#service-interruption), [Transmission des communications sans fil perturbée]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure_fr.markdown %}#disrupted-transmission-of-wireless-communications), [Accès réseau indisponible]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure_fr.markdown %}#network-unavailability), [Équipement informatique ou de communication en panne]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware_fr.markdown %}#failure-of-it-or-communications-equipment)),
* Physical intrusions (SMEs: see [Pénétration dans les locaux]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure_fr.markdown %}#infiltrating-the-premises), [Insertion ou suppression de matériel]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware_fr.markdown %}#addition-or-removal-of-hardware), [Récupération des supports]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware_fr.markdown %}#device-recovery), [Vol caractérisé]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware_fr.markdown %}#aggravated-theft)),
* Phénomènes électrostatiques,
* Inaccessibilité du centre informatique.


#### Mesures organisationnelles de sécurité
* [Organisation de la sécurité]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity_fr.markdown %})
  * [Attribution des responsabilités]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity_fr.markdown %}#attribution-of-responsibilities)
  * [Accès par des tiers et sous-traitance]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity_fr.markdown %}#third-party-access-and-outsourcing)
* [Classification et maîtrise des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %})
  * [Classification et responsabilité des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %}#classification-and-responsibility-for-resources)
* [Aspects humains]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %})
  * [La formation et l’information]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %}#training-and-information)
  * [La réponse aux incidents et dysfonctionnements de sécurité]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %}#response-to-incidents-and-malfunctions)
* [Sécurité physique et environnementale]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %})
  * [Périmètre de sécurité physique]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#physical-security-perimeter)
  * [Règles dans le périmètre]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#rules-within-the-perimeter)
  * [Sécurité électrique des équipements]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#electrical-equipment-safety)
  * [Maintenance]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#maintenance)
  * [Sécurité des équipements hors des locaux]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#off-site-equipment-security)
  * [Mise au rebut ou ré-utilisation des équipements]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#disposal-and-reuse-of-equipment)
  * [Bureaux en ordre]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#tidy-office-policy)
* [Aspects opérationnels et communications]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %})
  * [Procédures documentées]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#documentation-of-procedures)
  * [Sauvegarde des données]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#data-backups)
* [Contrôle d’accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %})
  * [Politique de contrôle d’accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-control-policy)
  * [Gestion des droits d’accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-rights-management)
* [Gestion de la continuité de l’entreprise]({% link _knowhow/cisoapproach/SecurityPolicy-ManagingBusinessContinuity_fr.markdown %})
  * [La continuité de fonctionnement]({% link _knowhow/cisoapproach/SecurityPolicy-ManagingBusinessContinuity_fr.markdown %}#operational-continuity)
* [Conformité]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %})
  * [Propriété intellectuelle]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %}#intellectual-property)
  * [Protection des données opérationnelles]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %}#protection-of-operational-data)
  * [Protection des données à caractère personnel]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %}#personal-data-protection)

## Le dégât des eaux

#### Les incidents
Ce type d'incidents peut avoir des origines diverses telles que :

* rupture de conduite d'eau domestique,
* rupture de conduite de réfrigération,
* filtration de façade ou de toiture,
* déclenchement de systèmes anti-incendie,
* obstruction des évacuations d'eaux usagées.

>NB:<br />
Ce point est d'autant plus critique que la plupart des salles informatiques sont équipées de faux-planchers qui empêchent la détection aisée d'un sinistre. De plus, les gainages de câblage entre les étages permettent des évacuations faciles pour l'eau, qui peut ainsi se propager dans toutes les salles de type «connectique».

#### Les conséquences
Les [conséquences]({% link _knowhow/glossary/Impact_fr.markdown %}) vont évidemment dépendre de l'ampleur du sinistre, mais on peut dire que les domaines susceptibles d'être touchés sont :

* divers courts-circuits entraînant la rupture de service des équipements,
* dangers d'électrocution,
* fonctionnement de certaines alarmes ou autres sécurités,
* détérioration des équipements,
* corrosion des câbles et connecteurs.

#### Les contre-mesures
##### Prévention

* déterminez judicieusement la localisation des locaux informatiques, en évitant les risques d'inondation (évitez les sous-sols, le dernier étage,...),
* évitez la circulation d'eau dans la salle informatique (placez le groupe de conditionnement d'air à l'extérieur de la salle informatique,...),
* choisissez les chemins de tuyauterie, en évitant de traverser ou de surplomber la salle informatique.

##### Protection

* mettez en place des systèmes de détection de fuites,
* surélevez les équipements informatiques,
* utilisez des tubes hermétiques pour le câblage d'alimentation (220V), ainsi que pour le câblage réseaux,
* compartimentez le plancher de manière à contenir et diriger l'eau vers des systèmes d'évacuation.

## Le dégât du feu
I
#### Incident par feu
Ce type d'incident, qu'il soit d'origine accidentelle ou criminelle, peut conduire à la destruction partielle de la société et plus particulièrement des équipements informatiques.

#### Les conséquences
Les conséquences peuvent être très importantes à tous les niveaux de la société. En ce qui concerne le système informatique, cela peut causer l'indisponibilité de tout ou d'une partie de l'architecture et ce pour une assez longue période. Les dommages sont souvent couplés à des dégâts des eaux causés par les tentatives d'extinction de l'incendie et à des dégâts causés par les fumées.

Les dégâts habituellement constatés sont de différents types tels que :

* destruction totale ou partielle du centre informatique,
* destruction totale ou partielle du câblage cuivre et fibre optique,
* dégâts liés à la pollution par la fumée et par les produits d'extinction,
* atteintes physiques aux équipements informatiques.

#### Les contre-mesures
##### Prévention

* prenez en compte le voisinage des bâtiments,
* évitez le stockage de produits inflammables dans, ou à proximité des salles informatiques,
* vérifiez régulièrement les circuits électriques,
* évitez les chapelets de blocs «multi-prises»,
* mettez en place des mécanismes de détection de fumée,
* étudiez les chemins de propagation du feu et mettez en place des équipements de compartimentage (sas, parois anti-feu,...).

##### Protection

* mettez en place de mécanismes d'extinction de feu sur base de produits ne portant pas préjudice au matériel informatique et ne portant pas atteinte au personnel (se renseigner auprès du service des pompiers de la localité),
* choisissez judicieusement les sorties de secours,
* faites respecter l'interdiction de fumer,
* établissez et mettez à l'épreuve un plan catastrophe, incluant un repli de l'informatique vers un centre spécifique,
* utilisez des armoires ignifugées pour le stockage des supports informatiques (veillez à garder ces armoires fermées).

PME: voir [incendie]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure_fr.markdown %}#fire)

## Les dégâts liés à l'électricité

#### Incidents lié à l'électricité
Les incidents électriques peuvent se manifester par des perturbations du courant sous forme de surtension, de baisse de tension, voire de coupures de courant. Ce type de coupure peut affecter tout ou partie de la société et peut être d'origine interne ou externe.

Malheureusement, l'apparition et la durée de ces phénomènes sont généralement imprévisibles, à l'exception des cas de coupure annoncées par le fournisseur ou par le service logistique en charge du bâtiment.

Une coupure de courant peut être malveillante ou résulter d'une fausse manœuvre, mais aussi être causée par des phénomènes naturels tels que les orages, les tempêtes,...;

#### Les conséquences
Le risque de dommages dépend de la brutalité de la coupure de courant, car certains équipements sont capables de gérer ce type de phénomènes de manière à clôturer sainement les transactions en cours.

Les conséquences peuvent être diverses :

* perte de données,
* panne d'équipements,
* risques d'incendie,
* électrocution du personnel.

##### Remarque
Il ne faut pas oublier que les équipements de type connectique distribués dans les étages, ainsi que les ordinateurs personnels et périphériques sont également des éléments critiques souvent très sensibles aux coupures de courant.

#### Les contre-mesures

* Prévention
* installez des paratonnerres,
* équipez le bâtiment d'un mécanisme évitant les remontées de «foudre»,
* mettez en place des mesures visant à éviter les blocs «multi-prises»,
* équipez les éléments critiques de l'informatique d'une double alimentation,
* veillez à une conception adéquate de l'alimentation électrique (tableaux, puissance,...),
* veillez à rendre les circuits d'alimentation au niveau du câblage électrique redondants.

##### Protection
* utilisez des solutions UPS (Uninterruptible Power Supply) avec logiciel d'alarme dans les salles ne pouvant fournir de circuit de secours,
* mettez en place des circuits «no break» dans l'ensemble du bâtiment pour y connecter les machines et périphériques sensibles,
* mettez en place des circuits de secours en cas de rupture (groupe électrogène).

##### Remarque
On remarque souvent que le problème de coupure de courant se prolonge lors du re-démarrage. En effet, les équipements, en tentant de redémarrer tous ensemble, créent une surcharge qui fait sauter les fusibles. Il est conseillé de procéder à un re-démarrage séquentiel des équipements.

PME: voir

* [Interruption de service]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure_fr.markdown %}#service-interruption)
* [Panne de courant]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure_fr.markdown %}#power-cut)

## Les défauts de canalisation

#### Les incidents liés à un défaut de canalisation
Les équipements informatiques sont conçus pour travailler dans un environnement spécifique qu'il s'agit de respecter afin d'éviter les incidents suivants :

* défaut de fonctionnement de l'approvisionnement en eau ou en courant de réseau,
* panne ou dysfonctionnement du système de réfrigération,
* effets du rayonnement solaire directe.

#### Les conséquences
Il faut veiller à respecter les conditions normales de fonctionnement, sous peine de s'exposer à divers dysfonctionnements aléatoires difficiles à diagnostiquer. Toutefois, on peut dire que les conséquences habituelles d'une panne de climatisation sont les suivantes :

* nécessité de couper et de redémarrer les équipements de façon cyclique,
* vieillissement prématuré des composantes informatiques,
* détérioration des batteries de secours des UPS.

#### Les contre-mesures
##### Prévention

* mettez en place des mécanismes veillant à limiter le rayonnement solaire direct,
* installez un système de ventilation redondant, dimensionné de manière à pouvoir suffire aux besoins actuels et futurs,
* mettez en place une solution de contrôle de la température équipée d'un module d'alerte.

##### Protection

* installez un mécanisme de contrôle d'accès physique des locaux informatiques,
* mettez en place une procédure de sauvegarde (pour un usage en mode restreint), permettant d'arrêter les éléments non critiques de votre infrastructure informatique.

## Les incidents de télécommunication

#### Les incidents

Parmi ce genre d'incidents, on peut citer les suivants :

* sabotage,
* panne ou perte d'équipement,
* perturbation du signal,
* rupture des canaux de liaison,
* rupture de service d'un fournisseur,
* panne d'un central téléphonique.

On inclut ordinairement sous ce nom d'autres incidents que ceux touchant directement les éléments physiques, comme les intrusions logiques sur les systèmes informatiques. Ceux-ci ne font pas l'objet de la présente fiche.

#### Les conséquences
L'impact dépend évidemment de l'usage qui est fait des services touchés dans les chaînes de production critiques. Les conséquences sont les suivantes :

* rupture de fonctionnement de certains logiciels,
* isolation de la société par rapport au monde extérieur,
* corruptions éventuelles de données,
* désactivation de certains mécanismes de surveillance (vidéo, alarme,...).

#### Les contre-mesures
##### Prévention

* protégez judicieusement les locaux de télécommunication,
* appliquez des gaines blindées aux liaisons extérieures (blindage, avertissement, bornes,...),
* séparez les gainages de courant fort, courant faible et les conduits de climatisation,
* protégez les équipements de communication (antennes,...) contre la foudre.

##### Protection

* mettez en place de liaisons «doubles» avec chemins d'accès séparés, et au travers de deux centraux différents,
* doublez tous les équipements critiques et mettez en place des systèmes de répartition des charges,
* mettez en place des liaisons de secours quand c'est possible,
* ayez recours à plusieurs opérateurs capables d'assurer le passage, en cas de rupture de service.  

PME: voir

* [Interruption de service]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure_fr.markdown %}#service-interruption)
* [Attaques par déni de service et déni de service distribués]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure_fr.markdown %}#denial-of-servicedistributed-service)
* [Transmission des communications sans fil perturbée]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure_fr.markdown %}#disrupted-transmission-of-wireless-communications)
* [Accès réseau indisponible]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure_fr.markdown %}#network-unavailability)
* [Équipement informatique ou de communication en panne]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware_fr.markdown %}#failure-of-it-or-communications-equipment)

## Les intrusions physiques

#### Les incidents
La circulation de personnes non autorisées dans les locaux informatiques (et dans les locaux de la société) peut mener à divers événements non désirés tels que :

* [vol de matériel]({% link _knowhow/glossary/PhysicalTheft_fr.markdown %}),
* perte de confidentialité,
* sabotage.

#### Les conséquences

Les [conséquences]({% link _knowhow/glossary/Impact_fr.markdown %}) peuvent être les suivantes :

* perte de réputation (mise en cause de la crédibilité dans le cas de divulgation d'informations hautement confidentielles,...),
* pertes financières directes (destruction de données cruciales, mise hors service de tout le système informatique,...),
* perte de temps (efforts pour rétablir les données détruites,...).

#### Les contre-mesures
Dans ce domaine particulièrement, il est indispensable d'encadrer toutes les parades avec des mesures organisationnelles, procédurales et d'audit.

##### Prévention

* mettez en place une protection générale du bâtiment (blindage, «bunker»,..) avec limitation du nombre d'ouvertures (fenêtres, portes,...),
* utilisez un service de détection de déplacements et d'intrusions relié à une centrale de contrôle 24h/24h,
* mettez en place un contrôle d'accès (badge, biométrie,...) permettant de contrôler et de tracer les accès aux locaux critiques,
* mettez en place une politique d'identification des visiteurs.

#### Protection

* utilisez des mécanismes antivol pour les périphériques et les ordinateurs personnels ou portables,
* veillez au respect d'une politique en matière de rangement de bureau, qui demeure une mesure très importante contre le risque de vol de données ou de matériel,
* mettez en place un mécanisme de surveillance vidéo.

##### Remarque
Avant d'implémenter ces mesures de surveillance veuillez en demander l'autorisation auprès de la ([Commission Nationale pour la Protection des Données](https://cnpd.public.lu/en.html)).

PME: voir

* [Pénétration dans les locaux]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure_fr.markdown %}#infiltrating-the-premises)
* [Insertion ou suppression de matériels]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware_fr.markdown %}#addition-or-removal-of-hardware)
* [Récupération des supports]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware_fr.markdown %}#device-recovery)
* [Vol caractérisé]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware_fr.markdown %}#aggravated-theft)

## Les phénomènes électrostatiques

#### Les incidents
Tous les phénomènes électromagnétiques et électrostatiques sont regroupés sous cette appellation.

Ces perturbations peuvent provenir d'une source extérieure à la société, dans le cas de phénomènes météo, d'émissions radios ou d'appareillages électriques divers. La source peut également être liée au bâtiment.

#### Les conséquences
Les conséquences peuvent être les suivantes :

* dysfonctionnements aléatoires,
* corruptions de données stockées sur des supports magnétiques.

##### Remarque
Un autre phénomène est l'utilisation des rayonnements émis par le système informatique pour intercepter des données. C'est le cas des réseaux «wireless», par exemple.

#### Les contre-mesures
##### Prévention

* éloignez les locaux informatiques (traitement et connectique) des installations électriques, des ascenseurs et des autres sources de perturbation,
* utilisez la fibre optique dans les liens verticaux (p.ex. entre les différents étages), de manière à limiter les risques,
* mettez à terre tous les équipements et non pas uniquement des composantes informatiques,
* choisissez judicieusement les revêtements des sols.

##### Protection
* portez des bracelets de mise à la terre pour toutes les interventions sur l'architecture informatique.

## L'inaccessibilité du centre informatique

#### Les incidents
L'accès au centre informatique peut être bloqué pour plusieurs raisons telles que :

* catastrophe naturelle et attentats,
* décision judiciaire suite à un sinistre,
* manifestations, émeutes et mouvements sociaux.

#### Les conséquences
Les conséquences d'une perte d'accessibilité peuvent être diverses :

* arrêt de fonctionnement du centre de traitement,
* altération du bon fonctionnement des équipements, spécifiquement des équipements sensibles.

#### Les contre-mesures
##### Prévention

* installez vos sites à des endroits où le risque de catastrophes naturelles est réduit,
* mettez en oeuvre des protections contre les intrusions.

##### Protection

* mettez en place une solution de prise de contrôle à distance sécurisée,
* prévoyez  un site de repli.
