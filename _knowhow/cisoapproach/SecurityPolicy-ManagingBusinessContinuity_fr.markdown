---
layout: knowhow
title:  "Security Policy – Managing business continuity"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: f-ciso
toc: true
ref: cisomanagingbusinesscontinuity
lang: fr
---
## La continuité de fonctionnement

[La continuité de fonctionnement]({% link _knowhow/glossary/DRP_fr.markdown %}) de "l’organisation" implique que les ressources considérées comme importantes ou vitales (voir [Classification et maîtrise des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %})) soient en état de marche en toute circonstance.

Selon leur type, ces ressources peuvent subir les dommages suivants:

* [effacement des données]({% link _knowhow/glossary/DataLoss_fr.markdown %});
* modification intentionnelle ou accidentelle de données;
* panne simple ou totale d’un équipement ou d’un logiciel (PME: voir [Accès réseau indisponible]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure_fr.markdown %}#network-unavailability) et [Panne de courant]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure_fr.markdown %}#power-cut) et [Discontinuité des fournisseurs de service]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure_fr.markdown %}#discontinuity-of-service-providers) et [Sauvegardes inutilisables]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware_fr.markdown %}#unusable-backups) et [Equipement informatique ou de communication en panne]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware_fr.markdown %}#failure-of-it-or-communications-equipment) et [Administration impossible]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Software_fr.markdown %}#unavailability-of-administrators));
* destruction complète d’un équipement ou de plusieurs, voire de l'infrastructure entière (sinistre type incendie) (PME: voir  [Incendie]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure_fr.markdown %}#fire)).

Un certain nombre de règles établies dans le présent document (Voir [sécurité physique]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity_fr.markdown %})) ont pour objet de réduire la probabilité d’un endommagement. Néanmoins il faut envisager qu’il puisse se produire et le prévoir.

Pour chacune des ressources répertoriées en [Classification et maîtrise des ressources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources_fr.markdown %}) un des cas de figures suivants doit être choisi:

* rien n’est prévu.
* ce sont des données: les sauvegardes, et notamment celles qui sont sauvegardées à l'extérieur du site sont suffisantes.
* une application: les sauvegardes sont suffisantes.
* une application: les sauvegardes sont associées à un contrat de maintenance auprès d’un fournisseur qualifié qui pourrait réinstaller et/ou re-configurer l’application en moins de XX jours,
* un matériel que l’on peut racheter et se faire livrer et installer en moins de XX jours.
* un matériel pour lequel un contrat de maintenance avec le fournisseur nous garantit une remise en état dans un délai de XX jours.
* un matériel pour lequel nous disposons d’un matériel de secours stocké dans le local XX.
* un matériel pour lequel nous disposons d’un contrat avec un fournisseur qui nous garantit de mettre l’équivalent à disposition en xx heures/jours.
* un matériel pour lequel nous disposons d’une configuration équivalente qui est accessible sur le site de XX.

Lors de la révision annuelle de la liste des ressources, il convient de se reposer la question et savoir si la même solution est toujours d'actualité et la mieux adaptée pour répondre aux besoins.

De même, en cas de sinistre total des locaux et des ressources technologiques et d'informations, il vaut mieux avoir prévu que les activités pourraient reprendre dans d'autres locaux, et dans un délai de le plus court possible. Les ressources non essentielles, mais dont il faut disposer au minimum (ex: téléphones et PC), sont obtenues auprès de nos fournisseurs dans un délai connu.
