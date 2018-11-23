---
layout: knowhow
title:  "Mesures de sécurité pour PME - Les ressources humaines face aux menaces"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: f-bestpract
toc: true
ref: bestpractthreatstohr
lang: fr
---
## Manipulation de l'être humain

Le "[social engineering]({% link _knowhow/glossary/SocialEngineering_fr.markdown %})" (ingénierie sociale) est une des techniques les plus redoutables pour attaquer les utilisateurs d'un système informatique (SI).  L'ingénierie sociale se base sur des techniques psychologiques subtiles pour amener l'être humain à livrer les informations souhaitées.  En exploitant les vulnérabilités humaines comme par exemple l’envie d’aider un pair ou le besoin d’impressionner un supérieur, une personne malveillante peut obtenir d'une personne l’accès à des données et des systèmes confidentiels.

Afin d'éviter la divulgation inopinée d'informations, il est important de sensibiliser le personnel aux principes généraux du "social engineering" et de lui montrer des manières adéquates de réagir et de communiquer. Il s'agit, entre autres :

* de former les employés à la communication et à la protection de l’image de l’organisation (notamment lors de la communication par email, de la participation à des forums de discussion, des relations avec les médias…). (Rédigez et faites respecter une Politique sectorielle liée aux Aspects humains - [Formation et information]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %}#training-and-information));
* de sensibiliser les employés aux bonnes pratiques de sécurité à l'extérieur du périmètre de l’organisation;
* d'affecter un code particulier à chaque employé faisant appel au help desk;
* d'établir un renforcement des contrôles d’identité lors de demandes d’informations. (Rédigez et faites respecter une Politique sectorielle pour la [Classification et maîtrise des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %}));
* de vérifier et de tracer les appels longue distance - respectivement de sécuriser les serveurs téléphoniques (PBX).

## Erreur humaine : mesures de prévention

Le spectre des erreurs humaines est étendu, pouvant aller du mail adressé par mégarde à la mauvaise personne, jusqu’à l’effacement accidentel de données vitales pour l’entreprise.

Pour éviter au mieux ce risque, veillez à instaurer :

* une formation adéquate du personnel. (Rédigez et faites respecter une Politique sectorielle liée aux Aspects humains - [Formation et information]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %}#training-and-information));
* un renforcement des mesures de sauvegardes pour les dossiers sensibles. (Rédigez et faites respecter une politique sectorielle liée aux Aspects opérationnels et communications - [Sauvegarde des données]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#data-backups));
* un système de double validation pour les opérations critiques;
* un logging des opérations effectuées sur les informations sensibles (registre papier, logs d’audit).

## Utilisation abusive des ressources informatiques

Les ressources informatiques mises à disposition des utilisateurs peuvent être détournées à des fins d’utilisation personnelle.  Une organisation doit respecter la vie privée de ses employés, tout comme ceux-ci doivent éviter un abus pour usage personnel de l'infrastructure informatique dans le cadre de leur travail, notamment en ce qui concerne l'utilisation d’Internet et de la messagerie électronique. Vous pouvez par exemple instaurez :

* un paragraphe dans la charte indiquant clairement ce qui sera considéré comme un abus dans les limites du respect de la vie privée sur le lieu de travail ;
* une politique d’utilisation restrictive des logiciels définie au niveau du système d’exploitation. (Rédigez et faites respecter une Politique sectorielle pour la [Classification et maîtrise des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %}) et une politique sectorielle pour le contrôle d'accès - [Politique de contrôle d'accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-control-policy) et [Gestion des droits d'accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-rights-management));
* le filtrage des sites Internet.  (Rédigez et faites respecter une Politique sectorielle relative au Contrôle d'accès - [Utilisation de réseaux externes]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#use-of-external-networks));
* le blocage des mails provenant et/ou à destination de l’extérieur. (Rédigez et faites respecter une Politique sectorielle liée aux Aspects opérationnels et communications - [courrier électronique]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#email)).

## Absence du personnel

La disponibilité du système d’information est liée à la disponibilité du personnel en général. Il faudrait, dans un cas idéal, s’assurer que toutes les informations soient accessibles en permanence. Ceci peut être organisé par le biais des habilitations, une mise en place d’une rotation du personnel et d'un service de garde, à plus forte raison au niveau des administrateurs du SI. La mise en place des éléments suivants peut être utile :

* calendrier prévisionnel des absences;
* mécanisme de délégation des tâches (qui fait quoi lorsque M/Mme Untel est absent(e)). (Rédigez et faites respecter une Politique sectorielle pour le contrôle d'accès - [Politique de contrôle d'accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-control-policy) et [Gestion des droits d'accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-rights-management));
* registre des numéros de téléphone personnels des collaborateurs, pour former un réseau d’alerte. (Rédigez et faites respecter une Politique sectorielle liée aux Aspects humains - [La réponse aux incidents et dysfonctionnements]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %}#response-to-incidents-and-malfunctions)).

## L'administrateur

L’administrateur d’un système d’information, de par sa fonction de superviseur, dispose de droits d'accès spécifiques. Il peut donc avoir accès à toutes les informations contenues dans le système informatique, et en cas de malveillance, empêcher l’accès au système d'information (SI). Par mesure de sécurité, il est utile de prévoir :

* l’enregistrement des opérations d’administration sur les données sensibles et la configuration des habilitations;
* la sensibilisation des administrateurs à leur responsabilités juridiques (Rédigez et faites respecter une Politique sectorielle liée aux Aspects humains - [Formation et information]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %}#training-and-information));
* la mise en place des mesures liées au problème de sécurité « [administration impossible]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Software_fr.markdown %}#unavailability-of-administrators) ».

## Spam / Phishing
Un [spam]({% link _knowhow/glossary/SPAM-UnwantedEmails_fr.markdown %}) est un courrier électronique non sollicité. Ce type de courrier à vocation publicitaire est dirigé vers le propriétaire de la boîte de messagerie dans le but de l'inciter à consulter un service/produit ou un site. Dans le meilleur des cas, la perte de temps et d’espace électronique que représente ce type de courrier peut saturer inutilement un système d’information, et doit, par conséquent, être combattu. De plus, le spam pourrait aussi contenir un logiciel malveillant et devenir ainsi une menace concrète pour les actifs de l'organisme.

Le [phishing]({% link _knowhow/glossary/Phishing_fr.markdown %}) est une technique particulière d'ingénierie sociale utilisant principalement les courriers électroniques et visant à obtenir des informations personnelles (notamment concernant vos comptes bancaires) en se faisant passer pour un organisme de confiance (par ex. une banque), via un site web falsifié. Ce type d’attaque s’adresse principalement à des particuliers, mais les données vitales de l’entreprise peuvent également être visées.

Ces deux menaces sont actuellement de véritables fléaux pour les messageries électroniques. Vous pouvez vous prémunir en :

* mettant en place un filtre anti-spam (client ou serveur). (Rédigez et faites respecter une Politique sectorielle liée aux Aspects opérationnels et communications - [courrier électronique]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#email));
* sensibilisant les employés aux bonnes pratiques dans ce domaine, comme par exemple :
  * ignorez tout spam ou  phishing ;
  * veillez à ce que des adresses email puissent uniquement être diffusées avec votre accord explicite. Certains fournisseurs d'accès ou prestataires peuvent automatiquement vous inscrire dans un annuaire web. (Rédigez et faites respecter une Politique sectorielle liée aux Aspects humains - [Formation et information]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %}#training-and-information)) ;
* évitez au maximum la publication de votre adresse email sur des forums ou des sites d'Internet;
* gardez secrètes des informations confidentielles (carte de crédit par ex.). (Rédigez et faites appliquer une Politique sectorielle pour la [Classification et maîtrise des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %}));
* restreignez la visibilité de l’annuaire électronique de l’organisation.

## Utilisation par un tiers d’un accès réservé

Pour pouvoir accéder à un système d’information les utilisateurs sont dotés de droits d’accès en fonction de leur profil d’utilisation du système informatique. Le cas le plus simple est l’accès physique à une machine. Lorsqu’un tiers utilise une ressource qui ne lui est pas autorisée, on parle d’intrusion. Lorsqu’un tiers utilise les droits d’un utilisateur pour accéder à une ressource, on parle d’usurpation d’identité. Il faut donc veiller à ce qu’une authentification reste synonyme d’identification et qu'une intrusion physique soit évitée. Il est utile :

* de verrouiller les équipements électroniques après utilisation, ou à défaut automatiquement après un temps donné. (Rédigez et faites respecter une politique sectorielle pour le contrôle d'accès - [Politique de contrôle d'accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-control-policy) et [Procédures de connexion]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#connection-procedures));
* d'interdire le prêt de clefs, badges, mots de passe (Rédigez et faites respecter une politique sectorielle pour le contrôle d'accès - Gestion des [mots de passe]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#password-management));
* de tracer les événements sur les lieux et données sensibles.
