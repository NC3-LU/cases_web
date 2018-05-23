---
layout: article
title:  "Data loss"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: knowhow
toc: true
---
<h3 class="titre-page" id="in-brief">In brief</h3>
We talk about loss of data when data is deleted or deteriorated in such a way as to make accessing it impossible. This situation may arise following various natural events (catastrophes), technical events (faults) or human actions (theft with destruction, or deliberate or accidental destruction).

We talk about corruption of data when part of the data has been modified, but access to the data itself has not been prevented.

Finally, we talk about data theft when a person accesses data which they ordinarily have no right to access, and which they extract fraudulently. Data theft can take place by copying or transferring data, or by printing it out. It may be accompanied by the destruction or corruption of the data.

<h3 class="titre-page" id="loss-of-data">Loss of data
To better understand this phenomenon and the methods of recovery, it is important to distinguish between:

### Loss of data due to loss of access to data
Various physical and logical circumstances may cause a loss of access to data. In the majority of cases, the data is still physically stored on the IT devices. But once they are no longer accessible, we talk about a loss of data. The recovery methods are different from those used to recover damaged or deleted data.

### Loss of data due to corruption of data
During certain fraudulent manipulations carried out by computer hackers on web servers, we see neither the destruction nor the theft of the data, but merely its corruption. The “cracker” can, for example, claim to have simply modified one data value somewhere. In this case, the authentic data is no longer accessible because it has been corrupted. This is equivalent to a loss of data.

Loss of data due to the corruption of data may also be caused by intentional or accidental illicit actions carried out on databases or files. This type of loss of data is usually more difficult to detect. (The data is still there, but it is incorrect.)

### Loss of data due to theft
Data theft does not necessarily result in its destruction or corruption. If the data is copied, transferred or printed, the originals remain unchanged. This is, moreover, one of the reasons why it is sometimes difficult to detect this type of loss.

The impact of confidential data theft (trade secrets, for example) can be significantly greater than a simple loss of data. We also talk about the loss of data confidentiality.

### Loss of data/loss of equipment due to theft
The loss or theft of laptop computers or any other IT device (cassette tape, floppy disk, CD-ROM –Compact Disk Read Only Memory, etc.) often results in the loss of data stored on these computer resources. Users rarely dispose of a saved copy entirely. The theft or loss of IT devices also runs a large risk of loss of data confidentiality.

### Loss of data due to intentional destruction

When the loss or corruption of data is not the result of a technical phenomenon, but a human attempt, it is important to distinguish between the following actions:

* malicious intentional (website hacking)
* non-malicious intentional (deleting a file)
* intentional (mishandling)

<h3 class="titre-page" id="preventative-measures">Preventative measures
Based on the analysis of actual cases, we can determine the areas directly affected by loss of data and assess the costs usually associated with this type of phenomenon.

### Storage solution suitable for requirements
It is important to adapt the storage technology to the degree of data sensitivity, as well as the type of data (office files, databases).

In order to avoid the storage infrastructure becoming quickly saturated and all the associated problems, it is necessary to implement a file archiving policy on suitable devices.

It is advisable to equip servers with [RAID](-) (Redundant Array of Independent/Inexpensive Disks) technology which distributes the storage of data over several hard drives. If one of the RAID hard drives is lost, the IT system is able to reconstruct the missing data. There are different levels of RAID configurations, which are discussed in a separate sheet.

The implementation of a SAN (Storage Area Network) cabled storage network may also prove useful for large infrastructures or the deployment of a second production or backup site.

### Adequate backup/restoration policies
Both the technologies and the backup and restoration policies must be adapted depending on the degree of sensitivity, as well as the nature of the data (office files, databases).

Technologies such as “snap shooting”, of which the aim is to create copies of changes to the database “on the go” during the day, prevent a return to the previous day’s situation and, in doing so, limit the need for any entry or recoding. This onerous and complex technology might be well-suited to a very complex type of use, but it is not necessary for the backup of normal office data.

The implementation of procedures known by everyone, respected and controlled, makes best use of the infrastructure in place, e.g. information given to users regarding the directories to be backed up on a daily basis.

The restoration time is, unfortunately, an underestimated necessity. The majority of IT managers are concerned with how long the backup takes, but are unaware of the restoration capabilities. However, in the event of a disaster, restoration is the critical element. A detailed look at the restoration and network architecture, confirmed by testing it, is still the best way to judge how well a solution meets the requirements.  

### Respect of correct usage in the IT room
The implementation of an IT architecture must meet certain environmental requirements. An IT room, a connectivity room, a telecommunications room, etc. must be fitted out in such a way as to ensure the equipment is operating under optimal conditions. This means: an emergency electrical supply or a UPS (Uninterruptible Power Supply), air conditioning and air filtering, static electricity control, a specific system to prevent water and file damage, and controlled access.

### Comments
All of these points are covered in a fact sheet on [physical security]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %}).

### Backup location
IT devices, such as cassette tapes, optical media and others must imperatively be stored in places that meet their requirements in terms of protection against dust, scratches, humidity and other factors that may cause them to deteriorate.

### Comments
It is advisable to store backup devices inside a safe, outside of the IT room or even in another building entirely.

### User rights management
To have the best chance of preventing accidental data deletion, there is the option of limiting user rights on files and critical devices as much as possible.

### Proactive management of the IT fleet
The majority of faults relating to the operation of IT equipment are preceded by warning signs. Most equipment comes supplied with software that analyses these signs and alerts the user in case of any issues. This software exists at both server level and on desktop computers (workstations) and laptops. It is advisable to let this software run and to pay attention to its warnings.

### User training
An effective solution to avoid mishandling is to train users in how to use their computer and its peripherals correctly, as well as in data and directory management.

<h3 class="titre-page" id="curative-measures">Curative measures
In this section, you will find all recovery measures to be taken after a disaster:

<h3 class="titre-page" id="recovery-software-or-companies">Recovery software or companies
There are a number of software programs that can recover lost or deleted data from a number of devices. This software is not necessarily expensive, but it does require a certain amount of expertise to use. It is therefore strongly recommended that you contact companies that specialise in this domain. However, you should request a service where payment is only made if the data can be recovered.

<h3 class="titre-page" id="comments">Comments
Security-conscious people are reminded that it is possible to recover deleted files. Making this sort of recovery impossible is always an option, and it is important to pay attention during the resale of IT equipment. (see [disposal]({% link _knowhow/sos/SOS-WhatBeforeGettingRidOldHardware.markdown %}))
