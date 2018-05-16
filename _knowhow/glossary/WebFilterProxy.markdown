---
layout: article
title:  "Web filter – Proxy"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: knowhow
toc: true
---
<h3 class="titre-page" id="in-brief">In brief</h3>
A large number of websites, both legal and illegal, that can be freely accessed online have content that is malicious, inappropriate, prohibited or bad for productivity. Accessing [malicious websites]({% link _knowhow/glossary/MaliciousWebsites.markdown %}) may result in the installation of [malicious codes]({% link _publications/bestpractices/MaliciousSoftwareBP.markdown %}) without the user’s knowledge. The organisation may also be held [liable]({% link _knowhow/glossary/Impact.markdown %}) for access to prohibited or illegal content.

To prevent employees accessing such websites, the organisation can install a web filter as a means of protection.

In technical terms, these filters are called “web proxies” and can take several forms. The best-known free proxies are “squid and squidguard”, “DansGuardian” and “HAVP”, which can be found in a large number of free or paid firewall products.

<h3 class="titre-page" id="how-it-works">How it works</h3>
A web filter analyses all communications (content and/or recipients) to and from the Internet to detect exchanges with sites hosting malicious, inappropriate or prohibited content. This filter is not to be confused with the browser’s [phishing filter]({% link _knowhow/glossary/Phishing.markdown %}), because unlike the latter, which is installed in the user’s browser, the web filter runs on a dedicated server and cannot be easily circumnavigated by the user.

<h3 class="titre-page" id="url-analysis">URL analysis</h3>
A web filter that analyses URLs has a database that links URLs with content categories. These databases are managed by specialised companies who associate the websites with various categories, such as pornography, gaming, gambling, and so on.

Once a new website has been discovered, it is categorised and, if necessary, added to the database. This type of filter does not prevent access to brand new websites that haven’t yet been categorised or access to websites that have only recently become malicious.

The organisation can nevertheless filter different content categories, such as pornography, gambling, social networks, etc.

### Content analysis
Some web filters are able to analyse the content of a website a user wants to visit. Based on a list of key words, the filter allocates a category to the websites visited and either displays or doesn’t display the requested content. This filter is useful for preventing access to recent content for which the URL analysis wouldn’t have worked, but can also generate a lot of false positives.

### Malicious content analysis
Some filters contain antivirus programs and can analyse the content of websites visited and block access to potentially [malicious software]({% link _publications/bestpractices/MaliciousSoftwareBP.markdown %}).

### Image analysis
Some web filters can analyse the requested images. The filter selects the images on the website visited and allocates them to a category before displaying or not displaying the content.

<h3 class="titre-page" id="security-policy">Security policy</h3>
Draw up and enforce the following sectoral policies:

* [Classification and monitoring of resources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources.markdown %})
  * [Classification of and responsibility for resources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources.markdown %}\#classification-and-responsibility-for-resources)
* [Human factors]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown %})
  * [Training and information]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown %}\#training-and-information)
  * [Response to incidents and security malfunctions]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown %}\#response-to-incidents-and-malfunctions)
* [Operational and communications aspects]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %})
  *[Documented procedures]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}\#documentation-of-procedures)
  * [Protection against malware]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}\#protection-against-malware)
  * [Email]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}\#email)
* [Access control]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %})
  * [Access control policy]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}\#access-control-policy)
  * [Access rights management]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}\#access-rights-management)
  * **[Use of external networks]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}\#use-of-external-networks)**
  * [Separation of networks]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}\#separation-of-networks)
* [Compliance]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance.markdown %})
  * [Personal data protection]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance.markdown %}\#personal-data-protection)
