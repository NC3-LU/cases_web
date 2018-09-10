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
lang: en
---
## Operational continuity
[The operational continuity of the organisation]({% link _knowhow/glossary/DRP.markdown %}) implies that resources deemed to be important or vital (see [Classification and control of resources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources.markdown %})) should be in good working order under all circumstances.

Depending on their type, these resources may suffer the following damage:

* [deletion of data]({% link _knowhow/glossary/DataLoss.markdown %});
* intentional or accidental modification of data;
* simple or total breakdown of a piece of equipment or software (SMEs: see [Network access unavailable]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}#network-unavailability) and [Power cut]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}#power-cut) and [Discontinuity of service providers]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}#discontinuity-of-service-providers) and [Unusable backups]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware.markdown %}#unusable-backups) and [Failure of IT and communications equipment]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware.markdown %}#failure-of-it-or-communications-equipment) and [Administration impossible]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Software.markdown %}#unavailability-of-administrators));
* complete destruction of one or more pieces of equipment, or even of the entire infrastructure (incident such as a fire) (SMEs: see [Fire]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}#fire)).

A certain number of rules established in this document (see [physical security]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %})) are intended to reduce the likelihood of damage. However, it should be remembered that damage can occur and plans should be put in place for this eventuality.

One of the following scenarios should be chosen for each of the resources indexed in [Classification and control of resources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources.markdown %}):

* nothing planned.
* this is data: backups – especially off-site backups – are sufficient.
* an application: backups are sufficient.
* an application: backups are associated with a maintenance agreement with a qualified supplier which can reinstall and/or reconfigure the application in under XX days,
* hardware that can be repurchased, delivered and installed in less than XX days.
* hardware for which a maintenance agreement with the supplier guarantees it being restored to working order within a period of XX days.
* hardware for which we have backup hardware stored in XX premises.
* hardware for which we have an agreement with a supplier which guarantees an equivalent replacement being made available within XX hours/days.
* hardware with equivalent configuration which can be accessed on the XX site.

During the annual review of the list of resources, the question should be asked again to see if the same solution is still applicable and best suited to meet requirements.

Similarly, in the event of the total loss of premises and technological and IT resources, it would be better to plan for business to recommence in other premises within the shortest possible time. Resources which are non-essential, but which the company must have at minimum (e.g.: telephones and PCs) can be obtained from our suppliers within a specified time frame.
