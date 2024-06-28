---
layout: post
title: Peppol May Release 2024
lang: en
ref: peppol-may-release-2024-en
excerpt_separator: <!--more-->
tags:
categories: news
permalink: /en/news/peppol-may-release-2024-en/
---
We inform you that the updates related to the May Release 2024 of OpenPeppol have been published, the entire release notes are available at the following addresses:

 - [Order only](https://peppol-docs.agid.gov.it/docs-next-release/docs/ITA/others/guides/release-notes-it/3-order-only/main.html);
 - [Ordering](https://peppol-docs.agid.gov.it/docs-next-release/docs/ITA/others/guides/release-notes-it/28-ordering/main.html);
 - [Order Agreement](https://peppol-docs.agid.gov.it/docs-next-release/docs/ITA/others/guides/release-notes-it/42-orderagreement/main.html);
 - [Despatch Advice](https://peppol-docs.agid.gov.it/docs-next-release/docs/ITA/others/guides/release-notes-it/30-despatchadvice/main.html);
 - [Billing](https://peppol-docs.agid.gov.it/docs-next-release/docs/ITA/invoice/guide/release-notes-it/main.html).

**These updates will be mandatory starting from 26th August 2024, nevertheless we advise to implement these changes in time and to download the schematron for the validation of the updated documents.**
<!--more-->
The current documentation, accessible until 25th August 2024, is available at the following addresses:
 - [Billing](https://peppol-docs.agid.gov.it/docs/my_index_fatt.jsp);
 - [Other processes (Order Only, Ordering, Order Agreement, Despatch Advice)](https://peppol-docs.agid.gov.it/docs/my_index.jsp).

The changes of the May Release 2024 are described below:
**Changes to the specification (documentation), syntax and code lists and validation artifacts – [Other processes (Order Only, Ordering, Order Agreement and Despatch Advice)](https://peppol-docs.agid.gov.it/docs-next-release/my_index.jsp)**

**Changes to code lists and validation artifacts**
 - Order, Order Response, Order Agreement, Despatch Advice – Modification in the test of rule PEPPOL-COMMON-R049 (Sweden);
 - Order Response:
    - Added new rule PEPPOL-T76-R007 regarding the check for the presence of at least one line in the case of an order response with response code 'CA' (Order accepted with modification), with severity level WARNING;
    - Added new rule PEPPOL-T76-R008 regarding the check for the absence of lines in the case of an order response with response code "AP" (Order accepted without modification), with severity level WARNING;
    - Added new rule PEPPOL-T76-R009 regarding the check for the absence of lines in the case of an order response with response code "RE" (Order rejected), with severity level WARNING;
    - Added new rule PEPPOL-T76-R010 regarding the check for the absence of lines in the case of an order response with response code 'AB' (order received and not yet processed), with severity level FATAL.

**Changes to the specification (documentation), syntax and code lists and validation artifacts - [Billing](https://peppol-docs.agid.gov.it/docs-next-release/my_index_fatt.jsp)**

**Changes to code lists and validation artifacts**
 - Added new rule SE-R-013 (Sweden);
 - Modification in the test of rules NL-R-007 (Netherlands) and PEPPOL-COMMON-R049 (Sweden);
 - Change in the code “SLL” with the code “SLE” (Sierra Leone) in the codelist ISO 4217 Currency codes;
 - Added code "98" (JP, Electronically Recorded Monetary Claims) in the codelist Payment means code (UNCL4461). Inserted correspondence with Payment Method code "MP01" (Cash) of FatturaPA; 
 - Added code “GMN” (Global model number) in the codelist Item type identification code (UNCL7143);
 - Added code “PRV” (Price variation) in the codelist codelist Charge reason code (UNCL7161);
 - Added codes "VATEX-FR-FRANCHISE” (Francia) and "VATEX-FR-CNWVAT” (Francia) in the VATEX codelist.

**EN 16931 schematrons updated**
 - Update of schematron EN 16931 to version 1.3.12.