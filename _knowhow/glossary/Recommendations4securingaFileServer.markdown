---
layout: articlesmall
title:  "Recommendations for securing a file server"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: knowhow
---
## In brief
A file server is a special server insofar as it is only rarely connected to the Internet, but rather is generally connected to the internal network directly or through a firewall. It is used as a shared storage location for all company files. and because of this it acts as a link between all computers, facilitating internal communication, and also spreading malicious software.

Despite the fact that this server should not be connected to the Internet, in general it is important to follow the same recommendations as for a server connected to the Internet.

## Security measures

1. It is strongly recommended to protect the file server against malicious software (malware). Anti-virus software should be regularly updated in order to recognise and remove the latest malicious code. Draft and enforce a Sectoral policy on Operational and communications aspects – Protection against malware.
2. It is strongly recommended to **use different anti-virus** software for the file server than for agent workstations. This makes the chances of detecting a virus that much bigger.
3. It is strongly recommended to **restrict the functionality** of the file server to this sole task and not to host any other application on the same virtual or physical server.
4. It is strongly recommended to place the **file server within the network** of the entity and not to authorise any access from the exterior to this network. Draft and enforce a Sectoral policy on access control – External connections and Separation of networks.
5. It is strongly recommended to apply a procedure for the **creation and deactivation of user accounts**. User accounts are created upon the arrival of each new agent. When an agent leaves, their account access is deactivated so that they can no longer access files. Draft and enforce a Sectoral policy on human factors as well as a sectoral policy on access control.
6. It is strongly advisable to introduce a **formal procedure for the allocation and return of access rights** (read, write). Access to data is allocated by the administrator of the data in question. Draft and enforce a Sectoral policy on the Classification and control of resources and a Sectoral policy on access control – Access control policy and Access rights management
7. It is recommended to implement **encryption functionalities** if strictly confidential content must be saved on the server. Draft and enforce a Sectoral policy on System development and maintenance – Use of encryption.
