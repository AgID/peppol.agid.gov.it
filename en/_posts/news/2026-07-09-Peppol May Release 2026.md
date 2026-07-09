---
layout: post
title: Peppol May Release 2026
lang: en
ref: Peppol May Release 2026
excerpt_separator: <!--more-->
tags:
categories: news
permalink: /en/news/Peppol May Release 2026/
---

We inform you that the updates related to the May Release 2026 of OpenPeppol have been published. The entire release notes are available at the following addresses:
- [Billing](https://peppol-docs.agid.gov.it/docs-next-release/docs/ENG/invoice/guide/release-notes-it/main.html)
- [Order only](https://peppol-docs.agid.gov.it/docs-next-release/docs/ENG/others/guides/release-notes-it/3-order-only/main.html)
- [Ordering](https://peppol-docs.agid.gov.it/docs-next-release/docs/ENG/others/guides/release-notes-it/28-ordering/main.html)
- [Order Agreement](https://peppol-docs.agid.gov.it/docs-next-release/docs/ENG/others/guides/release-notes-it/42-orderagreement/main.html)
- [Dispatch Advice](https://peppol-docs.agid.gov.it/docs-next-release/docs/ENG/others/guides/release-notes-it/30-despatchadvice/main.html)
These updates will be mandatory starting from **17th of August 2026**, nevertheless we advise implementing these changes in time and downloading the schematron for the validation of the updated documents.
<!--more-->
The current documentation, accessible until 16th of August 2026, is available at the following addresses:
 
- [ Billing](https://peppol-docs.agid.gov.it/docs/my_index_fatt-ENG.jsp)
- [Other processes (Order Only, Ordering, Order Agreement, Despatch Advice)](https://peppol-docs.agid.gov.it/docs/my_index-ENG.jsp)

The changes of the May Release 2026 are described below:

**Changes to the syntax, code lists and validation artifacts - [Other processes (Order Only, Ordering, Order Agreement, Despatch Advice)](https://peppol-docs.agid.gov.it/docs/my_index-ENG.jsp)**

Changes to the syntax

Order:
- Added the new structure cac:QuotationLineReference with the element cbc:LineID within the structure cac:OrderLine to indicate the reference to a specific line of the quotation document. 

Changes to code lists and validation artifacts 

Order Only, Ordering, Order Agreement, Despatch Advice:
-	Electronic Address Scheme (EAS)
    - Added: 0242,0245,0246,0248
    - Removed: 0037,0177,0193,0212,0213,0215,0147,0154,0170,0194,0203,0217
    - Modified: 0088,0096,0184,0190,0191,0192,0195,0196,0198,0204,9959
    
 -  ISO 6523 ICD list
    - Added: 0245,0246,0247,0248
    - Modified: 0096,0158,0241,0243

- ISO 4217 Currency codes
    - Removed: ANG, BGN, STD
    - Added: STN, XCG
    
- UNCL7161
    - Aggiunti: CAX, CAY, CAZ, DAC, DAF, DAG, DAH, DAI, DAJ, DAK, DAL, DAM, DAN, DAO, DAP, DAQ, PRV

- Changed rule PEPPOL-COMMON-R052 (Denmark) and PEPPOL-COMMON-R053 (Denmark) to be errors instead of warnings, as the rules are now mandatory for all profiles.

- New rule PEPPOL-COMMON-R054 (Netherlands), PEPPOL-COMMON-R055 (Netherlands), PEPPOL-COMMON-R056-1 (Netherlands), PEPPOL-COMMON-R056-2 (Netherlands), PEPPOL-COMMON-R057 (Netherlands) as warnings. Rules will become fatal in future release, but are warnings in this release to allow for transition period for implementers to update their systems and data.

Schematron update 
- Update of schematron

**Changes to the specification, code lists and validation artifacts – Billing – [Billing](https://peppol-docs.agid.gov.it/docs-next-release/my_index_fatt-ENG.jsp)**

Changes to the documentation
New optional profile added for a process where an invoice response is a required step in the collaboration. The profile (02) requires a separate SMP registration. The same profile identifier has been added to the Invoice Response BIS, which specification is available at the OpenPeppol[Other BIS](https://docs.peppol.eu/poacc/upgrade-3/upcoming/) site.

Changes to code lists and validation artifacts
- Electronic Address Scheme (EAS)
    -	Removed: 0037,0147,0154,0170,0177,0193,0194 ,0203 ,0212,0213,0215,0217
    -	Modified: 0088,0184,0190,0191,0192,0195,0196,0198,0199,0204,9959
	
- ISO 6523 ICD list
    - Added: 0246,0247,0248
    - Modified: 0096,0158,0208,0241,0243

- ISO 4217 Currency codes
    - Removed: ANG, BGN
    - Added: XCG
    
 -   Changed rule PEPPOL-COMMON-R052 (Denmark) and PEPPOL-COMMON-R053 (Denmark) to be fatal instead of warnings, as the rules are now mandatory for all profiles.
 -  New rule PEPPOL-COMMON-R054 (Netherlands), PEPPOL-COMMON-R055 (Netherlands), PEPPOL-COMMON-R056-1 (Netherlands), PEPPOL-COMMON-R056-2 (Netherlands), PEPPOL-COMMON-R057 (Netherlands) as warnings. Rules will become fatal in future release, but are warnings in this release to allow for transition period for implementers to update their systems and data.

Schematron update EN 16931
-	Update of schematron EN 1693
-	Removed rule BR-CO-25
-	Update rule PEPPOL-EN16931-R004
-	Added in rule PEPPOL-EN16931-R007 for France 2 new temporary profiles on UBL Invoice and Credit Note
