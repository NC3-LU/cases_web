---
layout: publication-list
title:  "Sandboxie"
menutitle: "Sandboxie"
logo:
date:  2017-11-06 00:00:00 +0100
short: "What's Sandboxie? How do we use it? And, why?"
categories: securing
toc: true
ref: sandboxie
lang: en
---
## Why try out a web browser in a protected space?
There is a well-known maxim repeated in security circles: “There are an unlimited number of security vulnerabilities for a given security device, system, or program, most of which will never be discovered.” Roger G. Johnston. Indeed, the more an application is analysed, the more experts appear to find vulnerabilities in it. Because of this, it is useful to consider your browser – the main program used to access web content – as an open door to all types of attacks or an access point for a lot of malicious programs. This is where the idea of testing out critical applications in a “sandbox” came from. This is so they cause no damage to the rest of the system. A simple way of doing this is to use a free program called “Sandboxie”. This utility can be downloaded from [http://www.sandboxie.com](http://www.sandboxie.com). After thirty days, the free version displays a window advertising the paid version. The utility is not a typical shareware program, but rather a free version, which can be used for private purposes after this period.

## First steps with Sandboxie
Sandboxie will run any programs you want in a protected space known as a “sandbox”. The software is thus sandboxed. This sandbox is physically a buffer directory on the hard disk, in which all the entries made by the “sandboxed” software are saved. After using the software, it will be easy to virtually rake through the sandbox and remove all the changes produced in the buffer directory. No changes will be made to the disk outside this buffer directory. By default, Sandboxie creates a sandbox called “DefaultBox”. Other sandboxes can be configured, but we will not go into detail about that here. After installation, it will load up in the memory automatically at machine start-up. To use it, just right-click on the Systray icon, choose the sandbox (“DefaultBox”) and click “Run web browser”. The system’s default browser will open (Firefox, in this example) and the “#” symbols will surround the application title to show it is properly “sandboxed”.

You can visit any pages you want to, and any changes to the system made by the “sandboxed” software will only be applied to the sandbox and therefore the buffer directory. The Sandboxie icon surrounded by little red dots shows that software is currently being used in a sandbox.

Once you have finished using the browser, select the “Delete content” option to delete all changes made by the browser, even those which may have been caused by malicious code seeking to exploit vulnerabilities. Please note that your browsing history and all other traces left by the browser will also be deleted.

A window will then ask you to save any files downloaded before completely deleting the data.

Once you have clicked on “Delete Sandbox”, your system will return to its initial state, from before launching the browser. This operation can be repeated as many times as necessary.

## Final observations

* Other solutions exist which can go up to the full virtualisation of a system. We have presented Sandboxie because it is an effective compromise and it is easy to use.
* Sandboxie also enables other software to be placed in the sandbox, and is therefore very practical for testing applications, installing them in a sandbox while keeping your system safe from unwanted changes.
* It is sometimes difficult to know whether or not to open a document. For example, a friend has sent you a PDF or PowerPoint file from an unknown source. You trust your friend, but can you trust the creator of the document you have been sent? To alleviate any concerns, right-click on the file and select the option “Run sandboxed” from the shortcut menu. This will open the document in a sandbox, thereby protecting your system in the event of a problem.
