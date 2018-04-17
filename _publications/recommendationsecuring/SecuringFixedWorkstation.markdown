---
layout: article
title:  "Securing a fixed workstation"
menutitle: "Securing a fixed workstation"
logo:
date:   2017-11-06 00:00:00 +0100
short: "Basic measures"
categories: knowhow
toc: true
---
## In brief

Practically all computers are connected to the Internet these days. Because of this, the advice below can be applied to all user workstations. It would be unrealistic to expect to achieve absolute security, so we will confine ourselves to a few priority security measures, but it should be clear that workstation security can always be tightened, depending on the sensitivity of the data being used.

Portable computers are a special case, and are dealt with in their own article.

## Basic measures

1. Every computer connected to the Internet must have **anti-virus** software preventing infection by malicious software (malware) received via email or removable media or even downloaded from malicious websites. Draft and enforce a Sectoral policy within your organisation on Operational and communications aspects – Protection against malware.
2. Every computer that is connected to the Internet should have a **personal firewall**. Almost all modern operating systems have a built-in firewall but this is enough in most cases. If you want additional protection, go for a preconfigured solution that doesn’t require any interaction with the user. These firewalls can sometimes even prevent data being stolen by Trojan horses. Draft and enforce a Sectoral policy within your organisation on access control – External connections and Separation of networks.
3. Every computer that is connected to the Internet must be regularly kept up to date. **Updating** the operating system and all the software installed can  prevent the exploitation of technical vulnerabilities aimed at compromising the machine (malware or infections contracted by browsing malicious websites) Draft and enforce a Sectoral policy on System development and maintenance – management of technical vulnerabilities.
4. It is strongly recommended **not to use administrator type user accounts** on your workstation. Administrator accounts have full rights and can therefore lead to the infection of the entire computer if compromised. When a user account with limited rights is compromised, however, the malware installation will be blocked. Sectoral policy on access control – Access control policy and Access rights management.
5. It is strongly recommended to implement [cryptographic](-) methods for the secure communication of confidential data with third parties. Users communicating externally need to know the classification level of information and identify their contact person with sufficient certainty., as well as choose the protective measures suitable for the security requirements of the information being sent. Draft and enforce a Sectoral policy on System development and maintenance – Use of encryption.
6. It is strongly recommended to use **uthentication methods suited** to the classification level of the assets processed during computer connections. Take care to protect these authentication methods. Guard them against copying or theft. All the passwords and PINs that you use should be carefully chosen and not revealed. Passwords should comply with the access policy instructions for your organisations. Draft and enforce a Sectoral policy on access control – Password management and Connection procedures and External connections.
7. It is strongly recommended to raise awareness among users over the risks relating to social engineering ([social engineering](-)) used during human-type attacks. Users should be able to recognise attacks seeking to extract confidential information through illicit requests for information via email, telephone or even social networks. Each user should therefore understand the classification level of the information they hold or are processing. Draft and enforce a Sectoral policy within your organisation on the Classification and control of resources.
8. **Create backups** for your important or vital information and software. Protect these backups against environmental threats such as fire. Protect all backups against theft, copying and illicit alteration. Test that these backups can be restored. Draft and enforce a Sectoral policy within your organisation on Operational and communications aspects – Data backup, as well as a sectoral policy on physical and environmental security – Physical security perimeter and Rules within the perimeter.
9. If the computer contains data classified as sensitive, it may be worth encrypting the hard disk. In this context, it is recommended to use a strong authentication method (very long password, USB holding an encryption key, etc.) for disk decryption.

## Quick win windows

1. Use 64bit systems, which improve system security (Windows 64bit only accepts signed drivers).
2. It is strongly recommended to introduce an automated update system. The solution offered by Microsoft, the WSUS server, can be easily extended (using third-party software) to update all the software on your machines.
