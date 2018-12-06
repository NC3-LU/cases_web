---
layout: article
title:  "Password"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: knowhow
toc: true
ref: glossarypassword
lang: fr
---
## En quelques mots

Le mot de passe, élément de base de la sécurité informatique, permet de [s'authentifier]({% link _knowhow/glossary/Authentication_fr.markdown %}) t d'accéder à une ressource ou un service personnel.

Afin de minimiser les risques d'usurpation, mieux vaut le choisir avec le plus grand soin en respectant quelques règles simples.

## 10 signes au minimum
Un bon mot de passe se compose au minimum de 10 signes. Pour augmenter la complexité du mot de passe, il est recommandé d'utiliser un mélange de chiffres, de lettres majuscules et minuscules, ainsi que des signes de ponctuation par exemple.

## Facile à mémoriser mais difficile à deviner
Le mot de passe doit être choisi de manière à être mémorisable sans avoir à le noter sur un support externe, tout en étant difficile à deviner par autrui, y inclus une personne vous connaissant bien (voir [Ingénierie sociale]({% link _knowhow/glossary/SocialEngineering_fr.markdown %})).

**Evitez à tout prix** :

* un mot du dictionnaire (même tiré d'un dictionnaire d'une langue étrangère),
* un prénom,
* votre login,
* une quelconque information liée à votre personne (prénom, date de naissance, etc.).

Un mot de passe fiable est souvent composé d'une phrase anodine. Vous pouvez y ajouter des préfixes, suffixes, ou signes pour en augmenter la complexité. Exemple de mot de passe : ```...:::deux vaches sur le toit:::...```.

En cas de longueur imposée, construisez votre mot de passe en prenant les premières lettres de chaque mot d'une phrase. Cela donne, en utilisant la phrase citée précédemment, pour un mot de passe à 9 caractères :  ```.:dvslt:.```

## Des mots de passe dédiés
Chaque mot de passe doit être dédié à un accès spécifique. Utilisez des mots de passe distincts pour des usages différents, sinon, en cas de vol (par [phishing]({% link _knowhow/glossary/Phishing_fr.markdown %}) ou shouldersurfing), le cybercriminel aura accès à plusieurs services en ligne.

Plus vous utiliserez vos mots de passe, mieux vous les retiendrez. Aussi nous vous recommandons de ne pas laisser votre navigateur mémoriser vos mots de passe à votre place. Pour les services peu utilisés, vous pourrez toujours sauvegarder les mots de passe dans des fichiers chiffrés, tels que créés avec *[keepass](https://keepass.info)*, par exemple.

## Changement régulier
Une bonne pratique est de changer de temps en temps vos mots de passe. La fréquence de changement dépendra de vous. Nous pensons que c'est un bon exercice de prévoir un jour par an ou tous les deux ans pour changer tous vos mots de passe.

Et bien évidemment, changez-les dès que vous soupçonnez une compromission ou une divulgation de ceux-ci.

## A usage personnel
Un accès par mot de passe est attribué de manière nominative. Un mot de passe ne doit pas être partagé entre plusieurs personnes et ne doit jamais être divulgué à quiconque, quelles que soient les circonstances.

N'oubliez pas que les organismes dignes de confiance ne vous demanderont jamais de communiquer votre mot de passe.

## Échanger les mots de passe
Les mots de passe servent à [authentifier]({% link _knowhow/glossary/Authentication_fr.markdown %}) une personne et à lui mettre à disposition les ressources prévues. Pour cette raison, il est déconseillé d'échanger les mots de passe avec des collègues. Si, pour des raisons d'organisation (logiciel spécial installé sur une seule machine), il est nécessaire de donner le mot de passe à une personne spécifique lors d'une absence prolongée (vacances, congé de maladie), il est recommandé de procéder la façon suivante:

1. le mot de passe est écrit sur un papier, renfermé dans une enveloppe signée et remise au responsable.
2. si une personne autorisée doit avoir accès au mot de passe, l'ouverture de l'enveloppe contenant le mot de passe est documentée sur papier en notant le nom de la personne ayant récupéré le mot de passe ainsi que la date et l'heure.
3. dès que la personne dont le mot de passe a été révélé revient au travail, elle change son mot de passe et le remet au responsable comme décrit sous 1)

De cette façon, la personne, dont le mot de passe a été révélé ne peut pas être tenue responsable pour les actions faites lors de sons absence. D'autre part il est toujours clair qui a accès à quelles ressources.

## Vulnérabilités fréquentes
Une authentification est nécessaire pour tous les accès de type *utilisateur* et *administrateur* aux serveurs et logiciels. Il ne faut pas oublier de tenir compte des accès aux éléments réseau constituant le système informatique, tels que les routeurs, les commutateurs, ... .

La solution *identifiant et mot de passe* est toujours la plus répandue. Cette solution courante base l'authentification sur une paire alliant un identifiant fourni par l'administrateur et un mot de passe que l'utilisateur final prendra soin de déterminer. On remarque que cette solution doit faire face à diverses vulnérabilités récurrentes :

### Existence de comptes avec des mots de passe peu résistants ou inexistants
Il existe quelques critères de qualité à respecter lors de la conception d'un mot de passe et ce afin d'éviter que des logiciels spécialisés ne puissent l'identifier en peu de temps.

### Existence de comptes installés par défaut lors de la mise en place de logiciels
Lors de l'installation de logiciels tels que les systèmes d'exploitation, il y a création de comptes par défaut. Ces comptes utilisent un mot de passe connu de tous les experts. Il est évident que ces comptes sont les premières cibles des personnes malintentionnées. Il est donc nécessaire de protéger ce compte par un mot de passe fiable.

### Mots de passe ayant perdu leur caractère secret
Un mot de passe est le secret permettant d'identifier l'utilisateur d'un compte. Il s'inscrit dans la même logique qu'un numéro de code pour les retraits aux guichets automatiques. Malheureusement, on voit trop souvent des mots de passe affichés sur les écrans ou connus de multiples personnes.

### Logiciels créant des utilisateurs pour usage interne
Certains logiciels, vont créer des comptes utilisés en interne pour converser avec les autres composantes du système informatique. Ces identifiants et leur mot de passe, souvent faibles ou même inexistants, sont documentés et évidemment connus de tous les experts.

### Formules de hachage des mots de passe non fiables ou inexistantes
La sauvegarde des mots de passe doit être faite sous forme de résultat d'une fonction irréversible comme par exemple une fonction de hachage. Il faut aussi s'assurer que le système utilise un hachage fort ainsi que d'autres mesures comme l'ajout d'un sel ainsi que le «stretching»

### Mémorisation des mots de passe sur les stations de travail
De nombreux logiciels, comme le navigateur, utilisant des mots de passe offrent la possibilité de les sauvegarder de manière à ne plus devoir les saisir. Il est évident que, malgré son aspect pratique, cette possibilité est vivement déconseillée.

### Vulnérabilités du système
Les vulnérabilités dans les logiciels peuvent permettre à des initiés de s'introduire dans le système sans mot de passe. Il est donc toujours important de mettre à jour tous ses logiciels et de faire faire des tests de pénétration sur les logiciels développés dans l'organisation.

### Absence de surveillance ou de blocage en cas de tentatives d'accès erronées
L'apparition de multiples tentatives d'introductions erronées de mots de passe pour un même compte représente évidemment un signal d'alarme très important pour un responsable de l'administration.
Alors que la plupart des systèmes informatiques permettent le blocage d'un compte après un certain nombre de tentatives erronées, cette fonctionnalités reste souvent inutilisée, ouvrant de ce fait la porte aux logiciels de cassage décrits dans ce document.

## Password cracking

Les mécanismes d'authentification comptent depuis longtemps parmi les vulnérabilités les plus exploitées.

Pour perpétrer ce genre d'attaques, les malfaiteurs utilisent des logiciels de déchiffrement spécialisés et se basant sur deux technologies distinctes :

### Le cassage par méthode exhaustive ou «brute-force»
Dans ce cas, le logiciel de déchiffrement va essayer toutes les combinaisons contenant aussi bien des caractères hybrides qu'alphanumériques. Cette méthode est efficace mais prend énormément de temps pour découvrir des chaînes de caractères complexes.

Certains des outils de cassage sont dédiés à des logiciels spécifiques tels que Microsoft Word, ou autres.

Il est à noter que même dans les meilleures conditions cette technique devient inutilisable pour des mots de passe dépassant environ 10 caractères.

### L'attaque par mots du dictionnaire
Dans ce cas, le logiciel de déchiffrement va passer en revue tous les termes d'une liste spécifique, appelée «dictionnaire». Souvent les logiciels qui effectuent cette attaque introduisent aussi des transformations aux mots de la liste comme par exemple la transformation des «e» en «3» ou l'ajout à la fin de chiffres. Cette méthode est un beaucoup plus rapide que l'exhaustive, mais ne permet de trouver que les mots de passe communs.

## Conseils supplémentaires
Les conseils donnés ci-après, traitent de l'usage de l'authentification par compte/mot de passe. Ces règles sont à configurer par vous dans le logiciel d'administration, de manière à ce qu'elles soient automatiquement applicables à tous les comptes créés.

### Contrôlez l'architecture informatique
Il est très important d'analyser périodiquement les fichiers journal (logs) afin de détecter les éventuelles tentatives d'accès frauduleux.
De même, il est indispensable de mettre à jour la liste des utilisateurs, leurs profils et leurs droits sur le système informatique, en tenant compte de la [classification des données]({% link _knowhow/cisoapproach/SecurityPolicy-Classification_fr.markdown %}).

### Limitez les comptes
Les comptes de type «administrateur», bénéficiant de beaucoup de droits, sont la cible privilégiée des [attaquants]({% link _knowhow/glossary/Cybercriminals_fr.markdown %})’ Il est conseillé de ne pas partager ce compte avec toute l'équipe informatique, mais de créer des profils correspondant aux besoins exacts de chacun des membres de l'équipe.

Sur la plateforme Microsoft Windows, il peut même être intéressant de limiter tous les pouvoirs du compte "administrateur" et de lui attribuer un mot de passe très complexe. Il suffit ensuite de redistribuer les tâches à d'autres comptes moins visibles. De cette manière, l'éventuel pirate / cracker passera son temps sur un leurre, puisque le compte ne lui permettra pas d'accéder aux informations. Malheureusement, cela n'est pas possible sur la plateforme Unix avec le compte root.

### Alternatives
[Des solutions d'authentification plus robustes]({% link _knowhow/glossary/Authentication_fr.markdown %}#multi-factor-authentication), telles que proposées par LuxTrust (basées sur des infrastructures à clé publique) ou  la biométrie, sont disponibles. L'avantage de ces solutions est de supprimer le problème de la divulgation des mots de passe ou de la transmission de données critiques au travers du réseau. Malheureusement, elles peuvent être coûteuses et complexes à mettre en place.
