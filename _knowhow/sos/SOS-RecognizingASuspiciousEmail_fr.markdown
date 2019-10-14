---
layout: knowhow
category: "Knowhow"
title:  "SOS – Reconnaître un email suspect"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: f-sos
toc: true
ref: sosrecognizeweirdemail
lang: fr
---

## En quelques mots
Les [Email]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#email) est un des moyens de communication préférés des cybercriminels. Son utilisation est bon marché, elle ne demande aucune identification de la part de l'expéditeur et le service est très rapide.

Le courrier électronique sert d'outil à de nombreuses formes d'attaque. Ce chapitre vous apprendra à analyser le courrier électronique pour y reconnaître un courrier suspect, sans pour autant ouvrir les liens proposés, ni les pièces jointes.

## E-mail d'une banque
Sachez qu'une banque de détail luxembourgeoise n'envoie pas de courriers électroniques. Pour communiquer avec ses clients, elle choisira plutôt d'envoyer des courriers traditionnels, de communiquer via sa plate-forme 'e-banking' ou de faire appeler son client par le gestionnaire de compte connu de lui.

## Spam
On appelle [Spam]({% link _knowhow/glossary/SPAM-UnwantedEmails_fr.markdown %}) les courriers électroniques non sollicités. Ce peuvent être des publicités, mais aussi des hoax (faux messages) ou des attaques de type [phishing]({% link _knowhow/glossary/Phishing_fr.markdown %}). Votre fournisseur de service, respectivement votre client mail devrait avoir une fonctionnalité pour reconnaître et marquer le Spam.

N'ouvrez pas le Spam, sauf si vous êtes certain que le courrier a été marqué à tort comme Spam. Ne répondez en aucun cas au Spam, cela confirmerait à son auteur que l'adresse de courrier électronique est valide.

## Courrier impersonnel
Si vous recevez un courrier impersonnel, soyez vigilants : il s'agit probablement d'un [email]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects_fr.markdown %}#email) de type [spam]({% link _knowhow/glossary/SPAM-UnwantedEmails_fr.markdown %}).

Un correspondant légitime, connaissant votre adresse e-mail, devrait disposer de vos données signalétiques et les utiliser pour s'adresser à vous comme il convient.

Manipulez ce type de courrier électronique avec beaucoup de précautions. Si le courrier contient un des indices décrits dans les rubriques suivantes, évitez de réagir.

## Courrier insinuant l'urgence
Si le courrier électronique est impersonnel et insinue l'urgence, il s'agit très probablement d'un hoax ou d'un [phish]({% link _knowhow/glossary/Phishing_fr.markdown %}). Ne réagissez pas à la demande et ignorez ce courrier électronique. (Voir : [Email – bonnes pratiques]({% link _knowhow/bestpractices/EMail-BestPractices_fr.markdown %})).

## Courrier contenant un lien
Si le courrier électronique est impersonnel et contient un lien, il s'agit très probablement d'un courrier essayant de vous attirer sur un [site web malicieux]({% link _knowhow/glossary/MaliciousWebsites_fr.markdown %}) ([phishing]({% link _knowhow/glossary/Phishing_fr.markdown %}) ou infection par [codes malicieux]({% link _knowhow/bestpractices/MaliciousSoftwareBP_fr.markdown %}) exploitant des [vulnérabilités techniques]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance_fr.markdown %}#managing-technical-vulnerabilities)). Dans tous les cas, laissez ce lien fermé. (Voir : [Email – bonnes pratiques]({% link _knowhow/bestpractices/EMail-BestPractices_fr.markdown %})).

## Courrier avec pièce jointe
Si le courrier électronique est impersonnel et contient un lien, il s'agit très probablement d'un courrier essayant de vous attirer sur un site web malicieux (phishing ou infection par codes malicieux exploitant des vulnérabilités techniques). Dans tous les cas, laissez ce lien fermé. (Voir : [Email – best practices]({% link _knowhow/bestpractices/EMail-BestPractices_fr.markdown %}))

## Courrier personnel
Même si le courrier électronique vous est correctement adressé, restez vigilants, et vérifiez les indices décrits ci-joint :

### Expéditeur connu
Vous connaissez et faites confiance à l'expéditeur. Le courrier électronique est attendu respectivement a été annoncé lors de communications antécédentes : vous pouvez faire confiance au courrier et au contenu. Vous devez cependant rester prudent quant à la manipulation des pièces jointes, qui peuvent malgré tout contenir des [codes malicieux]({% link _knowhow/bestpractices/MaliciousSoftwareBP_fr.markdown %})  respectivement des liens amenant sur des [sites web malicieux]({% link _knowhow/glossary/MaliciousWebsites_fr.markdown %}).

Au cas où l'expéditeur est connu, mais s'adresse à vous d'une manière différente que d'habitude, soyez très prudent. L'utilisation d'une autre langue, d'un autre style d'écriture ou la présence de fautes d'orthographe inhabituelles sont des indices très importants pour estimer ce courrier électronique comme illicite. Manipulez-le avec précaution et appelez l'expéditeur (connu) pour vous assurez qu'il provient vraiment de lui.

(Voir : [Email – best practices]({% link _knowhow/bestpractices/EMail-BestPractices_fr.markdown %}))

### Expéditeur inconnu
Vous recevez un courrier d'un expéditeur inconnu et  le courrier ne s'inscrit pas dans un contexte connu et strictement professionnel. Restez vigilant quant à la manipulation du contenu, respectivement des pièces jointes.

Le courrier peut contenir des pièces jointes infectées par [code malicieux]({% link _knowhow/bestpractices/MaliciousSoftwareBP_fr.markdown %}) , ou vous inciter à visiter un [site web malicieux]({% link _knowhow/glossary/MaliciousWebsites_fr.markdown %}) en suivant le lien affiché dans le courrier.

(Voir : [Email – best practices]({% link _knowhow/bestpractices/EMail-BestPractices_fr.markdown %}))
