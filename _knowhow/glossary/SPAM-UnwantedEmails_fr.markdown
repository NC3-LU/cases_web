---
layout: article
title:  "Spam - les courriers indésirables"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: knowhow
toc: true
ref: glossaryspamemails
lang: fr
---

## En quelques mots
Ce terme a fait son apparition dans l'Internet, au niveau de l'Usenet, où il désignait des articles de news, envoyés en masse à différents newsgroups. Il s'agissait le plus souvent de messages publicitaires qui n'avaient rien à voir avec les newsgroups concernés.

Ce genre de publicité étant le plus souvent véhiculé par e-mail, le terme de spam ou de pourriel a fini par désigner également les e-mails non sollicités en masse. Techniquement, il serait plus juste de parler de UBE (Unsolicited Bulk E-Mail) ou de UCE (Unsolicited Commercial E-Mail).

Il n'existe pas de définition officielle du mot « spam ». Le mot est, à l'origine, une marque anglaise de charcuterie vendu en conserve. Ce sont les Monty Pythons qui, dans un de leurs fameux sketchs où ils répétaient sans cesse le mot « spam » dans une conversation, ont introduit la notion de désagrément.

Aujourd'hui, le mot « spam » est communément utilisé pour caractériser un [courrier électronique]({% link _knowhow/bestpractices/EMail-BestPractices_fr.markdown %}) non sollicité envoyé en masse à une multitude de destinataires. Ce courrier provoquera donc une gêne pour les destinataires.

Ces courriers ne coûtent pratiquement rien pour l’expéditeur. Par contre, ils peuvent coûter très cher aux destinataires, en terme de coût de connexion et de volume de transferts de données. On peut parler d’un véritable gaspillage de bande passante et d’espace de stockage pour les administrateurs de réseaux et de serveurs de messagerie mais aussi les destinataires des spams (particuliers ou entreprises) dans le temps passé et perdu à télécharger, trier et éliminer les spams reçus avec le risque d'éliminer par erreur un courrier qui n'est pas un spam.

## Qui pratique le spamming?
Le spamming est pratiqué par des criminels et est à ce titre une activité illégale. Il s'agit de l'envoi de publicité pour des produits illicites, d'arnaques, de  [phishing]({% link _knowhow/glossary/Phishing_fr.markdown %}) ou d'envoi de [ logiciels malveillants]({% link _knowhow/glossary/MaliciousCodes_fr.markdown %}).

À ce titre il ne faut pas confondre le spam et les courriers commerciaux qui sont, contrairement au spam, régis par les règles de :

* opt-in : vous acceptez de recevoir ce genre d'e-mails et l'avez fait savoir  vous inscrivant dans une mailing list ou en acceptant des conditions spéciales sur un site ;
* opt-out : l'expéditeur doit mettre à disposition un moyen de se désabonner du service de courriers.

## Comment se fait-il que je sois visctime de spam?
Le seul élément nécessaire pour faire de vous une victime potentielle de pourriels est votre adresse électronique (E-mail).

#### Méthodes de récupération d´adresse E-Mail
Les spammeurs disposent de plusieurs moyens pour récupérer votre adresse électronique sur Internet (dans les forums, sur les sites Internet, dans les groupes de discussion, etc.), grâce à des logiciels (appelés «robots» ) parcourant les différentes pages et stockant au passage dans une base de données toutes les adresses E-mail y figurant.

Pour l'anecdote, Bill Gates reçoit 4 millions d'e-mail par jour dont la majorité sont des spams mais seulement 10 parviennent effectivement dans sa inbox, tous les autres étant filtrés par des solutions anti-spams. (source : BBC News – 18 nov. 2004)

* Votre adresse E-Mail a été vendue

En revendant sa liste d’abonnés à un tiers, qui lui-même l’a revendue à un autre, etc., votre fournisseur d’accès Internet a permis la diffusion de votre adresse en de nombreux exemplaires sur Internet. Attention, l’opération est légale si vous avez accepté que votre adresse soit diffusée.

* Vous l’avez publiée sur Internet

Vous avez affiché votre adresse électronique sur votre page personnelle? Vous avez laissé votre adresse sur des forums de discussion sur le Web ou dans les newsgroups? Sachez que des logiciels permettent de récolter automatiquement les adresses e-mail publiées. Dans tous ces cas vous êtes suscecible d'intégrer un fichier d'adresse.

* Vous avez communiqué votre adresse à un site web

En passant une commande sur un site de commerce électronique, en souscrivant à des services via un site web; si le service web utilisé n'est pas sûr il risque de se faire voler toutes sa base de données, non-seulement d'adresses mails mais potentiellement aussi de numéros de cartes VISA.

* Votre adresse a été générée au hasard

Prenez d'un côté les listes des noms et prénoms les plus courants, de l'autre celle de fournisseurs d'accès connus, en utilisant toutes les combinaisons possibles (prenom.nom, nom.prenom, nprenom, etc.), vous pouvez générer des centaines de milliers d'adresses e-mail, qui ont de fortes chances d'exister! Et c'est ce que font certains spammeurs.

#### Exemple de Spam

<img class="txtcenter img-border" src="{{ "/assets/img/spam.gif" | relative_url }}" alt="{{ site.title | escape }}" />

## Comment se protéger?

#### Surtout ne pas répondre à un message spam.
Les spammeurs utilisent généralement de fausses adresses d'envoi. Il est donc totalement inutile de répondre. De plus, si l’adresse de l’émetteur est correcte, vous ne feriez que renseigner cet émetteur sur la validité de votre adresse mail et recevoir plus de spams encore.

#### La meilleure solution reste la prévention.

* N’utilisez jamais publiquement l'adresse email confiée par votre fournisseur d'accès ou votre entreprise, réservez-la à un cercle restreint d'amis ou des collègues en lesquels vous avez toute confiance.
* Vérifiez que votre adresse email ne sera pas diffusée sans votre accord explicite. Certains fournisseurs d'accès ou prestataires peuvent automatiquement vous inscrire dans un annuaire web.
* Evitez au maximum la publication de votre adresse email sur des forums ou des sites Internet.
* Créez une ou plusieurs «adresses poubelles» servant uniquement à vous inscrire ou vous identifier sur les sites jugés non dignes de confiance.
* En cas de doute, saisissez une fausse adresse ou maquillez votre véritable adresse en utilisant par exemple la Spam Safe Notation .

#### Utilisation d´un logiciel Anti-spam
Il existe des dispositifs anti-spam permettant de repérer et, le cas échéant, de supprimer les messages indésirables sur la base de règles évoluées. On distingue généralement deux familles de logiciels anti-spam :

* Les dispositifs anti-spam côté client, situés au niveau du client de messagerie. Il s'agit généralement de systèmes possédant des filtres permettant d'identifier les spams, sur la base de règles prédéfinies ou d'un apprentissage. (Junk E-mail dans Outlook 2003)
* Les dispositifs anti-spam côté serveur, permettant un filtrage du courrier avant remise aux destinataires. Ce type de dispositif est de loin le meilleur, car il permet de stopper le courrier non sollicité en amont et d’éviter l'engorgement des réseaux et des boîtes aux lettres des internautes.
