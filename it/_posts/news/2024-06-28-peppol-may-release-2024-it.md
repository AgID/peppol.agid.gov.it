---
layout: post
title: Peppol May Release 2024
lang: it
ref: peppol-may-release-2024-it
excerpt_separator: <!--more-->
tags:
categories: news
permalink: /it/news/peppol-may-release-2024-it/
---
Si comunica che sono stati pubblicati gli aggiornamenti relativi alla May Release 2024 di OpenPeppol, contenenti una serie di modifiche le cui release notes complete sono disponibili agli indirizzi:

 - [Ordinazione Semplice](https://peppol-docs.agid.gov.it/docs-next-release/docs/ITA/others/guides/release-notes-it/3-order-only/main.html);
 - [Ordinazione Completa](https://peppol-docs.agid.gov.it/docs-next-release/docs/ITA/others/guides/release-notes-it/28-ordering/main.html);
 - [Ordinazione Pre-concordata](https://peppol-docs.agid.gov.it/docs-next-release/docs/ITA/others/guides/release-notes-it/42-orderagreement/main.html);
 - [Documento di Trasporto](https://peppol-docs.agid.gov.it/docs-next-release/docs/ITA/others/guides/release-notes-it/30-despatchadvice/main.html);
 - [Fatturazione](https://peppol-docs.agid.gov.it/docs-next-release/docs/ITA/invoice/guide/release-notes-it/main.html).

**Tali aggiornamenti avranno efficacia in via obbligatoria dal giorno 26 agosto 2024, ciononostante si consiglia di recepire per tempo tali modifiche e di scaricare gli schematron per la validazione dei documenti aggiornati.**
<!--more-->
Le specifiche tecniche che rimarranno in vigore fino al giorno 25 agosto 2024 sono disponibili agli indirizzi:

 - [Fatturazione](https://peppol-docs.agid.gov.it/docs/my_index_fatt.jsp);
 - [Altri processi (Ordinazione semplice, Ordinazione completa, Ordinazione pre-concordata, Documento di trasporto)](https://peppol-docs.agid.gov.it/docs/my_index.jsp).

Di seguito si riportano i cambiamenti effettuati con la May Release 2024:

**Cambiamenti alla documentazione, alla sintassi e alle code lists e artefatti di validazione - [Altri profili (ordine, ordine con risposta, ordine pre-concordato e documento di trasporto)](https://peppol-docs.agid.gov.it/docs-next-release/my_index.jsp)**

**Cambiamenti alle code lists e artefatti di validazione**
 - Ordine, Risposta all’Ordine, Ordine Pre-Concordato, Documento di Trasporto – Aggiornato il controllo della regola PEPPOL-COMMON-R049 (Svezia);
 - Risposta all’Ordine: 
    - Aggiunta nuova regola PEPPOL-T76-R007 relativa al controllo della presenza di almeno una riga in caso di risposta all’ordine con codice di risposta “CA” (Ordine accettato con modifica), con livello di severità WARNING;
    - Aggiunta nuova regola PEPPOL-T76-R008 relativa al controllo dell’assenza di righe in caso di risposta all’ordine con codice di risposta “AP” (Ordine accettato senza modifica), con livello di severità WARNING;
    - Aggiunta nuova regola PEPPOL-T76-R009 relativa al controllo dell’assenza di righe in caso di risposta all’ordine con codice di risposta “RE” (Ordine respinto), con livello di severità WARNING;
    - Aggiunta nuova regola PEPPOL-T76-R010 relativa al controllo dell’assenza di righe in caso di risposta all’ordine con codice di risposta “AB” (Ordine ricevuto e non ancora processato), con livello di severità FATAL.

 **Cambiamenti alla documentazione, alla sintassi e alle code lists e artefatti di validazione – [Fatturazione](https://peppol-docs.agid.gov.it/docs-next-release/my_index_fatt.jsp)**

**Cambiamenti alle code lists e artefatti di validazione**
 - Introduzione della nuova regola SE-R-013 (Svezia);
 - Aggiornamento dei controlli delle regole NL-R-007 (Paesi Bassi) e PEPPOL-COMMON-R049 (Svezia);
 - Aggiunta del codice “98” (JP, Electronically Recorded Monetary Claims) nella codelist Payment means code (UNCL4461). Inserita corrispondenza con codice Modalità di Pagamento “MP01” (Contanti) di FatturaPA;
 - Aggiunta del codice “GMN” (Global model number) nella codelist Item type identification code (UNCL7143); 
 - Aggiunta del codice "PRV” (Price variation) nella codelist Charge reason code (UNCL7161);
 - Aggiunta dei codici "VATEX-FR-FRANCHISE” (Francia) e "VATEX-FR-CNWVAT” (Francia) nella VATEX codelist.

**Aggiornamento schematron EN 16931**
 - Aggiornamento dello schematron EN 16931 alla versione 1.3.12.;
