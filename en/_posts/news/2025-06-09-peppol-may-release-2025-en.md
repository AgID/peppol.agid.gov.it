---
layout: post
title: Peppol May Release 2025
lang: en
ref: peppol-may-release-2025-en
excerpt_separator: <!--more-->
tags:
categories: news
permalink: /en/news/peppol-may-release-2025-en/
---
We inform you that the updates related to the May Release 2025 of OpenPeppol and other modifications related to the Italian context have been published, the entire release notes are available at the following addresses:

 - [Order only](https://peppol-docs.agid.gov.it/docs-next-release/docs/ENG/others/guides/release-notes-it/3-order-only/main.html);
 - [Ordering](https://peppol-docs.agid.gov.it/docs-next-release/docs/ENG/others/guides/release-notes-it/28-ordering/main.html);
 - [Despatch Advice](https://peppol-docs.agid.gov.it/docs-next-release/docs/ENG/others/guides/release-notes-it/30-despatchadvice/main.html);
 - [Billing](https://peppol-docs.agid.gov.it/docs-next-release/docs/ENG/invoice/guide/release-notes-it/main.html).

**These updates will be mandatory starting from 25th of August 2025, nevertheless we advise to implement these changes in time and to download the schematron for the validation of the updated documents.**

<!--more-->

The current documentation, accessible until 24th of August 2025, is available at the following addresses:
 - [Billing](https://peppol-docs.agid.gov.it/docs/my_index_fatt-ENG.jsp);
 - [Other processes (Order Only, Ordering, Order Agreement, Despatch Advice)](https://peppol-docs.agid.gov.it/docs/my_index-ENG.jsp).

The changes of the May Release 2025 are described below:

**Changes to the specification (documentation), syntax and code lists and validation artifacts – [Other Processes (order only, ordering and despatch advice)](https://peppol-docs.agid.gov.it/docs-next-release/my_index-ENG.jsp)**

**Changes to documentation**
•	Order:
o	Changed paragraph “7.16.1. Delivery Location (DeliveryLocation)”;
o	Changed paragraph “7.4.2. Details on Medical Devices and their identification - UDI code”.
•	Despatch Advice:
o	Added new paragraph “4.2.1 Process of return of goods” that describes the scenario in case of returns advice;
o	Added new paragraph “5.4 Despatch Type” that describes the different process of despatch (despatch advice, consignment dispatch advice, returns advice);
o	Changed the paragraph “8.1.2. Details on Medical Devices and their identification - UDI code” as of the new element cac:ItemInstance/cbc:ProductTraceID to indicate the UDI code for medical devices.

**Syntax changes**
 - Order:
    - Added new structure cac:Despatch with two elements cbc:RequestedDespatchDate and cbc:RequestedDespatchTime;
    - Updated schematron to version 3.6;
- Despatch Advice:
    - Added new element cac:ItemInstance/cbc:ProductTraceID and relative @schemeID to indicate the UDI code;
    - Added new element cbc:DespatchAdviceTypeCode to indicate the type of despatch advice, if it is a despatch advice, consignment dispatch advice or returns advice.

**Changes to code lists and validation artifacts**
 - Order, Order Response – Updated the codelists Electronic Address Scheme (EAS), ISO 6523 ICD list, ISO 4217 Currency codes, Item type identification code (UNCL7143);
 - Order Response – Modification of the severity level from WARNING to FATAL of the rules PEPPOL-T76-R007, PEPPOL-T76-R008 e PEPPOL-T76-R009
 - Despatch Advice – Updated the codelists Electronic Address Scheme (EAS), ISO 6523 ICD list, Item type identification code (UNCL7143), Measured attribute code for despatch advice (UNCL6313 Subset) and added new codelists ProductTraceIDschemeID and Despatch advice type code (UNCL1001 subset).

**Changes to the specification (documentation), syntax and code lists and validation artifacts – [Billing](https://peppol-docs.agid.gov.it/docs-next-release/my_index_fatt-ENG.jsp)**

**Changes to documentation**
 - Small editorial changes.

**Changes to syntax**
 - Removed reference to rule BR-CO-25 in the element cbc:PaymentDueDate in the Credit Note syntax.

**Changes to code lists and validation artifacts**
 - Modification of the rules PEPPOL-EN16931-R051, PEPPOL-COMMON-R042, DK-R-003 (Denmark), DK-R-004 (Denmark) e DK-R-008 (Denmark);
 - Small changed to codelists Electronic Address Scheme (EAS), ISO 6523 ICD list, ISO 4217 Currency codes, Invoiced object identifier scheme (UNCL 1153), Payment means code (UNCL4461), Item type identification code (UNCL7143), VATEX code list, Invoice type code (UNCL1001 subset).
 
**EN 16931 schematrons updated**
 - Update of schematron EN 16931.
