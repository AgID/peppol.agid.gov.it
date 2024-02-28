---
layout: post
title: Peppol November Release 2023 e other Italian modifications
lang: en
ref: peppol-november-release-2023-en
excerpt_separator: <!--more-->
tags:
categories: news
permalink: /en/news/peppol-november-release-2023-en/
---
We inform you that the updates related to the November Release 2023 of OpenPeppol and other modifications related to the Italian context have been published, whose entire release notes are available at the following addresses:

 - [Order only](https://peppol-docs.agid.gov.it/docs-next-release/docs/ITA/others/guides/release-notes-it/3-order-only/main.html); 
 - [Ordering](https://peppol-docs.agid.gov.it/docs-next-release/docs/ITA/others/guides/release-notes-it/28-ordering/main.html); 
 - [Order Agreement](https://peppol-docs.agid.gov.it/docs-next-release/docs/ITA/others/guides/release-notes-it/42-orderagreement/main.html); 
 - [Despatch Advice](https://peppol-docs.agid.gov.it/docs-next-release/docs/ITA/others/guides/release-notes-it/30-despatchadvice/main.html); 
 - [Billing](https://peppol-docs.agid.gov.it/docs-next-release/docs/ITA/invoice/guide/release-notes-it/main.html). 

The original content released by OpenPeppol is available [here](https://peppol.org/post-award-artefacts-for-november-2023-release-published/).

**These updates will be mandatory starting from 26th February 2024, nevertheless we advise to implement these changes in time and to download the schematron for the validation of the updated documents.**
<!--more-->

The current documentation, accessible until 25th February 2024, is available at the following addresses: 
 - [Billing](https://peppol-docs.agid.gov.it/docs/my_index_fatt.jsp); 
 - [Other Processes (Order only, Ordering, Order Agreement, Despatch Advice)](https://peppol-docs.agid.gov.it/docs/my_index.jsp).

The changes are described below: 
**Changes to the specification (documentation), syntax and code lists and validation artifacts – [Other Processes (order only, ordering, order agreement and despatch advice)](https://peppol-docs.agid.gov.it/docs-next-release/my_index.jsp)**

**Changes to specification (Documentation)**

 - BIS Order only, BIS Ordering, BIS Order Agreement, BIS Despatch Advice – Fixed an error in the section **4. Semantic datatypes*, where it previously stated that a “Boolean” is based on the primitive datatype “String”, this has been corrected to “Boolean”. This fix is purely editorial;
 - BIS Despatch Advice – Integration of section *6.3.2. Despatch address* with the indication of home delivery in analogy to the order specification;
 - BIS Order only, BIS Ordering, BIS Order Agreement, BIS Despatch Advice – Minor editorial modifications.

**Syntax changes**

 - Order
    - Renamed the element cbc:OrderTypeCode from "Consignment Order" to "Order Type" to avoid confusion. No changes to the italian specification;
    - Minor editorial modifications.

**Changes to code lists and validation artifacts**

 - Added type codes 105 "Purchase order" and 402 "Intermediate handling cross docking order to the Order Type Code code list;
 - Added code 0218 (Latvia) to EAS code list;
 - Added correlation between CEL code and °C [Celsius degree] unit in Recommendation 20, including Recommendation 21 codes - prefixed with X (UN/ECE).
 - Modification in the severity level of the business rules for the Peppol Despatch Advice from WARNING to FATAL.

**Changes to the specification (documentation), syntax and code lists and validation artifacts – [Billing](https://peppol-docs.agid.gov.it/docs-next-release/my_index_fatt.jsp)**

**Changes to specification (Documentation)**

 - Update of section *4. Negative invoices and credit notes*, and removal of the reference to the BIS2 format. This fix is purely editorial;
 - Added specific examples in sections *4.9.1. Stamp Withdrawal and 4.9.2. Stamp refund*;
 - Added new section *4.11 Indication of advance payment on the balance invoice* containing the operational procedures for indicating an advance payment on the balance invoice;
 - Update of sections *15.1. Peppol transaction business rules e 15.2. EN 16931 transaction business rules* to align with the EN 16931 schematron updates;
 - Update of sections Appendix C: *National rules* to align with the technical rules of Agenzia delle Entrate related to the management of European invoices - version 2.3 and modifications of the following rules:
    - *C.1. CIUS*: BR-IT-120; BR-IT-180; BR-IT-200; BR-IT-230;
    - *C.4. Domestic Extensions*: BR-IT-DE-011; BR-IT-DE-046; BR-IT-DE-049.
 - Integration of the sections of *Appendix C: National Rules* to align with the SDI controls of the documents and insertion of the following new rules:
    - *C.1. CIUS*: BR-IT-071; BR-IT-081; BR-IT-091; BR-IT-171; BR-IT-222; BR-IT-361;
    - *C.2. Domestic CIUS*: BR-IT-DC-141; BR-IT-DC-161; BR-IT-DC-221; BR-IT-DC-262; BR-IT-DC-291; BR-IT-DC-351;
    - *C.4. Domestic Extensions*: BR-IT-DE-013*; BR-IT-DE-050; BR-IT-DE-051; BR-IT-DE-052
 - Update of the rule BR-IT-DC-480* related to the control of the presence of the stamp on the documents with amount exceeding 77,47 euros;
 - Minor editorial modifications.

**Changes to code lists and validation artifacts**

 - Removal of rule PEPPOL-EN16931-R006 from *Rules for Peppol BIS 3.0* because it duplicates the European standard rule UBL-SR-04, making it redundant and unnecessary;
 - Modifications of specific *Rules for Italian CIUS* (CIUS ID BR-IT-120; BR-IT-180; BR-IT-200; BR-IT-230; BR-IT-520C*; BR-IT-DC-203) and *Rules for Italian extension* (CIUS ID BR-IT-DE-009NC1*; BR-IT-DE-011) to align with the technical rules of Agenzia delle Entrate related to the management of European invoices – version 2.3;
 - Integration of the *Rules for Italian CIUS* and *Rules for Italian extension* to align with the SDI controls of the documents and insertion of the following new rules:
    - *Rules for Italian CIUS*: BR-IT-071; BR-IT-081; BR-IT-091; BR-IT-171; BR-IT-222; BR-IT-361; BR-IT-DC-141; BR-IT-DC-161; BR-IT-DC-221; BR-IT-DC-262; BR-IT-DC-291; BR-IT-DC-35;
    - *Rules for Italian extension*: BR-IT-DE013*; BR-IT-DE-050; BR-IT-DE-051; BR-IT-DE-052.
 - Added code 0218 (Latvia) to EAS code list;
 - Added correlation between CEL code and °C [degree Celsius] unit in Recommendation 20, including Recommendation 21 codes - prefixed with X (UN/ECE).

**EN 16931 schematrons updated**

 - Adopted version 1.3.11 of EN 16931 validation artefacts.

**Changes in the Downloads section**

 - Added a new example file related to the invoice on account – balance.
