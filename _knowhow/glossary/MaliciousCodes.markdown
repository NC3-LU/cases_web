---
layout: article
title:  "Malicious Codes"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short: "Security Measures"
categories: knowhow
toc: true
ref: glossarymaliciouscode
lang: en
---

## In brief
Les logiciels malveillants ou codes malicieux sont des logiciels qui infectent la machine d'un utilisateur à son insu. L'[impact]({% link _knowhow/glossary/Impact.markdown %}) de l'infection peut être multiple, comme notamment la perte de [confidentialité]({% link _knowhow/glossary/Confidentiality.markdown %}), d'[intégrité]({% link _knowhow/glossary/Integrity.markdown %}) ou de [disponibilité]({% link _knowhow/glossary/Availability.markdown %}) des actifs d'une entité. Une infection par codes malicieux ne se remarque pas toujours, parfois elle est même très difficile à détecter.

L'infection peut avoir lieu en incitant la victime par des méthodes d'[ingénierie sociale]({% link _knowhow/glossary/SocialEngineering.markdown %}) (social engineering) par exemple, à ouvrir un fichier annexé à un [courrier électronique]({% link _knowhow/bestpractices/EMail-BestPractices.markdown %}), à ouvrir un fichier se trouvant sur un [support amovible]({% link _knowhow/glossary/RemovableDevices.markdown %}) ou simplement à motiver la victime à visiter une [page web malicieuse]({% link _knowhow/glossary/MaliciousWebsites.markdown %}).

Les codes malicieux peuvent avoir différents [impacts]({% link _knowhow/glossary/Impact.markdown %}). Ils présentent une [menace]({% link _knowhow/glossary/Threat.markdown %}) considérable et peuvent selon le type soit exploiter des [vulnérabilités humaines]({% link _knowhow/glossary/Vulnerabilities.markdown %}#human-vulnerabilities) soit des [vulnérabilités techniques]({% link _knowhow/glossary/Vulnerabilities.markdown %}#technical-vulnerabilities).

## Les virus
Un virus est un logiciel, ou une partie de logiciel qui, pour pouvoir se propager, s'attache à tout type de fichier ou autre logiciel dans le but d'infecter la machine concernée, ainsi que d'autres, à l'insu des utilisateurs.

Un virus s'active en général dès qu'une personne ouvre le fichier (attaché à un [courrier électronique]({% link _knowhow/bestpractices/EMail-BestPractices.markdown %}) ou se trouvant sur un [support amovible]({% link _knowhow/glossary/RemovableDevices.markdown %})) ou exécute le logiciel hébergeant le virus. En conséquence, le créateur du virus essayera d'inciter la victime potentielle à ouvrir le fichier infecté en exploitant des [vulnérabilités humaines.]({% link _knowhow/glossary/Vulnerabilities.markdown %}#human-vulnerabilities)

Dès qu'un virus a été lancé, il va essayer deux choses :

1. lancer son payload, c'est-à-dire ses fonctionnalités malicieuses;

2. essayer de se propager en utilisant des canaux de distribution comme le réseau de l'entreprise, les courriers électroniques ou encore les supports amovibles.

Il est donc vivement conseillé d'ignorer les fichiers joints provenant de personnes qui nous sont inconnues, ou des contenus dans des mails ou sur des supports informatiques qui suscitent notre méfiance.

## Les vers
Contrairement au virus, un ver n'a pas besoin de l'intervention humaine pour infecter une machine. Il dispose d'un « moteur » (automatisme) qui lui permet dans un premier temps de délivrer et d'exécuter automatiquement son code malicieux -

Morris worm - Le Morris Worm du nom de son créateur « Robert Morris » a été un des premiers vers (1988) à se propager rapidement sur Internet et à infecter un grand nombre de machines.

## Cheval de Troie
Le terme 'cheval de Troie' apparaît dans la mythologie grecque, notamment dans l'Iliade de Homer qui raconte l'histoire des Grecs décidés à envahir la ville de Troie. Se servant d'une ruse pour assaillir cette ville bien protégée, ils firent construire un grand cheval de bois et l'envoyèrent à Troie en guise de cadeau et de signe de paix. Le peuple de Troie apprécia ce geste et emmena le cheval dans la ville. Pendant la nuit quelques soldats grecs, abrités à l'intérieur du cheval en bois, sortirent de leur cachette et ouvrirent les portes de la ville au reste de l'armée, qui s'en empara.

Par analogie un cheval de Troie est un logiciel espion installé sur une machine dans le but d'ouvrir une porte dérobée à l'[attaquant]({% link _knowhow/glossary/Cybercriminals.markdown %}). A la différence d'un virus ou d'un ver, un cheval de Troie n'a pas vocation à se reproduire ou à se propager. Mais tout comme les virus, les chevaux de Troie se cachent dans des fichiers anodins et exploitent souvent des [vulnérabilités humaines]({% link _knowhow/glossary/Vulnerabilities.markdown %}#human-vulnerabilities) pour être lancés.

En général, le cheval de Troie sert à créer et à maintenir un accès permanent non-autorisé sur une machine, lorsque cette dernière est connectée à Internet. Le nombre de « trojans » est aussi impressionnant que la variété des actions qu'ils permettent aux attaquants sur les ordinateurs cibles.

Certains ouvrent simplement un accès à des fichiers de la machine, d'autres permettent une véritable interaction avec la machine infectée depuis Internet ou un réseau local.

## Les spyware
Un spyware est un logiciel espion. C'est un programme conçu dans le but de collecter sans autorisation des données personnelles sur les utilisateurs, et de les envoyer à son concepteur, ou à un tiers, via Internet ou tout autre réseau informatique. Les spywares ont pour objectif primaire d’espionner le comportement de l’internaute et de transmettre les informations collectées aux créateurs et éditeurs de logiciels afin d’alimenter une gigantesque base de données.

Un spyware « s’attrape » en général en naviguant sur Internet, ainsi qu'en téléchargeant des logiciels.

Il existent différents types de spyware :

### **LES SPYWARES COMMERCIAUX**
Les spywares commerciaux collectent des données sur leurs utilisateurs et interagissent de manière visible avec eux, en gérant l'affichage de bannières publicitaires ciblées, en déclenchant l'apparition de fenêtres pop-up, voire en modifiant le contenu des sites web visités afin d'y ajouter par exemple des liens commerciaux. Ce sont les spywares les plus courants. Leur existence est généralement mentionnée dans la licence d'utilisation du logiciel concerné, mais souvent de manière ambiguë et/ou dans une langue étrangère, ce qui fait que l'utilisateur n'est pas clairement informé.

### **LES MOUCHARDS**
Les mouchards collectent également des données sur leurs utilisateurs, mais le font dans la plus totale discrétion. La surveillance et la réutilisation éventuelle des données collectées se font à l'insu des utilisateurs, généralement dans un but de collecter des statistiques, des informations de marketing, de débogage ou de maintenance technique, voire de cyber-surveillance. L'existence de ces mouchards est délibérément cachée aux utilisateurs.

### **LE SPYWARE INTÉGRÉ**
Le spyware intégré (ou interne) est un programme exécutable inclus dans le code source d'un logiciel ayant une fonction propre, pour lui donner la possibilité de collecter et de transmettre des informations par Internet. Ces spywares sont téléchargeables séparément ou sont proposés à l'installation en même temps que d'autres programmes gratuits, eux-mêmes généralement des spywares, grâce à des accords entre éditeurs de logiciels.

### **LE SPYWARE EXTERNALISÉ**
Le spyware externalisé est une application autonome dialoguant avec le logiciel principal qui lui est associé, et dont la seule fonction est de se charger de la "relation client" : collecte et transmission d'informations, affichage de bannières publicitaires, etc. Ces spywares sont conçus par des régies publicitaires ou des sociétés spécialisées.

## Comment se protéger?

### **MESURES COMPORTEMENTALES**

* Il est indispensable de suivre les conseils comportementaux liés aux courriers électroniques, les conseils par rapport à la manipulation de supports amovibles et ceux concernant les sites web malicieux. Respectez les bonnes pratiques par rapport aux logiciels malveillants.

### **MESURES ORGANISATIONNELLES**

L'organisme doit rédiger et faire respecter plusieurs politiques sectorielles :

* [Classification et maîtrise des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources.markdown %})
  * [Classification et responsabilité des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources.markdown %}#classification-and-responsibility-for-resources)
* [Aspects humains]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown %})
  * [La sécurité comme mission]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown %}#security-as-a-mission)
  * [La formation et l’information]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown %}#training-and-information)
  * [La réponse aux incidents et dysfonctionnements de sécurité]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown %}#response-to-incidents-and-malfunctions)
* [Aspects opérationnels et communications]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %})
  * [Protection contre les codes malveillants]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}#protection-against-malware)
  * [Courrier électronique]({% link _knowhow/bestpractices/EMail-BestPractices.markdown %})
* [Contrôle d’accès]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %})
  * [Utilisation de réseaux externes]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#use-of-external-networks)
  * [Connexion de l’extérieur]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#external-connections)
  * [Séparation de réseaux]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#separation-of-networks)
* [Gestion de la continuité de l’entreprise]({% link _knowhow/cisoapproach/SecurityPolicy-ManagingBusinessContinuity.markdown %})
  * [La continuité de fonctionnement]({% link _knowhow/cisoapproach/SecurityPolicy-ManagingBusinessContinuity.markdown %}#operational-continuity)

### **MESURES TECHNIQUES**
L'utilisation d'un [antivirus]({% link _knowhow/glossary/AntiVirus.markdown %}) peut aider contre l'infection par des codes malicieux.

La [segmentation de réseaux]({% link _knowhow/glossary/NetworkSegmentation.markdown %}) à l'aide d'un [firewall]({% link _knowhow/glossary/Firewall.markdown %}) peut protéger contre l'infection par des codes malicieux de type 'vers', ainsi que contre l'extraction de données par des chevaux de Troie.

La mise à jour des [correctifs (patch)]({% link _knowhow/glossary/Patches.markdown %}) de toutes les applications, ainsi que du système d'exploitation peut aider contre l'infection par des codes malicieux de type 'vers'.
