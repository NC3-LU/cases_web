---
layout: article
title:  "Recommendations to secure a server connected to Internet"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: knowhow
ref: glossaryrecomm4securingserver
lang: en
hidden: true
---
En quelques mots
----------------
Les mesures de sécurité sont des mesures comportementales,
organisationnelles ou techniques qui cherchent à garantir la
[confidentialité]({% link _knowhow/glossary/Confidentiality_fr.markdown %}),
[l'intégrité]({% link _knowhow/glossary/Integrity_fr.markdown %}) et la
[disponibilité]({% link _knowhow/glossary/Availability_fr.markdown %}) d'un
[actif]({% link _knowhow/glossary/Assets_fr.markdown %}). Les mesures de sécurité
cherchent à réduire les
[vulnérabilités]({% link _knowhow/glossary/Vulnerabilities_fr.markdown %}) exploitées
par les [menaces]({% link _knowhow/glossary/Threat_fr.markdown %}) pour ainsi
réduire les [impacts]({% link _knowhow/glossary/Impact_fr.markdown %}). Elles sont
définies lors de la phase de traitement du risque du processus [gestion des risques]({% link _knowhow/glossary/RiskProcessing_fr.markdown %}).


Mesures de sécurité
-------------------

1.  Il est fortement recommandé de **[mettre à jour]({% link _knowhow/glossary/Patches_fr.markdown %})** régulièrement
    **le système d'exploitation** ainsi que les applications du serveur.
    L’exploitation de ces vulnérabilités techniques
    peut provoquer une corruption du fonctionnement du serveur ou un vol
    respectivement une [destruction des fichiers]({% link _knowhow/glossary/DataLoss_fr.markdown %}) et
    éventuellement des détournements des flux de données. Rédigez et
    faites respecter une politique sectorielle de développement et maintenance des systèmes.
2.  Il est fortement recommandé de restreindre la fonctionnalité du
    serveur à une seule tâche et de n’héberger aucune autre application
    sur ce même serveur virtuel, respectivement physique.
3.  Il est fortement recommandé de segmenter le réseau et de mettre le
    serveur dans une **DMZ**. L’accès au serveur doit donc passer un
    [firewall]({% link _knowhow/glossary/Firewall_fr.markdown %}) et
    idéalement par un [IDS/IPS]({% link _knowhow/glossary/IDS-IPS_fr.markdown %}).
    Rédigez et faites respecter une Politique sectorielle pour le
    contrôle d'accès.
4.  Il est fortement recommandé d’intégrer le serveur dans le **plan de
    sauvegarde**. Rédigez et faites respecter une politique sectorielle
    pour la gestion de l'exploitation et des télécommunications. Rédigez
    et faites respecter une politique sectorielle liée aux Aspects
    opérationnels et communications.
5.  Il est fortement recommandé de mettre en place une
    **[authentification]({% link _knowhow/glossary/Authentication_fr.markdown %}) forte**
    pour tout accès depuis l’extérieur de l’entité. Rédigez et faites
    respecter une politique sectorielle pour le contrôle d'accès.
6.  Il est fortement recommandé d’imposer une certaine **robustesse du
    mot de passe** des utilisateurs, ainsi que pour le compte
    administrateur. Rédigez et faites respecter une politique
    sectorielle pour le contrôle d'accès.
7.  Il est fortement recommandé de mettre en place un système de
    journalisation (logging) s'il n'est pas déjà en place par défaut. De
    plus, il est évidemment important de pouvoir évaluer le contenu des
    fichiers journal; de ce fait l'utilisation d'outils d'aggrégation et
    d'analyse, voire d'alerte, de fichiers journal est très utile. Cette
    journalisation doit être conforme avec les lois sur la protection
    des données à caractère personnel - surveillance sur le lieu de
    travail (voir le site de la CNPD).
8.  Il est fortement recommandé de protéger ce serveur contre les codes malicieux.
    Le logiciel d'analyse
    [antivirus]({% link _knowhow/glossary/AntiVirus_fr.markdown %}) doit être
    régulièrement mis à jour pour pouvoir reconnaître les derniers
    codes malicieux et les supprimer. Rédigez et faites respecter une politique
    sectorielle sur Aspects opérationnels et communications.
9.  Pour des serveurs classifiés comme
    importants ou vitaux, il est proposé de conclure un **contrat de
    maintenance** avec un délai d'intervention correspondant au niveau
    de classification du serveur. Rédigez et faites respecter une
    Politique sectorielle Sécurité physique et environnementale.
10. Pour des serveurs classifiés comme
    importants ou vitaux, il est fortement recommandé d'utiliser des
    onduleurs pour assurer une sécurité électrique. Rédigez et faites
    respecter une Politique sectorielle pour la Sécurité physique et
    environnementale.
11. Il est fortement recommandé de **sécuriser l'accès physique au
    serveur** aux seules personnes ayant droit. Rédigez et faites
    respecter une Politique sectorielle pour la Sécurité physique et
    environnementale.
12. En cas de mise au rebut du serveur, il est fortement recommandé de
    physiquement détruire (par broyeur ou démagnétiseur) les disques
    durs. Rédigez et faites respecter une Politique sectorielle Sécurité
    physique et environnementale.
13. Documentez les plus importantes manipulations sur le serveur
    (sauvegarde, mise en arrêt, démarrage,...). Rédigez et faites
    respecter une Politique sectorielle sur les Aspects opérationnels et
    communications.
