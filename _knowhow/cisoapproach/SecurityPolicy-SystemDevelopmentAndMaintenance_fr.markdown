---
layout: knowhow
category: "Knowhow"
title:  "Security Policy – System development and maintenance"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: f-ciso
toc: true
ref: cisosystemdeploymentmaintenance
lang: fr
---
## Le chiffrement

Le [chiffrement]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}#encryption)  consiste à rendre illisible des données à un tiers non autorisé et à l’empêcher de les sauvegarder ou de les transporter. L'usage de cette méthode est recommandée dans le cadre du transfert d’informations classées comme vitales et confidentielles pour "l’organisation", notamment lors de communication via [e-mail]({ % link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#email). Le choix du moyen cryptographique incombe au responsable informatique. Il peut faire appel, le cas échéant, à des compétences externes. (PME: voir [Interception des communications]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure_fr.markdown %}#interception-of-communications)).

### Appliquer des mesures de sécurité pour:

* [les serveurs de fichiers]({% link _publications/recommendationsecuring/Recommendations4securingWebServer_fr.markdown %})
* [les serveurs mail]({% link _publications/recommendationsecuring/Recommendations4securingEmailServer_fr.markdown %})
* [réseau fixe]({% link _publications/recommendationsecuring/SecuringFixedNetwork_fr.markdown %})
* [réseau wifi interne]({% link _publications/recommendationsecuring/SecuringWifiNetwork_fr.markdown %}#wifi-for-employees)
* [réseau wifi pour clients]({% link _publications/recommendationsecuring/SecuringWifiNetwork_fr.markdown %}#wifi-for-visitorsexternal-users)
* [Les ordinateurs connectés à l'Internet]({% link _publications/recommendationsecuring/SecuringFixedWorkstation_fr.markdown %})
* [Les ordinateurs portables]({% link _publications/recommendationsecuring/SecuringLaptops_fr.markdown %})

### Mesures organisationnelles directement liées:

* [Classification et maîtrise des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %})
  * [Classification et responsabilité des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %}#classification-and-responsibility-for-resources)
* [Sécurité physique et environnementale]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %})
  * [Sécurité des équipements hors des locaux]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %}#off-site-equipment-security)
* [Aspects opérationnels et communications]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %})
  * [Procédures documentées]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#documentation-of-procedures)
  * [sauvegarde des données]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#data-backups)
  * [Sécurité des médias pendant les transports]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#device-security-during-transport)
  * [Courrier électronique]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#email)
* [Développement et maintenance des systèmes]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %})
  * [La signature électronique]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}#electronic-signatures)
* [Conformité]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %})
  * [Propriété intellectuelle]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %}#intellectual-property)
  * [Protection des données opérationnelles]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %}#protection-of-operational-data)
  * [Protection des données à caractère personnel]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %}#personal-data-protection)

### Mesures techniques:

* le [chiffrement]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}#encryption)

## Mise en oeuvre

Quelques exemples d'outils de chiffrement libres:

### VeraCrypt
[VeraCrypt](https://veracrypt.codeplex.com/) est un logiciel libre de chiffrement avec lequel vous pouvez chiffrer un disque dur entier ou créer des conteneurs chiffrés dans lequel vous pouvez déposer des fichiers sensibles. Ces conteneurs peuvent se trouver sur un disque dur, un serveur de fichier ou même des [supports amovibles]({% link _knowhow/glossary/RemovableDevices_fr.markdown %}). Il est simple d'utilisation et fiable d'un point de vue sécurité.

### 7Z
[7Z](https://www.7-zip.org/) est un outil gratuit pour comprimer et archiver des fichiers. Cet outil a aussi une option de chiffrement forte en AES 256 bits. Il peut donc être utilisé pour transférer des fichiers confidentiels chiffrés sur des supports amovibles, respectivement envoyés par courrier électronique puisque les fichiers se trouvent dans un archive comprimé.

Il s'agit ici d'un outil de chiffrement symétrique comme veracrypt, il faut donc échanger la clé de chiffrement de façon sécurisée avec le destinataire. Utilisez un canal sûr, mais différent de celui utilisé pour le transfert des données. Vous pouvez par exemple envoyer la clé via voie postale, fax ou par sms, respectivement la remettre en main propre.

## Dépôt des clés d'encryption

### Responsabilité

Le CSSI et le gestionnaire des clés sont responsables du processus de chiffrement.

### Deposit creation

Le CSSI définit un emplacement sécurisé (typiquement un coffre-fort [classé]({% link _knowhow/cisoapproach/SecurityPolicy-Classification_fr.markdown %}) SECRET) dans lequel il conserve les copies des clés mises à disposition par les utilisateurs. Le dépôt n’a pas de backup. En cas de destruction, les gestionnaires de clés doivent déposer une nouvelle fois leurs clés.

### Dépôt "papier" dans un coffre-fort de clés classé "Secret".

Les mesures de sécurité applicables:

* Deux personnes sont requises (principe des quatre yeux; [l'authentification]({% link _knowhow/glossary/Authentication_fr.markdown %}) séparée);
* Protocole d’ouverture et d’accès aux clés;
* Clés dans des enveloppes scellées;
* Inventaire du contenu indiquant:
  * le nom du créateur de la clé; le nom des personnes autorisées à y accéder;
  * le nom de l’environnement et du logiciel utilisant la clé;
  * le type de données protégées;
  * l'identifiant de l’enveloppe contenant la valeur de la clé.

###  Dépôt "électronique" (pour clé du coffre-fort)

Il s'agit de la même procédure de question que décrit précédemment, à l'exception du principe des quatre yeux, car seul le CSSI peut accéder au coffre-fort. Voilà pourquoi il peut conserver les clés sous forme électronique (dans un contenant suffisamment protégé). Il peut remplacer l’identifiant de la clé par la clé elle-même. Le CSSI doit cependant assurer que ses sauvegardes puissent également permettre  d'accéder au fichier de clé.

### Importation dans le dépôt physique

L’auteur de la clé prépare un formulaire, note la clé, et l’enferme en présence du responsable du coffre-fort, après lui avoir montré le formulaire, uniquement le temps nécessaire pour voir que le formulaire est rempli de manière complète, que la qualité de la clé est suffisamment bonne.

Le responsable du dépôt met à jour l’inventaire du dépôt et le fait signer par l’auteur de la clé ajoutée.

### Exportation d’une clé du dépôt

Une clé ne peut pas être enlevée du dépôt. En cas d’utilisation, les personnes autorisées peuvent venir la consulter:
Sont autorisés:

1. l’auteur de la clé;
2. toute personne déléguée explicitement par le gestionnaire des informations protégées par la clé, à condition qu’il y ait une légitimité validée par le responsable Sécurité.

Toute exportation de l’inventaire du coffre est signée par la personne ayant pris connaissance de la clé, ainsi que les responsables du coffre-fort.

### Destruction d’une clé du dépôt

Sur demande écrite de l’auteur et validée par le gestionnaire de l’information protégée, les responsables du coffre-fort procèdent à la destruction d’une clé. À cet effet, il détruit l’enveloppe avec la clé dans un destructeur de documents, après avoir vérifié la demande de destruction.

L’inventaire est mis à jour, en conservant la demande de destruction comme preuve de légitimation.

## La signature électronique

La signature électronique est une méthode utilisée pour garantir l’authenticité de la source d’un message (l’expéditeur), et l'[intégrité]({% link _knowhow/glossary/Integrity_fr.markdown %}) de son contenu.

Cette technologie doit être mise en œuvre lors d’échanges via e-mails avec des entités extérieures et qui pourraient avoir valeur d’engagement pour "l’organisation". Il incombe au responsable informatique de mettre en place cette technologie pour les utilisateurs.

[LuxTrust](https://www.luxtrust.lu) offre des solutions de signature électronique. [OpenPGP](https://www.openpgp.org/) st une alternative libre pour la signature et le chiffrement.

Les signatures électroniques peuvent notamment être apposées sur des documents, ainsi que sur des courriers électroniques. La signature garantit l'authenticité de l'expéditeur ainsi que l'[intégrité]({% link _knowhow/glossary/Integrity_fr.markdown %}) du contenu du fichier respectivement du message.

### Appliquer des mesures de sécurité pour:

* garantir l'intégrité
* garantir la non-répudiation

### Mesures organisationnelles:

* [Aspects opérationnels et communications]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %})
  * [Procédures documentées]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#documentation-of-procedures)
* [Développement et maintenance des systèmes]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %})
  * [Utilisation du chiffrement]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}#encryption)
  * [Gestion des vulnérabilités techniques]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}#managing-technical-vulnerabilities)

### Mesures techniques:

* le [chiffrement]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}#encryption)

## Gérer les vulnérabilités techniques

Tout organisme doit veiller à réduire les risques liés à l’exploitation des [vulnérabilités techniques]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}#managing-technical-vulnerabilities) ayant fait l’objet d’une publication.
Pour ce faire, il met en place, pour l’ensemble de son infrastructure y compris les logiciels, les systèmes d’exploitation et les équipements réseau, une gestion efficace et systématique des vulnérabilités techniques. Celle-ci s'opère par l'application de [correctifs]({% link _knowhow/glossary/Patches_fr.markdown %}) ou d'autres outils aptes à prévenir l'exploitation de vulnérabilités techniques. Le suivi des mesures effectuées permet d'en mesurer l'efficacité concrète.

### Appliquer des mesures de sécurité pour:

* [les serveurs fichier]({% link _publications/recommendationsecuring/Recommendations4securingWebServer_fr.markdown %})
* [les serveurs mail]({% link _publications/recommendationsecuring/Recommendations4securingEmailServer_fr.markdown %})
* [les ordinateurs connectés à l'Internet]({% link _publications/recommendationsecuring/SecuringFixedWorkstation_fr.markdown %})
* [les ordinateurs portables]({% link _publications/recommendationsecuring/SecuringLaptops_fr.markdown %})

### Mesures comportementales:

* [les sites web malicieux]({% link _knowhow/glossary/MaliciousWebsites_fr.markdown %})
* [malicious code]({% link _knowhow/glossary/MaliciousCodes_fr.markdown %})

### Mesures organisationnelles directement liées:

* [Organisation de la sécurité]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity_fr.markdown %})
  * [Attribution des responsabilités]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity_fr.markdown %}#attribution-of-responsibilities)
* [Aspects humains]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %})
  * [La réponse aux incidents et dysfonctionnements de sécurité]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors_fr.markdown %}#response-to-incidents-and-malfunctions)
* [Aspects opérationnels et communications]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %})
  * [Procédures documentées]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#documentation-of-procedures)
  * [Séparation des environnements de développement et de production]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#separation-of-environments)
* [Gestion des incidents liés à la sécurité]({% link _knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents_fr.markdown %})
  * [Gestion des incidents et des améliorations de la sécurité de l’information]({% link _knowhow/cisoapproach/SecurityPolicy-ManagementOfSecurityIncidents_fr.markdown %}#incident-management-and-improvements-information-security)


### Mesures techniques:
* [les correctifs]({% link _knowhow/glossary/Patches_fr.markdown %})
* [le pare-feu]({% link _knowhow/glossary/Firewall_fr.markdown %})
* [la segmentation de réseau]({% link _knowhow/glossary/NetworkSegmentation_fr.markdown %})
