---
layout: publication-list
category: "In depth articles"
title:  "Recommandations pour sécuriser un serveur web"
menutitle: "Recommandations pour sécuriser un serveur web"
logo:
date:  2017-11-06 00:00:00 +0100
short: "Security measures for securing a web server"
categories: securing
toc: true
ref: recommendations4securingwebserver
lang: fr
---
## Considérations de base
Un serveur web est un serveur connecté en permanence à l'Internet. Il est donc conseillé de suivre les [recommandations pour sécuriser les serveurs connectés à l'Internet]({% link _publications/recommendationsecuring/Recommendations4securingServerConnectedInternet_fr.markdown %}).

## Mesures de sécurité

* Les serveurs web ont la particularité de servir des applications web sur l'Internet. Souvent le niveau de sécurité de ces applications est peu ou pas connue. Il est donc important d'empêcher, voire de limiter l'étendue des dégâts en cas de compromission :
    - veillez à ce que vos applications aient un degré de sécurité maximal en effectuant des tests de pénétration au préalable ;
    - installez un parefeu applicatif comme Microsoft Forefront, Modsecurity ou Naxsi pour IIS, Apache et Nginx respectivement ;
    - limitez les droits de l'application serveur web, si possible contenez la dans un espace d'exécution restreint ;
    - pensez à faire appliquer des [règles de bonne pratique]({% link _publications/recommendationsecuring/SecurityChecklistForPHPWebApplications_fr.markdown %}) à vos développeurs.
* Certaines applications web permettent de télécharger sur le serveur des fichiers de n'importe quel type. Il est important de tester les fichiers ainsi téléchargés avec un antivirus.
* En cas d'utilisation de bases de données sur le serveur même, pensez à restreindre son accès aux utilisateurs locaux.
* Pensez à l'installation de modules protégeant des dénis de service.
* Vérifiez vos fichiers journal régulièrement pour découvrir toute anomalie.
