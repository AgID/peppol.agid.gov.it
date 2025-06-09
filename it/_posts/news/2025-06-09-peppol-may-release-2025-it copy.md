---
layout: post
title: Peppol May Release 2025
lang: it
ref: peppol-may-release-2025-it
excerpt_separator: <!--more-->
tags:
categories: news
permalink: /it/news/peppol-may-release-2025-it/
---
Si comunica che sono stati pubblicati gli aggiornamenti relativi alla May Release 2025 di OpenPeppol e ad ulteriori modifiche relative al contesto italiano, le cui release notes complete sono disponibili agli indirizzi:

 - [Ordinazione Semplice](https://peppol-docs.agid.gov.it/docs-next-release/docs/ITA/others/guides/release-notes-it/3-order-only/main.html);
 - [Ordinazione Completa](https://peppol-docs.agid.gov.it/docs-next-release/docs/ITA/others/guides/release-notes-it/28-ordering/main.html);
 - [Documento di Trasporto](https://peppol-docs.agid.gov.it/docs-next-release/docs/ITA/others/guides/release-notes-it/30-despatchadvice/main.html);
 - [Fatturazione](https://peppol-docs.agid.gov.it/docs-next-release/docs/ITA/invoice/guide/release-notes-it/main.html).

**Tali aggiornamenti avranno efficacia in via obbligatoria dal giorno 25 agosto 2025, ciononostante si consiglia di recepire per tempo tali modifiche e di scaricare gli schematron per la validazione dei documenti aggiornati.**
<!--more-->

Le specifiche tecniche che rimarranno in vigore fino al giorno 24 agosto 2025 sono disponibili agli indirizzi:

 - [Fatturazione](https://peppol-docs.agid.gov.it/docs/my_index_fatt.jsp);
 - [Altri processi (Ordinazione semplice, Ordinazione completa, Ordinazione pre-concordata, Documento di trasporto)](https://peppol-docs.agid.gov.it/docs/my_index.jsp).

Di seguito si riportano i cambiamenti effettuati con la May Release 2025:

**Cambiamenti alla documentazione, alla sintassi e alle code lists e artefatti di validazione - [Altri processi (ordine, ordine con risposta, ordine pre-concordato e documento di trasporto)](https://peppol-docs.agid.gov.it/docs-next-release/my_index.jsp)**

**Cambiamenti alla documentazione**
 - Ordine:
   - Modificato paragrafo “7.4.2. Dettaglio sui Dispositivi Medici e loro identificazione - Codice UDI”;
   - Modificato paragrafo “7.16.1. Luogo di consegna (DeliveryLocation)”;
 - Documento di Trasporto:
   - Aggiunto nuovo paragrafo “4.2.1 Processo di reso della merce” che descrive il flusso nel caso di documento di trasporto di reso;
   - Aggiunto nuovo paragrafo “5.4 Tipologia di consegna” che descrive i diversi processi di consegna (acquisto, conto deposito, reso);
   -  Modificato il paragrafo “8.1.2. Dettaglio sui Dispositivi Medici e loro identificazione - Codice UDI” in virtù dell’aggiunta del nuovo campo cac:ItemInstance/cbc:ProductTraceID per indicare il codice UDI dei dispositivi medici.

**Cambiamenti alla sintassi**
 - Ordine:
   - Aggiunta nuova struttura cac:Despatch contenente due campi cbc:RequestedDespatchDate e cbc:RequestedDespatchTime;
   - Aggiornato lo schematron alla versione 3.6;
 - Documento di Trasporto:
   - Aggiunto nuovo campo cac:ItemInstance/cbc:ProductTraceID e relativo @schemeID per identificare il codice UDI;
   - Aggiunto nuovo campo cbc:DespatchAdviceTypeCode per identificare il tipo di documento di trasporto, ossia il fatto che sia una semplice consegna, un'integrazione in conto deposito o un reso.

**Cambiamenti alle code lists e artefatti di validazione**
 - Ordine, Risposta all’Ordine – Aggiornate le codelist Electronic Address Scheme (EAS), ISO 6523 ICD list, ISO 4217 Currency codes, Item type identification code (UNCL7143);
 - Risposta all’Ordine – Modificato il livello di severità da WARNING a FATAL delle regole PEPPOL-T76-R007, PEPPOL-T76-R008 e PEPPOL-T76-R009
 - Documento di Trasporto – Aggiornate le codelist Electronic Address Scheme (EAS), ISO 6523 ICD list, Item type identification code (UNCL7143), Measured attribute code for despatch advice (UNCL6313 Subset) e aggiunte nuove codelist ProductTraceIDschemeID e Despatch advice type code (UNCL1001 subset).

 **Cambiamenti alla documentazione, alla sintassi e alle code lists e artefatti di validazione – [Fatturazione](https://peppol-docs.agid.gov.it/docs-next-release/my_index_fatt.jsp)**

**Cambiamenti alla documentazione**
 - Piccole modifiche editoriali.

**Cambiamenti alla sintassi**
 - Rimosso il riferimento alla regola BR-CO-25 nel campo cbc:PaymentDueDate nel tracciato della Nota di Credito.

**Cambiamenti alle code lists e artefatti di validazione**
 - Modificate le regole PEPPOL-EN16931-R051, PEPPOL-COMMON-R042, DK-R-003 (Danimarca), DK-R-004 (Danimarca) e DK-R-008 (Danimarca);
 - Piccole modifiche alla codelist Electronic Address Scheme (EAS), ISO 6523 ICD list, ISO 4217 Currency codes, Invoiced object identifier scheme (UNCL 1153), Payment means code (UNCL4461), Item type identification code (UNCL7143), VATEX code list, Invoice type code (UNCL1001 subset).

**Aggiornamento schematron EN 16931**
 - Aggiornamento dello schematron EN 16931.



