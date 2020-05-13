---
layout: article
title:  "Recommendations to secure a server connected to Internet"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: knowhow
ref: glossaryrecomm4securingserver
lang: en
---
In Brief
--------
Security measures are behavioural, organisational or technical measures that seek to guarantee the [confidentiality]({% link _knowhow/glossary/Confidentiality.markdown %}), [integrity]({% link _knowhow/glossary/Integrity.markdown %}) and [availability]({% link _knowhow/glossary/Availability.markdown %}) of an [asset]({% link _knowhow/glossary/Assets.markdown %}). Security measures aim to reduce the [vulnerabilities]({% link _knowhow/glossary/Vulnerabilities.markdown %}) exploited by [threats]({% link _knowhow/glossary/Threat.markdown %}), thereby reducing [impacts]({% link _knowhow/glossary/Impact.markdown %}). They are defined during the [risk treatment]({% link _knowhow/glossary/RiskProcessing.markdown %}) phase of the risk management process.

Security Measures
-----------------

1.  It is strongly recommended to regularly **[update]({% link _knowhow/glossary/Patches.markdown %}) the operating system** as well as the server applications. The exploitation of these technical vulnerabilities can cause corruption of the operation of the server or theft, respectively [destruction of files]({% link _knowhow/glossary/DataLoss.markdown %}) and possibly hijacking of data flows. Write and enforce a sectoral system development and maintenance policy.
2.	It is strongly recommended to limit the functionality of the server to a single task and not to host any other application on this same virtual server, respectively physical.
3.	It is strongly recommended to segment the network and put the server in a **DMZ**. Access to the server must, therefore, go through a [firewall]({% link _knowhow/glossary/Firewall.markdown %}) and ideally through an [IDS/IPS]({% link _knowhow/glossary/IDS-IPS.markdown %}). Write and enforce a Sector Policy for access control.
4.	It is strongly recommended to integrate the server in the **backup plan**. Write and enforce a sectoral policy for the management of operations and telecommunications. Write and enforce a sectoral policy related to operational aspects and communications.
5.	It is strongly recommended to set up a **strong [authentication]({% link _knowhow/glossary/Authentication.markdown %})** for any access from outside the entity. Write and enforce a sectoral policy for access control.
6.	It is strongly recommended to impose certain **robustness of the password** of the users, as well as for the administrator account. Write and enforce a sectoral policy for access control.
7.	It is strongly recommended to set up a logging system if it is not already in place by default. It is also important to be able to evaluate the content of the log files; therefore, the use of tools for aggregation and analysis, or even alerting, of log files is very useful. This logging must comply with the laws on the protection of personal data - surveillance at the workplace (see the CNPD website).
8.	It is strongly recommended that you protect this server from malicious code. [Antivirus]({% link _knowhow/glossary/AntiVirus.markdown %}) scanning software must be updated regularly to be able to recognise and remove the latest malicious code. Write and enforce a sectoral policy on operational aspects and communications.
9.	For servers classified as important or vital, it is proposed to conclude a **maintenance contract** with an intervention period corresponding to the classification level of the server. Write and enforce a physical and environmental security sector policy.
10.	For servers classified as important or vital, it is strongly recommended to use inverters to ensure electrical security. Write and enforce a Sector Policy for Physical and Environmental Security.
11.	It is strongly recommended to **secure physical access to the server** only to those entitled. Write and enforce a Sector Policy for Physical and Environmental Security.
12.	If the server is discarded, it is strongly recommended that you physically destroy the hard disks (using a shredder or demagnetiser). Write and enforce a physical and environmental security sector policy.
13.	Document the most important manipulations on the server (backup, shutdown, startup…). Write and enforce a Sector Policy on Operational Aspects and Communications.
