---
layout: article
title:  "Perte de données"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: knowhow
toc: true
ref: glossarydataloss
lang: fr
---
En quelques mots
----------------
On parle de *perte de données* lorsque les données sont supprimées ou
détériorées de manière à en rendre leur accès impossible. Cette
situation peut se produire suite à divers événements naturels
(catastrophes), techniques (pannes) ou actions humaines (vol avec
destruction, destruction volontaire ou involontaire).

On parle *d'altération de données* quand une partie des données est
modifiée sans pour autant rendre 'accès aux données impossible.

Finalement, on parle de *vol de données* quand une personne accède à des
données auxquelles il n'a normalement pas droit d'accéder, et qu'il les
soustrait frauduleusement. Le vol de données peut s'effectuer par une
copie, un transfert des données ou par l'impression de ces dernières. Il
peut être couplé à des actes de destruction ou d'altération des données.

La perte de données
-------------------
Pour mieux comprendre ce phénomène et les moyens de recouvrement, il est
nécessaire de distinguer  :

### La perte de données due à la perte d'accès aux données
Diverses circonstances physiques ou logiques peuvent provoquer la perte
d'accès aux données. Dans la majorité des cas, les données sont encore
physiquement sauvegardées sur les supports informatiques. Mais dès lors
qu'elles ne sont plus accessibles, on parle de *perte de données*. Les
méthodes de récupération se distinguent des méthodes utilisées pour
récupérer des *données détériorées* ou *supprimées*.

### La perte de données due à l'altération de données
Lors de certaines manipulations frauduleuses effectuées par des pirates
informatiques sur des serveurs web, on assiste non pas à la destruction
ou au vol de données, mais simplement à l'altération de ces dernières.
En effet, le «cracker» peut, par exemple, annoncer avoir simplement
modifié une donnée quelque part. Dans ce cas, les données authentiques
ne sont plus accessibles, car elles ont été altérées. Ce qui équivaut à
une *perte des données*.

La perte de données due à *l'altération de données* peut aussi être
provoquée par des actions volontairement ou involontairement illicites
sur des bases de données ou des fichiers. Cette forme de perte de
données est généralement difficilement détectable. (Les données existent
toujours là, mais elles ne sont incorrectes).

### La perte de données par vol
Les vols de données n'entraînent pas nécessairement leur destruction ou
altération. Si les données sont copiées, transférées ou imprimées, les
originaux restent inchangés. C'est d'ailleurs une des raisons pour
lesquelles il est parfois difficile de détecter ce genre de perte.

L'impact d'un vol de données confidentielles (par exemple des secrets de
fabrication) peut être nettement supérieur à la simple perte de données.
On parle aussi de perte de confidentialité des données.

### Perte de données/perte d'équipement par vol

La perte ou le vol d'ordinateurs portables comme de tout support
informatique (bande magnétique, disquette, CD ROM - Compact Disk Read
Only Memory, ....) entraîne souvent la perte des données sauvegardées
sur ces ressources informatiques. En effet, les utilisateurs disposent
rarement d'une copie de sauvegarde complète. Le vol ou la perte des
supports informatiques engendre aussi un grand risque de perte de
confidentialité des données.

### La perte de données par destruction volontaire
Lorsque la perte ou l'altération des données n'est pas le résultat d'un
phénomène technique, mais bien d'une tentative humaine, il faut faire la
différence entre les actions :

-   volontaires malveillantes (piratage d'un site web)
-   volontaires non malveillantes (effacement d'un fichier)
-   volontaires (mauvaise manipulation)


Mesures préventives
-------------------
En se basant sur l'analyse de cas réels, on peut déterminer les zones
directement concernées en cas de perte de données et évaluer les
dépenses habituellement liées à ce type de phénomène.

### Solution de stockage adaptée aux besoins
Il est important d'adapter la technologie de stockage au degré de
sensibilité des données ainsi qu'au type de données (fichiers
bureautiques, bases de données).

Afin d'éviter un rapide engorgement de l'infrastructure de stockage et
tous les problèmes qui y sont directement liés, il est nécessaire de
mettre en place une politique d'archivage des fichiers sur des supports
adaptés.

Il est conseillé d'équiper les serveurs de la
technologie RAID (Redundant Array of
Independent/Inexpensive Disks) qui permet de répartir le stockage des
données sur plusieurs disques durs. Lors de la perte éventuelle d'un des
disques durs composant le RAID, le système informatique est capable de
reconstituer l'information manquante. Il existe différents niveaux de
configuration RAID, lesquels font l'objet d'une fiche séparée.

La mise en place d'un réseau filaire de stockage SAN (Storage Area
Network) peut également s'avérer utile dans le cas de grosses
infrastructures ou de déploiement d'un second site de production ou de
repli.

### Politiques de sauvegarde/restauration adéquates
Il faut adapter les technologies ainsi que les politiques de sauvegarde
et de restauration des données selon le degré de sensibilité, mais aussi
selon la nature des données (fichiers bureautiques, bases de données).

Des technologies telles que le «snapshooting», dont le but est de
réaliser des copies des modifications de la base de données et ce «à la
volée» durant la journée, permettent d'éviter un retour à la situation
de la veille, limitant de ce fait la saisie ou le ré-encodage
éventuellement nécessaire. Si cette technique onéreuse et complexe est
bien adaptée à un type d'utilisation très complexe, elle n'a aucun
intérêt dans le cadre de la sauvegarde de données bureautiques
habituelles.

La mise en place de procédures connues de tous, respectées et
contrôlées, permet d'exploiter au mieux l'infrastructure en place, comme
par exemple l'information donnée aux utilisateurs quant aux répertoires
à sauvegarder quotidiennement.

Le délai de restauration est malheureusement un impératif sous-estimé.
En effet, la plupart des responsables informatiques sont préoccupés par
la vitesse de sauvegarde mais ignorent la capacité de restauration. Or,
en cas de sinistre, c'est la restauration qui est critique. Une étude
détaillée de l'architecture de restauration ainsi que du réseau, validée
par une mise à l'épreuve, demeure le meilleur moyen de juger de
l'adéquation de la solution avec les besoins.  

### Respect des bons usages en matière de salle informatique
La mise en place d'une architecture informatique se doit de répondre à
certaines exigences en matière environnementale. Une salle informatique,
une salle de connectique, une salle de télécommunication etc.,
doivent être équipées de manière à assurer aux équipements des
conditions optimales de fonctionnement. Cela sous-entend : un circuit
électrique de secours ou un UPS (Uninterruptible Power Supply), une
climatisation et un filtrage d'air, un contrôle de l'électricité
statique, un système spécifique de lutte contre les dégâts des eaux et
du feu, et un contrôle d'accès.

### Remarque
L'ensemble de ces points est couvert dans une fiche relative à la
[sécurité physique]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}).

### Lieu de sauvegarde
Les supports informatiques, tels que les bandes magnétiques, supports
optiques et autres doivent absolument être stockés dans des endroits
répondant à leurs exigences en matière de protection contre la
poussière, les griffes, l'humidité et autres facteurs pouvant les
dégrader.

### Remarque
II est conseillé de stocker les supports de sauvegarde dans un
coffre-fort, en dehors de la salle informatique voire dans un autre
bâtiment.

### Gestion des droits des utilisateurs
Pour assurer au maximum l'effacement involontaire de données il y a lieu
de limiter au minimum les droits des utilisateurs sur des fichiers et
supports critiques.

### Gestion proactive du parc informatique
La majorité des pannes relatives au fonctionnement des équipements
informatiques ont des signes « avant-coureurs ». La plupart des
équipements sont fournis avec un logiciel qui analyse ces signes et
avertit l'utilisateur en cas de doute. Ces logiciels existent tant au
niveau des serveurs que des ordinateurs (postes de travail) et
ordinateurs portables. Il est conseillé de laisser agir ce logiciel et
de tenir compte des ses avertissements.

### Formation des utilisateurs
Une solution efficace pour éviter les maladresses consiste à former les
utilisateurs à une manipulation adéquate de la machine et de ses
périphériques, ainsi qu'à la gestion des données et des répertoires.


Mesures curatives
-----------------
Sont regroupées sous ce point toutes les mesures de récupération après
un sinistre :

### Logiciels ou sociétés de récupération
Il existe de nombreux logiciels capables de récupérer des données
perdues ou effacées sur différents supports. Ces logiciels ne sont pas
forcément coûteux mais leur usage demande une certaine maîtrise du
sujet. Il est donc fortement conseillé de faire appel à des entreprises
spécialisées dans ce domaine. En revanche exigez un service qui n'est
payant que quand les données sont récupérables.

### Remarque
Les personnes sensibles à la sécurité sont interpellées par le fait que
l'on puisse récupérer des fichiers effacés. Il est toujours possible de
rendre ce type de récupération inopérant, et il est important d'y prêter
attention lors de reventes d'équipements informatiques. (voir [mise au
rebut]({% link _knowhow/sos/SOS-WhatBeforeGettingRidOldHardware.markdown %}))
