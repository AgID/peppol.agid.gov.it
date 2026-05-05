---
layout: post
title: Attività per la migrazione del Service Metadata Locator (SML) di OpenPeppol
lang: it
ref: migrazione-SML
excerpt_separator: <!--more-->
tags:
categories: news
permalink: /it/news/migrazione-SML/
---

Si comunica che è in corso l’attività di migrazione del Service Metadata Locator (SML), attualmente gestito dalla Commissione Europea (DG DIGIT), ad OpenPeppol. L'obiettivo dell’Associazione è di acquisire il pieno controllo operativo e contrattuale di questa infrastruttura critica, mantenendo continuità e stabilità della rete Peppol.
<!--more-->

L'SML è un componente fondamentale dell'architettura di Dynamic Discovery di Peppol che consente la ricerca DNS tra un Partecipant Identifier e il relativo Service Metadata Publisher (SMP), permettendo agli Access Point di localizzare i metadati e gli endpoint tecnici necessari per lo scambio dei documenti.

Pertanto, si chiede ai Service Provider di aggiornare i puntamenti sia in ambiente di produzione che in ambiente di test, come segue:

**Per gli AP provider**: aggiornare gli endpoint DNS per le ricerche di lookup verso il nuovo SML Peppol.
**Per i SMP provider**: aggiornare gli endpoint API di registrazione verso il nuovo SML Peppol
 
Il piano di migrazione previsto da OpenPeppol prevede che le attività siano completate entro le seguenti date:

 - **31 maggio 2026 – SMP Provider**: scadenza per l'aggiornamento degli endpoint API di registrazione SML
 
|**Endpoint utilizzabili fino a 31 maggio**|**Endpoint utilizzabili dal 1° giugno**|
|------------------------------------------|---------------------------------------|
|**Test Management Interface** EC Environment (SMK)|**Test Management Interface** Peppol Environment (T-SML)|
|Domain: https://acc.edelivery.tech.ec.europa.eu|Domain: https://api.sml.test.tech.peppol.org|
|Service name: edelivery-sml/|Service name: edelivery-sml/|
|URL:https://acc.edelivery.tech.ec.europa.eu/edelivery-sml/|URL: https://api.sml.test.tech.peppol.org/edelivery-sml/|
|URL:https://acc.edelivery.tech.ec.europa.eu/edelivery-sml/|URL: https://api.sml.test.tech.peppol.org/edelivery-sml/|
|**Production Lookup** EC Environment (SML)|**Production Lookup** Peppol Environment (SML)|
|Domain: https://edelivery.tech.ec.europa.eu|Domain: https://api.sml.prod.tech.peppol.org|

 - **31 agosto 2026 – AP Provider**: scadenza per l'aggiornamento degli endpoint DNS per le ricerche di lookup
 
|**Endpoint utilizzabili fino a 31 agosto**|**Endpoint utilizzabili dal 1° settembre**|
|------------------------------------------|------------------------------------------|
|**Test Lookup** EC Environment (SMK)|**Test Lookup** Peppol Environment (T-SML)|
|Domain: https://acc.edelivery.tech.ec.europa.eu|Domain: https://participant.sml.test.tech.peppol.org|
|**Production Lookup** EC Environment (SML)|**Production Lookup** Peppol Environment (SML)|
|Domain: https://edelivery.tech.ec.europa.eu|Domain: https://participant.sml.prod.tech.peppol.org|


Per ulteriori informazioni si rimanda alla pagina dedicata [SML Insourcing](https://openpeppol.atlassian.net/wiki/spaces/PTPUB/pages/5059608580/SML+Insourcing) di OpenPeppol e al piano di migrazione allegato.



