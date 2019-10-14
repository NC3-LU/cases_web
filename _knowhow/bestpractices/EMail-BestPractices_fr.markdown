---
layout: knowhow
category: "Knowhow"
title:  "E-mail : bonnes pratiques"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short: "Mesures comportementales et techniques visant à prévenir les risques liés à l'envoi de courriels"
categories: f-bestpract
toc: true
ref: emailbestpractice
lang: fr
---
## En quelques mots

Le courrier électronique est une des principales formes de communication privée et professionnelle. L'outil est convivial, rapide et peu coûteux. Malgré les avantages, son utilisation nécessite des précautions à prendre en compte, aussi bien au niveau de l'expédition que de la réception d'un message.

S'il est vrai que l'envoi de courriers électroniques à l’intérieur d'une société ne présente pas le risque d'une écoute extérieure, quand la société possède un serveur mail interne, il faut néanmoins être conscient que les informations ainsi envoyées ne sont plus sauvegardées uniquement sur le serveur sécurisé de la société. Elles se retrouvent en effet également dans les boîtes aux lettres de l'expéditeur et du destinataire. La plupart de temps, ces ordinateurs sont physiquement et logiquement beaucoup moins protégés que les serveurs - et donc plus vulnérables à une attaque - alors qu'ils contiennent, le cas échéant, les mêmes informations, avec les mêmes niveaux de classification, que ces derniers.

L'envoi de courriers électroniques au sein d'une société est donc souvent source d'éparpillement ou de diffusion inappropriée d'informations confidentielles ou secrètes. Ces informations seraient d'avantage en sécurité, si elles étaient sauvegardées en un lieu unique et protégé, avec un accès aux informations selon leur niveau de classification.

Le problème de perte d'information est également aggravé par l'utilisation d'ordinateurs portables au sein d'une entreprise.

Pour la sécurité de la société, il serait également nécessaire de mettre en place, entre autres, des procédures spécifiques de [mise au rebut du matériel informatique]({% link _knowhow/sos/SOS-WhatBeforeGettingRidOldHardware_fr.markdown %}).

## Risques
Risques liés à l'envoi de courrier électronique

* Pertes de [confidentialité]({% link _knowhow/glossary/Confidentiality_fr.markdown %}) dues à :
  * l'envoi de données [confidentielles]({% link _knowhow/glossary/Confidentiality_fr.markdown %}) par courrier électronique (écoute externe ou [ingénierie sociale]({% link _knowhow/glossary/SocialEngineering_fr.markdown %}));
  * l'envoi de données confidentielles au mauvais destinataire;
  * l'intégration de nouveaux destinataires au cours d'une discussion ayant un antécédent confidentiel;
  * au fait que le destinataire de la même entreprise transfère ses courriers électroniques sur une messagerie hors entreprise pour pouvoir profiter du mode 'push' sur smartphones;
  * une connexion à la messagerie électronique sans mode [SSL]({% link _knowhow/glossary/SSLTLS-EncryptionTechnologiesOnWeb_fr.markdown %});
  * la compromission du serveur mail depuis l'extérieur ou de l'intérieur (mauvaise protection, mauvaise configuration, faible mot de passe administrateur,...);
  * l'extraction malicieuse de données confidentielles par un employé;
  * l'extraction malicieuse de données confidentielles via un poste mal protégé (sécurité physique, sécurité des accès, mot de passe faible ou affiché près du poste de travail);
  * au vol d'un ordinateur disposant d'un compte e-mail;
  * au vol d'un serveur mail;
  * au non respect des consignes de classification des données;
* Perte d'intégrité due à la multiplication des versions d'un document éparpillé à travers de multiples boîtes aux lettres de l'entreprise.


## Risques liés à la réception de courrier électronique

* Risque de perte de [confidentialité]({% link _knowhow/glossary/Confidentiality_fr.markdown %}), d'[intégrité]({% link _knowhow/glossary/Integrity_fr.markdown %}) ou de [disponibilité]({% link _knowhow/glossary/Availability_fr.markdown %}) par:
  * l'infection via [logiciels malveillants]({% link _knowhow/glossary/MaliciousCodes_fr.markdown %}) à travers des fichiers liés;
  * l'infection via [logiciels malveillants]({% link _knowhow/glossary/MaliciousCodes_fr.markdown %}) à travers des liens proposés dans le courrier électronique;
* risque de perte de confidentialité par l'incitation à la divulgation de données confidentielles par des techniques d'[ingénierie sociale]({% link _knowhow/glossary/SocialEngineering_fr.markdown %});
* risque de perte de disponibilité:
  * ddû à la présence de [spam]({% link _knowhow/glossary/SPAM-UnwantedEmails_fr.markdown %});
  * à cause de canulars (hoax).

## Mesures comportementales

* Faites attention à ne pas révéler des informations confidentielles en répondant à des courriers électroniques. Vérifiez la légitimité de la demande et faites attention de ne pas divulguer trop d'informations dans vos réponses;
* la plupart des [courriers électroniques]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#email) contenant des fichiers joints sont annoncés par des discussions précédentes, respectivement s'inscrivent dans un contexte spécifique légitimant l'ajout de pièces jointes. Si cela n'est pas le cas, soyez très prudents lors de la réception de courrier avec fichier joint, car ceux-ci peuvent contenir des [codes malicieux;]({% link _knowhow/glossary/MaliciousCodes_fr.markdown %});
* les personnes malintentionnées essayent souvent d'exploiter les [vulnérabilités humaines]({% link _knowhow/glossary/Vulnerabilities_fr.markdown %}), comme notamment la curiosité, la pitié, la peur, l'appât du gain ou encore la libido. Si le courrier électronique reçu contient de telles allusions, il est fortement probable qu'il s'agisse d'un courrier électronique malicieux;
  * parmi les courriers électroniques malicieux, on distingue entre hoax, [phishing]({% link _knowhow/glossary/Phishing_fr.markdown %}) spear phishing (type de phishing très ciblé), nigériens, [codes malicieux]({% link _knowhow/bestpractices/MaliciousSoftwareBP_fr.markdown %}), [spam]({% link _knowhow/glossary/SPAM-UnwantedEmails_fr.markdown %});
* vérifiez si le courrier électronique prétendant provenir d'une certaine personne ressemble aux courriers électroniques précédemment envoyés par cette personne. La langue utilisée, la façon d'écrire, l'orthographe, le style etc. peuvent être des indices. Si vous avez un doute, il s'agit probablement d'un courrier électronique malicieux;
* ne cliquez jamais sur des liens dans des courriers électroniques dont vous ne connaissez pas l'expéditeur, respectivement le courrier électronique qui présente des indices de malice, il pourrait s'agir de phishing ou d'un lien vers une page web piégée;
* ne répondez pas à des courriers électroniques suspects. Une réponse de votre part ne fait que confirmer que l'adresse utilisée est bien active.

## Mesures organisationnelles

* formation du personnel à la [classification des données]({% link _knowhow/cisoapproach/SecurityPolicy-Classification_fr.markdown %}) et aux règles associées;
* formation du personnel aux risques liés à l'[ingénierie sociale]({% link _knowhow/glossary/SocialEngineering_fr.markdown %});
* essayez d'éliminer tout processus impliquant des pièces jointes;
* en cas d'obligation à ouvrir les fichiers joints :
  * attendez 4 jours avant d'ouvrir les fichiers joints. Ce laps de temps augmente les chances de détection par l'[antivirus]({% link _knowhow/glossary/AntiVirus_fr.markdown %}) de [codes malicieux]({% link _knowhow/bestpractices/MaliciousSoftwareBP_fr.markdown %}). En effet, au moins 3 à 4 jours sont nécessaires pour détecter un nouveau virus après sa première apparition et l'introduire dans les bases de signatures les [antivirus]({% link _knowhow/glossary/AntiVirus_fr.markdown %}) correspondants.
  * équipez les ordinateurs servant à ouvrir les fichiers joints, d'un système d'exploitation moins répandu et de ce fait moins attaqué, comme par exemple 'Linux';
  * appelez la personne qui vous a envoyé un courrier électronique suspect et demandez-lui si elle vous a vraiment envoyée ce courrier. Informez-là sur les raisons qui vous ont poussé à estimer le courrier électronique comme étant suspect;
  * évitez de consulter des courriers électroniques sur des [actifs]({% link _knowhow/glossary/Assets_fr.markdown %}) critiques ou ayant accès à des actifs critiques comme notamment des informations [confidentielles]({% link _knowhow/glossary/Confidentiality_fr.markdown %}) ou encore des actifs indispensables.

## Les politiques sectorielles applicables
Rédigez et faites appliquer les politiques sectorielles suivantes :

* [Classification et maîtrise des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %})
  * [Classification et responsabilité des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %}#classification-and-responsibility-for-resource)
* [Aspects humains]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %})
  * [La formation et l’information]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %}#training-and-information)
* [Aspects opérationnels et communications]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %})
  * [Protection contre les logiciels malveillants]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#protection-against-malware)
  * [Courrier électronique]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#email)
* [Contrôle d’accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %})
  * [Utilisation de réseaux externes]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#use-of-external-networks)
  * [Connexion de l’extérieur]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#external-connections)
  * [Séparation de réseaux]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#separation-of-networks)
  * [Procédure de connexion]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#connection-procedures)
* [Développement et maintenance des systèmes]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %})
  * [Utilisation de l’encryption]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}#encryption)
  * [La signature électronique]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}#electronic-signatures)
* [Gestion des incidents liés à la sécurité]({% link _knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents_fr.markdown %})
  * [Signalement des événements liés à la sécurité de l’information]({% link _knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents_fr.markdown %}#reporting-information-security-events)
* [Conformité]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %})
  * [Propriété intellectuelle]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %}#intellectual-property)
  * [Protection des données opérationnelles]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %}#protection-of-operational-data)
  * [Protection des données à caractère personnel]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %}#personal-data-protection)

## Mesures techniques

* Tenez constamment à jour votre logiciel [antivirus]({% link _knowhow/glossary/AntiVirus_fr.markdown %}). Normalement il télécharge les mises à jour automatiquement;
* Utilisez un autre logiciel antivirus sur le serveur mail que sur les postes de travail. Ceci augmente la probabilité de découvrir les logiciels malveillants. Aucun antivirus ne détecte plus de 80% des [codes malicieux]({% link _knowhow/bestpractices/MaliciousSoftwareBP_fr.markdown %}) existants;
* ne travaillez pas sur une station de travail en étant connecté en mode administrateur. Les codes malicieux exécutés sur ces postes héritent de vos droits et peuvent donc s'installer et accéder à tous les comptes de la machine;
* activez le filtre [spam]({% link _knowhow/glossary/SPAM-UnwantedEmails_fr.markdown %}) dans votre logiciel de courrier électronique;
* [chiffrez]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}#encryption) le contenu de vos ordinateurs portables;
* respectez consciencieusement les consignes de mise au rebut du matériel, tant des serveurs que des ordinateurs et GSM;
* utilisez des moyens d'[authentification]({% link _knowhow/glossary/Authentication_fr.markdown %}) forte pour vos solutions web-mail (OTP, LuxTrust);
* ne proposez que des connexions sécurisées par [SSL]({% link _knowhow/glossary/SSLTLS-EncryptionTechnologiesOnWeb_fr.markdown %}) pour vos solutions web-mail.
