---
layout: post
title: Peppol May Release 2023 EN
lang: en
ref: peppol-may-release-2023-en
excerpt_separator: <!--more-->
tags:
categories: news
permalink: /en/news/peppol-may-release-2023-en/
---
We inform you that the updates related to the May Release 2023 of OpenPeppol have been published. These updates include several changes, whose entire release notes are available at the following addresses:

 - [Order only](https://peppol-docs.agid.gov.it/docs-next-release/docs/ENG/others/guides/release-notes-it/3-order-only/main.html);
 - [Ordering](https://peppol-docs.agid.gov.it/docs-next-release/docs/ENG/others/guides/release-notes-it/28-ordering/main.html);
 - [Order Agreement](https://peppol-docs.agid.gov.it/docs-next-release/docs/ENG/others/guides/release-notes-it/42-orderagreement/main.html);
 - [Despatch Advice](https://peppol-docs.agid.gov.it/docs-next-release/docs/ENG/others/guides/release-notes-it/30-despatchadvice/main.html);
 - [Billing](https://peppol-docs.agid.gov.it/docs-next-release/docs/ENG/invoice/guide/release-notes-it/main.html).

The original content released by OpenPeppol is available [here](https://peppol.org/may-2023-release-of-the-peppol-post-award-artefact/).

**These updates will be mandatory starting from 7th August 2023, nevertheless we advise to implement these changes in time and to download the schematron for the validation of the updated documents.**

The current documentation, accessible until 6th August 2023, is available at the following addresses:
 - [Billing](https://peppol-docs.agid.gov.it/docs/my_index_fatt-ENG.jsp);
 - [Other processes (Order Only, Ordering, Order Agreement, Despatch Advice)](https://peppol-docs.agid.gov.it/docs/my_index-ENG.jsp).

The changes are described below:
Changes to the specification (documentation), syntax and code lists and validation artifacts – [Other processes (Order Only, Ordering, Order Agreement and Despatch Advice)](https://peppol-docs.agid.gov.it/docs-next-release/my_index.jsp)

**Changes to specification (Documentation)**
 - BIS Order Only, BIS Ordering – Section 6.4. Product identification has been integrated with the indication of the Manufacturers item identification;
 - BIS Order Only, BIS Ordering – Section 6.14. Other references has been integrated with the indication of the Catalogue reference at header level;
 - BIS Order Only, BIS Ordering – Section 6.16. Delivery has been integrated with a description of the method for indicating the priority required by the Buyer for delivery;
 - BIS Order Only, BIS Ordering – Examples have been updated according to syntax changes.

**Syntax changes**
- Order Only
    - Added cac:CatalogueReference – Catalogue Reference as an optional header-level structure;
    - Added cbc:ShippingPriorityLevelCode - Requested shipping priority as an optional field of the cac:Shipment structure;
    - Added cbc:StartTime – Start time and cbc:EndTime – End time as optional fields of the cac:RequestedDeliveryPeriod line-level structure;
    - Added cac:ManufacturersItemIdentification – Producer item identification as an optional line-level structure.
- Ordering
    - Added cbc:StartTime – Start time and cbc:EndTime – End time as optional fields of the cac:PromisedDeliveryPeriod line-level structure.
