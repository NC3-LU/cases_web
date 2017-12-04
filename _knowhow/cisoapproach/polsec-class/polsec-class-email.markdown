---
layout: articlesmall
title:  "Recommandations pour sécuriser un serveur E-Mail"
menutitle:  
logo:
date:   2017-11-06 00:00:00 +0100
short: "Renforcez vos défenses. Organisez votre protection."
categories: knowhow
toc: false
---
## En quelques mots

Les serveurs mail sont des serveurs particuliers dans le sens qu'au moins une partie doit être branchée à Internet et qu'il est soumis à énormément de messages qui ne sont pas forcément bienveillants. Comme expliqué dans l'article sur les e-mails ce serveur peut être divisé en une ou deux parties dont au moins la partie MTA (Mail Transfer Agent) doit être branchée sur Internet. De ce fait il est recommandé aussi de suivre les recommandations générales pour les serveurs branchés sur Internet.

## Mesures de sécurité

1. Il est fortement recommandé d'utiliser un antivirus pour scanner les e-mails transitant par le serveur. Ceci afin de protéger les destinataires des codes malicieux. Le logiciel d'analyse antivirus doit être régulièrement mis à jour pour pouvoir reconnaître les derniers codes malicieux et les supprimer. Rédigez et faites respecter une Politique sectorielle sur Aspects opérationnels et communications - protection contre les logiciels malicieux
2. Il est fortement recommandé d’utiliser un logiciel antivirus différent pour le serveur e-mail et pour les postes des agents. Ceci augmente la probabilité de détection d'un virus.
3. Il est fortement recommandé d’activer un filtre spam au niveau du serveur. Rédigez et faites respecter une Politique sectorielle liée aux Aspects opérationnels et communications - courrier électronique
4. Il est fortement recommandé de configurer le serveur e-mail pour empêcher tout relais d'e-mails. Ainsi, les utilisateurs malicieux venant d'Internet ne peuvent pas utiliser le serveur mail pour envoyer des messages en profitant de sa fonction de relais de messagerie.
5. Il est recommandé de séparer le serveur MTA ("Mail Transfer Agent") et le serveur MDA ("Mail Delivery Agent"). Le MTA devrait se trouver dans la DMZ et le MDA à l’intérieur du réseau de l’entité. Ainsi le firewall entreprise peut être configuré pour offrir un maximum de sécurité. Rédigez et faites respecter une Politique sectorielle pour le contrôle d'accès - Connection de l'extérieur et séparation de réseaux
6. Il est fortement recommandé d’appliquer une procédure de création et de désactivation de comptes e-mail. Les comptes utilisateurs sont créés à l'arrivée de chaque nouvel agent. Au départ ou lors de la mutation d'un agent, son  ancien accès à la messagerie électronique est fermé et son compte d'accès désactivé, afin qu'il ne puisse pas continuer à envoyer et recevoir de messages électroniques en utilisant l'ancienne adresse. Rédigez et faites respecter une Politique sectorielle liée aux aspects humains et une Politique sectorielle pour le contrôle d'accès - Politique de contrôle d'accès et Gestion des droits d'accès
7. Il est fortement recommandé de rédiger une charte de bon usage de la messagerie électronique et de la porter à la connaissance de tous les utilisateurs. Ceux-ci doivent la respecter pour le bien de tous. Rédigez et faites respecter une Politique sectorielle liée aux aspects humains ainsi qu’une Politique sectorielle liée aux Aspects opérationnels et communications - Courrier électronique
8. Il est fortement recommandé de former tous les agents aux risques inhérents à l’utilisation des courriers électroniques.
9. Il est recommandé de mettre en place des fonctionnalités de chiffrement si des contenus internes ou confidentiels doivent être transférés via e-mail. Rédigez et faites respecter une Politique sectorielle Développement et maintenance des systèmes - Utilisation de chiffrement
10. Il est fortement recommandé de mettre en place un méthode de combat de SPAM comme le SPF, DKIM ou DMARC.
