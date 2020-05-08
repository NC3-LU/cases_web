---
layout: article
title:  "Update softwares with Secunia PSI"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: knowhow
toc: true
ref: glossarysecuniapsi
lang: en
---

## Why Update Software on Your Computer
Software is, like many other human productions, a work in progress. No work is perfect and all can have more or less hidden flaws. Imagine a house that would have been built without a lock on the front door. The architect proud of his work presents the work and the buyer moves in. A month later, a burglar takes advantage of the lockless door to steal the television. The owner then protests to the architect, who hastens to add a lock to the front door on his plans and sponsors a company to make the necessary physical modifications. 

In terms of IT, the architect carried out an [update]({% link _knowhow/glossary/Patches.markdown %}) of his plan, then commissioned the update on his client’s installation. Regular updates are interesting from different points of view:

* Users benefit from the latest features added to the software
* Errors in programs are corrected
* Security vulnerabilities ([technical vulnerabilities]({% link _knowhow/glossary/Vulnerabilities.markdown %}#technical-vulnerabilities)) in the software are eliminated

It is especially this last point that interests us here because a security breach in software can lead to theft or even destruction (loss of [availability]({% link _knowhow/glossary/Availability.markdown %})) of your [confidential]({% link _knowhow/glossary/Confidentiality.markdown %}) data (see [classification]({% link _knowhow/cisoapproach/SecurityPolicy-Classification.markdown %})), and this can go as far as to use of your computer for illicit purposes. For example, imagine a technical vulnerability in your web browser; using a special procedure, a [malicious web page]({% link _knowhow/glossary/MaliciousWebsites.markdown %}) can cause [malware]({% link _knowhow/glossary/MaliciousCodes.markdown %} to be installed on your computer. 

The creators of the browser in question learn of the existence of the defect and produce an update for their application. Following this, knowing that many browser users will not have been informed of the update, a criminal decides to exploit this flaw to install his [Trojan horse]({% link _knowhow/glossary/MaliciousCodes.markdown %}#cheval-de-troie), which steals [passwords]({% link _knowhow/glossary/Password.markdown %}) from email sites or web banking. He will then build a custom Internet page, exploiting the flaw, to install his Trojan horse. 

For users to visit the malicious page, the criminal decides to buy ad slots from different trusted sites. Besides, he will get a list of email addresses and put a link to his page in a [Spam]({% link _knowhow/glossary/SPAM-UnwantedEmails.markdown %}) email that he will send to this whole list. Its page will be quickly reported, but will still have had, for one to two days, the time to exist. Exploiting curiosity as [human vulnerability]({% link _knowhow/glossary/Vulnerabilities.markdown %}#human-vulnerabilities), it will generate large traffic on its false page and thus allow it to install its Trojan horse on the vulnerable computers of its victims. Victims using the new version of their browser will not have been infected despite their visit to this page.

## How to Update Your Computer

Fortunately, most operating systems have simple or automatic update mechanisms. Unfortunately, your computer does not only have a basic installation of an operating system, but it also contains a multitude of other software that you use regularly and which, at least under Windows, do not enter the normal procedure of update. Some of this software, like the Firefox browser, update themselves by a mechanism of their own. Others do not have an automatic updating procedure, so you have to remember to keep them updated manually. 

As a sad, critical example, we can cite the browsers’ flash module. If you have ever watched videos on [http://www.youtube.com](http://www.youtube.com) for example, this module has already been installed in your home. It is often installed once at the very beginning of the computer’s life, then forgotten, never updated, it becomes an important entry point for [malware]({% link _knowhow/glossary/MaliciousCodes.markdown %}). If you want to be conscientious then you should regularly watch for the release of new versions of the software.

## Software That Checks the Status of Your Software for You

Secunia, a very active player in the security field, provides a powerful tool free of charge which will help you keep your entire system up to date. It exists for Windows, for personal and non-professional use, and can be downloaded at the following address: [http://secunia.com/vulnerability_scanning/personal/](http://secunia.com/vulnerability_scanning/personal/). 

After downloading, installing and launching this software, an initial automatic scan will be performed. Secunia PSI lists the vulnerabilities published by the security expert community and compares the announcements with the versions of programs installed on your computer. By hovering the mouse over the colour scale indicating the degree of severity, you get a brief explanation of the vulnerabilities present. For a more precise report, you can click on this same scale, which will open the web page corresponding to the vulnerability on the Secunia site. 

By clicking on the corresponding solution button, you can then directly download the new version of the vulnerable software (or even activate the automatic update) or find a simple and adequate solution to the problem, like the software download page or the Windows update interface. 

Secunia PSI remains resident in memory and will start automatically with Windows, notifying you when an update is necessary. It replaces tedious manual control of the versions of installed programs.

## Remarks

Although Secunia PSI constantly checks the status of your software, it does not replace a good antivirus. Be sure to install an antivirus and keep it constantly up to date.

From version 2 of the software, it offers automatic updating of your software. 

Secunia and other companies offer professional versions of patch management. In particular, find out about the extensions to the WSUS server (Microsoft’s update server), which allow you to update all software on all workstations centrally. 
