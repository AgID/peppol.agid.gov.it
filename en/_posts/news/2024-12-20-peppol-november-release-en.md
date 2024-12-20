---
layout: post
title: Peppol November Release 2024 e other Italian modifications
lang: en
ref: peppol-november-release-2024-en
excerpt_separator: <!--more-->
tags:
categories: news
permalink: /en/news/peppol-november-release-2024-en/
---
We inform you that the updates related to the November Release 2024 of OpenPeppol and other modifications related to the Italian context have been published, the entire release notes are available at the following addresses:

 - [Order only](https://peppol-docs.agid.gov.it/docs-next-release/docs/ITA/others/guides/release-notes-it/3-order-only/main.html); 
 - [Ordering](https://peppol-docs.agid.gov.it/docs-next-release/docs/ITA/others/guides/release-notes-it/28-ordering/main.html); 
 - [Order Agreement](https://peppol-docs.agid.gov.it/docs-next-release/docs/ITA/others/guides/release-notes-it/42-orderagreement/main.html); 
 - [Despatch Advice](https://peppol-docs.agid.gov.it/docs-next-release/docs/ITA/others/guides/release-notes-it/30-despatchadvice/main.html); 
 - [Billing](https://peppol-docs.agid.gov.it/docs-next-release/docs/ITA/invoice/guide/release-notes-it/main.html). 

**These updates will be mandatory starting from 17th February 2025, nevertheless we advise to implement these changes in time and to download the schematron for the validation of the updated documents.**
<!--more-->

The current documentation, accessible until 16th February 2025, is available at the following addresses:
 - [Billing](https://peppol-docs.agid.gov.it/docs/my_index_fatt.jsp); 
 - [Other Processes (Order only, Ordering, Order Agreement, Despatch Advice)](https://peppol-docs.agid.gov.it/docs/my_index.jsp).

The changes of the November Release 2024 are described below:

**Changes to the specification (documentation), syntax and code lists and validation artifacts – [Other Processes (order only, ordering, order agreement and despatch advice)](https://peppol-docs.agid.gov.it/docs-next-release/my_index.jsp)**

**Syntax changes**

 - Order, Order Agreement, Despatch Advice – Added new optional element cbc:ID in the cac:AdditionalItemProperty structure;
 - Despatch Advice:
    - Added new optional attribute @schemeID to the element cbc:ID in the cac:TransportHandlingUnit structure;
    - Added new optional structure cac:DeliveryParty.

**Changes to code lists and validation artifacts**

 - Order, Order Response, Order Agreement, Despatch Advice – Modification of the Item type identification code (UNCL7143), Dangerous goods regulations code (UNCL8273) Recommendation 20, including Recommendation 21 codes - prefixed with X (UN/ECE) codelists;
 - Despatch Advice – Added new codelist Transport Handling Unit ID scheme (openPEPPOL) containg only the code [SSCC] *Serial Shipping Container Code*.

**Updates related to "BIS compliance"**

 - Order, Order Response, Order Agreement, Despatch Advice – Added new compliance rules on the use of sender/receiver identifiers when enveloping a BIS3 message in Peppol Business Message Envelope (SBDH).

**Changes to the specification (documentation), syntax and code lists and validation artifacts – [Billing](https://peppol-docs.agid.gov.it/docs-next-release/my_index_fatt.jsp)**


**Changes to code lists and validation artifacts**

 - Formal revisions of specific Rules for italian CIUS (CIUS ID BR-IT-261; BR-IT-370; BR-IT-DC-480) and Rules for italian extensions (CIUS ID BR-IT-DE-013; BR-IT-DE-024; BR-IT-DE-026) to align with the technical rules of Agenzia delle Entrate related to the management of European invoices - version 2.5;
 - Added new set of rules from DE-R-001 to DE-R-030 (Germany);
 - •	Modification of the rules PEPPOL-EN16931-R002, NL-R-008 (Netherlands), SE-R-003 (Sweden), SE-R-004 (Sweden) and SE-R-013 (Sweden).

**EN 16931 schematrons updated**

 - Update of schematron EN 16931 to version 1.3.13.

**Updates related to "BIS compliance"**

 - Added new compliance rules on the use of sender/receiver identifiers when enveloping a BIS3 message in Peppol Business Message Envelope (SBDH).
