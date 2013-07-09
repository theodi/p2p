---
layout: default
title: Privacy
link: /privacy/
menu: bottom
---

### Personal data

The P2P data derives mostly from individuals and hence counts as personal data. To avoid re-identification of individuals we completed the following three steps:

1. Published the data without postcodes or other direct identifiers
2. Omitted all variables which are not relevant to this study such as sector or purpose
3. Conducted a privacy impact assessment (see below) 

### Small-scale privacy impact assessment (PIA)

Following the ICO's [guide](http://www.ico.org.uk/upload/documents/pia_handbook_html_v2/html/1-Chap1-1.html) we conducted a small-scale PIA. The [screening questions](#screening) for the small-scale PIA are in the next section. 

The initial consultation included all three P2P lending platforms. The main concerns for re-identification were fields that included free-text comments and the postcode of the lender or recipient. 

We therefore decided not to include the fields that held additional information such as loan purpose or comment. They were not used in this project. Regarding the risk of releasing postcodes we relied on the following guidelines:

> In England, when anonymising postcodes the following average characteristics of postcodes should be considered:
> 
> * full postcode = approx 15 households (although some postcodes only relate to a single property)
> * postcode minus the last digit = approx 120/200 households 
> * postal sector = 4  outbound digits + 1 inbound gives approx 2,600 households 
> * postal district = 4 outbound digits approx 8,600 households 
> * postal area = 2 outbound digits approx 194,000 households
>  
> Source: Centre for Advanced Spatial Analysis: UCL

A acceptable trade-off between granularity and usefulness resulted in postal districts. In Scotland, some districts may be below 8,600 households; this is still far above standard thresholds for avoiding re-identification.

The only output that utilises postcodes are maps that show the growing market over time. However, the resolution is not high enough to identify particular postcodes and, moreover, there is no additional information about loans displayed on the map.

Prior to publication, and in the final stage of the project, we conducted another consultation with the three P2P platforms. The unanimous assessment was that the risk of re-identification following these anonymisation steps is close to zero. If this project continues past pilot stage, we will have this independently audited.

### <span id="screening">Screening questions for small-scale PIAs</span>

#### 1. Does the project apply new or additional information technologies that have substantial potential for privacy intrusion?

* No. Web technologies are arguably no longer new technologies and financial data exists similarly in the traditional banking sector.
* The data relates to individual loan parts and does not provide any information regarding the identity of the lender or recipient.

#### 2. Does the project involve new identifiers, re-use of existing identifiers, or intrusive identification, identity authentication or identity management processes?

* No. The project only uses identifiers for loans.
* The original identifiers were masked by a generic list.

#### 3. Might the project have the effect of denying anonymity and pseudonymity, or converting transactions that could previously be conducted anonymously or pseudonymously into identified transactions?

* No. The data does not include names or any other identifiers.
* The transactions are never completely anonymous as individuals have to sign up to the platform.

#### 4. Does the project involve multiple organisations, whether they are government agencies (eg in 'joined-up government' initiatives) or private sector organisations (eg as outsourced service providers or as 'business partners')?

* The project involves three private businesses.

#### 5. Does the project involve new or significantly changed handling of personal data that is of particular concern to individuals?

* The publication of P2P transactions does not involve any new or or significantly changed handling of personal data.

#### 6. Does the project involve new or significantly changed handling of a considerable amount of personal data about each individual in the database?

* No. The data relates to loans, is considerably reduced in size and is a snapshot in time.

#### 7. Does the project involve new or significantly changed handling of personal data about a large number of individuals?

* No, as outlined in question 6. 

#### 8. Does the project involve new or significantly changed consolidation, inter-linking, cross-referencing or matching of personal data from multiple sources?

* No. The only link to other data sources occurs on a regional level and are population estimates.

#### 9. Does the project relate to data processing which is in any way exempt from legislative privacy protections?

* No. 

#### 10. Does the project's justification include significant contributions to public security measures?

* No.

#### 11. Does the project involve systematic disclosure of personal data to, or access by, third parties that are not subject to comparable privacy regulation?

* The data can be viewed outside the UK. However, after the process of anonymisation it is no longer personal data.

