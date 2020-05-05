---
layout: article
title:  "Firewall"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short: "Security Measures"
categories: knowhow
toc: true
ref: glossaryfirewall
lang: en
---

## In Brief
A firewall is a physical (hardware) or logical (software) device that serves as a protection system for computers. It can also serve as an interface between one or more corporate networks to control and possibly block the flow of data by analysing the information contained in the data flows (network partitioning).

A firewall functions as a network frame filter and analyser. A company that has a file server for its internal network and wants it to be inaccessible from the Internet could effectively use a firewall to block communications to it.

It allows, on the one hand, to block suspicious attacks or connections which can come from [malicious codes]({% link _knowhow/glossary/MaliciousCodes.markdown %}) like viruses, worms or Trojans. On the other hand, a firewall is also used in many cases to prevent uncontrolled information leakage to the outside.

Firewall often contain other security tools such as an [antivirus]({% link _knowhow/glossary/AntiVirus.markdown %}) or a proxy and thus allow not only to block unwanted connections but also to automatically check the content of communications and block unwanted content. 

Some firewalls also offer a [VPN]({% link _knowhow/glossary/VPN.markdown %}) possibility.

There are mainly two categories of firewalls:
* personal firewalls protecting only workstations or personal computers. They are installed directly on the user’s computer.
* corporate firewalls installed on dedicated machines. This type of firewall is often placed between the Internet and a corporate network to protect the latter from various threats from the Internet. It is also used for the creation of demilitarised zones (DMZ) for the hosting of public servers. In some cases, it even serves to separate different parts of the corporate network into different security perimeters ([segmentation or network partitioning]({% link _knowhow/glossary/NetworkSegmentation.markdown %})).

## Behavioural Measures
* A firewall is not absolute protection against attacks from the Internet. Data exfiltration largely depends on the configuration made. Users should remain alert to such attacks.

## Organisational Measures
* Firewall management must follow strict rules. Any rule change must be documented.
* The organisation must draw up and enforce a sectoral policy for access control.
* Create and apply an access control - [network separation]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#separation-of-networks) sector policy

## Technical measures
* You must recurrently test the firewall rules
* Firewall logs must be kept and analysed. They are often the only help to identify malicious codes that extract information to certain destinations.
