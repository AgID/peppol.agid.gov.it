---
layout: post
title: Peppol November Release 2025 e altre modifiche italiane
lang: it
ref: peppol-november-release-2025-it
excerpt_separator: <!--more-->
tags:
categories: news
permalink: /it/news/peppol-november-release-2025-it/
---
Si comunica che sono stati pubblicati gli aggiornamenti relativi alla November Release 2025 di OpenPeppol, le cui release notes complete sono disponibili agli indirizzi:

 - [Fatturazione](https://peppol-docs.agid.gov.it/docs-next-release/docs/ITA/invoice/guide/release-notes-it/main.html).
 - [Ordinazione Semplice](https://peppol-docs.agid.gov.it/docs-next-release/docs/ITA/others/guides/release-notes-it/3-order-only/main.html);
 - [Ordinazione Completa](https://peppol-docs.agid.gov.it/docs-next-release/docs/ITA/others/guides/release-notes-it/28-ordering/main.html);
 - [Ordinazione Pre-concordata](https://peppol-docs.agid.gov.it/docs-next-release/docs/ITA/others/guides/release-notes-it/42-orderagreement/main.html);
 - [Documento di Trasporto](https://peppol-docs.agid.gov.it/docs-next-release/docs/ITA/others/guides/release-notes-it/30-despatchadvice/main.html);


**Tali aggiornamenti avranno efficacia in via obbligatoria dal giorno 23 febbraio 2026, ciononostante si consiglia di recepire per tempo tali modifiche e di scaricare gli schematron per la validazione dei documenti aggiornati.**
<!--more-->

Le specifiche tecniche che rimarranno in vigore fino al giorno 22 febbraio 2026 sono disponibili agli indirizzi:

 - [Fatturazione](https://peppol-docs.agid.gov.it/docs/my_index_fatt.jsp);
 - [Altri processi (Ordinazione semplice, Ordinazione completa, Ordinazione pre-concordata, Documento di trasporto)](https://peppol-docs.agid.gov.it/docs/my_index.jsp).

Di seguito si riportano i cambiamenti effettuati con la November Release 2025:

**Cambiamenti alla sintassi e alle code lists e artefatti di validazione –[Altri processi (ordine, ordine con risposta, ordine pre-concordato e documento di trasporto)](https://peppol-docs.agid.gov.it/docs-next-release/my_index.jsp)**

**Cambiamenti alla sintassi**
 - Ordine:
    - Aggiunta la nuova struttura cac:DeliveryLocation all’interno della struttura  cac:Delivery a livello della riga dell’ordine.
 - Documento di Trasporto:
    - Aggiunta la nuova struttura cac:AdditionalItemProperty all’interno della struttura cac:ItemInstance.

**Cambiamenti alle code lists e artefatti di validazione**
 - Ordine, Risposta all’Ordine, Ordine Pre-Concordato, Documento di Trasporto:
    - Aggiornate le codelist Electronic Address Scheme (EAS), ISO 6523 ICD list, ISO 4217 Currency codes.
    - Introduzione delle regole PEPPOL-COMMON-R042 (Danimarca), PEPPOL-COMMON-R052 (Danimarca) e PEPPOL-COMMON-R053 (Danimarca).
    - Rimozione della regola PEPPOL-COMMON-R048 (Italia).

**Cambiamenti alla documentazione, alla sintassi e alle code lists e artefatti di validazione – [Fatturazione](https://peppol-docs.agid.gov.it/docs-next-release/my_index_fatt.jsp)**

**Cambiamenti alla documentazione**
 - Nel paragrafo 7.2.10 rimozione del seguente testo: "La funzionalità dell’allegato non è inteso per includere una copia della fattura in un formato immagine (come un PDF). Allegare una copia della fattura non è compatibile con questa specifica."
 - Nel paragrafo 11.3.10 revisione dell’esempio UBL per il riferimento alla fattura principale. 

**Cambiamenti alla sintassi**
 - Revisione testuale della descrizione degli elementi cac:BillingReference, cac:InvoiceDocumentReference, cac:AdditionalDocumentReference.

**Cambiamenti alle code lists e artefatti di validazione**
 - Aggiornate le codelist Electronic Address Scheme (EAS), ISO 6523 ICD list, ISO 4217 Currency codes, VATEX code list.
 - Introduzione delle regole PEPPOL-COMMON-R052 (Danimarca), PEPPOL-COMMON-R053 (Danimarca) e DK-R-017 (Danimarca); aggiornamento del testo della regola DK-R-010 (Danimarca). 

 **Aggiornamento schematron EN 16931**
 - Aggiornamento schematron EN 16931;
 - Rimozione regola UBL-CR-631.


