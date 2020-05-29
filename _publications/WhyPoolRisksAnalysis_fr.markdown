---
layout: publication-list
category: "In depth articles"
title:  "Pourquoi mutualiser l'analyse des risques ?"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short: "Pourquoi mutualiser l'analyse des risques ?"
categories: securing
toc: true
ref: whypoolrisksanalysis
lang: fr
---
L’[analyse des risques]({% link _publications/WhyManageRisks_fr.markdown %}) consiste à identifier les scénarios d’attaque provoquant les plus graves impacts et à proposer un traitement pour atténuer leurs conséquences.

La difficulté de cet exercice réside dans l’obligation **d’être exhaustif et aussi exact que possible**. Des oublis au niveau des [actifs]({% link _knowhow/glossary/Assets_fr.markdown %}) ou des **estimations erronées** de la probabilité des [menaces]({% link _knowhow/glossary/Threat_fr.markdown %}), de l’aisance d’exploitation des [vulnérabilités]({% link _knowhow/glossary/Vulnerabilities_fr.markdown %}) ou encore des impacts causés mèneraient à des conclusions erronées… et à des **mesures de sécurité non appropriées**.

Dans le meilleur des cas, ces mesures seraient trop sévères, et dans le pire des cas, elles seraient inefficaces puisque mal ciblées. Pour être efficace dans l’exercice d’une analyse des risques, il faut donc avoir une bonne perception des actifs primaires de l’organisation ; connaître parfaitement les processus métier les informations ainsi que leurs valeurs.

L’analyse des risques est malheureusement un exercice très difficile pour toutes les petites structures qui ne seront généralement pas capables de faire cet exercice &nbsp;avec les moyens du bord. L’analyse des risques est discriminatoire autant par sa complexité que par son coût.

Cependant l’analyse des petites structures comme les PME, les communes &nbsp;ou encore les petites administrations montre **que les processus métiers, les informations traitées, les actifs de support utilisés sont assez semblables**. De cette constatation découle une solution pragmatique et simple. Dans un même secteur d’activité, **on peut mutualiser les efforts d’analyse de risques** pour la rendre accessible même aux plus petites structures, tout en préservant la qualité des résultats générés.

Par exemple, en analysant les processus métier des communes, on se rend compte que toutes les communes traitent en gros les mêmes quarante-six processus et les mêmes types de données. En y regardant de plus près, on se rend compte qu’ils utilisent tous plus ou moins les mêmes actifs secondaires (avec les mêmes vulnérabilités) et sont &nbsp;exposés aux mêmes menaces. Même les impacts potentiels sont similaires et surtout du type judiciaire et de réputation.

Ainsi fut lancée l’idée de construire des modèles contextuels décrivant :

* les processus métier,
* les informations,
* les impacts potentiels et
* les scénarios d’attaque type existants dans ce contexte…

**Les responsables des différentes structures n’ont pas besoin de refaire chacun cet exercice, mais peuvent avoir accès à un modèle spécifique à leur contexte**. La seule chose qu’ils doivent encore faire c’est identifier leurs spécificités et les entrer dans le modèle.

La probabilité des **menaces**, , hors de la portée des organisations, est estimée par contexte. Cette estimation résulte pour la plupart des cas de l’expérience des experts luxembourgeois travaillant dans le domaine de la veille des menaces, c'est-à-dire les  [CERTs](www.cert.lu). Les organismes n’ont qu’à renseigner la probabilité des menaces spécifiques, comme notamment des attaques ciblées pour des raisons diverses comme p.ex. la vengeance.

L’estimation de l’aisance d’exploitation des **vulnérabilités** , propres aux actifs de supports, peut dans la majorité des cas être mutualisée. Les experts pour ces métriques sont généralement les fournisseurs. Ceux-ci publient de façon régulière des alertes concernant des vulnérabilités dans leurs produits. Puisque les CERTs luxembourgeois font aussi une veille de ces vulnérabilités, ils peuvent **mettre à disposition des différents contextes des échelles réelles**. Bien sûr, certaines vulnérabilités sont propres à certaines structures et doivent être renseignées par les organismes eux-mêmes respectivement les experts qui les accompagnent dans la démarche (p.ex. vétusté des bâtiments).

**Les impacts**  sont aussi souvent spécifiques aux différents contextes. Ceux-ci peuvent même être définis par une instance centrale (un régulateur). Ainsi l’impact judiciaire d’une commune A est le même que pour la commune B en cas de perte de confidentialité au niveau du fichier des citoyens. Donc même les différents impacts peuvent être gérés de façon mutuelle.

**La mutualisation** de cette approche ne rend l’analyse de risques non seulement **plus objective et correcte, mais aussi accessible à des non experts**. La mutualisation réduira de façon conséquente les coûts car elle autorise la mise en place de mesures de sécurité efficaces et efficientes et donc à minimiser le budget investi dans la sécurité tout en garantissant un niveau de sécurité acceptable.

La mutualisation réduit aussi le **risque juridique** (voir [aspects légaux]({% link _knowhow/BestPractices-ProtectingYourself_fr.markdown %}#common-methods)) pour les différentes organisations, car cette approche prouve que l’organisation a géré la sécurité en bon père de famille en employant des méthodes et outils ‘state of the art’ tel qu’exigé par la loi du 2 août 2002 sur la protection des données à caractère personnel.

En plus, cette approche d’analyse de risque ne doit pas être un «one shot». Pour être efficace, il faut prendre en compte **l’évolution des menaces**, des **vulnérabilités** et des **impacts**. L’analyse de risque doit être refaite dès qu’un de ces paramètres change.

La loi du 2 août 2002 sur la [protection des données à caractère personnel]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance_fr.markdown %}#protection-of-operational-data) est un bon exemple de changement des impacts. La loi a introduit beaucoup de nouvelles exigences du point de vue de la sécurité du traitement des données à caractère personnel. Beaucoup d’entreprises n’ont pas encore pris en compte cette loi et ne sont même pas conscientes de ses impacts. Le **nouveau règlement européen en préparation** va même intensifier les exigences et augmenter davantage les impacts judiciaires potentiels.
