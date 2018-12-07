---
layout: article
title:  "Sauvegarde de données"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: knowhow
toc: true
ref: glossarydatabackups
lang: fr
---
En quelques mots
----------------
La sauvegarde des données est primordiale pour tout système
d’information. En effet, un support de données n’est fiable que pour une
certaine durée dans le temps. A l'instar des tablettes de pierre
utilisées dans l’Antiquité qui étaient sujettes aux intempéries, aux
catastrophes naturelles et à l’usure, tout système d'information actuel
est faillible. Pour une entreprise, la perte de données peut se solder
par l’arrêt définitif de l’activité. Dès lors, si vous souhaitez
conserver vos données essentielles
([disponibilité]({% link _knowhow/glossary/Availability_fr.markdown %})), il faudra
tôt ou tard penser à des stratégies de sauvegarde pour celles-ci.


Réflexions préliminaires
------------------------
Il peut être intéressant, avant de choisir une solution de sauvegarde,
de procéder à une analyse des risques. Les principaux risques auxquels
la plupart des gens sont confrontés sont les suivants
([menaces]({% link _knowhow/glossary/Threat_fr.markdown %}) mettant en cause la
[disponibilité]({% link _knowhow/glossary/Availability_fr.markdown %})
respectivement l'[intégrité]({% link _knowhow/glossary/Integrity_fr.markdown %}) des
données) :

1.  perte de données par effacement (erreur humaine ou logiciel
    malveillant) (PME : voir [Erreur humaine]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2HR.markdown %}#human-error-prevention-measures));
2.  perte de données par défaillance matérielle (disque dur défectueux,
    destruction accidentelle de support) (PME : voir [Sauvegardes inutilisables]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware_fr.markdown %}#unusable-backups),
    [Endommagement du matériel pendant le transport]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware_fr.markdown %}#hardware-damaged-during-transport),
    [Équipement informatique ou de communication en panne]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware_fr.markdown %}#failure-of-it-or-communications-equipment),
    [Administration impossible]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Software_fr.markdown %}#unavailability-of-administrators),
    [Environnement logiciel inapproprié]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Software_fr.markdown %}#unsuitable-software-environment));
3.  sinistre (PME : voir
    [Incendie]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure_fr.markdown %}#fire),
    dégât des eaux) ;
4.  vol de support (PME : voir [Pénétration dans les locaux]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure_fr.markdown %}#infiltrating-the-premises),
    [Vol caractérisé]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware_fr.markdown %}#aggravated-theft)).

Une réflexion sur les différents risques énoncés ci-dessus vous
indiquera la stratégie de sauvegarde à suivre. Pour les points 1 et 2
(les plus fréquents) il suffit de faire des sauvegardes sur disque dur
externe, sur disque réseau ou sur support amovible. Pour les points 3 et
4 (événements rares mais très destructeurs), une sauvegarde hors site
devient essentielle.


Les choix du support
--------------------
La question du choix du support de sauvegarde est au moins aussi
importante que celle de la stratégie. Les plus communs sont les suivants:

-   supports amovibles (CD, DVD) ; très bon marché, mais de capacité limitée et rapidement
    détruits avec le temps ; il n'est plus conseillé de nos jours
    d'effectuer des sauvegardes sur ces support (sauf très petits
    volumes).

-   les disques durs magnétiques ; bon marché, offrant les capacités de
    stockage les plus élevées, résistent assez bien à la dégradation au
    fil du temps ;

-   les mémoires flash, SSD ; plus chères que les disques durs
    conventionnels, très rapides, résistent de mieux en mieux à la
    dégradation au fil du temps, mais leur prix les rend encore
    inutilisables pour stocker de grandes quantités de données ;

-   les bandes magnétiques ; offrant de bonnes capacités de stockage,
    mais chères et peu pratiques, elles sont réservées à des très
    grandes quantités de données ;

-   services en ligne (cloud) ; prix, disponibilité et
    pérennité dépendent du fournisseur ; grâce aux débits actuels des
    lignes par fibre, ces services sont maintenant même accessibles aux
    très petites entreprises.

Dans tous les cas, l’espace de stockage sera souvent le facteur
déterminant le prix, mais aussi la faisabilité de la sauvegarde. Ceci
nous amène au concept d’organisation du dépôt de données.


Dépôt et rotation des sauvegardes
---------------------------------
La fréquence de sauvegarde indiquera la quantité de données perdues en
cas d’incident. Si vous faites une sauvegarde de vos données une fois
par semaine, vous perdrez au maximum une semaine de données. Êtes-vous
prêts à accepter cette perte ? Serait-il judicieux d’augmenter la
fréquence de sauvegarde à une fois par jour par exemple ? La réponse à
ces questions dépendra de chaque cas.

Un autre problème se pose : si vous faites une sauvegarde unique par
semaine et qu’un [logiciel
malveillant](https://www.cases.lu/fr/logiciels-malveillants.html) a
détruit une partie de vos documents un mois auparavant sans que vous ne
vous en rendiez compte, vous aurez perdu des données malgré votre
sauvegarde. De ce fait il est recommandé de garder un historique de
plusieurs sauvegardes dans votre dépôt. L’espace de stockage étant
limité, il faudra choisir une méthode de rotation des sauvegardes,
déterminer quelles sauvegardes passées effacer pour faire de la place
aux nouvelles. Pour l’exemple précédent d’une sauvegarde par semaine, il
serait envisageable de garder les six dernières sauvegardes et couvrir
ainsi plus d’un mois d’historique.\
Un exemple plus adapté à des plus grandes structures serait de faire une
sauvegarde quotidienne en gardant une semaine de sauvegardes. Garder une
sauvegarde par semaine pendant un mois, garder une sauvegarde mensuelle
pendant un an et ainsi de suite.

Le niveau de
[classification](https://www.cases.lu/fr/classification.html) des
sauvegardes correspond à celui des données sauvegardées. Si celles-ci
sont hautement
[confidentielles](https://www.cases.lu/fr/confidentialite.html), les
sauvegardes sont aussi hautement confidentielles.


Types de sauvegarde
-------------------
Pour préserver de l’espace - qui dans le passé était souvent très cher -
en plus de la compression des données, différents types de sauvegardes
sont proposés par la plupart des logiciels :

### La sauvegarde pleine (full backup)
Toutes les données sont sauvegardées. C’est la sauvegarde qui prend le
plus d’espace, mais aussi la plus sûre et facile à récupérer car elle
contient toutes les données.

### La sauvegarde incrémentale
Une sauvegarde incrémentale suit toujours, soit une sauvegarde pleine,
soit une autre sauvegarde incrémentale et ne contient que les fichiers
qui ont changé depuis la dernière sauvegarde, quel que soit son type.
Pour récupérer tous les fichiers, il faudra donc disposer de toute la
série de sauvegardes depuis la dernière sauvegarde pleine. Ce type de
sauvegarde est celui qui utilise le moins d’espace.

### La sauvegarde différentielle
La sauvegarde différentielle englobe tous les fichiers ayant changé
depuis la dernière sauvegarde pleine uniquement. Elle utilisera plus
d’espace que les sauvegardes incrémentales mais la récupération des
données complète ne nécessitera que la dernière sauvegarde pleine ainsi
que la dernière sauvegarde différentielle.

### Sauvegarde des fichiers ou du système
Vos fichiers sont importants et leur sauvegarde primordiale en cas de
perte de données. Mais avez-vous également pensé à la disponibilité de
votre système ? Que se passerait-t-il si votre disque dur venait à avoir
une panne (voir [pannes
physiques](https://www.cases.lu/fr/pannes-physiques.html)) ? Vous auriez
bien tous vos fichiers importants dans votre sauvegarde, mais il
faudrait acheter un nouveau disque, réinstaller votre système
d’exploitation et finalement réinstaller aussi tous vos logiciels avant
de pouvoir récupérer vos photos et documents.

Pour éviter ce type de désagrément certains logiciels permettent une
sauvegarde non seulement des fichiers mais aussi de tout le disque. Ces
logiciels font ce qu’on appelle une « image » du disque et permettent en
cas de panne de prendre un nouveau disque et de recopier toute l’image
sur celui-ci, rendant la panne moins douloureuse en temps et en efforts.

Remarques
---------

-   Si vous vous décidez pour une sauvegarde en utilisant un service en
    ligne d'une entreprise tierce, pensez à vérifier que vos données
    soient bien chiffrées **avant** l'envoi sur les serveurs du
    prestataire ; vous devriez être le seul possesseur de la clé de
    chiffrement, votre fournisseur ne doit pas pouvoir voir vos données.

-   Les supports les plus adaptés pour une utilisation "TPE" (très
    petite entreprise) du point de vue prix, espace et pérennité sont
    les disques durs ou la sauvegarde sur service en ligne.



Politique de sécurité
---------------------

Rédigez et faites appliquer les politiques sectorielles suivantes:

-   [Organisation de la
    sécurité](https://www.cases.lu/fr/polsec-organisation-de-la-securite.html)

    -   [Attribution des
        responsabilités](https://www.cases.lu/fr/polsec-organisation-de-la-securite.html&WCE_section_194_1=1&WCE_section_194_1=1#574)
-   [Classification et maîtrise des
    ressources](https://www.cases.lu/fr/polsec-classification-et-maitrise-des-ressources.html)
    -   [Classification et responsabilité des
        ressources](https://www.cases.lu/fr/polsec-classification-et-maitrise-des-ressources.html&WCE_section_206_1=1&WCE_section_206_1=1#579)
-   [Sécurité physique et
    environnementale](https://www.cases.lu/fr/polsec-securite-physique-et-environnementale.html)
    -   [Périmètre de sécurité
        physique](https://www.cases.lu/fr/polsec-securite-physique-et-environnementale.html&WCE_section_219_1=1&WCE_section_219_1=1#582)
    -   [Sécurité des équipements hors des
        locaux](https://www.cases.lu/fr/polsec-securite-physique-et-environnementale.html&WCE_section_219_1=5&WCE_section_219_1=5#586)
-   [Aspects opérationnels et
    communications](https://www.cases.lu/fr/polsec-aspects-operationnels-et-communications.html)
    -   [Procédures
        documentées](https://www.cases.lu/fr/polsec-aspects-operationnels-et-communications.html&WCE_section_242_1=1&WCE_section_242_1=1#589)
    -   [**sauvegarde de données**](https://www.cases.lu/fr/polsec-aspects-operationnels-et-communications.html&WCE_section_242_1=5#593)
    -   [Sécurité des médias pendant les
        transports](https://www.cases.lu/fr/polsec-aspects-operationnels-et-communications.html&WCE_section_242_1=6&WCE_section_242_1=6#594)
-   [Contrôle
    d’accès](https://www.cases.lu/fr/polsec-controle-d-acces.html)
    -   [Politique de contrôle
        d’accès](https://www.cases.lu/fr/polsec-controle-d-acces.html&WCE_section_265_1=1&WCE_section_265_1=1#596)
    -   [Gestion des droits
        d’accès](https://www.cases.lu/fr/polsec-controle-d-acces.html&WCE_section_265_1=2&WCE_section_265_1=2#597)
-   [Gestion de la continuité de
    l’entreprise](https://www.cases.lu/fr/polsec-gerer-la-continuite-de-l-entreprise.html)
    -   [La continuité de
        fonctionnement](https://www.cases.lu/fr/polsec-gerer-la-continuite-de-l-entreprise.html&WCE_section_287_1=1&WCE_section_287_1=1#605)
