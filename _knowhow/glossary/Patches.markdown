---
layout: article
title:  "Patches"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: knowhow
toc: true
---
## In brief
Flaws can in some cases be used as an entry point for malicious code or malicious sites seeking unauthorised access to the computer. It is therefore important to correct these flaws by applying patches.

A patch is an update, in the form of a file or software, that corrects a security flaw in an operating system or program.

In some cases, the patch will not only fix a flaw, but will also add new features to the computer software or operating system.

## Life cycle
The life cycle of a security patch starts in most cases when the software manufacturer sends notification of the flaw or even makes a direct public announcement. In limited cases, depending on certain national laws and regulations, public announcement without the manufacturer's authorisation may be considered unlawful.

From this time, for an arbitrary period, the software manufacturer validates the existence of the flaw by an announcement or by publishing a security bulletin.

In most cases, the announcement is accompanied by the provision of a patch to correct the existing flaw.

## Behavioural measures
It is important to carry out updates. The saying "Never touch a running system" is not valid from the point of view of security.

Obviously, however, care is required when installing new programs.

## Organisational practices
The organisation must draft and enforce a sectoral policy on systems development and management  – [management of technical vulnerabilities]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.markdown %}#managing-technical-vulnerabilities)

## Technical measures
* It is important to test patches before deploying them on key systems. It is practical to keep a test computer for this purpose.
* You can use the Secunia online service to check for patches for your operating system or your installed software. Alternatively, download a [Secunia application]({% link _knowhow/glossary/SecuniaPSI.markdown %}) (note that their PSI version must not be used in a professional context). These services will tell you which software to update.
* In a Microsoft infrastructure it is advisable to set up a WSUS update server, if possible with extensions enabling updates to all software on workstations.
