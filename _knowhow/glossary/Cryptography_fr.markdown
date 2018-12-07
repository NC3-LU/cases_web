---
layout: article
title:  "Cryptographie"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: knowhow
toc: true
ref: glossarycryptography
lang: fr
---

Histoire
--------
Depuis tous les temps, l'être humain cherche à garder secret certaines
informations ou données, à défaut, à en restreindre l'accès à certaines
personnes. Un des plus anciens exemples d'utilisation cryptographique
nous provient de Jules César.

L'empereur romain utilisait une méthode spécifique pour communiquer avec
son état-major. En effet, les messages étant à l'époque transmis par des
messagers, Jules César tenait à en protéger la confidentialité. Sa
méthode de transcription consistait à remplacer une lettre par un
décalage de trois. Par exemple, le 'A' était remplacé par un 'D', le 'B'
par un 'E', ainsi de suite. De cette manière, seules les personnes
connaissant ce subterfuge étaient capables de déchiffrer l'information.

Jusqu'au XXième siècle, l'utilisation de la cryptographie était
relativement mineure et les méthodes utilisées bien souvent
rudimentaires.

Ce n'est que lors de la 2ème guerre mondiale, avec l'apparition de
technologies de communication évoluées telles que la radio, que  la mise
au point de mécanismes de chiffrement empêchant l´interception des
signaux par l'ennemi est devenue indispensable. Il fallait en effet
commencer à chiffrer les données transmises par les ondes (Enigma) ! La
cryptographie a eu une réelle incidence sur ce conflit mondial.

Depuis cette époque, mais surtout avec l'apparition de l'algorithme DES
et de la réalisation de la cryptographie asymétrique, l'utilisation de
la cryptographie a explosé. Les besoins des applications militaires se
sont mêlés aux besoins des applications civiles et les techniques de
chiffrement sont devenues un élément moteur de progrès. (Applications
bancaires, télécommunications, informatique, monétique...)


Définitions
-----------

### Cryptographie

Il s´agit de la science qui étudie les principes et méthodes
mathématiques appliqués à dans des buts tels que la confidentialité ou
l'intégrité des données. Elle tend donc à développer des techniques
permettant de stocker des informations sensibles et de les transmettre
via des réseaux non sécurisés (comme Internet) de telle sorte que ces
données ne puissent être lues ou modifiées que par les personnes
autorisées.

### Cryptanalyse

La cryptanalyse étudie la sécurité des procédés de cryptographie. Elle
consiste à mettre à l´épreuve les fonctions cryptographiques existantes,
afin d´en visualiser les forces et les faiblesses. La cryptanalyse est
donc une combinaison de raisonnement analytique, d'application d'outils
mathématiques, de découverte de redondances, de patience, de
détermination, mais aussi de... chance.

### Cryptologie

Il s'agit de la science qui englobe la cryptographie et la cryptanalyse.


### Chiffrement et déchiffrement

On appelle « texte en clair » les données lisibles et compréhensibles
sans intervention spécifique. Le  chiffrement est la méthode permettant
de dissimuler du texte en clair en masquant son contenu. Cela consiste à
transformer un texte normal en un charabia inintelligible appelé texte
chiffré. Cette opération permet de s'assurer que seules les personnes
auxquelles les informations sont destinées pourront y accéder. Le
processus inverse de transformation du texte chiffré vers le texte
d'origine est appelé le déchiffrement.

### Clé

On appelle clé une valeur utilisée dans un algorithme de cryptographie,
afin de chiffrer un texte. Il s´agit souvent d´un nombre très grand dont
la taille se mesure en bits. Plus la clé est grande, plus elle contribue
à élever la sécurité à la solution. Toutefois, c´est la combinaison
d´algorithmes et de clés qui sera la garantie d´une solution bien
sécurisée. Les clés doivent être stockées de manière sécurisée et de
manière à ce que seul leur propriétaire soit en mesure de les atteindre
et de les utiliser.

### Cryptosystème

Un cryptosystème est une solution globale de cryptographie. Ce système
comprend donc non seulement l´algorithme de chiffrement, mais aussi
toutes les clés utilisées et les protocoles nécessaires à son
fonctionnement.


La cryptographie symétrique
---------------------------

Les systèmes de chiffrement à clé privée, appelés aussi systèmes de
chiffrement symétrique, sont utilisés depuis plusieurs siècles déjà.

### Principe de base

Un expéditeur et un destinataire souhaitant communiquer de manière
sécurisée à l'aide du chiffrement symétrique doivent convenir d'une clé
et ne pas la divulguer. Dans les systèmes de chiffrement symétrique la
clé de chiffrement et la clé de déchiffrement sont identiques.

### Avantages

![](http://cases.dimsonline.com/index-quick.php?dims_op=doc_file_download&docfile_md5id=285461a4c1329d604fc9043d81afac2a)

Le chiffrement symétrique comporte un avantage majeur : sa rapidité. Il
est particulièrement adapté à la transmission de grandes quantités de
données.

### Faiblesses

Ce système nécessite la connaissance de la clé par l'émetteur et par le
destinataire. C'est la transmission de cette clé entre les intervenants
qui représente la faiblesse inhérente au système. S'ils se trouvent à
des emplacements géographiques différents, ils devront faire confiance à
une tierce personne ou un moyen de communication sécurisé.

Toute personne interceptant la clé lors d'un transfert peut ensuite
lire, modifier et falsifier toutes les informations chiffrées  avec
cette clé.

De la norme de chiffrement de données AES au code secret de Jules César,
la distribution des clés reste le problème majeur du chiffrement
symétrique. (Autrement dit, comment faire parvenir la clé à son
destinataire sans qu'aucune personne ne l'intercepte ?) Les moyens à
déployer pour garantir la distribution sécurisée des clés entre les
correspondants sont très onéreux, ce qui constitue un inconvénient
supplémentaire.\
En général il est important d'utiliser des canaux sûrs pour la
transmission de la clé comme par exemple la voie postale ou le
téléphone. Il est aussi possible d'utiliser de la cryptographie
asymétrique pour l'échange de clés.

### Exemples

En anglais on parle de : Single-key, one-key, private-key, symmetric-key
encryption.

Les principaux algorithmes à clé privée sont:

-   Blowfish

-   DES / 3DES

-   IDEA

-   RC2, RC5, RC6

-   Rijndael/AES


La cryptographie asymétrique
----------------------------

La cryptographie à clé publique est une réponse au problème de
transmission clés dans le chiffrement à clé privée. Le concept a été
introduit par Whitfield Diffie et Martin Hellman en 1975, même s'il est
communément accepté que les services secrets britanniques avaient déjà
fait cette même découverte plusieurs années auparavant, protégée en tant
que secret militaire.

### Principe de base

![](http://cases.dimsonline.com/index-quick.php?dims_op=doc_file_download&docfile_md5id=c84774827c2c9ffd28e8d38d8a308265)

La cryptographie à clé publique est un procédé asymétrique utilisant une
paire de clés pour le chiffrement, soit une clé publique qui chiffre des
données, et une clé privée ou secrète correspondante pour le
déchiffrement.

Le principe est donc de distribuer la clé publique tout en conservant la
clé privée secrète. Tout utilisateur possédant une copie de la clé
publique pourra ensuite chiffrer des informations que seul le
propriétaire de la clé privée pourra déchiffrer.

On peut également remarquer qu'il est impossible de deviner la clé
privée à partir de la clé publique.

C'est l'ensemble de ces constatations qui fait que l'on appelle ce
système «asymétrique».

Il est à noter que la clé privée peut être aussi utilisée pour le
chiffrement; c'est alors la clé publique qui est utilisée pour le
déchiffrement. Cette propriété est utilisée, non pas pour la
confidentialité mais pour pour la signature électronique (intégrité).

### Avantages

La cryptographie à clé publique présente un avantage majeur : elle
permet d'échanger des messages de manière sécurisée sans aucun
dispositif de sécurité annexe.

En effet l'expéditeur et le destinataire n'ont plus besoin de partager
des clés secrètes via une voie de transmission sécurisée. Les
communications impliquent uniquement l'utilisation de clés publiques et
plus aucune clé privée n'est transmise ou partagée.

Le chiffrement à clé publique représente une révolution technologique
qui offre à tout citoyen la possibilité d'utiliser une cryptographie
robuste. En effet, la cryptographie symétrique était auparavant la seule
méthode de transmettre des informations secrètes. Les coûts de
transmission et de distribution sécurisée des clés avaient cantonné son
utilisation aux institutions disposant de moyens suffisants, telles que
gouvernements et banques.

### Exemples de cryptographie à clé publique

Elgamal (d'après le nom de son inventeur, Taher Elgamal), RSA (d'après
le nom de ses inventeurs, Ron Rivest, Adi Shamir et Leonard Adleman),
Diffie-Hellman (également d'après le nom de ses inventeurs) et DSA,
l'algorithme de signature numérique (élaboré par David Kravitz), sont
des exemples de systèmes de cryptographie à clé publique.

Un exemple pratique de la cryptographie à clé publique est
OpenPGP pour chiffrer le courrier électronique ou le
TLS (https) pour chiffrer les communications web; le TLS utilise la
cryptographie à clé publique pour l'échange de clés, puis la
cryptographie symétrique pour chiffrer la communication.


Politique de sécurité
---------------------


Rédigez et faites applique une politique sectorielle pour:


-   [Classification et maîtrise des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources.markdown %})
    -   [Classification et responsabilité des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources.markdown %}#classification-and-responsibility-for-resources)
-   [Aspects humains]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown %})
    -   [La formation et l’information]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown %}#training-and-information)
-   [Sécurité physique et environnementale]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %})
    -   [Sécurité des équipements hors des locaux]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %}#off-site-equipment-security)
-   [Aspects opérationnels et communications]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %})
    -   [Procédures documentées]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}#documentation-of-procedures)
    -   [Sauvegarde des données]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}#data-backups)
    -   [Sécurité des médias pendant les transports]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}#device-security-during-transport)
    -   [Courrier électronique]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}#email)
-   [Contrôle d’accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %})
    -   [Politique de contrôle d'accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#access-control-policy)
    -   [Utilisation de réseaux externes]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#use-of-external-networks)
    -   [Connexion de l’extérieur]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#external-connections)
-   [Développement et maintenance des systèmes]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.markdown %})
    -   **[Utilisation de l'encryption]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.markdown %}#encryption)**
    -   [La signature électronique]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.markdown %}#electronic-signatures)
-   [Conformité]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance.markdown %})
    -   [Protection des données opérationnelles]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance.markdown %}#protection-of-operational-data)
    -   [Protection des données à caractère personnel]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance.markdown %}#personal-data-protection)
