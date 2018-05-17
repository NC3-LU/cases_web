---
layout: publication-list
title:  "Risk management"
menutitle: "Risk management"
logo:
date:  2017-11-06 00:00:00 +0100
short: "How is a risk analysis conducted? What are the different criteria? Or how are the risks estimated"
categories: bestpractice
toc: true
---
General guidelines regarding risk management as used by CASES are taken from the ISO/IEC 27005 standard, part of the [ISO/IEC 27000]({% link _publications/ISO27000SF.markdown %}) family of standards. [ISO/IEC 27001]({% link _publications/ISO27000SF/ISO27001-ISMS.markdown %}) governs the implementation of an information security management system which must include a risk management procedure. Risk management is the approach specified in ISO/IEC 27001 which forms the basis of the [security policy]({% link _knowhow/CISOApproach.markdown %}) for the organisation concerned.

The diagram below outlines the risk management process.

<h3 class="titre-page" id="definition-of-the-context">Definition of the context</h3>
To produce a risk analysis, it is first important to specify the basic criteria (risk assessment, impact, acceptance of risks, availability of resources, etc.), the objective and the scope of the analysis. The definition of the context notably describes the environment and the subject of the risk management process.

The risk **assessment criteria** notably include:

* the strategic values of the processes
* [asset](-) [criticality]({% link _knowhow/cisoapproach/SecurityPolicy-Classification.markdown %})
* legal and contractual requirements
* the importance of CAI ([confidentiality](-), [availability](-), [integrity](-))
* the expectations of the invested parties and the reputation

So for a registration service, for example, the confidentiality criterion is less important than the integrity criterion. In certain business lines, there are risks that must be avoided at all costs. In others, there are assets that must be protected at all costs. These contextual values are defined during the assessment phase. They must be applied throughout the whole risk analysis.

The **[basic criteria](-)** must also be determined:

* [Impact](-) criteria:
  * how to express the degree of damage and the associated costs, how to express damage in terms of reputation or damage caused by legal consequences.
  * qualitative and quantitative scale
* Risk acceptance criteria:
  * define acceptable levels of risk (potentially different for confidentiality, integrity and availability)
* Define the objective and the scope of the risk analysis
  * which assets must be included
  * what is the scope of the risk analysis
  * how to deal with risks within the scope
* Definition of the organisation’s values
  * business line
  * missions
  * values
  * structure
  * sociocultural values
  * limitations...

Then, the **organisation** of the risk analysis must be defined:

* management process
* actors and their respective roles
* escalation mechanisms
* relationships between actors and stakeholders
* records that need to be kept and are used to document the risk management process

<h3 class="titre-page" id="risk-identification">Risk identification</h3>
The purpose of risk identification is to determine the causes of impacts and understand how, where and why this damage can occur. This is the preparation phase for the risk estimation itself. It proceeds as follows:

* Identification of [assets](-):
  * primary assets, such as business line processes and information
  * secondary assets or support assets
* Identification of [threats](-)
* Identification of existing [security measures]({% link _publications/ProtectingYourCompany.markdown %})
* Identification of [vulnerabilities]({% link _knowhow/glossary/Vulnerabilities.markdown %}) (inherent to the identification of risk specifics)
* Identification of [impacts](-) (consideration of impact criteria: see also [classification]({% link _knowhow/cisoapproach/SecurityPolicy-Classification.markdown %}))

As a result, it is possible to draw up a list of assets which require risk management.

<h3 class="titre-page" id="risk-estimation">Risk estimation</h3>
Risk estimation is comprised of several phases:

1. the choice of methodology
2. estimation of the [impacts](-)
3. estimation of likelihood of occurrence
4. estimation of risk level

It involves calculating a value, in other words an approximative level for identified risks, based on the method used (which must guarantee repeatability), by estimating the impacts as well as the likelihood of occurrence. (For example, an approximate impact (qualitative scale) is multiplied by the likelihood of occurrence (qualitative scale) to determine the risk estimation).

<h3 class="titre-page" id="risk-assessment">Risk assessment</h3>
During this stage, you’ll need to use the knowledge of the risk obtained from the risk analysis, and also take the entity’s contractual, legal and regulatory obligations into consideration.
The estimated risks are prioritised in order of importance, based on the decisions made when defining the context of the risk analysis.

<h3 class="titre-page" id="risk-treatment"> Risk treatment</h3>
This final stage suggests the measures to be put in place. For this, the security measures need to be organised depending on:

* the measures to be considered;
* the order of importance and priorities.

The whole system is based on the “Return on Security Investment” calculation – the income obtained from the implementation of risk reduction solutions. These calculations are based on the previously calculated ALE (“Annualised Loss Expectancy”) and on the calculation of costs incurred to implement the solution.

The risk analysis method ends with the choice of treatment. The analysis must still be implemented and the methods applied. However, it does help with the implementation of an action plan.

There are 4 risk treatment options:

1. “Risk reduction”, which consists of reducing the risk by choosing the appropriate security objectives and measures (See: [Sectoral risk analysis – risk treatment]({% link _services/diagnostic.markdown %}));
2. “Risk conservation”, which consists of accepting current risks without taking further action;
3. “Risk refusal”, which consists of giving up the activity or domain at the source of the risk;
4. “Risk transfer” to a third party, by means of insurance coverage, for example.

Any resulting residual risk must be approved by the management board of the entity concerned.

<h3 class="titre-page" id="risk-acceptance">Risk acceptance</h3>
Risk acceptance is the approval given by the management board of choices made during the risk treatment. The management board therefore agrees to the treatment plan, as well as to the residual risks.

<h3 class="titre-page" id="information-sharing">Information sharing</h3>
This is a continuous process that allows for the exchange and sharing of information on the risks between the decision-makers and the stakeholders. The purpose of risk communication is to:

* reduce misunderstandings with decision-makers
* improve coordination for incident response
* share the results of the risk assessment and present the treatment plan
* gain new knowledge about security
* improve security awareness

<h3 class="titre-page" id="monitoring-and-re-examination">Monitoring and re-examination</h3>
This process consists of monitoring and re-examining elements of the risk:

* asset values and categories
* impacts, [threats](-), vulnerabilities, likelihoods of occurrence
* external elements (legal or environmental context)
* modification of the risk assessment approach (impact, assessment, risk acceptance criteria)
* etc.
