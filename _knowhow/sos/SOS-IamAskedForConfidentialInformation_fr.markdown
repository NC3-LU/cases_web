---
layout: knowhow
title:  "SOS – I am being asked for confidential information"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: f-sos
toc: true
ref: sosaskedforconfidentialinfo
lang: fr
---

## In brief
Check the [classification]({% link _knowhow/cisoapproach/SecurityPolicy-Classification.markdown %}) level of the information requested. Afterwards, make sure that:

* the person requesting this information can be sufficiently well-identified for the criticality of the information (if secret or confidential information is requested, the identity of the requesting party must be ascertained with certainty);
* the requesting party is authorised to hold this information ([access control policy]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#access-control-policy));
* the criticality of the information authorises the use of the proposed communications channel ([sectoral policy on the classification and control of resources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources.markdown %})).

If these three conditions are fulfilled, the information can be transmitted. If there is any doubt over this, refuse to communicate the information requested.

## Checking somebody’s identity
It is very difficult to be sure of someone’s identity:

* The identity of someone who sends an [email]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}#email) can only be verified if the email bears an electronic signature and the resource used results in the necessary level of trust.
* The identity of someone over the telephone is very difficult to verify. The telephone number displayed can be faked (‘caller id spoofing’). There are also ways to fake the timbre of a person’s voice. A certain level of assurance can be established if you offer to call back the displayed number, so as to verify that it really does belong to who the person claims to be.

## Check the legitimacy of the request
Before forwarding information to an identified person, check whether that person is entitled to receive the desired information. This obviously depends on the situation and partly depends on common sense, the security policy implemented or other rules defined within the organisation.

## Choose the communications channel
Before transmitting any information, be sure to select the appropriate communications channel corresponding to the criticality level of the data to be transmitted. Remember that:

* Email provides no guarantee of confidentiality. By using strong [encryption]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.markdown %}#encryption), the use of email is conceivable.  However, the encryption key still needs to be transferred securely, without using email, so secure methods for exchanging keys or [asymmetric cryptography]({% link _knowhow/glossary/Cryptography.markdown %}) must be used. See also [Email: best practices]({% link _knowhow/bestpractices/EMail-BestPractices.markdown %}) and [OpenPGP](https://www.openpgp.org).
* The landline telephone network and GSM networks are a great deal safer (although in some cases it is possible to listen in on them) and can be used to exchange passwords.
