---
layout: knowhow
category: "Knowhow"
title:  "Security Policy – Compliance"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: f-ciso
toc: true
ref: cisocompliance
lang: fr
---
## Respecter la législation

Le non-respect de la législation dans le domaine des technologies de l'information peut mettre "l’organisation" dans une situation délicate ([impacts]({% link _knowhow/glossary/Impact_fr.markdown %})) à l'égard de ses clients (image de marque). Il peut également en résulter des conséquences financières (amendes) ou pénales (responsabilité des personnes). "L’organisation" doit donc respecter la loi, notamment en ce qui concerne:

* la propriété intellectuelle ou les droits d’auteurs
* la protection des données opérationnelles obligatoires et les données à caractère personnel. (PME: voir [Exigences réglementaires]({% link _knowhow/bestpractices/SecurityMeasures4SME-LegalAspects_fr.markdown %}#regulatory-requirements) et [Défaut de traçabilité des opérations]({% link _knowhow/bestpractices/SecurityMeasures4SME-LegalAspects_fr.markdown %}#lack-of-traceability-of-operations)).

## Propriété intellectuelle

"L’organisation" doit aussi veiller au respect des [droits d’auteur]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %}#intellectual-property) et licences. Les sanctions pour le non-respect de ces lois peuvent mettre en danger "l’organisation" (PME: voir [Licence non valide ou inexistante]({% link _knowhow/bestpractices/SecurityMeasures4SME-LegalAspects_fr.markdown %}#invalid-or-non-existent-licence)).  Il s'agit en particulier des droits d’auteur sur les œuvres littéraires et artistiques originales auxquelles sont assimilés les bases de données et les programmes d’ordinateur, comme défini dans la loi du 18 avril 2001.

L'équipe informatique est sensée vérifier autant les obligations pour les programmes utilisés que celles des données pour lesquelles l'organisation est propriétaire. En cas de doute, elle peut consulter la loi luxembourgeoise à l’adresse https://meco.gouvernement.lu/fr/le-ministere/domaines-activite/propriete-intellectuelle.html, ou faire appel à un juriste.

Les principes de base à ce sujet sont les suivants:

* toute reproduction, communication au public ou distribution au public doit être autorisée par l’auteur;
* ceci s’applique à la diffusion par l'Internet;
* il faut respecter les licences des logiciels;
* il faut respecter les brevets;
* il faut respecter les marques, dessins et modèles;

## Protection de données opérationnelles

Selon le caractère des données traitées, "l’organisation" est tenue par le règlement général sur la protection des données (RGPD) de mettre en place des mesures appropriées pour empêcher toute personne non autorisée d’accéder aux installations utilisées pour le traitement des données (voir [aspects légaux]({% link _knowhow/glossary/LegalAspects_fr.markdown %})).

Les données correspondant à l’activité commerciale doivent être conservées, sous une forme ou une autre, pendant dix ans à partir de la clôture de l’exercice auquel elles se rapportent.

### Appliquer des mesures de sécurité pour:

* Tous les systèmes de traitement d'informations vitaux ou importants.

### Mesures comportementales:

* * [Bonnes pratiques concernant le courrier électronique]({% link _knowhow/bestpractices/EMail-BestPractices_fr.markdown %})

### Mesures organisationnelles directement liées:

* [Organisation de la sécurité]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity_fr.markdown %})
  * [Attribution des responsabilités]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity_fr.markdown %}#attribution-of-responsibilities)
* [Classification et maîtrise des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %})
  * [Classification et responsabilité des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %}#classification-and-responsibility-for-resources)
* [Aspects opérationnels et communications]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %})
  * [Procédures documentées]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#documentation-of-procedures)
* [Contrôle d’accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %})
  * [Politique de contrôle d’accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-control-policy)
  * [Gestion des droits d’accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-rights-management)
* [Gestion des incidents liés à la sécurité]({% link _knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents_fr.markdown %})
  * [Signalement des événements liés à la sécurité de l’information]({% link _knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents_fr.markdown %}#reporting-information-security-events)
* [Gestion de la continuité de l’entreprise]({% link _knowhow/cisoapproach/SecurityPolicy-ManagingBusinessContinuity_fr.markdown %})
  * [La continuité de fonctionnement]({% link _knowhow/cisoapproach/SecurityPolicy-ManagingBusinessContinuity_fr.markdown %}#operational-continuity)
* [Conformité]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %})
  * [Protection des données à caractère personnel]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %}#personal-data-protection)


### Mesures techniques:

* La [cryptographie]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}#encryption)
* La [sauvegarde]({% link _publications/ProtectingYourCompany_fr.markdown %}#data-backups)

## Protection de données à caractère personnel

Toute création d'un fichier ou d’une base de données doit être faite dans le respect du règlement général sur la protection des données (RGPD). Il en est de même pour les traitements appliqués à ces données et pour les données déjà existantes. (PME: voir [Traitement non autorisé de données personnelles - Surveillance des employés]({% link _knowhow/bestpractices/SecurityMeasures4SME-LegalAspects_fr.markdown %}#unauthorised-processing-of-personal-data--employee-monitoring))

Afin de travailler dans le respect de cette loi, le responsable informatique et le responsable juridique, après avoir obtenu les textes applicables auprès de la [Commission Nationale pour la Protection des Données](https://cnpd.public.lu/fr.html) (ci-après "La Commission") s'assurent de l'adéquation de la structure, notamment au niveau:

* de la déclaration des données et traitements auprès de la Commission;
* de l'obtention d'une autorisation auprès de la Commission quand elle est nécessaire;
* de la qualité des données et de la légitimité des traitements;
* des droits d'information et d'opposition des personnes concernées;
* des données potentiellement discriminatoires (raciales, ethniques, politiques, religieuses, philosophiques, syndicales) ou relatives à la santé.

### Appliquer des mesures de sécurité pour:

* tous les systèmes de traitement d'informations vitaux ou importants
* Voir aussi: [aspects légaux]({% link _knowhow/bestpractices/SecurityMeasures4SME-LegalAspects_fr.markdown %})

### Mesures comportementales:

* [Bonnes pratiques concernant le courrier électronique]({% link _knowhow/bestpractices/EMail-BestPractices_fr.markdown %})

### Mesures organisationnelles directement liées:

* [Organisation de la sécurité]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity_fr.markdown %})
  * [Attribution des responsabilités]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity_fr.markdown %}#attribution-of-responsibilities)
* [Classification et maîtrise des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %})
  * [Classification et responsabilité des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %}#classification-and-responsibility-for-resources)
* [Aspects opérationnels et communications]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %})
  * [Procédures documentées]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#documentation-of-procedures)
* [Contrôle d’accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %})
  * [Politique de contrôle d’accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-control-policy)
  * [Gestion des droits d’accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl_fr.markdown %}#access-rights-management)
* [Gestion des incidents liés à la sécurité]({% link _knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents_fr.markdown %})
  * [Signalement des événements liés à la sécurité de l’information]({% link _knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents_fr.markdown %}#reporting-information-security-events)
* [Gestion de la continuité de l’entreprise]({% link _knowhow/cisoapproach/SecurityPolicy-ManagingBusinessContinuity_fr.markdown %})
  * [La continuité de fonctionnement]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %})
* [Conformité]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %})
  * [Protection des données à caractère personnel]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %}#personal-data-protection)

### Mesures techniques:

* La [cryptographie]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}#encryption)
* La [sauvegarde]({% link _publications/ProtectingYourCompany_fr.markdown %}#data-backups)
