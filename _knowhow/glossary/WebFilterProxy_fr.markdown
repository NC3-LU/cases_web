---
layout: article
title:  "Filtre web - Proxy"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: knowhow
toc: true
ref: glossarywebfilterproxy
lang: fr
---
## En quelques mots
Bon nombre de sites web (licites et illicites) librement accessibles sur l'Internet proposent des contenus malicieux, inappropriés, prohibés ou nuisibles à la productivité. L'accès à des [sites malicieux]({% link _knowhow/glossary/MaliciousWebsites_fr.markdown %}) peut avoir comme conséquence l'installation de [codes malicieux]({% link _knowhow/glossary/MaliciousCodes_fr.markdown %}) à l'insu de utilisateur. Quant à l'accès à des contenus prohibés ou illégaux, il peut engendrer la [responsabilité légale]({% link _knowhow/glossary/Impact_fr.markdown %})  

Pour prévenir l'accessibilité des employés à de tels sites, l'organisme peut installer un filtre web comme moyen de protection.

Techniquement parlant ces filtres sont appelés «proxy web» et peuvent se présenter sous plusieurs formes. Les proxy libres les plus connus sont «squid et squidguard», «DansGuardian» ou encore «HAVP» qui se retrouvent dans un grand nombre de produits firewall libres ou commerciaux.

## Fonctionnement
Un filtre web analyse toutes les communications (contenus et/ou destinataires) vers et depuis l'Internet pour détecter des échanges avec des sites hébergeant des contenus malicieux, inappropriés ou prohibés. Ce filtre ne doit pas être confondu avec le [filtre phishing]({% link _knowhow/glossary/Phishing_fr.markdown %}), du navigateur, car contrairement à ce dernier qui est installé dans le navigateur de l'utilisateur, le filtre web tourne sur un serveur dédié et ne peut pas être facilement contourné par l'utilisateur.

### Analyse des URL
Un filtre web qui analyse les URL dispose d'une base de données qui associe des URL avec des catégories de contenus. Ces bases de données sont gérées par des sociétés spécialisées qui associent les sites à différentes catégories, comme notamment les sites pornographiques, de jeux, de jeux d'argent et ainsi de suite.

Dès qu'un nouveau site est découvert, il est catégorisé et, si besoin, ajouté à la base de données. Ce type de filtrage ne protège pas contre l'accès à des sites tout neufs, non encore catégorisés, respectivement l'accès à des sites récemment devenus malicieux.

L'organisme peut néanmoins filtrer différentes catégories de contenus, tels que les sites pornographiques, jeux d'argent, réseaux sociaux ...

### Analyse de contenus
Certains filtres web sont capables d'analyser le contenu d'un site web qu'un utilisateur souhaite visiter. Sur base d'une liste de mots clés, le filtre attribue une catégorie aux sites visités, et affiche ou n'affiche pas le contenu demandé. Ce filtre est efficace pour protéger contre les contenus récents pour lesquels l'analyse par URL n'aurait pas marché, mais peut produire beaucoup de faux positifs.

### Analyse de contenus malicieux
Certains filtres contiennent des antivirus et peuvent analyser le contenu des sites visités et bloquer l'accès à d'éventuels [logiciels malicieux]({% link _knowhow/bestpractices/MaliciousSoftwareBP_fr.markdown %}).

### Analyse d'images
Certains filtres web sont capables d'analyser les images demandées. Le filtre sélectionne les images du site visité et les attribue selon certaines catégories avant d'en afficher le contenu ou non.

## Politique de sécurité
Rédigez et faites appliquer les politiques sectorielles suivantes :

* [Classification et maîtrise des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %})
  * [Classification et responsabilité des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %}#classification-and-responsibility-for-resources)
* [Aspects humains]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %})
  * [La formation et l’information]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %}#training-and-information)
  * [La réponse aux incidents et disfonctionnements de sécurité]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %}#response-to-incidents-and-malfunctions)
* [Aspects opérationnels et communications]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %})
  * [Procédures documentées]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#documentation-of-procedures)
  * [Protection contre les logiciels malveillants]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#protection-against-malware)
  * [Courrier électronique]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#email)
* [Contrôle d’accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %})
  * [Politique de contrôle d’accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-control-policy)
  * [Gestion des droits d’accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-rights-management)
  * **[Utilisation des réseaux externes]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#use-of-external-networks)**
  * [Séparation de réseaux]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#separation-of-networks)
* [Conformité]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %})
  * [Protection des données à caractère personnel]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %}#personal-data-protection)
