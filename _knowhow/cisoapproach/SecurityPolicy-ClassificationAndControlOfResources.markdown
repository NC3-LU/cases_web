---
layout: knowhow
title:  "Security Policy – Classification and control of resources"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: f-ciso
toc: true
---
<h3 class="titre-page">Classification and responsibility for resources</h3>
An [inventory of the “organisation’s” vital and important resources]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources.html#inventory-of-assets) should be kept up to date. It takes the form of a table describing the resource and naming the person or persons in charge. The [classification]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-Classification.html) of [assets]({% link _knowhow/glossary/Assets.markdown %}) is an extremely important task.

The level of importance of the resource for the company is also specified:

* vital
* important

The following elements are considered [resources]({{site.url}}):

* computers (PC, laptops, servers, netbooks) and printers;
* communications equipment (modem, switch, router, PABX, fax, etc.);
* files and databases (regardless of the device: disks, CD-ROMs, tapes, etc.);
* applications (software);
* documents (contracts, procedures, plans, archives, etc.).

#### Comments
Elements classified as "**vital**" are those that could compromise the *organisation’s* existence if they disappear, are disclosed externally or become defective.

Elements considered as "**important**" are those that could cause serious consequences for the company under the same conditions.

#### Security measures:

* [file servers]({% link _publications/recommendationsecuring/Recommendations4securingFileServer.markdown %})
* [email servers]({% link _publications/recommendationsecuring/Recommendations4securingEmailServer.markdown %})
* [fixed network]({% link _publications/recommendationsecuring/SecuringFixedNetwork.markdown %})
* [internal WiFi network]({% link _publications/recommendationsecuring/SecuringWifiNetwork.markdown %}\#wifi-for-employees)
* [customer WiFi network]({% link _publications/recommendationsecuring/SecuringWifiNetwork.markdown %}\#wifi-for-visitorsexternal-users)
* [computers connected to the Internet]({% link _publications/recommendationsecuring/SecuringFixedWorkstation.markdown %})
* [laptop computers]({% link _publications/recommendationsecuring/SecuringLaptops.markdown %})

#### Directly associated organisational measures:

* [Organisation of security]({% link _knowhow/cisoapproach/SecurityPolicy-OrganisationOfSecurity.markdown %})
  * [Attribution of responsibilities]({% link _knowhow/cisoapproach/SecurityPolicy-OrganisationOfSecurity.markdown %}\#attribution-of-responsibilities)
* [Operational and communications aspects]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %})
  * [Documented procedures]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}\#documentation-of-procedures)
* [Access control]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %})
  * [Access control policy]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}\#access-control-policy)
  * [Access rights management]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}\#access-rights-management)
* [Compliance]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance.markdown %})
  * [Identification of applicable legislation]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance.markdown %}\#comply-with-legislation)
  * [Intellectual property]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance.markdown %}\#intellectual-property)
  * [Protection of operational data]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance.markdown %}\#protection-of-operational-data)
  * [Personal data protection]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance.markdown %}\#personal-data-protection)

#### Technical measures:

* [classification]({% link _knowhow/cisoapproach/SecurityPolicy-Classification.markdown %})

<h3 class="titre-page">Inventory of assets</h3>

An inventory of the “organisation’s” major resources ([assets]({% link _knowhow/glossary/Assets.markdown %})) should be kept up to date. It takes the form of a table describing the resource and naming the person or persons in charge. Each asset should be [classified]({{site.url}}/knowhow/cisoapproach/SecurityPolicy-Classification.html)) according to [confidentiality]({{site.url}}/knowhow/bestpractices/SecurityMeasures4SME-CheckList.html)), [integrity]({% link _knowhow/glossary/Integrity.markdown %})) and [availability]({% link _knowhow/glossary/Availability.markdown %})) requirements.

Elements classified as “vital” are those that could compromise the “organisation’s” existence if they disappear, are disclosed externally or become defective. Elements considered as “important” are those that could cause serious consequences for the company under the same conditions.

The management and classification of properties is based on the following principles:

1. Application to all assets, in other words, anything with value, including information, such as listed in an inventory.
2. Determination of a manager for each asset type.
3. Ensure the correct use of assets in accordance with the security rules for the different classes.
4. Regular review by the manager.
5. Classification based on 3 criteria: confidentiality, integrity and availability.
6. Classification depending on [impact]({% link _knowhow/glossary/Impact.markdown %})).
7. Confidentiality classification legacy.
8. Qualification of contents to simplify management rules.
9. Default classification.
10. Marking to ensure the security rules are taken into account when handling assets.
11. Use of [encryption]({{site.url}}/knowhow/glossary/Cryptography.html)) to ensure that sensitive information is transported in a sufficiently well-protected container.

Which is where the following rules and responsibilities come in:

1. Each item must be inventoried and attributed to a manager who is responsible for determining its classification and the [security measures]({{site.url}}/publications/ProtectingYourCompany.html)) to be applied.
2. An item that contains other items must have at least the same classification as the most sensitive item it contains.
3. Information always has the same classification, regardless of the form in which it is found.
4. The security manager is responsible for characterising the contents.
5. The security policy and any document contained within it will be inspired by internationally recognised best practice in security management. Best practice is documented in [ISO/IEC standards 27001]({{site.url}}/publications/ISO27000SF/ISO27001-ISMS.html)) and [27002]({{site.url}}/publications/ISO27000SF/ISO27002-CodeBestPractices4ISM.html)).
6. An item’s manager must have reached the rank of division manager or his replacement.
7. The security manager is responsible for characterising the contents.
8. The classification policy is implemented through procedures.
9. These procedures and documents are available to all staff.
