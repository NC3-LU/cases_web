---
layout: article
title:  "IDS/IPS"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: knowhow
toc: true
ref: glossaryidsips
lang: en
---
## The Intrusion Detection System (IDS)
The Intrusion Detection System, or IDS, plays a special role in IT security. Rather than actively protect the equipment, it works passively, recording network activity and setting off an alarm whenever a suspicious action is detected. This detection may occur using the strategies listed below. However, the complexity of network flows may result in the IDS sounding numerous false alarms, also known as false positives. Therefore, a large amount of post-treatment work needs to be done on the alarm logs to determine which attacks are real and which are false, which can prove tedious. Nevertheless, the IDS can be a very useful tool for identifying risks (threats and vulnerabilities) to which the IT systems may be subject. IDS availability is crucial to the effectiveness of the collected data. The ideal solution is to place it at interconnection points between networks, just like firewalls.

## The Intrusion Prevention System (IPS)
The Intrusion Prevention System, or IPS, has been developed to overcome the two major disadvantages of the IDS, namely its passiveness and the generation of false positives. The IPS doesn't just detect suspicious behaviour, it also blocks it. It uses the same detection system as the IDS and therefore also generates false positives. However, the IPS comes equipped with detection filters and a set of rules that show it how to react correctly: block the network flow, let it through or request human intervention, a bit like a firewall. Once more, to be effective, the IPS must be placed at interconnection points between the networks.
