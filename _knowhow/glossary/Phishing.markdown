---
layout: article
title:  "Phishing"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: knowhow
toc: true
---
<h3 class="titre-page" id="in-brief">In brief</h3>
Phishing, or Fishing, is a technique employed by computer hackers to get personal information for the purpose of committing identity fraud. The technique consists of making the victim believe they are communicating with a trusted third-party – bank, administration, etc. – in order to get them to disclose personal information: password, credit card number, date of birth, etc. It is a form of IT attack that relies on [social engineering]({% link _knowhow/glossary/Phishing.markdown %}). It may be perpetrated by email, on fraudulent websites or by other electronic means.

Generally speaking, IT criminals use phishing to steal money. The most common targets are online banking services, Internet service providers and auction websites such as eBay and PayPal. Phishing proponents usually send emails to a large number of potential victims.

<h3 class="titre-page" id="how-to-recognise-phishing">How to recognise phishing</h3>
A phishing email can usually be recognised by the following tell-tale signs:

* the email does not address you by name
* the email incites you to act quickly
* the email contains a link you have to click on

If you’ve received an email that includes one of these clues, you can simply ignore it. Do not click on the suggested link. If you have doubts regarding the authenticity of the message, you can also open your browser and enter the address of the site you wish to visit yourself.

<h3 class="titre-page" id="behavioural-measures">Behavioural measures</h3>
The most important behavioural measure consists of ignoring suggested links in [emails]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}\#email), or visiting websites you are not familiar with.

<h3 class="titre-page" id="organisational-practices">Organisational practices</h3>
In France, Internet users are invited to report their own (bad) experiences to the National Police’s monitoring unit or to send them links to any websites they suspect are illegal.

There are charitable organisations that help Internet users protect themselves against this type of fraud:

* [PhishTank](https://www.phishtank.com)
* [Phishing Initiative](https://phishing-initiative.fr/contrib)
* [APWG](https://apwg.org)

<h3 class="titre-page" id="technical-measures">Technical measures</h3>
The following technical measures can be implemented:

* SPAM filter in your email client
  * Phishing attacks are normally large-scale attacks. It is therefore likely that your email client recognises it as spam and marks it accordingly.
* Phishing filter in your browser
  * Modern browsers are capable of identifying phishing websites. Turn on this filter so your browser can alert you against this type of attack:
  * [Google Chrome and browser safety](https://support.google.com/chrome/answer/114836?hl=fr&ref_topic=7437824)
  * [Mozilla Firefox phishing filter](https://support.mozilla.org/en-US/kb/how-does-phishing-and-malware-protection-work)
  * [Microsoft Smart Screen](https://www.microsoft.com/en-us/security/default.aspx)
* Use the Web of Trust ([WOT]({% link _knowhow/glossary/WOT.markdown %})) add-on
* Use a [web filter]({% link _knowhow/glossary/WebFilterProxy.markdown %}) (proxy)
