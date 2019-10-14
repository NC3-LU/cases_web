---
layout: knowhow
category: "Knowhow"
title:  "Logiciels malveillants : bonnes pratiques"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short: "Mesures comportementales pour prévenir de l'infection"
categories: f-bestpract
toc: true
ref: malicioussoftwarebp
lang: fr
---
## En quelques mots

Les logiciels malveillants représentent une des plus grandes [menaces]({% link _knowhow/glossary/Threat_fr.markdown %}) pour tout système d'information, indépendamment de sa taille. Tout type de système d'exploitation est concerné, et toutes les administrations, communes et entreprises peuvent y succomber.

Depuis leur existence, les [cybercriminels]({% link _knowhow/glossary/Cybercriminals_fr.markdown %}) ont fortement développé leur manière de travailler et de cibler les victimes ; les logiciels malveillants ou malware, un de leurs principaux outils, ont tout naturellement bénéficié de cette situation. Ainsi vous ne trouverez plus de nos jours de logiciels malveillants écrits à dessein purement ludique. Actuellement les codes malicieux les plus utilisés sur le marché sont différentes variantes de [chevaux de Troie]({% link _knowhow/glossary/MaliciousCodes_fr.markdown %}#cheval-de-troie), qui donnent accès aux machines pour les utiliser soit à des fins illicites, soit pour en dérober des informations confidentielles.

TAujourd'hui, les codes malicieux servent avant tout à :

* dérober des informations confidentielles (extraction de données),
* attaquer des systèmes de e-banking,
* envoyer du [spam]({% link _knowhow/glossary/SPAM-UnwantedEmails_fr.markdown %})/[phishing]({% link _knowhow/glossary/Phishing_fr.markdown %}) (PME : voir [Spam]({% link _knowhow/glossary/SPAM-UnwantedEmails_fr.markdown %})/[Phishing]({% link _knowhow/glossary/Phishing_fr.markdown %}) et [Ingénierie sociale/Communication inadéquate]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2HR_fr.markdown %}#manipulation-of-people))
* perpétrer des attaques de type déni de service (PME : voir [Attaques par déni de service et déni de services distribués]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure_fr.markdown %}#denial-of-servicedistributed-service)),
* héberger des contenus illicites

Ils présentent donc une [menace]({% link _knowhow/glossary/Threat_fr.markdown %}). importante et omniprésente. Sans mesures préventives, mesures de protection et mesures curatives, une entité risque des [impacts]({% link _knowhow/glossary/Impact_fr.markdown %}) considérables.

## Les vecteurs d'infection

Il existe de nombreux moyens pour infecter une machine. Les plus couramment utilisés sont :

* infecter des sites web licites, (de préférence à grande fréquentation). Ils subissent des attaques opportunistes ou ciblées. L'agresseur va profiter des [vulnérabilités techniques]({% link _knowhow/glossary/Vulnerabilities_fr.markdown %}#technical-vulnerabilities), du site, souvent mal géré, respectivement essayer d'accéder au système de gestion du site, en exploitant des mots de passe par défaut, ou dont la sécurité est faible. Il installe ensuite ses outils pour pouvoir exploiter des vulnérabilités techniques dans les navigateurs des visiteurs, respectivement inciter les utilisateurs à installer eux-mêmes des codes malicieux (exemple : faux [þantivirus]({% link _knowhow/glossary/AntiVirus_fr.markdown %}) ou faux lecteurs de vidéos).
* [sites web malicieux]({% link _knowhow/glossary/MaliciousWebsites_fr.markdown %}) spécialement conçus pour exploiter les vulnérabilités techniques des navigateurs des visiteurs. Puisque ces sites sont inconnus par les visiteurs, l'agresseur doit l'attirer à s'y rendre. Pour ce faire, il va :
  * leurrer la victime en lui envoyant des [Spam]({% link _knowhow/glossary/SPAM-UnwantedEmails_fr.markdown %}) contenant des liens ;
  * leurrer la victime par des attaques de type [phishing]({% link _knowhow/glossary/Phishing_fr.markdown %}) ;
  * leurrer les victimes par des publicités affichées sur des sites à grande fréquentation.
* [courriers électroniques]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#email) avec des pièces jointes infectées. Cette technique est utilisée autant pour des attaques ciblées que pour des attaques opportunistes. Des méthodes issues de l'ingénierie sociale servent à manipuler les victimes pour ouvrir des fichiers infectés.
* [supports amovibles]({% link _knowhow/glossary/RemovableDevices_fr.markdown %}) contenant des fichiers infectés. Les codes malicieux exploitent les vulnérabilités techniques des machines visées. Ce moyen est surtout utilisé pour des attaques ciblées, en employant des techniques d'ingénierie sociale.

## Les impacts

L'existence de codes malicieux étant omniprésente, la probabilité d'y être confronté est extrêmement grande ([menaces]({% link _knowhow/glossary/Threat_fr.markdown %}) EBIOS: écoute à distance, piégeage du logiciel).

Les [impacts]({% link _knowhow/glossary/Impact_fr.markdown %}) causés se situent généralement au niveau d'un :

* Impact financier
  * L'accès à des applications d'e-banking peut résulter en une perte d'argent. Veillez à contrôler notamment les applications de type "multi-line", puisque les mouvements de comptes des entreprises sont fréquents et les manipulations ne sont souvent détectées qu'après quelques jours voir semaines.
  * La perte de données confidentielles (vol de propriété intellectuelle, vol de secrets de fabrication, vol de données stratégiques de l'entreprise, vol de données clients) résulte souvent en une perte d'argent.
* Impact juridique
  * Si les machines infectées sont utilisées à des fins illicites, la victime peut se voir confrontée à des plaintes (attaques de déni de service, infection des machines des visiteurs, hébergement de contenus illégaux,...).
  * La perte de données confidentielles, comme notamment des données à caractère personnel peut engendrer des plaintes de la part des victimes respectivement de la CNPD.
* Impact sur la réputation
  * Le fait qu'un site web d'une organisation soit utilisé pour infecter les machines des visiteurs peut engendrer de sérieux problème au niveau de son image de marque. Au même titre que tout commerce, le commerce électronique vit de la confiance des consommateurs. Un incident de sécurité peut avoir impact néfaste sur celle-ci.
* Impact sur le «savoir faire»
  * Le vol, respectivement la destruction de données relatives aux données clients, ou aux secrets de fabrication,  peut résulter en une perte de savoir-faire.
* Impact sur le «temps»
  * L'analyse du système compromis, ainsi que le rétablissement des machines infectées peut engendrer une importante perte de temps.


## Mesures comportementales

Que ce soit pour perpétrer une attaque ciblée ou opportuniste, un grand nombre de codes malicieux pénètrent sur les machines des victimes via des vecteurs d'infection se servant des [vulnérabilités humaines]({% link _knowhow/glossary/Vulnerabilities_fr.markdown %}#human-vulnerabilities).

Avant de publier un logiciel malveillant, les auteurs vérifient s'il est détectable via des sites tels que [www.virtest.com](https://www.virtest.com).

Les codes restent ensuite souvent invisibles aux logiciels antivirus, du moins pendant les premiers jours de l'attaque, le temps nécessaire aux antivirus de se munir de signatures mises à jour.

Il est donc primordial pour toute organisation de sensibiliser et de former ses employés aux risques engendrés par les codes malicieux, ainsi qu'aux vecteurs d'infection couramment utilisés.

## Prévenir l'infection

​La prévention à l'infection par codes malicieux passe par l'adoption d'un comportement responsable et prudent lors de la manipulation de [courriers électroniques]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#email), de [supports amovibles]({% link _knowhow/glossary/RemovableDevices_fr.markdown %}) et lorsque l'on navigue sur l'Internet.

Veillez à :

* respecter les [bonnes pratiques liées aux courriers électroniques]({% link _knowhow/bestpractices/EMail-BestPractices_fr.markdown %})
* évitez l'utilisation de supports amovibles inconnus.
  * Si vous trouvez de tels supports, transmettez-les pour analyse à votre service informatique.  
  * Si vous reçevez des supports amovibles lors de conférences, faites-les d'abord analyser par des experts avant de vous en servir.
  * Si l'on vous envoie des supports amovibles, soyez très prudents. Ne les utilisez pas si l'expéditeur vous est inconnu. Dans le cas contraire, assurez-vous que ce soit bien lui qui vous les a transmit, et faites également analyser ces supports par des experts avant toute utilisation.

En surfant sur l'Internet :

* ouvrez uniquement les liens proposés par des sites dans lesquels vous avez entièrement confiance. Dans les autres cas, vous risquez de tomber sur des sites [web malicieux]({% link _knowhow/glossary/MaliciousWebsites_fr.markdown %}).
* soyez attentifs aux avertissements donnés par votre navigateur web ("safe browsing" pour [IE](https://www.microsoft.com/en-us/security/default.aspx), [Firefox](https://support.mozilla.org/en/US/kb/use-master-password-protect-stored-logins), [Chrome](https://support.google.com/chrome/answer/114836?hl=en&ref_topic=7437824)), respectivement des ajouts comme WOT.
* soyez prudents quant aux publicités affichées sur des sites dans lesquels vous n'avez pas une entière confiance. Ils peuvent contenir des codes malicieux, respectivement vous amener sur des sites [web malicieux]({% link _knowhow/glossary/MaliciousWebsites_fr.markdown %}).

Lors de voyages ou de déplacements, veillez à :

* surveiller votre matériel informatique. Des personnes malintentionnées pourraient essayer de le piéger ou d'installer des codes malicieux. ([Menaces]({% link _knowhow/glossary/Threat_fr.markdown %}) : voir piégeage de matériel, piégeage de logiciel).

Soyez également conscients que, même le matériel qui se trouve à l'intérieur de l'enceinte d'un organisme peut facilement être infecté, du moment que des personnes malintentionnées se sont procuré accès. (PME voir : [pénétration dans les locaux]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure_fr.markdown %}#infiltrating-the-premises) et [insertion ou suppression de matériel]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware_fr.markdown %}#addition-or-removal-of-hardware) et [Utilisation de logiciels non approuvés]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Software_fr.markdown %}#use-of-unapproved-software)).

## Minimiser les impacts

Chaque employé doit savoir comment réagir en cas d'infection :  

* la machine infectée doit être isolée et retirée du réseau ;
* elle ne doit plus servir tant qu'elle n'a pas été nettoyée ;
* il faut, sans délais, informer les responsables s'occupant de ce genre d'incidents.


## Mesures organisationnelles

Pour prévenir une infection par des codes malicieux, il est nécessaire de mettre en place des mesures organisationnelles. Rédigez et faites respecter les politiques sectorielles suivantes :

* [Classification et maîtrise des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %})
  * [Classification et responsabilité des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %}#classification-and-responsibility-for-resource)
* [Aspects humains]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %})
  * [La sécurité comme mission]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %}#security-as-a-mission)
  * [La formation et l’information]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %}#training-and-information)
  * [La réponse aux incidents et dysfonctionnements de sécurité]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %}#response-to-incidents-and-malfunctions)
* [Aspects opérationnels et communications]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %})
  * [Courrier électronique]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#email)
  * [Protection contre les logiciels malveillants]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#protection-against-malware)
* [Contrôle d’accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %})
  * [Politique de contrôle d’accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-control-policy)
  * [Gestion des droits d’accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-rights-management)
  * [Utilisation de réseaux externes]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#use-of-external-networks)
  * [Connexion de l’extérieur]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#external-connections)
  * [Séparation de réseaux]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#separation-of-networks)
* [Développement et maintenance des systèmes]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %})
  * [Gestion des vulnérabilités techniques]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}#managing-technical-vulnerabilities)
* [Gestion des incidents liés à la sécurité]({% link _knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents_fr.markdown %})
  * [Signalement des événements liés à la sécurité de l’information]({% link _knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents_fr.markdown %}#reporting-information-security-events)
  * [Gestion des incidents et des améliorations de la sécurité de l’information]({% link _knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents_fr.markdown %}#incident-management-and-improvements-information-security)
  * [Analyse des manquements avec obligations]({% link _knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents_fr.markdown %}#analysis-of-non-fulfilment-of-obligations)
* [Gestion de la continuité de l’entreprise]({% link _knowhow/cisoapproach/SecurityPolicy-ManagingBusinessContinuity_fr.markdown %})
  * [La continuité de fonctionnement]({% link _knowhow/cisoapproach/SecurityPolicy-ManagingBusinessContinuity_fr.markdown %}#operational-continuity)
 
## Mesures techniques

Outre les mesures comportementales et organisationnelles, il est important de mettre en place des mesures techniques pour aider à prévenir les infections, respectivement réduire l'impact d'une potentielle infection.

Il est conseillé d'installer les mesures techniques suivantes :

* [antivirus]({% link _knowhow/glossary/AntiVirus_fr.markdown %})<br />
  Les antivirus sont capables de détecter un grand nombre de codes malicieux et de prévenir une infection. Chaque ordinateur au sein de votre organisation, ainsi que les serveurs de fichier et les serveur mail doivent être munis d'antivirus. Utilisez de préférence un antivirus différent pour les ordinateurs et pour les serveurs afin d'augmenter la probabilité de détecter les codes malicieux. Mettez régulièrement à jour ces antivirus. Veillez à ce que les utilisateurs ne soient pas en mesure de désactiver l'antivirus.
* [firewall]({% link _knowhow/glossary/Firewall_fr.markdown %})<br />
  Un firewall installé sur une machine peut à la fois aider à prévenir l'infection d'une machine via des [vulnérabilités techniques]({% link _knowhow/glossary/Vulnerabilities_fr.markdown %}#technical-vulnerabilities) et aider à détecter une éventuelle infection.
* [segmentation du réseau]({% link _knowhow/glossary/NetworkSegmentation_fr.markdown %})<br />
  Un 'firewall entreprise' peut aider à prévenir une propagation sur tout le réseau de l'entreprise. Il peut également aider à prévenir l'exploitation de certaines vulnérabilités techniques grâce au filtrage de tentatives de connexion via des ports spécifiques.
* [Fltre web]({% link _knowhow/glossary/WebFilterProxy_fr.markdown %})<br />
  Les filtres web peuvent empêcher les infections des ordinateurs en empêchant de visiter des sites web malicieux ou de mauvaise réputation.
* [correctifs (patch)]({% link _knowhow/glossary/Patches_fr.markdown %})<br />
  Certains logiciels malveillants essayent d'exploiter des vulnérabilités techniques. Grâce aux correctifs, celles-ci peuvent être corrigées. Cependant aucun système n'est vraiment à l'abri d'une vulnérabilité technique.
* [sauvegardes]({% link _knowhow/glossary/DataBackups_fr.markdown %})<br />
  Les sauvegardes sont un moyen efficace pour prévenir les pertes de disponibilité et d'intégrité. Elles ne peuvent malheureusement pas prévenir la perte de confidentialité. Les sauvegardes peuvent également aider à réduire l'impact causé lors d'une compromission du système par un code malicieux destructeur.
* [cryptographie]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}#encryption)<br />
  La cryptographie peut, dans le cas d'une infection, aider à réduire la probabilité d'une perte de confidentialité de données hautement confidentielles.

## La désinfection

Voir: [SOS - je crois que mon ordinateur est infecté]({% link _knowhow/sos/SOS-IThinkMyComputerInfected_fr.markdown %})
