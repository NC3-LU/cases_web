---
layout: article
title:  "Authentication"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: knowhow
toc: true
ref: glossaryauthentication
lang: fr
---


En quelques mots
----------------

Les êtres humains ont une capacité innée à reconnaître leurs congénères,
une grande partie de notre société repose sur cela. Ils possèdent un
système d’identification très évolué et à facteurs multiples tels que
l’apparence, la voix, la manière de parler, la posture, etc.

Cette habileté humaine est quelque chose qui manque cruellement aux
ordinateurs. Bien qu’il existe certains systèmes automatisés de
reconnaissance faciale, ceux-ci sont loin d’être au point. Le "secret
partagé", c’est-à-dire le mot de passe, reste donc le facteur
d’authentification prépondérant pour un ordinateur. Cependant les
facteurs d’authentification sur machine sont encore bien éloignés de nos
facultés naturelles à reconnaître les personnes et représentent ainsi
souvent le maillon faible de la sécurité de l’information. En effet,
l’authentification est loin d’être une procédure prise au sérieux par
les êtres humains. Elle est plutôt considérée par la plupart d'entre
nous comme un mal nécessaire. Pourtant, c’est souvent la seule
protection que les utilisateurs ont face à l’utilisation frauduleuse de
leur identité en ligne.


Facteurs d’une authentification
-------------------------------


L'authentification sur un ordinateur se fait par différentes manières,
classées ici selon 4 facteurs :

### Authentification par quelque chose que vous savez

Il s'agit généralement d'une authentification par mot de passe ou par
code pin. L'avantage de cette manière de s'identifier réside dans la
simplicité de sa mise en œuvre et dans le fait que la plupart des gens
sont familiers avec cette forme d'authentification. Les inconvénients
sont cependant multiples:

-   Un [mot de passe]({% link _knowhow/glossary/Password.markdown %}) peut
    facilement être copié à l'insu de l'utilisateur légitime. L'on peut
    se faire voler son mot de passe par exemple lors d'une attaque de
    type '[codes malicieux]({% link _knowhow/bestpractices/MaliciousSoftwareBP.markdown %})' ou
    '[phishing]({% link _knowhow/glossary/Phishing.markdown %})' ; en les
    sauvegardant sur un site web non sécurisé par
    [SSL]({% link _knowhow/glossary/SSLTLS-EncryptionTechnologiesOnWeb.markdown %})
    ; ou encore par le simple fait que quelqu'un regarde par-dessus
    votre épaule et note votre mot de passe lorsque vous l'inscrivez
    ('shoulder surfing').

-   Beaucoup de personnes utilisent des mots de passe faciles à deviner
    par autrui, comme le montre notamment l'[étude faite suite à
    l'exfiltration des mots de passe du site
    rockyou.com](http://www.imperva.com/docs/WP_Consumer_Password_Worst_Practices.pdf).

-   Beaucoup de personnes utilisent le même mot de passe pour plusieurs
    applications. Si un agresseur arrive à compromettre l'une de ces
    applications en utilisant votre mot de passe, il ne tardera pas à
    essayer ce même mot de passe pour s'infiltrer dans les autres
    applications.

### Authentification par quelque chose que vous possédez

Cette manière d'authentification se réalise généralement grâce à une clé
permettant un accès physique à l'ordinateur; à une carte cryptographique
que l'on garde le plus souvent dans son portefeuille ; ou encore grâce à
une carte du type 'TAN'.

Le niveau de sécurité de cette manière d'identification dépend de la
facilité à faire des copies de l'outil concerné.

Il est par exemple très facile de copier une carte TAN (par photo, par
photocopieuse) ; il est également facile de faire une double d'une clé.

Par contre, il est impossible de faire une copie d'une carte
'[LuxTrust](https://www.luxtrust.lu/fr/product_page/30)'. Les avantages
d'un tel système d'authentification sont:

-   la certitude d'avoir une carte non-reproductible

-   trois essai erronés mènent au blocage de la carte

-   lors d'une perte, la carte peut être révoquée et ne fonctionnera
    plus, même si le voleur est en possession du code PIN

### Authentification par quelque chose que vous êtes

Il s'agit ici de l'authentification par empreinte digitale, ou encore la
reconnaissance par la disposition de vos veines dans votre main ou
l'image de votre rétine.

### Authentification par quelque chose que vous savez faire

Il s'agit ici le plus souvent de faire copier à l'utilisateur un mot
déformé (les fameux champs « captcha », où l’on vous demande de recopier
un mot par exemple). Cette manière d'identification permet surtout de
différencier les êtres humains des ordinateurs, et non les êtres humains
entre eux, car la plupart des compétences humaines sont partagées par de
larges groupes de la population et l’identification ne serait de ce fait
pas être univoque.



Authentification par facteurs multiples
---------------------------------------

L'on comprend par
[authentification]({% link _knowhow/glossary/Authentication_fr.markdown %}) à
facteurs multiples, l'utilisation d'au moins deux des trois premiers
facteurs d'authentification. Il va de soi que plus on utilise de moyens
d'authentification, plus on augmente le niveau de sécurité de l'accès
aux informations.

N'oublions pas non plus que plus un bien ou service en ligne attire
l'intérêt d'un [attaquant]({% link _knowhow/glossary/Cybercriminals_fr.markdown %}),
plus celui-ci mettra en oeuvre les efforts pour y arriver. C'est pour
cette raison, que les services en ligne sont sécurisés selon différents
niveaux. L'idéal pour la sécurité d'accès serait biensûr de toujours
utiliser des authentifications à facteurs multiples. Malheureusement le
coût de la mise en oeuvre, l’accessibilité à la technologie et
l'évolution constante des solutions liées à la sécurité, font que
actuellement ce comportement n'est pas encore une réalité auprès des
utilisateurs. Peu de gens possèdent un lecteur d’empreintes digitales et
moins encore sont prêts à le transporter lors de leurs déplacements.
C’est pour ces raisons que la forme la plus répandue d’authentification
est celle du mot de passe, c’est-à-dire celle où l'utilisateur partage
avec son ordinateur une information secrète et identifiable par
celui-ci.


Politique de sécurité
---------------------


Rédigez et faites appliquer les politiques sectorielles:

-   [Classification et maîtrise des
    ressources](https://www.cases.lu/fr/polsec-classification-et-maitrise-des-ressources.html)
    -   [Classification et responsabilité des
        ressources](https://www.cases.lu/fr/polsec-classification-et-maitrise-des-ressources.html&WCE_section_206_1=1&WCE_section_206_1=1#579)
-   [Contrôle
    d’accès](https://www.cases.lu/fr/polsec-controle-d-acces.html)
    -   [Politique de contrôle
        d’accès](https://www.cases.lu/fr/polsec-controle-d-acces.html&WCE_section_265_1=1&WCE_section_265_1=1#596)
    -   [Gestion des droits
        d’accès](https://www.cases.lu/fr/polsec-controle-d-acces.html&WCE_section_265_1=2&WCE_section_265_1=2#597)
    -   [Gestion des mots de
        passe](https://www.cases.lu/fr/polsec-controle-d-acces.html&WCE_section_265_1=3&WCE_section_265_1=3#598)
    -   [Procédure de
        connexion](https://www.cases.lu/fr/polsec-controle-d-acces.html&WCE_section_265_1=7&WCE_section_265_1=7#602)
