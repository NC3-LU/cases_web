---
layout: article
title:  "Disposal"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: knowhow
toc: true
ref: glossarydisposal
lang: fr
---
## In brief
Data that belongs to you or which you process using your computer has different levels of [confidentiality]({% link _knowhow/glossary/Confidentiality.markdown %}). You probably don’t treat data you post on [social networks](-) and that which you keep solely on your hard drive in the same way. Customer information, your company’s strategic data, texts, letters or [emails]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}#email) constitute only the visible part of your behaviour on the computer. In addition to that, a certain amount of data is generated as a secondary product during such use: temporary files, browser history, user profiles and saved passwords are just a few examples. You therefore need to bear in mind that when you use a computer, you leave behind a trace, like a snail, of everything you have done.

If you would like to scrap your computer or pass it on to someone else, it is important [to get rid of these traces]({% link _knowhow/sos/SOS-WhatBeforeGettingRidOldHardware.markdown %}) entirely. Simply deleting the files or reformatting the hard drive is not enough. The section below will tell you what you need to know in advance.

For classified data, such as confidential data, we recommend total physical destruction by a crusher or a demagnetiser. Passing on this equipment to someone else is out of the question.

## Total destruction of your data

### Objective
You want to resell or scrap your PC. The hard drives containing your data are going to fall into unknown hands. You need to delete everything.

### Procedure to follow
To effectively delete all the aforementioned data, it is important to use a different system to the one you want to get rid of. You could, for example, remove the drives and connect them to another computer. The easiest way to do this, however, consists of using a “live” system that can restart your computer without using its internal hard drives.

The “Darik’s Boot and Nuke” live system is available free of charge from the following website: [http://www.dban.org/](http://www.dban.org/)

Please download the file with the “iso” extension. This file resembles a compact disc that is ready to be burned. To use it, you simply need to use burning software. Take care not to burn your CD as a conventional data disk with the image file as the contents, but search for the “burn image” option.

Once the CD has been burned, you’ll need to restart your computer with the CD in the CD ROM drive. On most computers, the disk will be launched at start-up instead of the operating system. If your usual operating system loads instead of “Darik’s Boot and Nuke”, you’ll have to put the CD ROM drive first in the boot order in your BIOS settings. We recommend you use an Internet search to help you set up this configuration.

### Data destruction
Once this live CD has started up, type autonuke[enter] to delete all your computers’ hard drives. Please note that this will also destroy the memories of any mass storage devices connected to the computer by USB (such as cameras or external hard drives). You will then be able to return to your usual activities. As this process can take a while, make sure you leave your computer on continuously for at least one day.

**Generally speaking, for magnetic media (conventional hard drives) the “Quick Erase” method should be sufficient. It also has the advantage of being the fastest process.**

**It is important to note that the only method you should use for flash memory (and therefore SSD drives) is the “Quick Erase” method. Other methods could damage this type of drive and wouldn’t be effective as they are best suited to magnetic media.**

### After destruction
Depending on what you plan to do with your computer, you can now reinstall your favourite operating system or get rid of your computer without any concerns.

### Advantages
Effective process which requires little interaction.

### Disadvantages
Lengthy process. For a company looking to destroy a lot of hard drives, physical destruction will be the fastest (and possibly cheapest) route.

## Targeted destruction of data

### Objective
You want to give your PC to someone you trust, perhaps one of your children. The method described above is particularly applicable if you have lost your PC’s re-installation disk and you would like to give them an operational computer. The aim is to delete confidential data while leaving the operating system intact.

Nevertheless, the targeted destruction of existing data has some major drawbacks, because not only will traces of your data remain forever, but this method also won’t destroy any malicious software that may have made its way onto your computer and you risk passing on an infected computer to one of your family or friends.

### Procedure to follow
In addition to the tools you already have on your computer, we’re going to use the following software: ccleaner – downloadable from [http://www.piriform.com/ccleaner](http://www.piriform.com/ccleaner)

### Data destruction
All Windows systems come with an *Administrator* account by default. Close your current session ```Start -> Log off```. The Windows Logon screen will appear. Unfortunately, the *Administrator* user account is hidden. You’ll need to press ```CTRL + ALT + DELETE``` to make the classic logon screen appear.

This special user is called *Administrator* in the English (and German) version of Windows (or *Administrateur* in French). If you cannot remember the *Administrator* password, we recommend you create a new user with administrator privileges and use this one. The main thing is that you’re not logged on with your usual account.

Right click on My Computer, then select *Manage*:

Now select your usual accounts and delete them by pressing the ```DELETE``` key:

Then delete the personal directory for the deleted accounts which is located at ```C:\Documents and Settings\``` or ```C:\Users\``` for more recent versions of Windows:

Next, it is important to uninstall software that you don’t want to pass on, due to user licences for example. It is possible to use Windows’ integrated uninstall features, but ccleaner is noticeably faster. So, launch ccleaner:

Remember to delete any WiFi passwords by going to Control Panel and looking for *Network Connections*. Right click on your network connection:

Go to *Properties*, then the *Wireless Network* tab

In Windows 7 and Vista, look for the wireless network manager in Control Panel, where you can select the networks and delete them.

Now remember to delete your restore points. Right click on My Computer, then select *System Properties*:

Then choose the *System Protection* tab and *System Restore* to deactivate this feature. Once you’ve clicked *OK*, your restore points will be deleted.

If you want to go even further, clear the virtual memory pagefile, which may contain snippets of compromising memory by going to the *Advanced* tab, click on the *Settings* button in *Performance*, *Advanced* tab, virtual memory. This last stage isn’t very important and you can ignore it if you wish.

If you still have data stored in other locations, it is important to delete it now. Select the folders or files to be deleted and hold down the [shift]+[delete] keys to delete them without sending them to the recycle bin. If you have deleted the files the conventional way, just remember to empty the recycle bin.

Then delete all hidden data using ccleaner:

The default settings should be sufficient given that you’ve deleted the main user profile.

All deleted data can in theory be recovered from the free space on the hard drive. Use ccleaner to clear the free space:

### After destruction
You can now create an account for the new user.

### Advantages
Process doesn’t require a system re-installation.

### Disadvantages
Process doesn’t guarantee the total destruction of data. Additionally, if the computer has previously been infected by malware, this won’t have been removed from the system.

## Conclusion
We have given you two ways of removing data from a PC. We strongly recommend you use the first method, which guarantees:

1. the total removal of data;
2. a malware-free system after re-installation.

Removal is easier, but takes longer than the second method. On the other hand, of you want to pass on an operational computer, you will need to reinstall the operating system.

A third very effective way is obviously to crush or demagnetise at least your hard drive, if not your computer. This is a very safe solution which is perfect for large volumes and, therefore, for companies. Some companies specialise in the destruction of data, and it is better to pay for them to be destroyed than have them stolen.
