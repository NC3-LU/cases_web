---
layout: article
title:  "Disinfect machine with a live CD"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: knowhow
toc: true
ref: glossarydisinfectthemachinelivecd
lang: en
---

## In Brief
A live operating system is an operating system that can be started from a CD and loads completely into memory, without permanently modifying the computer.

This system makes it possible to carry out analyses of the computer, without the main system being started. Therefore, it can perfectly be used to antivirus analyses or other forensic analysis operations.

## Why Use It?
It is, of course, very important to have a functional and updated [antivirus]({% link _knowhow/glossary/AntiVirus.markdown %}), which can act as the first line of defence against [malware]({% link _knowhow/glossary/MaliciousCodes.markdown %}). Unfortunately, the installation of such antivirus is not an absolute guarantee of security. In order to distinguish malicious programs from harmless programs, antiviruses depend on signatures (virus fingerprints) that antivirus creators regularly make available in the form of updates. 

Sometimes viruses can be faster and nestle in operating systems before an antivirus can detect them. Since some malware can escape systems, they can remain undetected, even after downloading the appropriate signature. Therefore, it is important to be able to analyse a system at a time when all of its elements are in standby (excluding the operating system), and in particular, possible malicious programs.

Some operating systems exist in a special form known as ‘Live’, with a compact disc allowing the starting of a computer without prior installation and making no change on the computer used.

Antivirus manufacturers have taken advantage of these fleeting operating systems to create malware detection systems. The system loads onto your computer, then it loads the antivirus and scans your hard drives while keeping your installed operating system dormant, thus making detection of [viruses]({% link _knowhow/glossary/MaliciousCodes.markdown %}#virus), [worms]({% link _knowhow/glossary/MaliciousCodes.markdown %}#vers), [Trojans]({% link _knowhow/glossary/MaliciousCodes.markdown %}#cheval-de-troie) and more particularly rootkits easier.

## Where to Find It?
In the references of this article, you will find some examples of [malicious code]({% link _knowhow/glossary/MaliciousCodes.markdown %}) analysis systems. In general, these are ‘image’ files to download. These ‘image’ files must be burned in a special way on CD or DVD; look for the ‘burn image’ option in your burning software.

## How to Use It?
Most computers are configured to boot from the CD player or USB sticks. It will, therefore, suffice to insert the burned CD (or even the stick) into the computer and to restart it. If you do not see the boot screen of the live CD, but your usual operating system starts, your BIOS (basic computer operating system) is not configured to boot from CD. This setting depends on your computer and unfortunately, we can only give you some leads to make the necessary settings:

At start-up, press the ‘Del’, ’F12’ or ‘Esc’ key (if this action does not work, ask your computer manufacturer). This will open either a boot media selection menu or your machine’s BIOS setup menu.

If the BIOS setup menu of your machine is opened by this action, select the option that sets the CD drive as the priority boot media before the hard drive.

During start-up, an update of the virus signatures will be attempted. For this, the computer must have direct access to the Internet. Be aware that Wi-Fi will not work most of the time, so consider using a network cable for the duration of the procedure.

After some waiting time (be patient, the CD player is much slower than a hard drive), the system analysis will be launched automatically.

In the case of malware detection, the antivirus will offer you certain modes of action. We advise you to delete any viruses. When you are done, right-click on the wallpaper and click on the ‘Exit’ option, as shown above. The system will shut down and eject the compact disc. Do not forget to remove the CD and restart your operating system normally.

## Precautions to Take
Since antiviruses on live CDs do not use the basic operating system of the computer, it may become unusable after detecting and erasing deeply rooted malware. So keep your operating system installation disc handy and make regular [backups]({% link _knowhow/glossary/DataBackups.markdown %}).
