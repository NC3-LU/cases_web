---
layout: articlesmall
title:  "Sécuriser le poste fixe"
menutitle:  
logo:
date:   2017-11-06 00:00:00 +0100
short: "Renforcez vos défenses. Organisez votre protection."
categories: knowhow
toc: false
---
## En quelques mots

De nos jours, pratiquement tous les ordinateurs sont connectés à l'Internet. De ce fait les conseils ci-dessous peuvent donc être appliqués à tous les postes de travail usuels. Il est illusoire de vouloir atteindre une sécurité absolue, nous nous bornerons donc à quelques mesures de sécurité prioritaires, mais il est évident qu'en fonction de la sensibilité des données manipulées, il faudra potentiellement resserrer la sécurité des postes.

La situation des ordinateurs portables étant spécifique un article leur est dédié.

## Mesures de base

1. Chaque ordinateur connecté à Internet doit disposer d'un logiciel antivirus qui prévient l'infection par des logiciels malveillants reçus dans des courriers électroniques respectivement sur des supports amovibles ou encore téléchargés sur des sites web malicieux. Rédigez et faites respecter au sein de votre organisation, une Politique sectorielle sur Aspects opérationnels et communications - protection contre les logiciels malveillants.
2. Chaque ordinateur connecté à Internet doit être doté d'un firewall personnel. Les systèmes d'exploitation modernes ont presque tous un firewall intégré et celui-ci peut suffire dans beaucoup de cas. Si vous désirez une protection supplémentaire optez pour une solution préconfigurée, qui ne demandera aucune interaction avec l'utilisateur ; ces firewalls peuvent même dans certains cas prévenir l'extraction de données par des chevaux de Troie. Rédigez et faites respecter au sein de votre organisme, une Politique sectorielle pour le contrôle d'accès - Connextions de l'extérieur et Séparation de réseaux.
3. Chaque ordinateur connecté à Internet doit être tenu à jour de façon régulière. La mise-à-jour du système d'exploitation ainsi que de tous les logiciels installés peut prévenir l'exploitation de vulnérabilités techniques dans le but de compromettre la machine (logigiels malveillants ou infections en navigant sur des sites web malicieux) Rédigez et faites respecter une politique sectorielle de développement et maintenance des systèmes - gestion des vulnérabilités techniques.
4. Il est fortement recommandé de ne pas utiliser des comptes d'utilisateur de type administrateur sur votre poste de travail. Le compte administrateur a tous les droits et peut donc mener en cas de compromission à l'infection de tout l'ordinateur. Par contre lors de la compromission d'un compte utilisateur ayant des droits restreints, le logiciel malveillant, ayant lui aussi des droits restreints, sera bloqué dans son installation. Politique sectorielle pour le contrôle d'accès - Politique de contrôle d'accès et Gestion des droits d'accès.
5. Il est fortement recommandé de mettre en place des moyens cryptographiques pour la communication sécurisée de données confidentielles avec des tiers. Les utilisateurs communiquant avec l'extérieur doivent connaître le niveau de classification des informations, doivent pouvoir identifier avec certitude leur interlocuteur et choisir des moyens de protection correspondant aux besoins de sécurité de l'information envoyée. Rédigez et faites respecter  au sein de votre organisme une Politique sectorielle Développement et maintenance des systèmes - Utilisation du chiffrement.
6. Il est fortement recommandé d’utiliser des méthodes d'authentification adaptées au niveau de classification des actifs que vous traitez lors des connexions avec l'ordinateur. Protégez consciencieusement ces moyens d'authentification. Protégez-les contre la copie et le vol. Tous les mots de passe et PIN que vous utilisez, choisissez-les avec prudence et ne les révélez pas. Les mots de passe doivent être conformes aux directives de la politique d'accès de votre organisme. Rédigez et faites respecter une Politique sectorielle pour le contrôle d'accès - Gestion des mots de passe et Procédures de connexion et Connextions de l'extérieur
7. Il est fortement recommandé de sensibiliser les utilisateurs aux risques liés à l'ingénierie sociale (social engineering) utilisés lors d'attaques de type humain. Les utilisateurs doivent pouvoir reconnaître des attaques qui cherchent à extraire des informations confidentielles par des demandes d'informations illicites via courrier électronique, par téléphone ou encore sur des réseaux sociaux. Chaque utilisateur doit donc aussi connaître le niveau de classification des informations qu'il détient ou traite. Rédigez et faites respecter au sein de votre organisme une Politique sectorielle pour la Classification et maîtrise des ressources.
8. Créez des sauvegardes pour vos informations et logiciels importants ou vitaux. Protégez ces sauvegardes contre des menaces environnementales comme notamment le feu ou l'eau. Protégez les sauvegardes contre le vol, la copie et l'altération illicite. Testez la restauration de ces sauvegardes. Rédigez et faites respecter au sein de votre organisme une Politique sectorielle sur les Aspects opérationnels et communications - Sauvegarde des données ainsi qu'une politique sectorielle pour la Sécurité physique et environnementale - Périmètre de sécurité physique et Règles dans le périmètre.
9. Si l'ordinateur contient des données classées sensibles voire confidentielles il peut être utile de chiffrer le disque dur. Dans ce contexte il est recommandé d'utiliser une méthode d'authentification forte (mot de passe très long, stick contenant la clé de chiffrement,...) pour le déchiffrement du disque.

## Quick wins windows

1. Utilisez des systèmes 64bit qui améliorent la sécurité du système (le windows 64bit n'accepte que les pilotes signés).
2. Il est fortement recommandé de mettre en place un système automatique de mise à jour. La solution proposée par Microsoft, le serveur WSUS, peut facilement être étendu (grâce à des logiciels tiers) pour mettre à jour tous les logiciels présents sur les machines.
