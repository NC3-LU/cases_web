---
layout: article
title:  "Data Backups"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: knowhow
toc: true
ref: glossarydatabackups
lang: en
---
## In Brief
Backing up data is essential for any IT system. However, digital storage media are only reliable for certain periods. Just as the stone tablets used in antiquity were subject to the effects of bad weather, natural disasters and wear, any modern IT system is also fallible. For a company, the loss of data can result in a definitive halt to business. If you want to keep your essential data ([availability]({% link _knowhow/glossary/Availability.markdown %})), sooner or later you will have to think about backup strategies for it.

## Preliminary Thoughts
Before choosing a backup solution, it may be of use to carry out a risk analysis. The main risks facing most people are as follows (threats affecting the availability or integrity of data):

1. loss of data by deletion (human error or malicious software) (SMEs: see [Human error]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2HR.markdown %}#human-error-prevention-measures));
2. loss of data following a hardware fault (defective hard disk, accidental destruction of the storage media) (SMEs: see [Unusable backups]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware.markdown %}#unusable-backups), [Hardware damage during transport]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware.markdown %}#hardware-damaged-during-transport), [Failure of IT or communications equipment]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware.markdown %}#failure-of-it-or-communications-equipment), [Administration impossible]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Software.markdown %}#unavailability-of-administrators), [Unsuitable software environment]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Software.markdown %}#unsuitable-software-environment));
3. disaster (SMEs: see [Fire]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}#fire), water damage);
4. theft of storage media (SMEs: see [Infiltrating the premises]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}#infiltrating-the-premises), [Aggravated theft]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware.markdown %}#aggravated-theft)).

Thinking about the various risks listed above will point you towards the backup strategy to follow. For points 1 and 2 (the most common), it is enough to back up data onto an external hard drive, a network drive or removable storage media. For points 3 and 4 (rare events, but highly destructive), it is essential to have an off-site backup.

## Choice of Storage Media
The issue of choosing backup storage media is at least as important as choosing the strategy. The most common storage media are as follows:

* removable media (CD, DVD); very inexpensive, but have limited capacity and are quickly destroyed over time; these days it is no longer recommended to make backups using this type of storage media (except in very small volumes).
* External hard drives; inexpensive, offering higher storage capacities, fairly resistant to damage over time;
* Flash memories, SSD cards; more expensive than conventional hard disks, very quick, increasingly resistant to damage over time, but their price still makes them impractical for storing large quantities of data;
* Magnetic tapes; presenting good storage capacities, but expensive and impractical – these are reserved for very large quantities of data;
* online services (cloud); price, availability and durability depend on the supplier; thanks to current fibre-optic bandwidths, these services are now even accessible to very small businesses.

In any event, storage space will often be a determining factor, along with price and also backup feasibility. This leads us to the concept of organising a data repository.

## Backup Repository and Rotation
The backup frequency will indicate the amount of data lost in the event of an incident. If you back up your data once a week, you stand to lose a maximum of one week’s worth of data. Are you prepared to accept such a loss? Would it be more prudent to increase the backup frequency to once a day, for example? The answer to these questions will depend on each individual case.

Another problem is if you perform one backup per week and some malware destroys part of your documents one month previously without you realising it, you will lose data despite having a backup policy. This is why it is recommended to keep a record of numerous backups in your repository. As storage space is limited, it is best to choose a backup rotation method, determining which past backups to delete to make way for new backups. In the above example of one backup per week, it would be possible to keep the six last backups and cover more than one month.

A more suitable solution for larger structures would be to make daily backups and keep one week's worth of backups. Keep one backup per week for one month, keep one monthly backup for one year, and so on.

The classification level for the backups should correspond to that of the backed-up data. If the data is highly confidential, the backups should also be highly confidential.

## Types of Backup
To save space – which in the past was often very expensive – different types of backups are offered by most software in addition to data compression:

#### Full Backup
All data is backed up. This backup takes up the most space, but it is also the safest and the easiest to retrieve, as it contains all the data.

#### Incremental Backup
An incremental backup always follows either a full backup or another incremental backup and only contains files (of any type) that have changed since the last backup. To retrieve all the files, you need to have a series of backups since the last full backup. This type of backup uses up the least space.

#### Differential Backup
A differential backup covers only all the files that have changed since the last full backup. It uses more space than incremental backups, but only the last full backup along with the differential backup is needed to retrieve all the backed-up data.

#### File or System Backup
Your files are important, and it is crucial to keep them backed up in the event you lose any data. But have you thought about your system availability? What would happen if your hard disk broke down (or physically broke)? Yes, you would still have your important files in your backup arrangement, but you would have to buy a new disk, reinstall your operating system and finally reinstall all your software before being able to retrieve your photos and documents.

To avoid this type of issue, some software enables not only files to be backed up, but also the entire disk. This software uses what we call an 'image' of the disk, enabling the entire image to be copied to a new disk in the event of any breakdown, thereby saving a lot of time and effort.

## Comments

* If you opt for a backup system using an online service with a third-party company, make sure you check that your data is properly encrypted before sending it to the service provider servers; you should be the only party to hold the encryption key – your supplier should not be able to see your data.
* The most suitable digital storage media for very small companies (from a price, space, and durability standpoint) are external hard disks or online cloud service backups.

## Security Policy
Write and apply the following sectoral policies:

* [Organisation of security]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity.markdown %})
  * [Attribution of responsibilities]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity.markdown %}#attribution-of-responsibilities)
* [Classification and monitoring of resources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources.markdown %})
  * [Classification of and responsibility for resources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources.markdown %}#classification-and-responsibility-for-resources)
* [Physical and environmental security]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %})
  * [Physical security perimeter]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %}#physical-security-perimeter)
  * [Off-site equipment security]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %}#off-site-equipment-security)
* [Operational and communications aspects]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %})
  * [Documented procedures]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}#documentation-of-procedures)
  * [Data backups]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}#data-backups)
  * [Device security during transport]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}#device-security-during-transport)
* [Access control]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %})
  * [Access control policy]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#access-control-policy)
  * [Access rights management]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#access-rights-management})
* [Managing business continuity]({% link _knowhow/cisoapproach/SecurityPolicy-ManagingBusinessContinuity.markdown %})
  * [Operational continuity]({% link _knowhow/cisoapproach/SecurityPolicy-ManagingBusinessContinuity.markdown %}#operational-continuity)
