---
layout: post
title: Peppol November Release 2022
lang: en
ref: peppol-november-release-en
excerpt_separator: <!--more-->
tags:
categories: news
permalink: /en/news/peppol-november-release-en/
---
We inform you that the updates relating to the November Release 2022 of OpenPeppol have been published. These updates contain several changes, whose complete release notes are available at the following addresses: 
 - [Order Only](https://peppol-docs.agid.gov.it/docs-next-release/docs/ENG/others/guides/release-notes-it/3-order-only/main.html);
 - [Ordering](https://peppol-docs.agid.gov.it/docs-next-release/docs/ENG/others/guides/release-notes-it/28-ordering/main.html);
 - [Order Agreement](https://peppol-docs.agid.gov.it/docs/docs/ENG/others/guides/release-notes-it/42-orderagreement/main.html);
 - [Despatch Advice](https://peppol-docs.agid.gov.it/docs/docs/ENG/others/guides/release-notes-it/30-despatchadvice/main.html);
 - [Billing](https://peppol-docs.agid.gov.it/docs/docs/ENG/invoice/guide/release-notes-it/main.html).

The original content released by OpenPeppol is available [here](https://peppol.org/post-award-november-release-publication/).
These updates will be mandatory from **06 February 2023**, nevertheless it is advisable to implement these changes in time and to download the schematron for the validation of the updated documents.
<!--more-->
The current documentation, accessible until 05 February 2023, is available at the following address:
- [Billing[](https://peppol-docs.agid.gov.it/docs/my_index_fatt-ENG.jsp);
- [Other processes](https://peppol-docs.agid.gov.it/docs/my_index-ENG.jsp) (Order Only, Ordering, Order Agreement, Despatch Advice).

The changes made are described below:

**Changes to the specification (documentation), syntax and code lists and validation artifacts – [Other processes](https://peppol-docs.agid.gov.it/docs-next-release/my_index-ENG.jsp) (Order Only, Ordering, Order Agreement and Despatch Advice)**

**Changes to specification (Documentation)**
 - BIS Order Only, BIS Ordering – The new types of Orders, 221 Budget Order and 226 Regulation Order, have been added;
 - BIS Order Only, BIS Ordering – The indication of the CUP at the header level has been changed;
 - BIS Ordering – Fixed the second order response example in section 7.1.1 of the documentation;
 - BIS Order Agreement – The indication the VAT number and Tax Code of the Supplier/Seller and Customer/Buyer has been changed;
 - BIS Order Only, BIS Ordering, BIS Order Agreement, BIS Despatch Advice – Updated examples to reflect syntax changes;
 - Removed the "Last updated" indication in the footer.

**Syntax changes**
- Order Only
    - Added cbc:StartTime – Start time and cbc:EndTime – End time as optional fields of the cac:RequestedDeliveryPeriod structure;
    - Added cac:ProjectReference – Project reference as an optional header-level structure.
- Ordering
    - Added cbc:StartTime – Start time and cbc:EndTime – End time as optional fields of the cac:PromisedDeliveryPeriod structure.
- Order Agreement
    - Added cbc:DocumentTypeCode as an optional field of the cac:ItemSpecificationDocumentReference structure at row level;
    - Added cbc:CompanyID as an optional field of the cac:PartyLegalEntity structure for both the Supplier (cac:SellerSupplierParty) and the Customer (cac:BuyerCustomerParty).
- Despatch Advice
    - Added cbc:SalesOrderLineID - Sales order line identifier as an optional field on the DA line level;
    - Added cac:CommodityClassification – Product classification as optional structure at line level of DA;
    - Added cac:AdditionalDocumentReference – Additional documents as an optional header-level structure. Added cac:DocumentsReference – Additional document reference as a row-level structure;
    - Added cac:ShipmentStage – Shipment status information as an optional structure at the header level. The related field cbc:TransportModeCode - Mode of transport is optional and can be filled in using the UN/ECE Recommendation 19 codelist;
    - Implemented the request of the Italian Peppol Authority to insert the structure cac:PartyIdentification of the Carrier (cac:CarrierParty), which is now no longer an extension of the Italian syntax;
    - Implemented the request of the Italian Peppol Authority to make mandatory the field cbc:DeliveredQuantity of the cac:DespatchLine structure.

**Changes to code lists and validation artifacts**
- Removed the following validation rules related to the tax category:
    - Order Only - Removed validation rules related to tax category: PEPPOL-T01-B20301 rule applied to the field cac:AllowanceCharge/cac:TaxCategory/cbc:ID and PEPPOL-T01-B28701 rule applied to the field cac:Item/cac:ClassifiedTaxCategory/cbc:ID;
    - Ordering – Removed the tax category validation rule: PEPPOL-T76-B07701 rule applied to the field cac:SellerSubstitutedLineItem/cac:Item/cac:ClassifiedTaxCategory/cbc:ID;
    - Order Agreement – Removed tax category validation rules: PEPPOL-T110-B13301 rule applied to the field cac:AllowanceCharge/cac:TaxCategory/cbc:ID, PEPPOL-T110-B14601 rule applied to the field cac:TaxTotal/cac:TaxSubtotal/cac:TaxCategory/cbc:ID and PEPPOL-T110-B22301 rule applied to the field cac:Item/cac:ClassifiedTaxCategory/cbc:ID.
- The Order Type Code (UNCL1001 subset) codelist has been integrated with two new order types: 221 (blanket order) and 226 (call off order);
- Changed the severity of the PEPPOL-COMMON-R049 (ICD 0007) rule for the validation of the format of the "Swedish organization number" from "warning" to "fatal", as announced in the May Release 2022;
- Corrected the PEPPOL-COMMON-R050 rule for the validation of the "Australian Business Number (ABN)";
- Added US code 9959 to EAS encoding. Removed the Italian codes 9906 and 9907 from the same coding. Adjusted the validation artifacts;
- Added codes 0217 (Netherlands), 0218, 0219 and 0220 (Latvia) to the ICD encoding and adjusted the validation artifacts.

**Changes to the specification (documentation), syntax and code lists and validation artifacts – [Billing](https://peppol-docs.agid.gov.it/docs-next-release/my_index_fatt-ENG.jsp)**
**Changes to specification (Documentation)**
- Removed the "Last updated" indication in the footer;

**Changes to code lists and validation artifacts**
- Changed the severity of the PEPPOL-COMMON-R049 (ICD 0007) rule for the validation of the format of the "Swedish organization number" from "warning" to "fatal", as announced in the May Release 2022;
- Corrected the PEPPOL-COMMON-R050 rule for the validation of the "Australian Business Number (ABN)";
- Added US code 9959 to EAS encoding. Removed the Italian codes 9906 and 9907 from the same coding. Adjusted the validation artifacts;
- Added codes 0217 (Netherlands), 0218, 0219 and 0220 (Latvia) to the ICD coding and adjusted the validation artifacts;
- Corrected specific business rules deriving from updates to EN16931 and related schematrons (for more information, see the link).

**Country Specific Rule Changes**
- Updated rules GR-S-008-1, GR-R-008-2 and GR-R-008-3, requiring the string ##INVOICE\|URL## instead of ##INVOICE-URL## (POAC-518);
- Eliminated the rule DK-R-015;
- Correction of rules text DK-R-004 PEPPOL UBL & CII;
- Correction of DK-R-003 PEPPOL CII rule text.
