---
layout: article
title:  "Erreurs humaines"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: knowhow
toc: true
ref: glossaryhumanerror
lang: fr
---
En quelques mots
----------------
Considérer les erreurs humaines comme des
[menaces]({% link _knowhow/glossary/Threat_fr.markdown %}) peut sembler un peu
indélicat et pourtant, comme le montrent les statistiques publiées par
différents organismes, elles demeurent une cause très courante de
sinistres informatiques. 

On considère comme « erreur humaine », tout comportement humain ne
respectant pas le bon usage et pouvant conduire de façon involontaire à
des préjudices divers.

Types d'erreurs
---------------
On considère comme « erreur humaine », tout comportement humain ne
respectant pas le bon usage et pouvant conduire de façon involontaire à
des [préjudices]({% link _knowhow/glossary/Impact_fr.markdown %}) divers. Les
actes volontaires réalisés dans un but malveillant ne sont pas qualifiés
d'erreurs.

Il est impossible de dresser une liste exhaustive des erreurs humaines.
Bien qu’il soit impossible de quantifier toutes les possibilités en
matière d’erreurs humaines, il est toutefois possible de dresser
quelques critères distinctifs permettant de classifier les erreurs
humaines.

### Les erreurs de type négligence

On regroupe sous ce titre toutes les actions menées par des personnes
bien informées mais ne respectant pas les règles. On pourrait donc
associer la négligence à un acte volontaire. Toutefois le but de la
négligence n'est généralement pas frauduleux.

Exemples :

-   ne pas respecter les procédures prévues pour la sauvegarde des
    données (PME: voir [Sauvegardes inutilisables]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware_fr.markdown %}#unusable-backups)),
-   arrêter la mise à jour de la solution anti-virale au démarrage de la
    machine,
-   confier son mot de passe à un collègue (PME: voir [Utilisation d’un accès réservé à un utilisateur par un tiers]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2HR_fr.markdown %}#use-of-limited-access-by-a-third-party)),
-   utiliser l'architecture informatique de l'entreprise à usage privé
    (PME: voir [Utilisation abusive des ressources de l’organisation]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2HR_fr.markdown %}#misuse-of-it-resources))
-   installer un logiciel « hors norme » sur une machine, notamment
    ordinateur ou serveur (PME: voir [Utilisation de logiciels non approuvés]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Software_fr.markdown %}#use-of-unapproved-software)
    et [Administrateur malveillant]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2HR_fr.markdown %}#the-administrator)).

### Les erreurs de type incapacité
Cette catégorie regroupe toutes les erreurs commises sans en avoir
conscience. En effet, de nombreuses erreurs peuvent être commises "de
bonne foi", sans que l'utilisateur ait conscience du non-respect du bon
usage ou du règlement et sans qu'il mesure l'impact de son geste.

Exemples :

-   le « [social engineering/ingénierie sociale]({% link _knowhow/glossary/SocialEngineering_fr.markdown %}) » (voir
    point relatif à ce sujet),
-   la mauvaise utilisation de l'outil informatique,
-   l’effacement de données.


Comment cela fonctionne-t-il?
-----------------------------
Les erreurs humaines sont des menaces non intentionnelles qui exploitent
différentes vulnérabilités notamment :

### La fainéantise et l'absence de conscience professionnelle
Dans cette catégorie sont repris tous les actes commis par négligence et
contre lesquels il est très difficile de lutter, si ce n'est en agissant
au niveau de la responsabilisation et des mécanismes de sanction.

### Le manque de formation ou de sensibilisation à la sécurité
L'absence de conscientisation d'une personne représente bien sûr une
énorme vulnérabilité dont la face cachée est l'absence de prise de
conscience de l'erreur commise, et donc l'absence de détection et de
correction par la personne elle-même.

Le manque de formation et de sensibilisation à la sécurité d'une
personne présente une vulnérabilité pouvant être exploitée par une
menace hautement dangereuse qui est le [social engineering]({% link _knowhow/glossary/SocialEngineering_fr.markdown %}).


Comment se protéger?
--------------------
La loi de « non fiabilité » de Gibbs (mathématicien américain) stipule
que « Tout système qui dépend de la fiabilité de l'homme n'est pas
fiable ».

Il existe de multiples moyens de lutter contre les erreurs humaines.
Toutefois, il est conseillé de consacrer beaucoup d'énergie à la
limitation de l'impact des erreurs humaines et de ne pas partir du
principe que l'on va être en mesure d'éviter toutes les erreurs
humaines. Les principales contre-mesures sont les suivantes :

### La sensibilisation
C'est dans ce domaine qu’il est facilement possible de diminuer de
manière sensible le risque.

En effet, la majorité des êtres humains sont de bonne volonté et si on
les informe de l'importance de leurs gestes quotidiens ainsi que de la
valeur des données traitées, ils prendront à cœur de les gérer en bon
père de famille.

### La formation
Le meilleur moyen d'éviter de mauvaises manipulations au niveau des
données et des logiciels, est de former les utilisateurs sur les
logiciels et sur la manipulation des supports.

### La mise en place et le contrôle de procédures
Il est primordial de mettre en place des procédures qui couvrent tous
les aspects importants (accès, sauvegarde...) touchant à la sécurité.
Ces procédures doivent être contrôlées de façon cyclique et leur non
respect devrait entraîner des sanctions. Ces procédures font
généralement partie de la [politique de sécurité]({% link _knowhow/CISOApproach_fr.markdown %}).

### La double validation
Afin d'éviter des erreurs de saisie au niveau des logiciels critiques
(paiement électronique...), il est prudent de mettre en place une double
saisie des données ou une double validation.

### La gestion et le suivi des erreurs
La gestion et le suivi des erreurs\
Les erreurs n'étant pas entièrement inévitables, il faut en tirer les
conséquences afin de ne pas les reproduire. Seule une analyse pointue
des erreurs commises, ainsi que des causes à l’origine de ces erreurs
permet d'en éviter la répétition.

### L'administration centralisée
Pour minimiser les erreurs humaines, il est conseillé de strictement
limiter les accès aux logiciels et aux données aux seules personnes qui
en ont vraiment besoin: gestion des accès et
[authentification]({% link _knowhow/glossary/Authentication_fr.markdown %}) .
