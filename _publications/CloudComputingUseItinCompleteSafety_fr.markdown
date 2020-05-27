---
layout: publication-list
category: "In depth articles"
title:  "Cloud computing  les clés pour en profiter en toute sécurité"
menutitle: "Cloud computing"
logo:
date:  2017-11-06 00:00:00 +0100
short: "This file addresses the key points of cloud computing, thanks to him you will master this subject"
categories: securing
toc: true
ref: cloudcomputinguseitincompletesafety
lang: fr
---
<style>
table {
    width:100%;
}
th {
  border: 1px solid #999999;
  text-align: center;
  background-color: #BBBBBB
}
th,td {
  padding: 8px;
}
</style>

## En quelques mots
Le cloud computing recouvre différents moyens mis à disposition des entreprises pour externaliser leurs ressources informatiques et y accéder au travers d’un réseau.
Généralement ces services, surtout s’ils sont gérés par un organisme tiers, sont hébergés dans des centres de calculs sur lesquels l’utilisateur à peu d’emprise.

Originellement le cloud computing décrit une grappe de serveurs partageant leurs tâches. Il s’agit donc de mutualiser des ressources qui sont généralement sous-utilisées. Chaque utilisateur n’utilise généralement qu’une petite partie de la puissance globale, mais peut bénéficier à certains moments de la pleine capacité d’une ressource partagée. Cette technologie permet d’adapter, sans grand investissement, les besoins informatiques d’une entreprise avec souplesse.

Les infrastructures des sites de commerce électronique sont un bon exemple de cloud computing. Elles connaissent souvent un gros pic d’utilisation aux alentours de Noël. Mais le reste de l’année, beaucoup moins de ressources sont nécessaires. Pour faire face au « pic de Noël », les sites de commerce électronique ont tout intérêt à louer des capacités supplémentaires uniquement pour cette période, sans avoir à financer des machines surdimensionnées toute l’année. S’il opte toutefois pour cette dernière solution, il pourra également devenir **fournisseur** de services « cloud ».

Ce n’est pas un hasard si l’un des plus grands acteurs dans le domaine du cloud computing est Amazon, qui a décidé de louer et étendre son infrastructure à des tiers.

## Types de cloud
Dans le domaine du cloud computing on rencontre généralement plusieurs types d’offres :

**IaaS**: Infrastructure as a Service : Le fournisseur (cloud provider) met à disposition une infrastructure, c’est-à-dire des moyens de communication, un nombre prédéfini de processeurs, de mémoire vive et d’espace de stockage. Le client doit lui-même installer et gérer ses systèmes d’exploitation et applications. En cas de besoin, l’application peut demander un plus grand débit, plus de processeurs, une plus grande mémoire vive ou encore plus d’espace de stockage. Le client a donc l’avantage de disposer d’une infrastructure qui peut réagir de façon dynamique à des pics de besoin, sans pour autant financer cette infrastructure sur toute l’année. Généralement le client ne paye que ce dont il a besoin, le fameux « pay as you go ».

**PaaS**: Plateform as a Service : Le cloud provider met, tout comme dans le modèle IaaS, à disposition du client l’infrastructure et y ajoute la couche système d’exploitation, et environnement de production comme notamment des serveurs web, serveur de base de données et ainsi de suite. Dans ce cas de figure, le client n’a besoin que de déposer son application dans l’infrastructure, le reste est géré par le cloud provider.

**SaaS**: Software as a service : Le cloud provider met à disposition du client l’application que celui-ci utilise. Le client n’a donc plus besoin de gérer quoi que ce soit. Il ne se concentre plus que sur l’utilisation de l’application mise à disposition.

## Caractéristiques du cloud

### La législation
Il n’y a pas de cadre législatif propre au Cloud Computing en Europe ou au Luxembourg. Comme vu en introduction, le Cloud Computing est une convergence de plusieurs services en ligne existants par ailleurs. Ces services sont eux-mêmes pour la plupart couverts par des particularités législatives propres (e-commerce, protection des données à caractère personnelles, archivage, …), et le Cloud Computing se retrouve donc à l’intersection d’une multitude de réglementations et de lois.

Les obligations qui peuvent exister au Luxembourg pour certains secteurs d’activités, comme le secteur financier, restent bien évidemment d’actualité dans le cadre du Cloud Computing. Plus largement, l’ensemble de la [législation applicable à la protection des données à caractères personnelles]({% link _knowhow/glossary/LegalAspects.markdown %}#personal-data-protection) reste d’actualité pour les entreprises cherchant à reposer sur une solution de Cloud Computing. En sous-traitant une partie ou l’intégralité d’une infrastructure informatique de stockage ou de traitement de données, toute entreprise reste responsable de l’intégrité et de l’usage qui est fait de ces données. Les entreprises souhaitant migrer vers des solutions de Cloud Computing auront donc tout intérêt à lire avec la plus extrême attention les contrats associés (dont les SLAs, pour Service Level Agreements) à la prestation de Cloud qu’elles auront choisi. En particulier, la localisation géographique des lieux de stockage de données est un élément fondamental car ces lieux de stockage peuvent être établis dans des pays ne respectant pas les obligations européennes et/ou Luxembourgeoises.

Enfin, la [propriété intellectuelle]({% link _knowhow/glossary/LegalAspects_fr.markdown %}#intellectual-property) est un point qui mérite d’être mentionné. Que ce soit pour respecter des engagements de confidentialité pris envers des tiers ou le secret de méthodes développées au sein de l’entreprise, sous-traiter son activité informatique signifie potentiellement s’exposer à des risques en matière de respect et de contrôle de la confidentialité des données. Des solutions techniques comme le chiffrement existent et sont présentées plus en avant dans ce document. Elles ne doivent surtout pas être sous-estimées.

### La sécurité des données

#### Transmission des données
Il faut vérifier si les données transmises vers le cloud sont protégées contre toute perte de confidentialité. Il est donc nécessaire qu’une ligne chiffrée soit utilisée ([SSL]({% link _knowhow/glossary/SSLTLS-EncryptionTechnologiesOnWeb_fr.markdown %})) ou que les données soient [chiffrées]({% link _knowhow/glossary/Cryptography_fr.markdown %}) avant d’être transférées vers le cloud.

Les protocoles de transmission utilisés lors des [backups]({% link _knowhow/glossary/DataBackups_fr.markdown %}) gèrent généralement assez bien la [disponibilité]({% link _knowhow/glossary/Availability_fr.markdown %}) des données ainsi que leur [intégrité]({% link _knowhow/glossary/Integrity_fr.markdown %}). Les données ne sont pas changées ou perdues lors de la transmission. Par contre si l’on utilise le cloud comme plate-forme collaborative, et si on édite les documents via des applications web, des pertes de connectivité peuvent mener à des pertes de données.

#### Stockage des données
Dans le cloud, vous n’êtes pas forcément la seule personne qui peut accéder à vos données. Si vous louez les services d’un fournisseur, ce dernier a aussi accès à vos données puisqu’il doit gérer l’infrastructure. En cas de problèmes, d’erreurs de manipulation ou d’exploitation de [vulnérabilités]({% link _knowhow/glossary/Vulnerabilities_fr.markdown %}) par des personnes malintentionnées, il se peut même que d’autres personnes aient accès à vos données. De tels cas ont déjà eu lieu chez des fournisseurs de stockage en ligne.

Certains fournisseurs offrent le chiffrement, mais il est parfois difficile de déterminer si vous restez la seule personne à pouvoir déchiffrer vos données. Ne vous laissez pas éblouir par des termes alambiqués et assurez-vous d’être le seul à détenir les clés de chiffrement.

Si ce n’était pas le cas, il sera préférable de ne faire confiance à personne et de chiffrer vos données sur vos postes locaux avant de les envoyer sur le cloud. Mais tout dépend de votre utilisation : si vous stockez des données non-confidentielles et voulez profiter de capacités de recherche dans le texte, il vous faudra renoncer au chiffrement.

Lorsque plusieurs personnes doivent travailler sur des documents stockés sur un cloud, il peut être utile de partager des [passwords]({% link _knowhow/glossary/Password.markdown %}) entre plusieurs personnes ou plusieurs machines. Pour ce faire, on peut recourir à une base de données de mots de passe. Cette dernière doit alors être correctement protégée par chiffrement pour éviter de retrouver ses mots de passe sur les pages de recherche des moteurs de recherche.

#### Accès aux données
En fonction du niveau de [classification]({% link _knowhow/cisoapproach/SecurityPolicy-Classification_fr.markdown %}) des données stockées dans le cloud, il faut vérifier qu’aucune personne non autorisée ne puisse y accéder, les effacer, les modifier ou les divulguer. Il faut donc vérifier que les mécanismes d’authentification sont adéquats:

* Identifiant et mot de passe : il faut choisir des mots de passe forts et bien les protéger. Il est conseillé de les changer régulièrement. Pour des données non critiques.
* Strong [Authentification]({% link _knowhow/glossary/Authentication_fr.markdown %}):
  * par identifiant, mot de passe et mot de passe à usage unique envoyé par sms ou généré sur un smartphone,
  * par identifiant, mot de passe et mot de passe à usage unique généré par un objet dédié (token),
  * par identifiant, mot de passe et mot de passe et certificat (carte à puce, certificat client) ou clé logicielle.

#### Destruction des données
À la fin du contrat respectivement lorsque vous voulez effacer les anciens back-up, il est important de veiller à ce que vos données soient détruites et ne soient plus accessibles à des personnes non autorisées. La meilleure façon de garantir cela est de nouveau de chiffrer vos données.

### La disponibilité
Certains fournisseurs garantissent un niveau spécifique de [disponibilité]({% link _knowhow/glossary/Availability.markdown %}), d’autres par contre ne prennent aucun engagement précis, sauf celui du « meilleur effort »..

Ainsi un fournisseur qui offre un niveau de disponibilité de 98,5%, peut tomber en panne 5,5 jours par an (même 5,5 jours consécutifs) sans pour autant violer les contrats. Faites à tout prix ce calcul pour déterminer si vous pouvez survivre à une telle [panne]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware_fr.markdown %}#failure-of-it-or-communications-equipment). Bien entendu, une disponibilité plus élevée vous coûtera plus cher qu’une disponibilité moyenne ou basse.  Les très bons centres garantissent jusqu’à 99,99% de disponibilité (moins d’une heure de non disponibilité par année).

La disponibilité des solutions cloud est aussi conditionnée par la connectivité. Une perte de connectivité au niveau de votre entreprise, de votre fournisseur d’accès à Internet ou de votre fournisseur de cloud rend ces services indisponibles. Des attaques de type DDOS (distributed denial of service) peuvent aussi mettre en péril toute une infrastructure cloud et vous affecter si un des clients de votre fournisseur en devient la cible.

La disponibilité d'un [actif]({% link _knowhow/glossary/Assets_fr.markdown %}) au sein d'une entité est définie par l'assurance que celui-ci est utilisable en termes de temps et de performance prévue. Pensez aussi au temps qu’il vous faut pour récupérer les sauvegardes depuis un service en ligne. Cette durée peut devenir très longue, voire prohibitive, à cause du débit réduit qui vous est alloué.

### La connectivité

#### Le débit
La plupart des services cloud assurent un certain débit de données à leurs clients. Il faut absolument que les entreprises vérifient que ces débits suffisent à l’utilisation qui en sera faite.

Il est ainsi important de vérifier pour un service de sauvegarde le débit du flux montant et de calculer combien de temps la sauvegarde va durer. D’un côté nous avons le débit proposé par votre fournisseur d’accès, de l’autre le débit proposé par votre fournisseur de cloud : le goulot d’étranglement sera forcément défini par la  valeur la plus petite:

| Volume de sauvegarde | Débit montant côté ISP | Bande passante côté cloud provider | Durée |
|:----:|:--------:|:--------:|:----------------------------------------:|
| 5 GB | 2.5 Mb/s | 2 Mb/s | 5.000\*8/2 = 20.000 secondes (ou 5,5 heures) |
| 5 GB | 2.5 Mb/s | 2.5 Mb/s | 5.000\*8/2.5 = 16.000 secondes (4,4 heures) |
| 5 GB | 5 Mb/s | 10 Mb/s | 5.000\*8/5 = 8.000 secondes (2,2 heures) |

#### Le volume de données transférées
Certains fournisseurs de cloud facturent le volume de données transférées. Vérifiez si ce modèle convient à votre besoin.

### Les services les plus demandés

#### La sauvegarde
[Backups]({% link _knowhow/glossary/DataBackups_fr.markdown %}) ne doit pas être confondu avec la conservation. En effet, au Luxembourg il existe depuis peu une loi sur les PSDC, les prestataires de service de dématérialisation et de conservation, les prestataires de services dans le domaine de l’archivage électronique.

La sauvegarde dans le cloud n’est rien d’autre que la délocalisation des données de sauvegarde dans un autre centre de calcul. Il faut donc nécessairement vérifier la sécurité des données lors de leur transmission, stockage et finalement destruction en cas de cessation des contrats, effacement par les utilisateurs ou faillite du cloud provider.

La sauvegarde peut durer toute la nuit, sans gêner la production. La restauration des données doit, elle, se faire aussi rapidement que possible. Veillez donc à disposer d’un débit suffisant pour pouvoir télécharger les données dans un délai raisonnable. Pour garder ce délai court, veillez à choisir une bonne stratégie de sauvegarde qui consiste à stocker localement les données et de garder les données dans le cloud pour les sinistres comme les incendies.

#### Synchronisation
La synchronisation de différents outils de travail est un besoin récurrent. Au lieu d’envoyer des documents par [courrier électronique]({% link _knowhow/bestpractices/EMail-BestPractices_fr.markdown %}) non sécurisé, ou de manipuler des [supports amovibles]({% link _knowhow/glossary/RemovableDevices_fr.markdown %}), il est préférable de synchroniser ces données via un service central accessible par tous.

Beaucoup de services existent qui offrent ces formes de collaboration respectivement de synchronisation. Le débit nécessaire ainsi que le volume de données échangés sont généralement plus réduits que pour les services de [sauvegarde]({% link _knowhow/glossary/DataBackups_fr.markdown %}).

Les documents sont ainsi toujours [disponibles]({% link _knowhow/glossary/Availability_fr.markdown %}) sur les différents outils de travail synchronisés, car une copie complète se retrouve sur toutes les plateformes. Une perte de disponibilité du service cloud ne résulte donc pas dans la perte de toutes les données, mais dans la perte de la possibilité de synchroniser. Une synchronisation manuelle via des courriers électroniques sécurisés ou des supports amovibles est toujours possible.

Les besoins de [confidentialité]({% link _knowhow/glossary/Confidentiality.markdown %}) sont par contre bien réels puisqu’il s’agit généralement de données actuelles, qui pourraient susciter l’intérêt de concurrents ou autres [personnes malintentionnées]({% link _knowhow/glossary/Cybercriminals_fr.markdown %}). Un [chiffrement]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}#encryption) lors de leur transmission et lors du stockage sur le serveur cloud s’imposent. Il est préférable que les clients soient les seuls à détenir les clés de chiffrement pour prévenir tout accès illicite via le cloud.

#### Plate-forme collaborative
La collaboration de plusieurs personnes sur les mêmes documents se fait généralement via un serveur de fichier ou un serveur similaire au sein d’une entreprise.

Si l’entreprise ne veut pas entretenir un serveur de fichiers, ou si plusieurs personnes de différentes entreprises doivent collaborer, sans avoir accès à un même serveur de fichier, il est possible d’utiliser des plateformes de collaboration en ligne.

Toutes les personnes d’un même projet ont accès même espace de projet et peuvent travailler sur les documents communs. Pour ce faire, ils ont deux possibilités :

* télécharger le document depuis le serveur cloud sur l’outil de travail et le remettent après avoir fini. Dans ce cas il est possible d’utiliser un [chiffrement]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}#encryption) qui est contrôlé par les clients et inconnu par l’opérateur du cloud.
* utiliser les outils en ligne fournis pour traiter les documents. Dans ce cas l’utilisation de moyens cryptographiques par les clients n’est pas possible. Cette façon de travailler ne garantit donc pas un niveau élevé de [confidentialité]({% link _knowhow/glossary/Confidentiality.markdown %}).

La collaboration sur plateforme cloud peut aussi poser un risque de [disponibilité]({% link _knowhow/glossary/Availability.markdown %}). Si le cloud n’est pas accessible, les documents de travail ne sont plus disponibles. En cas de désastre dans le cloud ou en cas de faillite, il y a un risque de perdre toutes les données. Il est donc très important de prévoir à temps des solutions de [sauvegarde]({% link _knowhow/glossary/DataBackups.markdown %}) hors cloud, dans les locaux d’un des partenaires.

La gestion des droits d’accès entre les ayants droits pose souvent un problème. Vérifiez la granularité de l’octroi de droits lors du choix du fournisseur.

Ces plateformes de collaboration offrent aussi d’autres avantages comme des calendriers, boîtes de messageries ou autres applications utiles.

Souvent il n’est pas possible de vérifier des logs d’accès aux données.

#### Autres services
On pense évidemment aux services en ligne comme l’hébergement des sites web ou des boîtes de messageries, mais il est même possible d’aller jusqu’à la virtualisation de l’environnement de travail complet. Il existe en effet des fournisseurs de bureaux virtuels auxquels on accède au travers d’un navigateur commun.

La cloud offre des possibilités énormes et transforme l’outil informatique en service que l’on peut louer au besoin, donnant ainsi la possibilité même aux petites entreprises d’avoir accès à des technologies réservées jusqu’ici uniquement aux grandes entreprises.

Toutes ces possibilités ont naturellement un prix et il est primordial de bien évaluer la valeur de ses données pour pouvoir mettre en place les mesures de sécurité adéquates.

#### Résumé

| Service | Authentification| Chiffrement | Disponibilité | Débit |
|----|----|----|----|----|
|**[Sauvegarde]({% link _knowhow/glossary/DataBackups.markdown %}) de données non critiques** | [Mot de passe]({% link _knowhow/glossary/Password.markdown %}) fort | Connexion SSL | Moyenne à forte | Selon le volume des données et la fréquence des sauvegardes |
| **Sauvegarde de données critiques** | Authentification à 2 facteurs / Authentification forte | Connexion SSL ET chiffrement des données | Forte, surtout si les données ont un caractère urgent | Elevé, si la restauration des données doit être rapide |
| **Synchronisation** | [Selon criticité des données]({% link _knowhow/cisoapproach/SecurityPolicy-Classification_fr.markdown %}) (cf. Sauvegarde) | [Selon criticité des données]({% link _knowhow/cisoapproach/SecurityPolicy-Classification_fr.markdown %}) (cf. Sauvegarde) | Faible ou Moyenne | Selon le volume des données à synchroniser |
| **Partage de fichiers** | [Selon criticité des données]({% link _knowhow/cisoapproach/SecurityPolicy-Classification_fr.markdown %}) (cf. Sauvegarde) | Connexion SSL<br />Chiffrement à clé partagée si les données sont critiques | Moyenne-Forte | Selon le nombre d’utilisateurs et le volume de fichiers à partager |
| **Travail collaboratif** | [Selon criticité des données]({% link _knowhow/cisoapproach/SecurityPolicy-Classification_fr.markdown %}) (cf. Sauvegarde) | Connexion SSL | Forte, pour éviter toute perte de donnée. Prévoir des sauvegardes en local ? | Elevé, pour permettre un accès simultané à plusieurs utilisateurs |
