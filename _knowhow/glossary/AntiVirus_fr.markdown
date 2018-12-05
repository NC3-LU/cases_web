---
layout: article
title:  "Antivirus"
menutitle:
logo:
date:   2017-11-06 00:00:00 +0100
short:
categories: knowhow
toc: true
ref: glossaryantivirus
lang: fr
---

En quelques mots
----------------

Les antivirus sont des logiciels dont le but est d'identifier et de
bloquer des [logiciels malveillants]({% link _knowhow/glossary/MaliciousCodes.markdown %})

Pour ce faire, ils emploient deux moyens :

-   Sur base des "signatures" des codes malicieux : dès qu'un nouveau
    code malicieux est découvert, il est analysé par les sociétés qui
    produisent des antivirus. Celles-ci établissent un protocole
    d'identification et d'éradication du code concerné. Elles
    transmettent ensuite ces informations aux logiciels des clients. Les
    tout nouveaux codes malicieux, ceux qui se transforment constamment,
    ou encore ceux qui ne sont utilisés que pour des attaques très
    ciblées, échappent à leur détection. De ce fait, les antivirus sont
    comparables à des ceintures de sécurité : leur protection est
    confirmée, mais pas absolue.

-   Sur base du "comportement" des codes malicieux : les anti-virus
    identifient les codes malicieux sur base des opérations que ceux-ci
    essayent d'exécuter (approche heuristique)

Les antivirus sont indispensables pour protéger les ordinateurs,
smartphones, tablets et serveurs contre les codes malicieux de plus en
plus nombreux et de plus en plus répandus.

Aucun système n'est infaillible aux attaques de codes malicieux,
d'autant plus qu'une machine est incapable de faire la différence entre
un code malicieux et un code légitime.



Les mesures supplémentaires
---------------------------


### Mesures comportementales

-   Un utilisateur qui détecte un fichier suspect ne doit pas l'ouvrir,
    peu importe qu'il l'ait reçu par [courrier électronique]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}#email) ou
    sur un [support amovible]({% link _knowhow/glossary/RemovableDevices.markdown %}).

-   Si l'on doit ouvrir un fichier et qu'il s'agit d'un fichier supposé
    contenir des données non-confidentielles, l'utilisateur peut le
    télécharger sur le site [virustotal](http://www.virustotal.com), qui
    offre d'analyser le fichier gratuitement par une multitude des
    logiciels.

-   Il peut aussi être bon d'attendre 3 à 4 jours avant de l'ouvrir. En
    effet s'il s'agit d'un nouveau [logiciel malveillant]({% link _knowhow/glossary/MaliciousCodes.markdown %}),
    ce laps de temps est nécessaire pour permettre aux producteurs de
    logiciels anti-virus de détecter le code, de l'analyser et de mettre
    à jour les bases de signatures anti-virus.

### Mesures organisationnelles

Au sein d'une organisation il importe:

-   d'éduquer l'utilisateur à reconnaître les fichiers suspects ou
    douteux et de le sensibiliser aux techniques de l'[ingénierie sociale]({% link _knowhow/glossary/SocialEngineering.markdown %});

-   d'établir des procédures claires et nettes pour la manipulation de
    fichiers suspects ou douteux;

-   d'avoir une personne de contact même pour les petits cas où un
    utilisateur aurait ouvert un fichier et cliqué sur un lien;

-   de rédiger et de faire respecter les [politiques de sécurité nécessaires]({% link _knowhow/glossary/AntiVirus.markdown %}]#security-policy);

### Mesures techniques

-   Les anti-virus doivent être mis à jour plusieurs fois par jour, afin
    que leurs bases de signatures soient constamment d'actualité.

-   Les anti-virus installés sur les postes de travail des utilisateurs
    et des différents serveurs devraient être différents, ceci pour
    pouvoir augmenter les chances de détection d'un code malicieux.

-   Lorsqu'un nouveau code malicieux est détecté par un expert de la
    sécurité, les producteurs de logiciels anti-virus nécessitent d'un
    certain temps (entre 1 à 4 jours) pour analyser ce code et mettre à
    jour leurs bases de signatures.

-   Mettez en place un service spécialisé pour analyser des fichiers
    suspects ou douteux. Le service informatique, respectivement un
    expert externe peut ouvrir les fichiers dans un environnement
    spécialisé.

-   En cas de suspicion d'infection, scannez votre ordinateur avec un
    antivirus sur live-cd.

-   Puisque certains codes malicieux
    ([vers](https://www.cases.lu/fr/logiciels-malveillants.html&WCE_section_83_1=3&WCE_section_83_1=3#147))
    exploitent des vulnérabilités techniques, il convient de toujours
    appliquer les
    [correctifs]({% link _knowhow/glossary/Patches.markdown %}) et
    mettre à jour le système d'exploitation ainsi que toutes
    applications utilisées sur le système concerné.

-   Puisque certains codes malicieux
    ([vers](https://www.cases.lu/fr/logiciels-malveillants.html&WCE_section_83_1=3&WCE_section_83_1=3#147))
    ont des mécanismes automatisés pour se répandre, il convient de
    [cloisonner le
    réseau](https://www.cases.lu/fr/la-segmentation-de-reseau.html) avec
    l'aide d'un
    [firewall](https://www.cases.lu/fr/pare-feu-firewall.html) et
    éventuellement de doter les ordinateurs d'un
    [pare-feu](https://www.cases.lu/fr/pare-feu-firewall.html). Ces
    système peuvent aussi aider à prévenir les exfiltration de données
    par des [chevaux de
    Troie](https://www.cases.lu/fr/logiciels-malveillants.html&WCE_section_83_1=4#149).


Politique de sécurité
---------------------



Rédigez et faites appliquer les politiques sectorielles suivantes:

-   [Organisation de la sécurité]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity.markdown %})
    -   [Procédure d’autorisation pour l’ajout d’outils de traitement de l’information]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity.markdown %}#authorising-the-addition-of-tools)
    -   [Accès par des tiers et sous-traitance]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity.markdown %}#third-party-access-and-outsourcing)
-   [Aspects humains]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown %})
    -   [La sécurité comme mission]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown %}#security-as-a-mission)
    -   [La formation et l’information]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown %}#training-and-information)
    -   [La réponse aux incidents et dysfonctionnements de sécurité]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown %}#response-to-incidents-and-malfunctions)
-   [Sécurité physique et environnementale]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %})
    -   [Périmètre de sécurité physique]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %}#physical-security-perimeter)
    -   [Règles dans le périmètre]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %}#rules-within-the-perimeter)
    -   [Sécurité des équipements hors des locaux]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %}#off-site-equipment-security)
-   [Aspects opérationnels et communications]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %})
    -   [Protection contre les logiciels malveillants]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}#protection-against-malware)
    -   [Sauvegarde des données]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}#data-backups)
    -   [Courrier électronique]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}#email)
      * [Access control]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %})
-   [Contrôle d’accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#access-rights-management)
    -   [Politique de contrôle d’accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#use-of-external-networks)
    -   [Gestion des droits d’accès](https://www.cases.lu/fr/polsec-controle-d-acces.html&WCE_section_265_1=2&WCE_section_265_1=2#597)
    -   [Utilisation de réseaux externes](https://www.cases.lu/fr/polsec-controle-d-acces.html&WCE_section_265_1=4&WCE_section_265_1=4#599)
    -   [Connexion de l’extérieur](https://www.cases.lu/fr/polsec-controle-d-acces.html&WCE_section_265_1=5&WCE_section_265_1=5#600)
    -   [Séparation de réseaux](https://www.cases.lu/fr/polsec-controle-d-acces.html&WCE_section_265_1=6&WCE_section_265_1=6#601)
-   [Gestion des incidents liés à la sécurité](https://www.cases.lu/fr/polsec-gestion-des-incidents-de-securite.html)
    -   [Signalement des événements liés à la sécurité de l’information](https://www.cases.lu/fr/polsec-gestion-des-incidents-de-securite.html&WCE_section_523_1=1#802)
    -   [Gestion des incidents et des améliorations de la sécurité de l’information](https://www.cases.lu/fr/polsec-gestion-des-incidents-de-securite.html&WCE_section_523_1=1#803)
    -   [Analyse des manquements avec obligations](https://www.cases.lu/fr/polsec-gestion-des-incidents-de-securite.html&WCE_section_523_1=1#804)
-   [Gestion de la continuité de l’entreprise](https://www.cases.lu/fr/polsec-gerer-la-continuite-de-l-entreprise.html)
    -   [La continuité de fonctionnement](https://www.cases.lu/fr/polsec-gerer-la-continuite-de-l-entreprise.html&WCE_section_287_1=1&WCE_section_287_1=1#605)
-   [Conformité](https://www.cases.lu/fr/polsec-conformite.html)
    -   [Propriété intellectuelle](https://www.cases.lu/fr/polsec-conformite.html&WCE_section_291_1=2&WCE_section_291_1=2#607)
    -   [Protection des données opérationnelles](https://www.cases.lu/fr/polsec-conformite.html&WCE_section_291_1=3&WCE_section_291_1=3#608)
    -   [Protection des données à caractère personnel](https://www.cases.lu/fr/polsec-conformite.html&WCE_section_291_1=4&WCE_section_291_1=4#609)


Les différents types d'antivirus
--------------------------------


### Les solutions pour ordinateurs


Les logiciels anti-virus sont des logiciels de protection importants qui
devraient être installés sur chaque machine, indépendamment du système
d'exploitation installé. De nombreuses solutions existent, mais
attention aucun antivirus n'est capable de détecter tous les codes
malicieux. Il est donc indispensable de suivre les **conseils
comportementaux liés aux courriers électroniques** ainsi que les
**conseils comportementaux liés à la manipulation des supports
amovibles**.

### Les solutions offertes par votre fournisseur d'accès à Internet

Les solutions offertes par votre fournisseur d'accès à Internet (FAI)
permettent de scanner les courriers électroniques ainsi que les
communications entre votre ordinateur et le site web que vous consultez.

À côté des avantages indéniables, ces solutions comportent néanmoins des
désavantages importants:

-   incapacité à scanner des contenus chiffrés, comme c'est notamment le
    cas lorsque vous consultez un site web en mode
    [SSL]({% link _knowhow/glossary/SSLTLS-EncryptionTechnologiesOnWeb.markdown %})
    ou si vous recevez des courriers électroniques chiffrés;

-   incapacité à scanner des fichiers que vous transférez depuis des
    supports amovibles comme notamment des DVD, CD, disques durs
    externes ou clés USB;

-   incapacité à scanner votre système et donc incapacité à trouver des
    **codes malicieux** qui auraient réussi à infecter votre ordinateur
    avant qu'ils ne soient répertoriés par l'antivirus;

-   vous ne pouvez pas choisir l'antivirus et ne savez pas si la
    solution est constamment tenue à jour.

Souscrire aux solutions de votre fournisseur d'accès à Internet est
certes une démarche utile, mais ne remplace pas les solutions locales
installées directement sur les ordinateurs ou les serveurs.

### Les solutions pour serveurs

Les antivirus pour serveurs sont plus ou moins les mêmes que pour
desktop. La différence réside dans certaines spécialisations de ces
antivirus. Par exemple, il est usuel de faire contrôler tous les e-mails
transitant par un serveur mail ou de vérifier les téléchargements des
clients sur un serveur proxy.


Modes de fonctionnement
-----------------------

La plupart des logiciels antivirus opèrent selon deux méthodes :

-   La protection en 'temps réel' ('realtime protection'), qui consiste
    à intercepter les codes malicieux dès qu'ils tentent d'infecter une
    machine.

-   L'inspection ponctuelle ('scan') de la machine, pour découvrir les
    codes malicieux qui ont déjà réussi à infecter le système. Le scan
    sera d'autant plus efficace si le code malicieux est inactif, par
    exemple lors de l'utilisation d'un système d'exploitation dit
    **'live' antivirus sur live-cd**.

Les logiciels antivirus inspectent donc en permanence tous les fichiers
qui sont traités par l'ordinateur, c'est-à-dire au moment de leur
entrée, pendant leur traitement
