---
layout: article
title:  "Sites Web malicieux"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: knowhow
toc: true
ref: maliciouswebsites
lang: fr
---
En quelques mots
----------------
Internet nous offre des opportunités uniques, mais représente aussi une
plateforme de choix pour les
[cybercriminels]({%link _knowhow/glossary/Cybercriminals_fr.markdown %}). De fait,
le navigateur est une fabuleuse porte d’entrée pour les Logigiels
malveillants.

L’une des manières d’infection les plus répandues reste de leurrer, par
des techniques de [social engineering]({% link _knowhow/glossary/SocialEngineering_fr.markdown %}) les
internautes afin que ceux-ci téléchargent et installent eux-mêmes des
codes malicieux sans s’en rendre compte.

En exploitant des sentiments humains (social engineering) comme la
curiosité ou encore la peur, on pousse les internautes à installer «
faux [antivirus]({% link _knowhow/glossary/AntiVirus_fr.markdown %})», scareware ou
autres codes malicieux. Le malfaiteur fait p.ex. croire à la victime
potentielle que son ordinateur est infecté, instaurant ainsi un
sentiment de peur. Grâce à ce vecteur, le criminel incite alors
l’utilisateur à télécharger un « anti-virus » qui, en fait, n’est pas un
programme de protection, mais bien un cheval de Troie.

Plusieurs logiciels peuvent aider les internautes à reconnaître ces
différentes formes d’attaque basées sur l’ingénierie sociale. Il y a
p.ex. l’ajout du navigateur
[WOT]({% link _knowhow/glossary/WOT_fr.markdown %}) (Web of Trust), qui
met l’internaute en garde lorsque celui-ci visite une page web de pauvre
réputation. L'utilisateur devrait aussi prendre garde aux alertes émises
par les moteurs de recherche ou leur propre navigateur quand celles-ci
mettent en garde contre la navigation sur une certaine page.


Drive-by-download
-----------------
Le drive-by-download est une méthode d'infection des ordinateurs par des
codes malicieux en exploitant des [vulnérabilités techniques]({% link _knowhow/glossary/Vulnerabilities_fr.markdown %}#technical-vulnerabilities)
du navigateur. L'utilisateur n'est donc pas leurré à télécharger un code
malicieux, mais celui-ci tente, à l'insu de l'utilisateur, d'exploiter
des vulnérabilités du navigateur et d'infecter automatiquement la
machine.


Comment se protéger
-------------------
### Mesures comportementales

-   Veillez aux attaques de type [social engineering]({% link _knowhow/glossary/SocialEngineering_fr.markdown %}).
-   Sachez reconnaître les messages de votre propre logiciel anti-virus.
    Beaucoup de sites malicieux leurrent les internautes à télécharger
    un faux logiciel anti-virus en prétendant que la machine de
    l'internaute est infectée.

### Mesures organisationnelles

### Mesures techniques

-   Utilisez un filtre de navigation tel que
    [WOT]({% link _knowhow/glossary/WOT_fr.markdown %}) ou activez les
    filtres de vos navigateurs:
    -   [Smart screen de
        Microsoft](http://www.microsoft.com/fr-fr/security/online-privacy/smartscreen.aspx)
    -   [Phishing filtre de mozilla
        firefox](http://www.mozilla.org/en-US/firefox/phishing-protection/)
    -   [Google Chrome et sécurité du
        navigateur](http://www.google.com/chrome/intl/fr/more/security.html)
-   Installez une solution de filtrage web pour votre
    société, ainsi vous bloquez déjà beaucoup de sites malicieux.
-   Utilisez une solution de virtualisation ou similaire pour contenir
    les menaces éventuelles (voir p. ex.
    [sandboxie]({% link _publications/Sandboxie_fr.markdown %}))
