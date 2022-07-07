---
layout: post
title: Peppol May Release 2022
lang: en
ref: peppol-may-release-en
excerpt_separator: <!--more-->
tags:
categories: news
permalink: /en/news/peppol-may-release-en/
---
We inform you that the updates relating to the May Release 2022 of OpenPeppol are published, containing a series of changes whose complete release notes are available at the addresses: 

 - [Simple Ordering](https://peppol-docs.agid.gov.it/docs/docs/ITA/others/guides/release-notes-it/3-order-only/main.html)
 - [Complete Ordering](https://peppol-docs.agid.gov.it/docs/docs/ITA/others/guides/release-notes-it/28-ordering/main.html)
 - [Pre-agreed ordering](https://peppol-docs.agid.gov.it/docs/docs/ITA/others/guides/release-notes-it/42-orderagreement/main.html)
 - [Transport document](https://peppol-docs.agid.gov.it/docs/docs/ITA/others/guides/release-notes-it/30-despatchadvice/main.html)
 - [Billing](https://peppol-docs.agid.gov.it/docs/docs/ITA/invoice/guide/release-notes-it/main.html)
<!--more-->


The original content released by OpenPeppol related to billing is available [here](https://docs.peppol.eu/poacc/billing/3.0/release-notes/), while the original content released by OpenPeppol related to the other processes is available [here](https://docs.peppol.eu/poacc/upgrade-3/release-notes/).
These updates will be effective on a mandatory basis from **May 30, 2022**.

The changes made are shown below:
 - **Changes to specification (Documentation)**
     - Fixed an error that caused the appearance of errors when loading / using schematron files in some XLS file converters / tools;
     - The severity of the PEPPOL-COMMON-R043 (ICD 0208) rule concerning the validation of the format of the “Belgian organization numbers”, as announced in the Fall release 2021, has been changed from “warning” to “fatal”;
     - Added a rule with severity "warning" for the validation of the format of the "Swedish organization numbers" (ICD / EAS 0007). The severity will change to "fatal" with the Fall release 2022;
     - Correction of the PEPPOL-EN16931-R080 rule which must be activated only for the credit note and not for the invoice;
     - Codes 0214, 0215 and 0216 have been added to the ICD encoding and the validation artefacts have been adapted;
     - Codes 0147, 0170, 0188, 0215 and 0216 have been added to the EAS coding and the validation artefacts have been adapted;
     - Correction of the repetition of the TSP code present in the UNCL7143 code.
     - Added additional invoice type codes 71, 102, 218, 219, 331, 382, ​​553, 817, 870, 875, 876 and 877, in line with the update made by
     TC434 / EC-DIGITAL. The indication in the Documentation section has been added that these additional invoice type codes can be treated as synonyms of code 380 and therefore do not require a modification in processing;
     - The invoice type code 0388 has been added. The indication that this invoice type code can be treated as a synonym for code 380 has been added to the Documentation section and therefore does not require a change in processing.

- **Changes to code lists and validation artifacts - Other processes (order, order with reply, pre-agreed order and packing slip)**
     - Added a rule with severity "warning" for the validation of the format of the "Swedish organization numbers" (ICD / EAS 0007). The severity will change to "fatal" with the Fall release 2022;
     - Fixed an error that caused the appearance of errors when loading / using schematron files in some XLS file converters / tools;
     - The severity of the PEPPOL-COMMON-R043 (ICD 0208) rule concerning the validation of the format of the “Belgian organization numbers”, as announced in the Fall release 2021, has been changed from “warning” to “fatal”;
     - Corrected the PEPPOL-T77-R001 rule that was erroneously ignored in cases of omission of the indication of the period of validity;
     - Added a rule with severity "warning" for the validation of the format of the "Australian ABN" (ICD / EAS 0151). The severity will change to "fatal" with the Fall release 2022;
     - Codes 0214, 0215 and 0216 have been added to the ICD encoding and the validation artefacts have been adapted;
     - Codes 0147, 0170, 0188, 0215 and 0216 have been added to the EAS coding and the validation artefacts have been adapted;
     - Removal of the repetition of the TSP code from the UNCL7143 code.