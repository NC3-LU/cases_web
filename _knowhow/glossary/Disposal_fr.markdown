---
layout: article
title:  "Mise au rebut"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: knowhow
toc: true
ref: glossarydisposal
lang: fr
---
En quelques mots
----------------
Les données qui vous appartiennent et que vous manipulez avec votre
ordinateur ont différents niveaux de
[confidentialité]({% link _knowhow/glossary/Confidentiality_fr.markdown %}).
Vous ne traitez probablement pas de la même manière les données que vous mettez
sur un réseau social et celles que vous gardez exclusivement sur votre
disque local. Données clients, données stratégiques de votre entreprise,
textes, lettres ou e-mails constituent seulement la partie visible de
votre comportement sur l'ordinateur. Une quantité de données sont par
ailleurs générées comme produit secondaire lors de cette utilisation :
fichiers temporaires, historiques de navigation, profils d’utilisateurs,
mots de passe sauvegardés en sont quelques exemples. Soyez donc
conscients que lorsque vous utilisez un ordinateur, vous laissez sur
votre passage, tel un escargot, une empreinte de tout ce que vous
faites.

Si vous souhaitez mettre au rebut ou léguer votre ordinateur à quelqu'un
d'autre, il est important de détruire entièrement ces traces. Un simple
effacement de fichiers ou reformatage du disque ne suffisent pas. La
section ci-après vous livre les explications nécessaires pour bien vous
préparer.

Pour les données classifiées comme confidentielles, nous vous conseillons une
destruction physique par broyeur ou démagnétiseur, il est hors de question de
léguer de tels équipements.

La destruction totale de vos données
------------------------------------

### Objectif
Vous voulez revendre ou mettre au rebut votre PC. Les disques qui
contiennent vos données vont tomber dans des mains inconnues. Il vous
faut tout effacer.

### Démarche à suivre
Pour effacer efficacement toutes les données précédemment citées, il est
important d’utiliser un système indépendant de celui dont vous souhaitez
vous débarrasser. Vous pourrez par exemple démonter les disques et les
brancher à un autre ordinateur. La manière la plus simple consiste
cependant à utiliser un système dit « live » qui peut démarrer votre
ordinateur sans utiliser ses disques durs internes.

Le système Live « Darik's Boot And Nuke » est gratuitement mis à
disposition sur le site suivant : http://www.dban.org/

Veuillez télécharger le fichier avec l’extension « iso ». Ce fichier est
une image de disque compact prête à être gravée. Pour l’utiliser, il
suffit de se servir d’un logiciel de gravure. Prenez bien garde de ne
pas graver votre CD comme disque de données conventionnel avec le
fichier image comme contenu, mais cherchez plutôt l’option « graver une
image » ou « burn image » en anglais.

Une fois le CD gravé il faudra redémarrer votre ordinateur avec le CD
dans votre lecteur. Sur la plupart des ordinateurs le disque sera lancé
au démarrage au lieu du système d’exploitation. Si votre système
d’exploitation habituel se charge au lieu de « Darik's Boot And Nuke »
il faudra définir dans votre BIOS le lecteur CD comme premier lecteur de
démarrage. Nous vous conseillons de faire une recherche sur Internet
pour vous aider à faire cette configuration.

### Destruction des données
Une fois ce live CD démarré, tapez autonuke\[entrée\] pour effacer tous
les disques sur votre ordinateur. Attention cela effacera aussi les
mémoires de masse attachées à l’ordinateur par usb (comme les appareils
photo, ou disques externes). Vous pourrez alors retourner à vos
activités habituelles car cette opération peut-être très longue,
prévoyez de laisser l’ordinateur allumé pendant au moins une journée.

**En général, pour des supports magnétiques (disques durs
conventionnels) la méthode « Quick Erase » suffit, elle a aussi
l’avantage d’être la plus rapide.**

**Précisons ici que la seule méthode que vous devriez utiliser pour la
mémoire flash (et donc pour des disques SSD) est la méthode « Quick
Erase ». Les autres méthodes risqueraient d’endommager ce type de
disques et ne seraient pas plus efficaces, car adaptées à des supports
magnétiques.**

### Après la destruction

Selon vos aspirations, vous pouvez maintenant réinstaller votre système
d’exploitation favori ou vous défaire en toute quiétude de votre
ordinateur.

### Avantages

Opération efficace et qui demande peu d’interactions.

### Désavantages

Opération longue à effectuer. Pour une entreprise désirant détruire
beaucoup de disques, une destruction physique sera plus rapide (et
peut-être moins chère).


La destruction ciblée des données
---------------------------------

### Objectif
Vous voulez céder votre PC à une personne de confiance, peut-être à l’un
de vos enfants. La méthode décrite ci-après est particulièrement valable
si vous avez égaré le disque de réinstallation de votre PC et que vous
souhaitez céder un ordinateur fonctionnel. Le but est d’effacer les
données confidentielles tout en laissant le système d’exploitation
intact.

La destruction ciblée des données présente néanmoins quelques gros
inconvénients, car non seulement il restera toujours quelques traces de
vos données, mais cette méthode ne pourra pas détruire les logiciels
malveillants, qui pourraient se trouver sur votre ordinateur et vous
risquez de léguer un ordinateur infecté à l’un de vos proches.

### Démarche à suivre
Nous allons, en plus des outils déjà présents sur votre ordinateur,
utiliser le logiciel suivant : ccleaner – téléchargeable sur
<http://www.piriform.com/ccleaner>

### Destruction des données
Il existe par défaut un compte « Administrateur » dans tout système
Windows. Fermez votre session actuelle (démarrer-&gt;Fermer la session).
Vous vous retrouverez devant un écran d’authentification Windows.
L’utilisateur « Administrateur » est malheureusement caché : il faut
donc appuyer sur ```CTRL + ALT + DELETE``` pour faire apparaître la fenêtre
d’authentification classique.

Cet utilisateur spécial s’appelle « Administrateur » dans la version
française de Windows mais « Administrator » en anglais ou allemand. Si
vous ne vous souvenez plus du mot de passe « Administrateur » nous vous
conseillons de créer un nouvel utilisateur ayant les droits
d’administration et d’utiliser celui-ci. Ce qui importe, c'est que vous
ne soyez pas authentifié avec votre utilisateur habituel.

Faites alors un click droit sur votre Poste de travail et sélectionnez «
Gérer ».

Sélectionnez maintenant vos comptes habituels et effacez-les en appuyant
sur la touche \[Delete\].

Puis effacez le répertoire personnel des comptes effacés qui se trouve
sur ‘C://Documents and Settings/’ ou ’C://Users’ pour des versions de
Windows plus récentes.
 
Ensuite il est important de désinstaller les logiciels que l’on ne veut
pas céder, par exemple pour des raisons de licences. Il est possible
d’utiliser les fonctionnalités de désinstallations intégrées à Windows,
mais ccleaner est sensiblement plus rapide. Lancez donc ccleaner.

Pensez aussi à effacer les mots de passe wifi éventuels en allant dans
le panneau de configuration cherchez l’icône « Connexions réseau ».
Sélectionnez votre connexion réseau et faites un click droit.

Choisissez « Propriétés » puis l’onglet « réseaux sans fil ».

Sous Windows 7 et Vista cherchez dans le panneau de configuration le
gestionnaire de réseaux sans fil, dans lequel vous pourrez sélectionner
des réseaux et les effacer.

Pensez maintenant à effacer vos points de restauration. Faites un click
droit sur votre poste de travail et sélectionnez « Propriétés ».

Choisissez alors l’onglet « Restauration du système » et désactivez
cette fonction. Après avoir cliqué sur « Ok » vos points de restauration
seront effacés.

Si vous souhaitez aller encore plus loin, éliminez le fichier de mémoire
virtuelle, qui pourrait contenir des bribes de mémoire compromettantes,
en allant sur l’onglet « Avancé », le bouton « Paramètres » de «
Performances », onglet « Avancées », mémoire virtuelle. Cette dernière
étape n’est pas aussi importante et peut être ignorée.

Si vous avez encore des données à d’autres endroits il est à présent
important de les effacer. Sélectionnez les dossiers ou fichiers à
effacer et appuyez sur les touches \[shift\]+\[delete\] pour les effacer
sans les envoyer par la corbeille. Si vous avez effacé les fichiers de
manière conventionnelle, pensez juste à vider la corbeille.

Effacez alors les données cachées en utilisant ccleaner.

Les configurations par défaut suffisent vu que vous avez effacé le
profil de l’utilisateur principal.

Toutes les données effacées sont en théorie récupérables dans l’espace
libre du disque. Utilisez ccleaner pour effacer l’espace libre.

### Après la destruction
Vous pouvez maintenant créer le compte du nouvel utilisateur.

### Avantages
Opération qui ne demande pas une réinstallation du système.

### Désavantages
Opération qui ne garantit pas la destruction totale des données. De
plus, en cas d’infection antérieure par un logiciel malveillant, le
système reste infecté.

Conclusion
----------
Deux méthodes ont été présentées pour effacer les données d’un PC. Il
est vivement conseillé d’utiliser la première méthode, qui permet de
garantir :

1.  l’effacement total des données ;
2.  après une réinstallation, un système exempt de logiciels
    malveillants.

L’effacement y est plus facile à effectuer, mais plus long que pour la
deuxième méthode. En revanche, si vous désirez léguer un ordinateur
fonctionnel, il vous faudra réinstaller le système d’exploitation.

Un troisième moyen très efficace est évidement de procéder à une
destruction par broyage ou par démagnétiseur, si ce n’est de votre
ordinateur, du moins de vos disques durs. C’est une solution très sûre,
parfaite pour les grands volumes et donc pour les entreprises. Certaines
entreprises sont spécialisées dans la destruction des données, et il
vaudra toujours mieux payer pour détruire ses données, que se les faire
voler.
