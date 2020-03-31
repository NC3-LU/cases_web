---
layout: article
title:  "Segmentation réseau"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: knowhow
toc: true
ref: glossarynetsegmentation
lang: fr
---
En quelques mots
----------------
Segmenter son réseau est un exercice utile, qui permet non seulement
d’améliorer sensiblement la sécurité de votre infrastructure mais oblige
surtout à effectuer un inventaire bien utile et une classification de
son parc informatique. La segmentation consiste à séparer les groupes
d’ordinateurs en sous-ensembles séparés les uns des autres par des
règles bien définies.

Une segmentation bien réalisée permet non seulement de contenir les
menaces éventuelles dans des zones bien définies mais surtout de mettre
en place des outils de sécurité supplémentaires.

Zone rouge - Internet
---------------------
De nos jours, il est impensable d’imaginer dans une entreprise un
système informatique complètement isolé d’Internet. La zone rouge
correspond à la zone sur laquelle on n’a pas de maîtrise; c’est de là
que vient une grande partie des menaces. Cette zone est à séparer du
réseau interne par un firewall ou au moins par un routeur NAT (ce qui
est le cas dans la plupart des ménages au Luxembourg). Un [firewall]({% link _knowhow/glossary/Firewall_fr.markdown %}) étant
un ordinateur servant à filtrer les communications entre zones, les
règles de filtrage doivent être définies par l’opérateur du firewall
mais, en général, il y aura au moins un blocage des connexions initiées
sur Internet.

Les seuls services exposés directement à Internet doivent être
identifiés et isolés dans la zone dite orange.


Zone orange - Les services exposés à l'Internet
-----------------------------------------------
La zone orange est la zone dans laquelle se trouvent les serveurs de
l’entreprise connectés directement à Internet. L’accès à cette zone doit
soigneusement être filtré (à l’aide d’un firewall) pour s’assurer que
seuls les services destinés au monde extérieur sont accessibles ; les
services de maintenance sont à protéger d’un accès direct depuis la zone
rouge. Aucune communication initiée dans cette zone ne doit pouvoir
entrer dans une autre zone du réseau interne.

La sécurité peut être améliorée à l’aide de commutateurs permettant
l’isolation des ports ; ainsi tous les serveurs se retrouvent isolés
entre eux, ce qui permet de contenir les
[attaques]({% link _knowhow/glossary/ComputerHacks_fr.markdown %}) en cas de
compromission de serveur.

Zone verte - Les ordinateurs du personnel
-----------------------------------------
La zone verte constitue le noyau du réseau interne. C’est cette zone qui
a le plus d’accès, principalement vers Internet, mais aussi de manière
restreinte vers la zone orange, pour des raisons de maintenance des
serveurs. En zone verte, le fait que les machines puissent parler entre
elles peut se révéler utile, une isolation des stations n’est donc pas
toujours souhaitable.

Souvent, des [proxys web]({% link _knowhow/glossary/WebFilterProxy_fr.markdown %})
de filtrage de pages et détection de
[virus]({% link _knowhow/glossary/MaliciousCodes_fr.markdown %}) seront
avantageusement installés pour amoindrir les dangers issus de
l’Internet.

La zone verte peut elle-même encore être séparée en sous-sections. Les
membres de l’équipe informatique par exemple sont les seuls habilités à
effectuer la maintenance des serveurs en zone orange. Il est donc
évident qu’ils devraient être les seuls à avoir accès aux services de
maintenance de ces serveurs.

Attention ! Ne vous laissez pas tromper par la couleur, beaucoup
d’attaques peuvent provenir de la zone verte (employés insatisfaits,
menaces externes qui se seraient infiltrées dans l’entreprise,
ordinateurs infectés pour ne citer que quelques exemples)  ; de ce fait,
les ordinateurs de cette zone ne devraient pas avoir tous les droits.


Zone jaune - Les services internes
----------------------------------
Serveurs de fichiers, serveur intranet ou autres services destinés aux
utilisateurs en zone verte nécessitent une attention particulière. Le
but est de les protéger des menaces de la zone verte tout en donnant les
accès nécessaires qui rendent ces services utiles. L’étude doit ici être
effectuée au cas par cas, néanmoins, cette zone peut être assimilée à
une zone orange offrant ses services à la zone verte au lieu de la zone
rouge.

L’installation de serveurs directement en zone verte, bien que
confortable, est à éviter en raison des dangers possibles qui en sont
issus.

Zone bleue - Les nomades et visiteurs
-------------------------------------
La zone bleue permet de donner des accès restreints (souvent uniquement
à Internet) à des visiteurs ou aux appareils privés du personnel (iPads
ou téléphones). C’est typiquement la zone du wifi. Les services internes
ne doivent être accessibles de cette zone qu’en observant certaines
précautions.


Pratique
--------
Une bonne segmentation de réseau ne peut se faire qu’avec les outils
adéquats. [Firewalls]({% link _knowhow/glossary/Firewall_fr.markdown %}),
commutateurs et, le cas échéant, antennes
[wifi]({% link _publications/recommendationsecuring/SecuringWifiNetwork_fr.markdown %})
constituent le cœur d’un réseau segmenté avec lesquels il est possible
d’obtenir de bons résultats même à moindre prix en utilisant des
produits libres. La segmentation de réseau est à la portée de tous et
déjà très utile pour toute petite entreprise.


Remarques
---------
Comme évoqué ci-dessus, il est important de ne pas considérer la zone
verte comme une zone sûre puisque c’est d’elle que viendra une grande
partie des attaques. L’équilibre entre services à mettre à disposition
et sécurité peut être difficile à gérer, de fait, celui-ci ne peut pas
être évalué sans analyse de risques préalable.

Une bonne segmentation du réseau ne constitue pas une protection absolue
et ne devrait pas être considérée comme telle, mais plutôt comme outil
nécessaire à la mise en place d’autres mesures de sécurité comme des
[systèmes de détection d’intrusion]({% link _knowhow/glossary/IDS-IPS_fr.markdown %}),
[filtrages]({% link _knowhow/glossary/WebFilterProxy_fr.markdown %}),
[antivirus]({% link _knowhow/glossary/AntiVirus_fr.markdown %}), etc.



Exemples
--------

### Petit réseau
Cas d’une très petite entreprise. La segmentation se résume à
l’utilisation d’un routeur NAT pour séparer le réseau interne
d’Internet.

![Réseau petit](/assets/img/knowhow/glossary/little-network.png)


### Réseau de taille moyenne

Cas d’une entreprise moyenne avec un serveur de fichiers  et de mails.
Un seul firewall s’occupe de la segmentation du réseau.

![Réseau moyen](/assets/img/knowhow/glossary/medium-network.png)

### Réseau de grande taille

Cas d’une grande entreprise avec réseau pour externes et un sous réseau
isolé en DMZ (zone orange dans laquelle les serveurs ne peuvent pas
communiquer entre eux).

![Réseau grand](/assets/img/knowhow/glossary/big-network.png)
