---
layout: knowhow
category: "Knowhow"
title:  "Arnaques à travers les téléchargements"
menutitle:  
logo:
date:   2017-11-06 00:00:00 +0100
short: "Vue d'ensemble des menaces et des mesures pour nous protéger"
categories: scams
toc: true
ref: scamsthroughdownloads
lang: fr
---
## En bref
Le Web est une source de inépuisable trésors en tout genre, à visiter ou bien à télécharger.

Grâce à la progression des débits disponibles, les téléchargements sont de plus en plus rapides et faciles à effectuer. Un document d’information ou un formulaire PDF téléchargé sur un site officiel ne pose normalement pas de problème.

Le problème se pose lorsque certains sites nous proposent de télécharger des fichiers qui auront un comportement non désiré voire néfaste sur notre ordinateur. Des programmes sains téléchargés depuis longtemps peuvent également poser problème s’ils contiennent des failles qui n’ont pas été corrigées par la suite.

## Panormama des [menaces]({% link _knowhow/glossary/Threat_fr.markdown %})

##### Virus
Le [virus]({% link _knowhow/bestpractices/MaliciousSoftwareBP_fr.markdown %}) est la forme la plus ancienne et la plus classique de programme malicieux. Les virus peuvent se cacher dans n’importe quel type de fichier, document, image ou vidéo. Ils affectent le bon fonctionnement de l’ordinateur ou l’empêchent purement et simplement de fonctionner. Ils ont un rôle essentiellement destructeur et ils ne constituent pas le meilleur moyen de gagner de l’argent, pour leurs auteurs.

##### Faux virus et faux anti-virus

Les fausses alertes utilisent notre peur d’être infecté par un véritable virus. Un site malveillant peut par exemple afficher une alerte nous qui nous fait croire que notre ordinateur est infecté. En cliquant sur cette alerte, nous serons guidés vers le téléchargement d’un prétendu antivirus qui n’est en fait qu’un programme malicieux, de type « [Cheval de Troie]({% link _knowhow/glossary/MaliciousCodes_fr.markdown %}#cheval-de-troie) ». Une fois ce programme téléchargé, il se dissimulera sur notre ordinateur et n’aura sans doute aucun effet visible. Par contre, le malfaiteur pourra prendre le contrôle de notre ordinateur pour effectuer d’éventuels actes illicites.

Secuser a dressé une liste de faux virus : [Secuser](http://www.secuser.com/hoax/)

Les conseils de Microsoft pour déjouer les fausses alertes : [Microsoft Blog - Real vs. Rogue Security Software – Can You Tell The Difference?](https://cloudblogs.microsoft.com/microsoftsecure/2013/01/03/real-vs-rogue-security-software-can-you-tell-the-difference/)

##### Vidéos et players

Les players sont des programmes qui nous permettent de lire des fichiers audio ou vidéo. Il en existe une grande variété. La plupart du temps, ils fonctionnent correctement. Mais 2 types de problèmes peuvent se poser :

1. Des players anciens non mis à jour peuvent contenir des failles qui sont exploitées par des des fichiers vidéo ou audio téléchargés.
2. Les sites de téléchargements illégaux obligent leurs utilisateurs à installer un player spécifique ou un programme spécifique pour télécharger le fichier vidéo « plus rapidement ». Ce dernier comporte en général du code malicieux. En outre, il faut savoir que les fichiers téléchargés sur des sites illégaux peuvent eux-mêmes comporter du code malicieux. A éviter !

![Download videos faster](assets/img/201610/1253_1.png "Download videos faster")

##### Plugins

Les plugins ne sont en général pas dangereux en eux-mêmes. Il faut simplement être conscient qu’il s’agit de logiciels comme les autres, et qu’ils peuvent comporter des failles et des vulnérabilités. Il convient donc de vérifier lors de leur téléchargement qu’ils sont légitimes et qu’ils fonctionnent comme annoncé. Ensuite, il faudra effectuer les mises à jour régulièrement, ainsi que celles du browser sur lequel ils sont installés.

Enfin, il faudra veiller à supprimer les plugins qui ne sont plus utilisés. Bref, pour éviter les infections, une certaine hygiène est de rigueur avec les plugins comme avec tout programme installé sur votre PC.

##### Adware

Certains programmes téléchargés ou plugins installent avec eux des adwares ou “publiciels”, qui font apparaître de façon pernicieuse de la publicité sur l’ordinateur, que ce soit au niveau des barres du navigateur internet, par des fenêtres surgissantes (popup), ou par des messages système. Même si ces programmes ne sont pas réellement malicieux, ils ralentissent votre PC et peuvent le rendre vulnérable.

##### Zombies

Certains fichiers malicieux téléchargés peuvent transformer votre PC en « zombie » qui peut être utilisé par des pirates pour perpétrer des attaques sans se faire repérer.

##### Ransomware

D’autres fichiers malicieux ont pour effet de chiffrer les données enregistrées sur votre disque dur. Vous n’y avez dès lors plus accès, et vous êtes priés de payer une somme conséquence pour déchiffrer vos propres données et y avoir de nouveau accès. L’arnaque suprême !

## Comment se protéger?

Contre les risques liés aux téléchargements, le slogan « Clever Klicken » est plus que jamais d’actualité. Voici les réflexes à adopter et les mesures à prendre.

##### Mesures comportementales

* Méfiez-vous des mails inopinés et des offres alléchantes sur le Web, de tout fichier non sollicité qui vous serait envoyé par mail ou sur les réseaux sociaux. Apprenez à résister social engineering d’une manière générale.
* Si vous avez un doute, demandez une confirmation avant d’ouvrir un fichier.
* Sachez reconnaître les messages de votre propre logiciel anti-virus. Beaucoup de sites malicieux leurrent les internautes à télécharger un faux logiciel anti-virus en prétendant que la machine de l'internaute est infectée.
* Tenez compte des alertes émises par les moteurs de recherche ou le navigateur lorsque celles-ci vous mettent en garde contre la navigation sur une certaine page.


##### Technical measures
* Utilisez un filtre de navigation tel que [WOT]({% link _knowhow/glossary/WOT_fr.markdown %}) ou activez les filtres de vos navigateurs :
  * Smart screen de Microsoft
  * Phishing filtre de mozilla firefox
  * Google Chrome et sécurité du navigateur
* Installez une solution de [filtrage web]({% link _knowhow/glossary/WebFilterProxy_fr.markdown %}) pour votre société, ainsi vous bloquez déjà beaucoup de sites malicieux.
* Utilisez une solution de virtualisation ou similaire pour contenir les [menaces]({% link _knowhow/glossary/Threat_fr.markdown %}) éventuelles (voir p. ex. [Sandboxie]({% link _publications/Sandboxie_fr.markdown %}))
