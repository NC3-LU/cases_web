---
layout: knowhow
title:  "Classification"
menutitle:  
logo:
date:   2017-11-06 00:00:00 +0100
short: "Renforcez vos défenses. Organisez votre protection."
categories: f-ciso
toc: true
ref: cisoclassification
lang: fr
---
Asset identification and classification are integral to risk management and are key elements of information security management (also called Information Security Management System – WSIS, see [ISO/IEC 27001]({% link _publications/ISO27000SF/ISO27001-ISMS.markdown %})). They define security needs in terms of confidentiality, availability and integrity.

Draft and enforce a sectoral policy on classification and control of resources

## Classification principles

* The greater the impact of a disclosure, the higher the confidentiality classification will need to be.
* The greater the impact of a loss due to the compromise of an asset, the higher the integrity classification will need to be.
* The longer the impact of a prolonged disruption to legitimate access to the asset, the higher the availability classification will need to be.

## Importance of classification
Asset classification is primarily used to perform risk analysis. Such classification requires that the criticality of an asset (= classification level – potential impact) be associated with the associated threats and vulnerabilities.

The classification will enable risks to be assessed as objectively as possible and a plan to be established to respond to them. The beneficiary will therefore be able to ensure that major risks are reduced, given the available investment.

## Classification scheme
Each company has assets that are more or less critical to ensuring that it runs smoothly. These assets include business processes, people, information and of course machines. In order to implement efficient and effective security measures, it is necessary to define a level of protection to be provided for each asset.

This means it is important to classify assets and determine their criticality in terms of the level of confidentiality, integrity and availability.

## Confidentiality
The following diagram shows the official abbreviation, the name, and a description of the confidentiality classes. It also refers to the classes of the "Traffic Light protocol" schema, defined by the English administration NISCC. These classes define distribution rules for information used to protect critical infrastructure.

<table class="classification">
<tr>
<th style="width: 15%;">Category</th>
<th>1) Impact 2) Management 3) Example 4) Tools</th>
<th style="width: 20%;">TLP Correspondence</th>
</tr>
<tr>
<td style="background-color:#DD0000; color:white; font-weight:bold;">SE, Secret</td>
<td>
<ol>
<li>Disclosure could seriously harm the interests of the organisation.</li>
<li>Management according to well-established procedures, stored only in encrypted locations under the exclusive control of the holder.</li>
<li>Information classified by law (EU, NATO, National, etc.), passwords, sensitive information.</li>
<li>Use of cryptography, safe, memory only.</li>
</ol>
</td>
<td>
<strong>Red</strong><br /><br />

Personal for named recipients only, mostly passed verbally or in person
</td>
</tr>
<tr>
<td style="background-color:orange; font-weight:bold;">
CO, Confidential
</td>
<td>
<ol>
<li>Disclosure could harm the interests of the organisation.</li>

<li>Management according to well-established procedures, access restricted to persons with an approved reason.</li>

<li>Bank secrets, sensitive personal data (health), security incidents.</li>

<li>Use of cryptography, non-shared local storage, formally managed access permissions.</li>
</ol>
</td>
<td>
<strong>Orange</strong><br /><br />

Limited distribution, within organization, but only on a ‘need-to-know’ basis.
</td>
</tr>
<tr>
<td style="background-color:#00CC00; font-weight:bold;">
RE, Restricted
</td>
<td>
<ol>
<li>Disclosure could be detrimental to the interests of the organisation or authorised group.</li>

<li>Management based on employment contract or NDA, personal data (salary), reason shared by a file manager.</li>

<li>Internal network documentation or diagram, source program.</li>

<li>Use of cryptography, strictly managed access permissions.</li>
</ol>
</td>
<td>
<strong>Green</strong><br /><br />

Community wide. Circulation, may not be published or posted on the Internet, nor released outside of the community.
</td>
</tr>
<tr>
<td style="background-color: #00CC00; font-weight:bold;">
IN, Internal
</td>
<td>
<ol>
<li>Disclosure could sometimes be detrimental to the interests of the organisation or authorised group.</li>

<li>Can be sent to other organisations in the same community.</li>

<li>User guide, some direct phone numbers, operating procedure.</li>

<li>Free internal use and transmission, protection must be ensured for external transmission. </li>
</ol>
</td>
<td>
<strong>Green</strong><br /><br />

Community wide. Circulation, may not be published or posted on the Internet, nor released outside of the community.
</td>
</tr>
<tr>
<td style="background-color: white; font-weight:bold;">
PU, Public
</td>
<td>
<ol>
<li>Information where disclosure is not generally harmful.</li>

<li>Can circulate freely because accessible outside the organisation.</li>

<li>Various publications, information content of a website.</li>

<li>No constraints on use or transmission.</li>
</ol>
</td>
<td>
<strong>White</strong><br /><br />

Unlimited, subject to standard copyright rules, WHITE information may be distributed freely, without restriction.
</td>
</tr>
</table>

## Integrity
The following diagram shows the official abbreviation, the name, and a description of the integrity classes.

<table class="classification">
<tr>
<th style="width: 15%;">
Category
</th>
<th>
1) Impact 2) Management 3) Example 4) Tools
</th>
</tr>
<tr>
<td style="background-color:#DD0000; color:white; font-weight:bold;">VIT, Vital</td>
<td>
<ol>
<li>Modification could result in significant losses to the organisation or might enable the person making the change to enrich themselves significantly.</li>
<li>Regular (very frequent) formal control procedures are implemented (approximately once a week to once a month maximum).</li>
<li>"DHL" mail, EDM system, configuration of servers or storage elements, telephone lines.</li>
<li>Use of signature, safe.</li>
</ol>
</td>
</tr>
<tr>
<td style="background-color: orange; font-weight:bold;">
IMP, Important
</td>
<td>
<ol>
<li>Modification could lead to inefficiencies or significant recovery costs./li>
<li>Regular formal control procedures are often implemented. (about every 3 months).</li>
<li>Registered mail, encrypted email, configuration of client computers (PC, laptop, PDA, etc.).</li>
<li>Limitation of Access rights.</li>
</ol>
</td>
</tr>
<tr>
<td style="background-color:white; font-weight:bold;">
NOR, Normal
</td>
<td>
<ol>
<li>There are no security requirements in addition to confidentiality protection.</li>
<li>Regular control procedures are often implemented. (about every 6 months to 1 year).</li>
<li>Internal mail, email, Internet browsing, etc.).</li>
<li>No constraints on use or transmission.</li>
</ol>
</td>
</tr>
</table>

## Availability
Availability is expressed in terms of estimated time to recover from any failure.

<table class="classification classification--small">
<tr><th>Category</th><th>Category code</th><th>Downtime per year in calendar days</th><th>owntime per year in working days</th></tr>
<tr><td>1</td><td>20D</td><td>1 month</td><td>+/- 20 days</td></tr>
<tr><td>2</td><td>10D</td><td>½ month</td><td>2 weeks</td></tr>
<tr><td>3</td><td>5D</td><td>1 week</td><td>5 days</td></tr>
<tr><td>4</td><td>2.5D</td><td>½ week</td><td>2½ days</td></tr>
<tr><td>5</td><td>1D</td><td>1 day</td><td>8 hours</td></tr>
<tr><td>6</td><td>0.5D</td><td>½ day</td><td>4 business hours</td></tr>
<tr><td>7</td><td>0.1D</td><td>1 hour</td><td>1 hours</td></tr>
</table>
