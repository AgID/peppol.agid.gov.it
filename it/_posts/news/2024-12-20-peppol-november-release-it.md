---
layout: post
title: Peppol November Release 2024 e altre modifiche italiane
lang: it
ref: peppol-november-release-2024-it
excerpt_separator: <!--more-->
tags:
categories: news
permalink: /it/news/peppol-november-release-2024-it/
---
Si comunica che sono stati pubblicati gli aggiornamenti relativi alla November Release 2024 di OpenPeppol e ad ulteriori modifiche relative al contesto italiano, le cui release notes complete sono disponibili agli indirizzi:

 - [Ordinazione Semplice](https://peppol-docs.agid.gov.it/docs-next-release/docs/ITA/others/guides/release-notes-it/3-order-only/main.html);
 - [Ordinazione Completa](https://peppol-docs.agid.gov.it/docs-next-release/docs/ITA/others/guides/release-notes-it/28-ordering/main.html);
 - [Ordinazione Pre-concordata](https://peppol-docs.agid.gov.it/docs-next-release/docs/ITA/others/guides/release-notes-it/42-orderagreement/main.html);
 - [Documento di Trasporto](https://peppol-docs.agid.gov.it/docs-next-release/docs/ITA/others/guides/release-notes-it/30-despatchadvice/main.html);
 - [Fatturazione](https://peppol-docs.agid.gov.it/docs-next-release/docs/ITA/invoice/guide/release-notes-it/main.html).

**Tali aggiornamenti avranno efficacia in via obbligatoria dal giorno 17 febbraio 2025, ciononostante si consiglia di recepire per tempo tali modifiche e di scaricare gli schematron per la validazione dei documenti aggiornati.**
<!--more-->

Le specifiche tecniche che rimarranno in vigore fino al giorno 16 febbraio 2025 sono disponibili agli indirizzi:

 - [Fatturazione](https://peppol-docs.agid.gov.it/docs/my_index_fatt.jsp);
 - [Altri processi (Ordinazione semplice, Ordinazione completa, Ordinazione pre-concordata, Documento di trasporto)](https://peppol-docs.agid.gov.it/docs/my_index.jsp).

Di seguito si riportano i cambiamenti effettuati con la November Release 2024:

**Cambiamenti alla documentazione, alla sintassi e alle code lists e artefatti di validazione –[Altri processi (ordine, ordine con risposta, ordine pre-concordato e documento di trasporto)](https://peppol-docs.agid.gov.it/docs-next-release/my_index.jsp)**

**Cambiamenti alla sintassi**
 - Ordine, Ordine Pre-Concordato, Documento di Trasporto – Aggiunto nuovo campo opzionale cbc:ID nella struttura cac:AdditionalItemProperty;
 - Documento di Trasporto:
    - Aggiunto nuovo attributo opzionale @schemeID al campo cbc:ID nella struttura cac:TransportHandlingUnit;
    - Aggiunta nuova struttura opzionale cac:DeliveryParty.

**Cambiamenti alle code lists e artefatti di validazione**
 - Ordine, Risposta all’Ordine, Ordine Pre-Concordato, Documento di Trasporto – Aggiornate le codelist Item type identification code (UNCL7143), Dangerous goods regulations code (UNCL8273) Recommendation 20, including Recommendation 21 codes - prefixed with X (UN/ECE);
 - Documento di Trasporto – Aggiunta nuova codelist Transport Handling Unit ID scheme (openPEPPOL) contentente unicamente il codice [SSCC] *Serial Shipping Container Code*.

**Aggiornamenti relativi alla “BIS compliance”**
 - Ordine, Risposta all’Ordine, Ordine Pre-Concordato, Documento di Trasporto – Aggiunte nuove regole di conformità sull’utilizzo degli identificatori del mittente/destinatario nell’inserimento di un messaggio BIS3 all’interno del Peppol Business Message Envelope (SBDH).

**Cambiamenti alla documentazione, alla sintassi e alle code lists e artefatti di validazione – [Fatturazione](https://peppol-docs.agid.gov.it/docs-next-release/my_index_fatt.jsp)**

**Cambiamenti alle code lists e artefatti di validazione**
 - Revisioni formale di specifiche Regole di business CIUS italiana (CIUS ID BR-IT-261; BR-IT-370; BR-IT-DC-480) e Regole di business estensione italiana (CIUS ID BR-IT-DE-013; BR-IT-DE-024; BR-IT-DE-026) per allineamento alle Regole tecniche dell’Agenzia delle Entrate relative alla gestione delle fatture europee - versione 2.5;
 - Introduzione delle nuove regole dalla DE-R-001 alla DE-R-030 (Germania);
 - Aggiornamento dei controlli delle regole PEPPOL-EN16931-R002, NL-R-008 (Paesi Bassi), SE-R-003 (Svezia), SE-R-004 (Svezia) e SE-R-013 (Svezia).

**Aggiornamento schematron EN 16931**
 - Aggiornamento dello schematron EN 16931 alla versione 1.3.13.

**Aggiornamenti relativi alla “BIS compliance”**
 - Aggiunte nuove regole di conformità sull’utilizzo degli identificatori del mittente/destinatario nell’inserimento di un messaggio BIS3 all’interno del Peppol Business Message Envelope (SBDH).


