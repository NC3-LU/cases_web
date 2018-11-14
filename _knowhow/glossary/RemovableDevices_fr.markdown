---
layout: article
title:  "Removable devices"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: knowhow
toc: true
ref: glossaryremovabledevices
lang: fr
---

## In brief
Removable storage media are data storage media which, as their name would indicate, can be transferred from one computer to another. They will typically be optical discs, such as CDs or DVDs, but they can also be external hard drives, memory sticks and more. Because of their portability, these storage media can represent a security breach for your network.

## Introduction of malicious software (malware)
Some [malware]({% link _knowhow/glossary/MaliciousCodes_fr.markdown %}) specialises in spreading itself by USB stick or external hard drive. Generally speaking, it uses Windows “autorun”. This automatically executes an application when the stick or hard drive is connected.

Although Microsoft changed the default behaviour when it released a patch, meaning that the “autorun” should no longer be activated by default, it is recommended to take care when using memory sticks:

* pay particular attention to computers you use with these sticks or drives; a publicly-accessible computer which is often used with different sticks has much more chance of being infected, and therefore infect your own memory stick;
* sticks are often handed out as a gift at events – you should always check them on a computer without the “autorun” function before using them;
* be especially careful about any sticks that you find – they may have been lost on purpose;
* use a dedicated workstation to scan removable storage media before using them within your organisation;
* if possible, block optical disc readers and USB ports on workstations (it is possible to do so using your operating system software);
* ensure your staff are aware of the dangers of removable storage media.

## Information leak
The theft of files or information can be facilitated by the use of removable storage media. Make sure you block USB ports and optical readers on your workstations. This will not prevent leaks over the Internet, so it would also be of use to consider DLP – Data Leakage Prevention.

## Destruction of hardware
It is sometimes possible to find this type of storage media lying around. Sometimes, simple human curiosity drives us to collect these tools together and to look at what's inside. Or if we are in a rush, we might be tempted to take the first storage media that we come across. But that risks ending badly. Some USB keys can easily transform themselves into “USB Killers” – a tool causing a powerful electrical discharge when inserted into a machine. You should therefore draw up an IT charter or internal instructions stating that the hardware used must be familiar to the person using it.
