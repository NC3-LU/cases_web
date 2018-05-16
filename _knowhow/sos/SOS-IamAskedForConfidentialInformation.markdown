---
layout: knowhow
title:  "SOS – I am being asked for confidential information"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: f-sos
toc: true
---

<h3 class="titre-page">In brief</h3>
Check the [classification]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-Classification.html) level of the information requested. Afterwards, make sure that:

* the person requesting this information can be sufficiently well-identified for the criticality of the information (if secret or confidential information is requested, the identity of the requesting party must be ascertained with certainty);
* the requesting party is authorised to hold this information ([access control policy]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-AccessControl.html#access-control-policy));
* the criticality of the information authorises the use of the proposed communications channel ([sectoral policy on the classification and control of resources]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources.html)).

If these three conditions are fulfilled, the information can be transmitted. If there is any doubt over this, refuse to communicate the information requested.

<h3 class="titre-page">Checking somebody’s identity</h3>
It is very difficult to be sure of someone’s identity:

* The identity of someone who sends an [email]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.html#email) can only be verified if the email bears an electronic signature and the resource used results in the necessary level of trust.
* The identity of someone over the telephone is very difficult to verify. The telephone number displayed can be faked (‘caller id spoofing’). There are also ways to fake the timbre of a person’s voice. A certain level of assurance can be established if you offer to call back the displayed number, so as to verify that it really does belong to who the person claims to be.

<h3 class="titre-page">Check the legitimacy of the request</h3>
Before forwarding information to an identified person, check whether that person is entitled to receive the desired information. This obviously depends on the situation and partly depends on common sense, the security policy implemented or other rules defined within the organisation.

<h3 class="titre-page">Choose the communications channel</h3>
Before transmitting any information, be sure to select the appropriate communications channel corresponding to the criticality level of the data to be transmitted. Remember that:

* Email provides no guarantee of confidentiality. By using strong [encryption]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.html#encryption), the use of email is conceivable.  However, the encryption key still needs to be transferred securely, without using email, so secure methods for exchanging keys or [asymmetric cryptography]({{site.url}}/knowhow/glossary/Cryptography.html) must be used. See also [Email: best practices]({{site.url}}/publications/bestpractices/EMail-BestPractices.html) and [OpenPGP](https://www.openpgp.org).
* The landline telephone network and GSM networks are a great deal safer (although in some cases it is possible to listen in on them) and can be used to exchange passwords.
