---
layout: post
title: Activities for the migration of the Service Metadata Locator (SML)
lang: en
ref: SML-migration
excerpt_separator: <!--more-->
tags:
categories: news
permalink: /en/news/SML-migration/
---

It is hereby communicated that the migration of the Service Metadata Locator (SML), currently managed by the European Commission (DG DIGIT), to OpenPeppol is underway. The objective of the Association is to acquire full operational and contractual control over this critical infrastructure, while maintaining continuity and stability of the Peppol Network.
<!--more-->

The SML is a key component of the Peppol Dynamic Discovery architecture. It enables DNS lookup between a Participant Identifier and the corresponding Service Metadata Publisher (SMP), allowing Access Points to locate the metadata and technical endpoints required for document exchange.

Therefore, Service Providers are requested to update the configuration of their endpoints in both the production and test environments, as follows:

- **For AP providers**: update the DNS lookup endpoints towards the new Peppol SML.
- **For SMP providers**: update the registration API endpoints towards the new Peppol SML.
 
The migration plan defined by OpenPeppol requires that activities be completed by the following dates:

- **31st May 2026 – AP Provider**: deadline for updating the SML registration API endpoints


|            **Endpoints valid until May 31st**              |             **Endpoints valid from June 1st**            |
|:----------------------------------------------------------:|:--------------------------------------------------------:|
| **Test Management Interface** EC Environment (SMK)         | **Test Management Interface** Peppol Environment (T-SML) |
| Domain: https://acc.edelivery.tech.ec.europa.eu            | Domain: https://api.sml.test.tech.peppol.org             |
| Service name: edelivery-sml/                               | Service name: edelivery-sml/                             |
| URL:https://acc.edelivery.tech.ec.europa.eu/edelivery-sml/ | URL: https://api.sml.test.tech.peppol.org/edelivery-sml/ |
| **Production Lookup** EC Environment (SML)                 | **Production Lookup** Peppol Environment (SML)           |
| Domain: https://edelivery.tech.ec.europa.eu                | Domain: https://api.sml.prod.tech.peppol.org             |
| Service name: edelivery-sml/                               | Service name: edelivery-sml/                             |
| URL: https://edelivery.tech.ec.europa.eu/edelivery-sml/    | URL: https://api.sml.prod.tech.peppol.org/edelivery-sml/ |

---

- **31st August 2026 – AP Provider**: mandatory deadline for updating DNS lookup domains


|            **Endpoints valid until August 31st**           |            **Endpoint valid from September 1st**         |
|:----------------------------------------------------------:|:--------------------------------------------------------:|
|**Test Lookup** EC Environment (SMK)                        |**Test Lookup** Peppol Environment (T-SML)                |
|Domain: https://acc.edelivery.tech.ec.europa.eu             |Domain: https://participant.sml.test.tech.peppol.org      |
|**Production Lookup** EC Environment (SML)                  |**Production Lookup** Peppol Environment (SML)            |
|Domain: https://edelivery.tech.ec.europa.eu                 |Domain: https://participant.sml.prod.tech.peppol.org      |

---

For more information, consult the [dedicated OpenPeppol page](https://openpeppol.atlassian.net/wiki/spaces/PTPUB/pages/5059608580/SML+Insourcing) and the attached migration plan.

 
