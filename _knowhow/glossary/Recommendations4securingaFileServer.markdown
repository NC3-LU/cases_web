---
layout: articlesmall
title:  "Recommendations for securing a file server"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: knowhow
---
<h3 class="titre-page" id="in-brief">In brief</h3>
A file server is a special server insofar as it is only rarely connected to the Internet, but rather is generally connected to the internal network directly or through a firewall. It is used as a shared storage location for all company files. and because of this it acts as a link between all computers, facilitating internal communication, and also spreading [malicious software]({% link _publications/bestpractices/MaliciousSoftwareBP.markdown %}).

Despite the fact that this server should not be connected to the Internet, in general it is important to follow the same [recommendations as for a server connected to the Internet]({% link _publications/recommendationsecuring/Recommendations4securingWebServer.markdown %}).

<h3 class="titre-page" id="security-measures">Security measures</h3>

1. It is strongly recommended to protect the file server against [malicious software]({% link _publications/bestpractices/MaliciousSoftwareBP.markdown %}) (malware). Anti-virus software should be regularly updated in order to recognise and remove the latest malicious code. Draft and enforce a Sectoral policy on Operational and communications aspects – [Protection against malware]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}\#protection-against-malware ).
2. It is strongly recommended to **use different anti-virus** software for the file server than for agent workstations. This makes the chances of detecting a virus that much bigger.
3. It is strongly recommended to **restrict the functionality** of the file server to this sole task and not to host any other application on the same virtual or physical server.
4. It is strongly recommended to place the **file server within the network** of the entity and not to authorise any access from the exterior to this network. Draft and enforce a Sectoral policy on access control – [External connections]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}\#external-connections) and [Separation of networks]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}\#separation-of-networks ).
5. It is strongly recommended to apply a procedure for the **creation and deactivation of user accounts**. User accounts are created upon the arrival of each new agent. When an agent leaves, their account access is deactivated so that they can no longer access files. Draft and enforce a Sectoral policy on [human factors]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown  %}) as well as a sectoral policy on [access control]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}).
6. It is strongly advisable to introduce a **formal procedure for the allocation and return of access rights** (read, write). Access to data is allocated by the administrator of the data in question. Draft and enforce a Sectoral policy on the [Classification and control of resources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources.markdown %}) and a Sectoral policy on access control – [Access control policy]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}\#access-control-policy) and [Access rights management]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}\#access-rights-management)
7. It is recommended to implement **encryption functionalities** if strictly confidential content must be saved on the server. Draft and enforce a Sectoral policy on System development and maintenance – [Use of encryption]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.markdown %}\#encryption ).
