---
layout: article
title:  "Recommendations to secure a Web server"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: knowhow
ref: glossaryrecomm4securingwebserver
lang: en
hidden: true
---
Considérations de base
----------------------
Un serveur web est un serveur connecté en permanence à l'Internet. Il
est donc conseillé de suivre les [recommandations pour sécuriser les
serveurs connectés à
l'Internet](https://www.cases.lu/fr/recommendations-pour-securiser-un-serveur-connecte-a-internet.html).


Mesures de sécurité
-------------------

1.  Les serveurs web ont la particularité de servir des applications web
    sur l'Internet. Souvent le niveau de sécurité de ces applications
    est peu ou pas connue. Il est donc important d'empêcher, voire de
    limiter l'étendue des dégâts en cas de compromission:
    1.  veillez à ce que vos applications aient un degré de sécurité
        maximal en effectuant des tests de pénétration au préalable;
    2.  installez un parefeu applicatif comme Microsoft Forefront,
        Modsecurity ou Naxsi pour IIS, Apache et Nginx respectivement;
    3.  limitez les droits de l'application serveur web, si possible
        contenez la dans un espace d'exécution restreint;
    4.  pensez à faire appliquer des [règles de bonne
        pratique](https://www.cases.lu/fr/checklist-securite-pour-les-applications-web-en-php.html)
        à vos développeurs.
2.  Certaines applications web permettent de télécharger sur le serveur
    des fichiers de n'importe quel type. Il est important de tester les
    fichiers ainsi téléchargés avec un antivirus.
3.  En cas d'utilisation de bases de données sur le serveur même, pensez
    à restreindre son accès aux utilisateurs locaux.
4.  Pensez à l'installation de modules protégeant des dénis de service.
5.  Vérifiez vos fichiers journal régulièrement pour découvrir toute
    anomalie.
