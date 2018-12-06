---
layout: article
title:  "Pannes physiques"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: knowhow
toc: true
ref: glossaryphysicalfaults
lang: fr
---
En quelques mots
----------------
On entend par panne physique la rupture de service ou le mauvais
fonctionnement d'un ou plusieurs éléments physiques constitutifs d'un
système informatique.


Causes possibles
----------------
Les causes sont aussi nombreuses que les éléments ou couches qui
constituent le système informatique en question. Toutefois, on essayera
de faire la différence entre : 

### Pannes logicielles et les pannes de matériel
Il y a des dysfonctionnement qui résultent directement d'un élément
physique du système et ceux qui relèvent de la couche logicielle des
éléments physiques. En effet, la plupart des équipements électroniques
exercent leur rôle grâce à des logiciels. Le dysfonctionnement des
couches logicielles peut rendre l'équipement inopérant, voir le
détruire.

### L'environnement
Dans de nombreux cas, l'inopérabilité des éléments informatiques est due
à l'absence de conditions adéquates pour leur bon fonctionnement. En
effet l'environnement dans lequel se situe le matériel informatique peut
être affecté par des circonstances extérieures telles que :

* [Pannes d'alimentation]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}#power-cut)
* Pannes du système de climatisation, provoquant une surchauffe
* [Incendie]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}#fire)
* [Interruption de services]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}#service-interruption)
* Perturbation de la [transmission des communications sans fil]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}#disrupted-transmission-of-wireless-communications)
* Indisponibilité du [réseau]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}#network-unavailability)
* [Discontinuité des fournisseurs de service]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}#discontinuity-of-service-providers)

L'environnement peut entraîner une indisponibilité du système, mais peut
également provoquer des pannes physiques au niveau des éléments
constitutifs.


Impacts possibles
-----------------
L'estimation des préjudices subis va évidemment dépendre des domaines
touchés par la ou les pannes physiques, ainsi que par la faculté de
faire face aux éventuelles altérations des données et systèmes.

### Perte d'équipements
Une panne peut parfois nécessiter le remplacement de l'équipement
concerné. Le coût direct équivaut donc à la valeur d'achat et de mise en
fonction du nouvel équipement.

Il est vivement conseillé d'éviter l'utilisation de technologies
hybrides ou hautement propriétaires, dont la nécessité de remplacement
risque d'engendrer une surcharge financière ou une obligation de revoir
complètement le système.

### Perte de données
En l'absence de mesure préventive installée avant la rupture de service,
des préjudices importants peuvent être causés par la perte de données.


Catégories
----------
La classification des pannes physiques se base sur la partie du système
directement concerné et fait une différence entre :

### Pannes agissant sur les fonctions de calcul

On inclut dans cette catégorie toutes les pannes qui empêchent le bon
fonctionnement du traitement des données par un serveur ou un ordinateur
personnel. Une interruption à ce niveau va agir sur des éléments
physiques tels que :

* la mémoire;
* le processeur;
* la carte mère.

### Pannes agissant sur les systèmes de stockage

Cette catégorie regroupe toutes les interruptions ayant une conséquence
sur l'accès aux données, que ce soit en mode écriture ou lecture.



Vulnérabilités exploitées
-------------------------
Il s'agit dans ce contexte plutôt d'événements qui surgissent de façon
inévitable et qui sont liés au caractère faillible des composantes d'un
système informatique. Les moyens pour prévenir l'apparition d'une panne
sont restreints, comme par exemple le bon entretien des systèmes et
machines. Toutefois, comme expliqué ci-dessous, l'on peut prendre des
mesures pour en restreindre l'impact causé.

Mesures préventives
-------------------
Les principales mesures préventives visant à limiter l'impact des pannes
physiques sont :

### Mise en place d'une salle informatique organisée
Il est indispensable d'offrir des conditions de fonctionnement optimales
à tous les éléments critiques du système informatique. Cela passe par la
mise en place d'une salle informatique, ainsi que de salles réservées à
la "connectique" munis de services tels que "no break" (pas
d'interruption du courant), onduleurs, climatisation, détection
d'incendie, et un contrôle des accès. Rédigez et faites respecter une
Politique de sectorielle liée à la Sécurité physique et environnementale
- [Périmètre de sécurité physique]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %})
et [Règles dans le périmètre]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %}#physical-security-perimeter)
et [Sécurité électrique des équipements]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %}#rules-within-the-perimeter)
et [Maintenance]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %}#electrical-equipment-safety).

### Conception d'une architecture redondante dite "à tolérance de panne"
Lors de la conception d'une architecture informatique, il y a moyen de
se prémunir contre les pannes physiques ou assimilées, de manière à
rendre " transparente" toute rupture de service de l'une ou l'autre des
composantes.

Cette redondance peut être mise en place au niveau des couches suivantes:

* câblage;
* réseau (HSRP - Hot Standby Router Protocol) télécommunication;
* serveur (Clustering);
* stockage (RAID - Redundant Array of Inexpensive/Independent Disks.

### Capacité de réponse aux incidents
Mettez en place des compétences internes pour pouvoir répondre à des
incidents. Rédigez et faites respecter une Politique de sectorielle liée
aux Aspects humains - [La formation et l’information]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown %}#training-and-information)
et [La réponse aux incidents et dysfonctionnements de sécurité]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown %}#response-to-incidents-and-malfunctions).

### Une politique d'archivage fonctionnel
Afin de limiter autant que possible le risque de perte de données, la
mise en place et le respect des procédures d'archivage des données, tant
au niveau des serveurs que des ordinateurs personnels, sont vivement
conseillés. Rédigez et faites respecter une Politique de sectorielle
liée aux Aspects opérationnels et communications - [Sauvegarde des données]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}#data-backups).

### Choix de standards
Le choix de solutions propriétaires qui peut paraître alléchant au
départ, peut devenir un vrai "cauchemar" en cas d'obligation de
remplacement de l'un ou l'autre élément qui ne serait plus produit. Le
risque peut aller jusqu'à la nécessité de revoir et remplacer
complètement la chaîne de traitement en cas de rupture physique d'un
élément. Il est donc conseillé de recourir le plus possible à des
éléments standard construits par un grand nombre de fabricants.
