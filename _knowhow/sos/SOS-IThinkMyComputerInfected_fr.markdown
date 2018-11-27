---
layout: knowhow
title:  "SOS – Je crois que mon ordinateur est infecté"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: f-sos
toc: true
ref: sosmycomputerinfected
lang: fr
---

## En quelques mots
De nos jours, il est très difficile de reconnaître si une machine est infectée. Les [cybercriminels]({% link _knowhow/glossary/Cybercriminals_fr.markdown %}) essayent surtout de déployer des [chevaux de Troie ]({% link _knowhow/glossary/MaliciousCodes_fr.markdown %}#cheval-de-troie) pour pouvoir extraire des données (espionnage), respectivement d'utiliser l'ordinateur pour des attaques de grande envergure ('déni de service distribué'), pour envoyer du [spam]({% link _knowhow/glossary/SPAM-UnwantedEmails_fr.markdown %}) ou autres usages illicites.

Certaines infections ne sont pas un but en soi et beaucoup d'infections initiales ne chargent qu'un logiciel d'installation. Dans ce cas, l'accès aux ordinateurs infectés est revendu au meilleur offrant qui peut alors utiliser l'installateur (trojan loader) pour installer le cheval de Troie définitif.

Les vecteurs d'infection les plus utilisés sont :

* Les [sites web malicieux]({% link _knowhow/glossary/MaliciousWebsites_fr.markdown %}) (sites à grande fréquentation qui ont été infectés, ou sites web malicieux sur lesquels les victimes sont leurrés par des publicités affichées sur des sites ou dans des courriers électroniques, respectivement par des liens contenus dans des [emails]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#email));
* les pièces jointes infectées;
* les [supports amovibles]({% link _knowhow/glossary/RemovableDevices_fr.markdown %}).

Pour prévenir des logiciels malveillants, respectez les [bonnes pratiques]({% link _knowhow/bestpractices/MaliciousSoftwareBP_fr.markdown %}) .

## Analyse des risques
Essayez d'effectuer une analyse des risques pour vérifier si vous êtes devenu victime d'une attaque ciblée ou opportuniste. Ces questions peuvent vous aider :

* Quelle est la probabilité que quelqu'un veuille vous espionner ?
* Possédez-vous des données qui pourraient intéresser d'autres sociétés ?
* Travaillez-vous pour le secteur militaire ?
* Travaillez-vous pour un service gouvernemental ?
* Avez-vous accès, en tant que sous-traitant, à des données hautement confidentielles ?
* Êtes-vous en train de répondre à un important appel d'offre ?
* Faites-vous partie d'un consortium international qui répond à un appel d'offre ?

Si vous répondez à l'affirmative à l'une de ces questions, il est probable qu'un cybercriminel puisse s'intéresser à vous et lancer une attaque ciblée. Dans les autres cas, il est probable que vous ayez été victime d'une attaque de type opportuniste. Votre machine sera revendue au meilleur offrant.

Un autre indice pour déterminer s'il s'agit d'une attaque ciblée ou volontaire, prenez en considération les moyens utilisés par l'agresseur pour vous infecter. Un courrier impersonnel oriente vers la possibilité d'une attaque opportuniste, alors que le courrier personnel renforce l'option d'une attaque ciblée.

## Victime d'une attaque opportuniste
Certains cybercriminels essayent par des attaques opportunistes d'infecter autant de machines que possible. Ces criminels se sont spécialisés dans "l'acquisition" de machines et n'installent qu'un logiciel autorisant l'accès à distance. Souvent ils essayent de répartir les victimes selon le pays, de catégoriser les citoyens et les entreprises, et essayent parfois même d'identifier clairement la victime infectée. (La qualité du profilage des machines infectées augmente leur prix de vente.) Ensuite ils revendent l'accès à ces machines au meilleur offrant. Ces derniers vont alors installer, via le logiciel d'accès à distance, des logiciels malveillants spécialisés selon leurs besoins :

* vol de données d'authentification ou autres données confidentielles (e-banking, e-commerce, réseaux sociaux, e-mails,...);
* utilisation de la machine infectée pour envoyer du spam ;
* utilisation de la machine infectée pour héberger des serveurs web malicieux, ou des serveurs avec des contenus illicites;
* utilisation des machines pour faire de attaques de type déni de service, comme proxy, pour cliquer sur des liens;
* attaques ciblées.

Les attaques opportunistes étant généralement des attaques de grande envergure, les codes malicieux utilisés pour garantir l'accès à distance ne seront, dans le meilleur des cas, que détectés après quelques jours par les fournisseurs de logiciels [anti-virus]({% link _knowhow/glossary/AntiVirus_fr.markdown %}). En général il est probable que l'antivirus résident ne détecte jamais les logiciels malveillants après détection et qu'il faille recourir à un live cd antivirus pour une meilleure détection.

## Victime d'une attaque ciblée
Contrairement aux attaques opportunistes, à large échelle, les attaques ciblées se concentrent généralement sur une victime spécifique, et souvent en visant une seule personne faisant partie de l'organisme visé. Des [codes malicieux]({% link _knowhow/bestpractices/MaliciousSoftwareBP_fr.markdown %}) sont spécialement conçus pour ce genre d'attaque et échappent dans la plupart des cas à l'interception par les [anti-virus]({% link _knowhow/glossary/AntiVirus_fr.markdown %}). Les attaques ciblées peuvent utiliser comme vecteur d'infection :

* l'achat d'accès à une machine d'un organisme spécifique auprès d'un délinquant effectuant des attaques opportunistes ;
* [l'ingéniérie sociale]({% link _knowhow/glossary/SocialEngineering_fr.markdown %}) par courrier électronique, avec fichiers infectés (PME : voir  [Spam / Phishing]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2HR_fr.markdown %}#spam--phishing), [Social engineering / Communication inadéquate]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2HR_fr.markdown %}#manipulation-of-people));
* l'ingénierie sociale par accès physique et infection des machines ciblées (PME : voir [Pénétration dans les locaux]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure_fr.markdown %}#infiltrating-the-premises), [Insertion ou suppression de matériels]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware_fr.markdown %}#addition-or-removal-of-hardware), [Utilisation de logiiels non approuvés]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Software_fr.markdown %}#use-of-unapproved-software), [Utilisation d’un accès réservé à un utilisateur par un tiers]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2HR_fr.markdown %}#use-of-limited-access-by-a-third-party));
* l'ingénierie sociale par accès physique et dépôt de [supports amovibles]({% link _knowhow/glossary/RemovableDevices_fr.markdown %}) infectés (PME: voir [Pénétration dans les locaux]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure_fr.markdown %}#infiltrating-the-premises), [Insertion ou suppression de matériels]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware_fr.markdown %}#addition-or-removal-of-hardware));
* l'ingénierie sociale par envoi de courrier physique contenant des supports amovibles infectés ;
* l'ingénierie sociale en offrant un cadeau infecté (lors d'une conférence, d'une foire,...) ;
* l'ingénierie sociale en attirant la victime sur un [site web malicieux]({% link _knowhow/glossary/MaliciousWebsites_fr.markdown %});
* l'infection du matériel informatique laissé sans surveillance (aéroports, hôtels, salles de conférence,...) (PME : voir [Pénétration dans les locaux]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure_fr.markdown %}#infiltrating-the-premises), [Insertion ou suppression de matériel]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware_fr.markdown %}#addition-or-removal-of-hardware), [Utilisation de logiciels non approuvés]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Software_fr.markdown %}#use-of-unapproved-software), [ Utilisation d’un accès réservé à un utilisateur par un tiers]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2HR_fr.markdown %}#use-of-limited-access-by-a-third-party), [Spam / Phishing]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2HR_fr.markdown %}#spam--phishing), [social engineering / Communication inadéquate]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2HR_fr.markdown %}#manipulation-of-people)).

Il est très difficile de reconnaître une attaque de ce type. Ces codes ne font pas de "bruit", puisqu'ils ne se propagent pas, ou que très lentement, et font tout pour rester inaperçu et pouvoir extraire aussi longtemps que possible des informations confidentielles.

L'activité du logiciel malveillant peut éventuellement être repérée dans les logs du firewall ou du proxy.

## Nettoyage d'une machine infectée
It is often difficult to tell whether a machine is infected, and it is even more difficult to clean it. The effort made and the method chosen need to be sufficient to match the criticality of the machine concerned.

* S'il s'agit plutôt d'une attaque opportuniste et que la machine ne contient pas de données confidentielles et n'est pas utilisée pour des opérations critiques, comme notamment le e-banking, vous pouvez essayer de désinfecter la machine :
  * votre antivirus ne détecte probablement pas l'infection, car s'il connaissait le code malicieux employé, il aurait dès le départ prévenu l'infection. Retirez la machine du réseau et essayez donc tout de suite de [désinfecter la machine avec le live cd d'un autre revendeur antivirus]({% link _knowhow/glossary/DisinfectWithLiveCD_fr.markdown %}). Ou mieux encore, attendez quatre à cinq jours avant ce nettoyage : un code malicieux récent passe inaperçu pendant les premiers jours et les fabricants d'anti-virus nécessitent ce laps de temps pour mettre à disposition une signature dans les antivirus. Attention : une désinfection par un antivirus peut éventuellement effacer des fichiers systèmes infectés. La machine risque donc de ne plus fonctionner après la désinfection; il faudra alors procéder à la réparation du système à l'aide d'un disque d'installation voire à la reinstallation du système.
* Si vous savez à quel moment votre machine a été infectée et que vous avez des sauvegardes de votre disque faites à un moment antérieur, vous pouvez essayer de restaurer la sauvegarde. N'oubliez pas de refaire toutes les mises à jour nécessaires après la restauration du système.
* Dans les autres cas nous vous conseillons une réinstallation complète:
  * sauvegardez vos données sur disque externe;
  * formatez le disque et réinstallez depuis un disque d'installation de préférence (il y a une petite chance que la partition de remise à zéro soit aussi infectée).
