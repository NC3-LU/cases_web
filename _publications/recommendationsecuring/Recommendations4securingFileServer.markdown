---
layout: publication-list
category: "In depth articles"
title:  "Securing a file server"
menutitle: "Securing a file server"
logo:
date:  2017-11-06 00:00:00 +0100
short: "Security Measures"
categories: securing
toc: true
ref: recommendations4securingfileserver
lang: en
---

## In brief
A file server is a special server in the sense that it is only rarely connected to the Internet; instead, it is generally directly or through a firewall connected to the internal network. It serves as a common storage location for all of the company's files and acts as a link between all computers, facilitating internal communication, but also the spread of [malware]({% link _knowhow/glossary/MaliciousCodes.markdown %}).
Although this server is not connected to the Internet in general, it is important to follow the same recommendations as described in the document [server connected to the Internet]({% link _publications/recommendationsecuring/Recommendations4securingServerConnectedInternet.markdown %}).

## Security Measures

1. It is strongly recommended to protect the file server from  [malware]({% link _knowhow/glossary/MaliciousCodes.markdown %}). [Antivirus]({% link _knowhow/glossary/AntiVirus.markdown %}) scanning software must be updated regularly to be able to recognise and remove the latest malicious code. Write and enforce a sectoral policy on operational aspects and communications - [protection against malicious software]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}#protection-against-malware).

2. It is strongly recommended to use **different antivirus** software for the file server than for the agents' workstations. Thus, the chance of detection of a virus is greater.

3. It is strongly recommended to **limit the functionality** of the file server to this single task and not to host any other application on this same virtual server, respectively physical.

4. It is strongly recommended that you put the **file server inside** the entity's **network** and not allow any access from outside this network. Write and enforce a sectoral policy for access control - [Connection from the outside]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#external-connections) and [Network separation]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#separation-of-networks).

5. It is strongly recommended to apply a procedure for **creating and deactivating user accounts**. User accounts are created when each new agent arrives. At the start or during the transfer of agents, their access accounts are deactivated so that they cannot continue to access the files. Write and enforce a sectoral policy related to [human aspects]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown %}) as well as a sectoral [access control policy]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}).

6. It is strongly advised to set up a **formal procedure for the allocation and recovery of access rights** (read, write). Access to data is granted by the data manager in question. Write and enforce a sectoral policy for the [Classification]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources.markdown %}) and Control of Resources and a sectoral policy for Access Control - [Access Control Policy]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#access-control-policy) and [Access Rights Management]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#access-rights-management).

7. It is recommended to set up **encryption functionalities** if strictly confidential content must be saved on the server. Write and enforce a sectoral policy for Development and maintenance of systems - [Use of encryption]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.markdown %}#encryption).
