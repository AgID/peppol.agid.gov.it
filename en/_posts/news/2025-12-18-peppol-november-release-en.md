---
layout: post
title: Peppol November Release 2025 e other Italian modifications
lang: en
ref: peppol-november-release-2025-en
excerpt_separator: <!--more-->
tags:
categories: news
permalink: /en/news/peppol-november-release-2025-en/
---
We inform you that the updates related to the November Release 2025 of OpenPeppol have been published, the entire release notes are available at the following addresses:

 - [Billing](https://peppol-docs.agid.gov.it/docs-next-release/docs/ENG/invoice/guide/release-notes-it/main.html).
 - [Order only](https://peppol-docs.agid.gov.it/docs-next-release/docs/ENG/others/guides/release-notes-it/3-order-only/main.html); 
 - [Ordering](https://peppol-docs.agid.gov.it/docs-next-release/docs/ENG/others/guides/release-notes-it/28-ordering/main.html); 
 - [Order Agreement](https://peppol-docs.agid.gov.it/docs-next-release/docs/ENG/others/guides/release-notes-it/42-orderagreement/main.html); 
 - [Despatch Advice](https://peppol-docs.agid.gov.it/docs-next-release/docs/ENG/others/guides/release-notes-it/30-despatchadvice/main.html); 
  

**These updates will be mandatory starting from 23rd of February 2026, nevertheless we advise to implement these changes in time and to download the schematron for the validation of the updated documents**
<!--more-->

The current documentation, accessible until 22nd of February 2026, is available at the following addresses:
 - [Billing](https://peppol-docs.agid.gov.it/docs/my_index_fatt-ENG.jsp); 
 - [Other Processes (Order only, Ordering, Order Agreement, Despatch Advice)](https://peppol-docs.agid.gov.it/docs/my_index-ENG.jsp).

The changes of the November Release 2025 are described below:

**Changes to the syntax and code lists and validation artifacts – [Other Processes (order only, ordering, order agreement and despatch advice)](https://peppol-docs.agid.gov.it/docs/my_index-ENG.jsp)**

**Changes to the syntax**

 - Order:
    - Added the new structure cac:DeliveryLocation within the structure cac:Delivery at the order line level; 
 - Despatch Advice:
    - Added the new structure cac:AdditionalItemProperty within the structure cac:ItemInstance.

**Changes to code lists and validation artifacts**

 - Order, Order Response, Order Agreement, Despatch Advice:
    - Updated the code lists Electronic Address Scheme (EAS), ISO 6523 ICD list, ISO 4217 Currency codes;
    - Added the rules PEPPOL-COMMON-R042 (Denmark), PEPPOL-COMMON-R052 (Denmark) and PEPPOL-COMMON-R053 (Denmark).
    - Removed the rule PEPPOL-COMMON-R048 (Italy).

**Changes to the specification (documentation), syntax and code lists and validation artifacts** - [Billing](https://peppol-docs.agid.gov.it/docs-next-release/my_index_fatt-ENG.jsp)

**Changes to the documentation"**

 - In paragraph 7.2.10, remove the following text: “The attachment functionality is not intended for of including a copy of the invoice in an image format (such as PDF). Attaching an invoice copy is not in compliance with this specification.”
 - In paragraph 11.3.10 revised the UBL example of reference to the main invoice. 


**Changes to syntax**

 - Textual revision of descriptions of the cac:BillingReference, cac:InvoiceDocumentReference, cac:AdditionalDocumentReference elements;

**Changes to code lists and validation artifacts**

 - Updated the codelists Electronic Address Scheme (EAS), ISO 6523 ICD list, ISO 4217 Currency codes, VATEX codelist.
 - Added the rules PEPPOL-COMMON-R052 (Denmark), PEPPOL-COMMON-R053 (Denmark) and DK-R-017 (Denmark); updated the text of the rule DK-R-010 (Denmark).  

**Schematron update EN 16931**

 - Update of schematron EN 16931.
 - Removed rule UBL-CR-631.
