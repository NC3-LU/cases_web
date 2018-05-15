---
layout: publication-list
title:  "Recommendations for securing an email server"
menutitle: "Recommendations for securing an email server"
logo:
date:  2017-11-06 00:00:00 +0100
short: "Security measures for securing an email server"
categories: securing
toc: true
---
## In brief
Mail servers are special servers in the sense that at least part of a mail server has to be connected to the Internet and it is sent a huge number of messages, not all of which will necessarily be benign. As explained in the article on emails, this server can be separated into one or two parts, where at least the MTA part (Mail Transfer Agent) must be connected to the Internet. Because of this, it is also recommended to follow the general recommendations for servers connected to the Internet.

## Security measures

1. It is strongly recommended to use anti-virus software to scan emails passing through the server. This is done to protect recipients from malicious code. Anti-virus software should be regularly updated in order to recognise and remove the latest malicious code. Draft and enforce a Sectoral policy on Operational and communications aspects – Protection against malware.
2. It is strongly recommended to use different anti-virus software for the email than for agent workstations. This increases the probability of detecting a virus.
3. It is strongly recommended to activate a spam filter at server level. Draft and enforce a Sectoral policy on Operational and communications aspects – Email
4. It is strongly recommended to configure the email server to prevent all mail relays. This means that malicious users from the Internet will not be able to use the mail server to send messages by using its email relay function.
5. It is recommended to separate the MTA server (“Mail Transfer Agent”) and the MDA server (“Mail Delivery Agent”). The MTA should be in the DMZ and the MDA inside the entity network. A corporate firewall can be set up to provide maximum security. Draft and enforce a Sectoral policy on access control – External connections and Separation of networks.
6. It is strongly recommended to apply a procedure for the creation and deactivation of email accounts. User accounts are created upon the arrival of each new agent. When an agent leaves or is transferred, their former access to electronic mail is closed and their access account is deactivated, so they cannot continue to send and receive emails using their old address. Draft and enforce a Sectoral policy on human factors and a Sectoral policy on Access control – Access control policy and Access rights management
7. It is strongly recommended to draw up an Acceptable Use Policy for email and to make all users aware of this policy. They should respect the charter for the good of everyone. Draft and enforce a Sectoral policy on human factors as well as a Sectoral policy on Operational and communications aspects – Email.
8. It is strongly recommended to train all agents on the risks inherent to the use of emails.
9. It is recommended to implement encryption functionalities if in-house or confidential content is going to be transferred via email. Draft and enforce a Sectoral policy on System development and maintenance- Use of encryption
10. It is strongly recommended to introduce a method to combat SPAM, such as SPF, DKIM or DMARC.
