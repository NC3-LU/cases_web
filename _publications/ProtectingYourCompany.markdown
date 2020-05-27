---
layout: publication-list
category: "In depth articles"
title:  "Protecting Your Company"
menutitle: "Protecting your company"
logo:
date:  2017-11-06 00:00:00 +0100
short: "Anticipate risks, protect your data, what are the good tips for protecting your business?"
categories: securing
toc: true
ref: protectingyourcompany
lang: en
---
## Prevent Risks
The best way to secure your company is to set up [a risk management process]({% link _knowhow/bestpractices/RiskManagement.markdown %}). This will identify protective measures tailored to the company’s situation and values, while simultaneously protecting the most important assets. See: '[Why manage risks?]({% link _publications/WhyManageRisks.markdown %})” and '[Why pool risk analysis?]({% link _publications/WhyPoolRisksAnalysis.markdown %})'

Risk can be defined using the following calculation: risk = vulnerability * [threat]({% link _knowhow/glossary/Threat.markdown %}) * impact. It is made up of a ‘probability’ factor (arising from the threat) and a ‘damage’ factor (arising from the value of the compromised asset, or corresponding to the value of the indirect damage suffered). The vulnerability used in this function takes into consideration the security measures have been implemented.

It is practically impossible to prevent a risk by acting on existing threats. We can, however, act on the risk by reducing the ‘vulnerability’ and ‘impact’ factors:

* Reduce the ‘vulnerability’ factor by implementing targeted security measures
* Reduce the potential impact through the implementation of data redundancies (this does not affect data confidentiality)

An organisation that is just setting up its data security may opt to introduce best practices without necessarily deploying processes specific to risk management.

'Threats' are all elements which could compromise the IT resources of an organisation. A list of threats that could affect a company is given in a dedicated article.

'Vulnerabilities' are all the human and technical weaknesses that could be exploited by threats to compromise them.

The 'impact' is the result of the exploitation of a vulnerability by a threat, and therefore the damage caused.

The combination of these three factors makes up the 'risk'.

## Protecting Data
As with data, business processes are known as primary assets ([Classification]({% link _knowhow/cisoapproach/SecurityPolicy-Classification.markdown %}) of [assets]({% link _knowhow/glossary/Assets.markdown %}); [risk management]({% link _knowhow/bestpractices/RiskManagement.markdown %})). The first priority for making an IT setup secure relates to the protection of these primary assets.

All entities have a particular interest in protecting their corporate data, especially information about the performance of their economic plan. Legal requirements, and even client expectations, also represent reasons which lead companies to protect specific data.

Different types of data that should be protected:

* [intellectual property]({% link _knowhow/cisoapproach/SecurityPolicy-Compliance.markdown %}#intellectual-property)
* manufacturing secrets
* client data
* process data, such as logistical, accounting, supplier data, etc.

[Loss of data]({% link _knowhow/glossary/DataLoss.markdown %}) generally has harmful consequences for any entity.

## Classification of Data
Before implementing protective measures, the entity should carry out at least a summary classification exercise over the data it processes. This classification is important to gain an awareness of the true value ([confidentiality]({% link _knowhow/glossary/Confidentiality.markdown %}), [integrity]({% link _knowhow/glossary/Integrity.markdown %}) and [availability]({% link _knowhow/glossary/Availability.markdown %})) of the data. Depending on the value of the data, with regard to the expected [impact]({% link _knowhow/glossary/Impact.markdown %}), if data becomes compromised, the entity will be able to decide on the investment to set aside for data security.

> Note: the classification applied to information should also be applied to the containers, meaning the physical locations and media holding the information. The term container should be understood in its broadest sense.

SME [security policy]({% link _knowhow/cisoapproach/SecurityPolicy-SecurityPolicy.markdown %}):

* [Classification and monitoring of resources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources.markdown %})
* [Access control]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}) -- [Access control policy]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#access-control-policy) and [Access rights management]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#access-rights-management)

## Data Backups
All data identified within a company as having an availability requirement must be backed up. By creating a backup copy, the loss or destruction of primary data can easily be offset. However, backing up data can become more problematic when the data to be backed up has confidentiality or integrity issues.

Data with a confidentiality requirement needs to be protected against any illicit access, regardless of the media on which it is found, and regardless of the location where it is stored.

Data with a major integrity requirement needs to be protected against any modification by unauthorised persons. This is just as true for the backups. Furthermore, concerning the original digitised papers, electronic archiving conditions need to be respected.

SME [security policy]({% link _knowhow/cisoapproach/SecurityPolicy-SecurityPolicy.markdown %}):

* [Operational aspects and communications]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}) --- [Data backups]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}#data-backups)
* [Physical and environmental security]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %}) --- [Physical security perimeter]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %}#physical-security-perimeter) and [Perimeter rules]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %}#rules-within-the-perimeter)
* [Access control]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}) -- [Access control policy]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#access-control-policy) and [Access rights management]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#access-rights-management)

## Data Destruction
Data no longer required by the company, meaning data which has to be deleted, must be destroyed in such a way that its confidentiality is not infringed.

The definitive and secure destruction of data must respect certain security criteria. There are methods which enable disks, or even the computer, to be reused.

For strictly confidential data, it is strongly recommended that data storage media, including hard disks, are destroyed by crusher or degausser.

SME [security policy]({% link _knowhow/cisoapproach/SecurityPolicy-SecurityPolicy.markdown %}):

* [Physical and environmental security]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %}) --- [Disposal and reuse of equipment]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %}#disposal-and-reuse-of-equipment)

## Transmission of Data
The technology used to transmit data must respect confidentiality and data integrity criteria (and more infrequently availability criteria).

The use of cryptographic measures is strongly recommended to protect the data to be transmitted against loss of confidentiality and integrity.

Any communication over the Internet (downloading, FTP) should be encrypted at least via SSL or preferably via a VPN network. Transmitting confidential data unencrypted via email should be strictly avoided.

SME [security policy]({% link _knowhow/cisoapproach/SecurityPolicy-SecurityPolicy.markdown %}):

* [Operational and communications aspects]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}) --- [E-mail]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}#email)
* [Development and maintenance of systems]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.markdown %}) --- [Use of encryption]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.markdown %}#encryption)
* [Access control]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}) --- [Use of external networks]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#use-of-external-networks)

SOS:

* [I am being asked for confidential information]({% link _knowhow/sos/SOS-IamAskedForConfidentialInformation.markdown %})

## Data Transport
The technology used for transport data must respect confidentiality, integrity and data availability requirements (especially for originals).

The use of cryptographic measures is strongly recommended, along with physical security to protect transported data against loss of confidentiality, integrity, and availability.

SME [security policy]({% link _knowhow/cisoapproach/SecurityPolicy-SecurityPolicy.markdown %}):

* [Operational and communications aspects]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}) --- [Device security during transport]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}#device-security-during-transport)
* [Physical and environmental security]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %}) --- [Off-site equipment security]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %}#off-site-equipment-security)
* [System development and maintenance]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.markdown %}) --- [Use of encryption]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.markdown %}#encryption)

## Protecting a Machine
The machines used to perform business processes and to process organisation information are known as secondary assets or support assets (see: [classification of]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources.markdown %}) [assets]({% link _knowhow/glossary/Assets.markdown %}); [risk analysis]({% link _publications/WhyPoolRisksAnalysis.markdown %})). To protect business processes or information, the support assets used to process such information must be protected.

If a computer or a server is compromised, this could obviously lead to a loss of confidentiality, availability and integrity in the processes or information they use.

For secondary assets, risk treatment measures should be introduced to prevent harmful impacts.

## Computers
Most organisations have at least one office computer for the management of the organisation. This computer must be protected against the commonest threats. Basic security measures are strongly advised.

Depending on the criticality of the data being processed, or the business processes supported, the protective measures should naturally be expanded.

SME [security policy]({% link _knowhow/cisoapproach/SecurityPolicy-SecurityPolicy.markdown %}):

* [Operational and communications aspects]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}) – [protection against malware]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}#protection-against-malware) and [Data backup]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}#data-backups)
* [access control]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %})

## Laptop Computers

Some organisations also use laptop computers as support assets for business processes or to process certain types of data. These laptop computers are often taken outside the secure office area and carried on private and public transport, and even used in private or public places. They are often connected to networks outside the organisation.
The potential threats to laptop computers are many, and any organisation wishing to use laptop computers should at least follow basic security measures.

SME [security policy]({% link _knowhow/cisoapproach/SecurityPolicy-SecurityPolicy.markdown %}):

* [Operational and communications aspects]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}) – [protection against malware]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}#protection-against-malware) and [Data backup]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}#data-backups)
* [Access control]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}) – [Access rights management]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#access-rights-management), and [Password management]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#password-management) and [Connection procedures]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#connection-procedures) and [External connections]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#external-connections) and [Use of external networks]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#use-of-external-networks)
* [Human factors]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown %}) – [Training and information]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown %}#training-and-information)
* [Classification and monitoring of resources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources.markdown %})
* [System development and maintenance]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.markdown %}) – [Use of encryption]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.markdown %}#encryption)

## File Servers
Some organisations use file servers to facilitate cooperation between different agents or to increase the level of resilience of stored data. Like other machines used by the organisation, file servers are support assets for business processes. However, they often represent the single point of failure for a small or medium-sized company.

Requirements in terms of confidentiality, availability and integrity in file servers are much greater than for other support assets owned by the organisation. It is crucial to apply basic security measures on this type of machine.

SME [security policy]({% link _knowhow/cisoapproach/SecurityPolicy-SecurityPolicy.markdown %}):

* [Operational and communications aspects]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}) – [protection against malware]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}#protection-against-malware) and [Data backup]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}#data-backups)
* [Access control]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}) – [Access control policy]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#access-control-policy) and [Access rights management]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#access-rights-management), and [Password management]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#password-management) and [Connection procedures]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#connection-procedures) and [External connections]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#external-connections) and [Separation of networks]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#separation-of-networks)
* [Human factors]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown %}) – [Training and information]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown %}#training-and-information)
* [Classification and monitoring of resources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources.markdown %})
* [Physical and environmental security]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %}) – [Physical security perimeter]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %}#physical-security-perimeter); [Rules within the perimeter]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %}#rules-within-the-perimeter); [Maintenance]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %}#maintenance) and [Disposal and reuse of equipment]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %}#disposal-and-reuse-of-equipment); [Electrical equipment safety]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %}#electrical-equipment-safety)

## E-mail Servers
Mail servers are always connected to the Internet. There is a large probability of being exposed to a threat, and it is often easy to exploit new vulnerabilities. Securing the mail server requires a degree of care, and sometimes even monitoring on the part of the organisation. E-mail is often the leading means of communication within a company (integrity) and very often contains files with sensitive content (confidentiality).

Small-scale organisations rarely have mail servers. It is too complex to manage and protect them within small operations.

SME [security policy]({% link _knowhow/cisoapproach/SecurityPolicy-SecurityPolicy.markdown %}):

* [Operational and communications aspects]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}) – [Protection against malware]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}#protection-against-malware) and [Data and email backup]({% link _knowhow/cisoapproach/SecurityPolicy-OperationalAndCommunicationAspects.markdown %}#data-backups)
* [Access control]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}) – [Access control policy]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#access-control-policy);[ Access rights management]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#access-rights-management), and [Password management]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#password-management); [Connection procedures]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#connection-procedures); [Separation of networks]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#separation-of-networks); [Use of external networks]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#use-of-external-networks)
* [Human factors]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown %}) – [Training and information]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown %}#training-and-information)
* [Classification and monitoring of resources]({% link _knowhow/cisoapproach/SecurityPolicy-ClassificationAndControlOfResources.markdown %})
* [System development and maintenance]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.markdown %}) – [Use of encryption]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.markdown %}#encryption)

## Web Server
Web servers do not always contain confidential data. Because of this, they are less affected by confidentiality issues. They are, however, supposed to operate constantly (availability) and must be able to withstand potential attacks or infection. Because of this, it is recommended to follow the recommendations for securing web servers.

## Protecting the Network
The network is a secondary asset supporting the business processes of the organisation, and transmitting the information processed within this organisation. It plays an essential role, as when compromised, it often leads to machines connected to it also being compromised.

## Local (fixed) Network
Most organisations connect their network, or part of their network, to the Internet. This exposes organisations to a huge number of potential threats. But the network can also be endangered by threats coming from within the organisation.

The installation of a firewall is an essential protective measure for the network, as it enables certain parts of the network to be partitioned.

Follow basic security measures to secure your local network.

SME [security policy]({% link _knowhow/cisoapproach/SecurityPolicy-SecurityPolicy.markdown %}):

* [Access control]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}) – [Connection procedures]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#connection-procedures) and [Access rights management]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#access-rights-management); [Use of external networks]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#use-of-external-networks) and [External connections]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#external-connections); [Separation of networks]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#separation-of-networks)
* [Physical and environmental security]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %}) – [Physical security perimeter]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %}#physical-security-perimeter) and [Perimeter rules]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %}#rules-within-the-perimeter)

## Wi-Fi Network
Many organisations set up a Wi-Fi network. It presents several benefits, but one major downside is that Wi-Fi waves travel through the air and are usually also accessible from outside the organisation.

Basic security measures for Wi-Fi networks are strongly advised.

SME [security policy]({% link _knowhow/cisoapproach/SecurityPolicy-SecurityPolicy.markdown %}):

* [Access control]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}) – [Connection procedures]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#connection-procedures) and [Access rights management]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#access-rights-management); [Use of external networks]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#use-of-external-networks)
; [Separation of networks]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#separation-of-networks)
* [IT systems management]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.markdown %}) – [Use of encryption]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.markdown %}#encryption)
* [Physical and environmental security]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %}) – [Physical security perimeter]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %}#physical-security-perimeter) and [Perimeter rules]({% link _knowhow/cisoapproach/SecurityPolicy-PhysicalAndEnvironmentalSecurity.markdown %}#rules-within-the-perimeter)

## Remote Working
Enabling secure access from outside the organisation can be done in different ways, based on the needs of the employees.

A mail access server is often enough and is easy to set up.

For greater access, it is strongly recommended to set up access via VPN.

SME [security policy]({% link _knowhow/cisoapproach/SecurityPolicy-SecurityPolicy.markdown %}):

* [Access control]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}) – [Connection procedures]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#connection-procedures) and [Access rights management]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#access-rights-management); [Use of external networks]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#use-of-external-networks)
; [Separation of networks]({% link _knowhow/cisoapproach/SecurityPolicy-AccessControl.markdown %}#separation-of-networks)
* [IT systems management]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.markdown %}) – [Use of encryption]({% link _knowhow/cisoapproach/SecurityPolicy-SystemDevelopmentAndMaintenance.markdown %}#encryption)

## Training and Awareness
Training and awareness-raising about the security of information and communication systems are crucial to ensure that security becomes a reality within our society.

SME [security policy]({% link _knowhow/cisoapproach/SecurityPolicy-SecurityPolicy.markdown %}):

* [Human factors]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown %}) – [Training and information]({% link _knowhow/cisoapproach/SecurityPolicy-HumanFactors.markdown %}#training-and-information);

Measures:

* [Awareness and training]({% link _publications/ProtectingYourCompany.markdown %}#training-and-awareness)

## Getting Organised
The security of a company in large part depends on its business processes. It is very difficult to apply security rules to a process that has not been designed with security in mind. Because of this, it is easier – and cheaper – to keep security in mind from the very creation of the company structure.

Analyse processes and try to change or eliminate those which are suboptimal – for example, those requiring a password to be shared.

The allocation of specific roles is essential: responsibilities for certain assets should be allocated, officers responsible for managing incidents should be appointed and good internal communication should be implemented.

SME [security policy]({% link _knowhow/cisoapproach/SecurityPolicy-SecurityPolicy.markdown %}):

* [Organisation of security]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity.markdown %}) – [Attribution of responsibilities]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity.markdown %}#attribution-of-responsibilities) and [Specialist advice]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity.markdown %}#specialist-advice); [Access by third-parties and sub-contracting]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity.markdown %}#third-party-access-and-outsourcing); [Independent review of information security]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity.markdown %}#independent-review-of-information-security);[ Authorisation procedure for the addition of tools]({% link _knowhow/cisoapproach/SecurityPolicy-OrganizationOfSecurity.markdown %}#authorising-the-addition-of-tools)

## Protecting the Premises
Most organisations have their own premises or establishment to host their offices, warehouses, archives and IT rooms. They may limit certain risks arising from threats that are environmental in origin, deliberate and accidental, compromising confidentiality, integrity or availability needs over important or vital assets.
 
The introduction of secure areas, as well as restricted access to these areas, and to assets found within them, significantly reduces the risk arising from deliberate or accidental threats.

Premises hosting important or vital assets must also be protected against environmental threats, such as fire (SMEs: see [Fire]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}#fire)), water damage, pollution, dust, corrosion, freezing temperatures, electrical damage or major incidents.

Please refer to the chapter devoted to the physical security of the organisation.

### Physical Access
The more important the asset, the more physical access must be controlled. The organisation will have a 'public' area, accessible to clients, and an internal area, only accessible to employees, as well as one or more secure areas only accessible to authorised personnel. Depending on their importance, the assets will only be deployed in the areas which correspond to their degree of protection. The security measures implemented should prevent physical intrusions.

For example, a file server containing critical documents for the organisation should not be located in a room with open access. The probability of malicious actions or accidents would be too high. (SMEs: see [Aggravated theft]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Hardware.markdown %}#aggravated-theft) and [Infiltrating the premises]({% link _knowhow/bestpractices/SecurityMeasures4SME-Threats2Infrastructure.markdown %}#infiltrating-the-premises))

## Communication and Social Networks
**Social networks** now form a part of our daily life. For companies and organisations, they present previously unheard-of opportunities. Many companies have already turned them into an effective **communication and marketing** lever.

Although they present many **benefits**, it is important not to ignore the **risks**, including:

* risk of loss of reputation
* risk of infection by virus or malicious code circulating on social networks
* risk of loss or disclosure of data
* risk of phishing, scam or form of social engineering through social networks.

Some simple measures can be set up to prevent this.

## Business Trips
Business data (commercial or strategic data, search results, expertise, etc.) must also be protected during any business trips which may take place.

If laptop computers, removable media or paper media holding this type of data leave the secure enclosure of the company, specific precautions must be taken.
