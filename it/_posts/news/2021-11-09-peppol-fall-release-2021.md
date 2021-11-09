---
layout: post
title: Peppol Fall Release 2021
lang: it
ref: peppol-fall-release-2021
excerpt_separator: <!--more-->
tags:
categories: news
permalink: /it/news/peppol-fall-release-2021/
---

Si comunica che sono stati pubblicati gli aggiornamenti relativi alla 
Fall Release 2021 di OpenPeppol, contenenti una serie di modifiche le 
cui release notes complete sono disponibili agli indirizzi:

  - [Ordinazione Semplice](https://peppol-docs.agid.gov.it/docs/docs/ITA/others/guides/release-notes-it/3-order-only/main.html)
  - [Ordinazione Completa](https://peppol-docs.agid.gov.it/docs/docs/ITA/others/guides/release-notes-it/28-ordering/main.html)
  -	[Ordinazione Pre-concordata](https://peppol-docs.agid.gov.it/docs/docs/ITA/others/guides/release-notes-it/42-orderagreement/main.html)
  -	[Documento di Trasporto](https://peppol-docs.agid.gov.it/docs/docs/ITA/others/guides/release-notes-it/30-despatchadvice/main.html)

Il contenuto originale rilasciato da OpenPeppol è disponibile [qui](https://docs.peppol.eu/poacc/upgrade-3/release-notes/)

Tali aggiornamenti avranno efficacia in via obbligatoria dal **giorno 15 novembre 2021**.

Di seguito si riportano i cambiamenti effettuati:
 - **Cambiamenti alla specifica (Documentazione)**
    - BIS Ordinazione Semplice – Aggiornamento editoriale al paragrafo “6.10 Totale imposte”; 
    - BIS Ordinazione Semplice, Ordinazione Completa, Ordinazione Pre-concordata – Aggiornamento 
    editoriale sulla descrizione dell’utilizzo della tassazione a livello di riga, paragrafo “6.11 
    Categoria imposte su riga”.

 - **Cambiamenti alla sintassi**
    - Risposta all’ordine – Aggiornamento editoriale al cac:Party del cac:SellerSupplierParty, ora 
    obbligatorio (1..1) invece di opzionale (0..1);
    - Ordine - Correzione della duplicazione dei “tir identifiers” dei campi presenti nei 
    cac:PartyLegalEntity di cac:BuyerCustomerParty e cac:SellerSupplierParty. Assegnati 
    nuovi ID per le informazioni contenute nel cac:PartyLegalEntity del Seller, utilizzando valori 
    che vanno da tir01-p038 fino a tir01-p041.

 - **Cambiamenti alle code lists e artefatti di validazione – Tutti i profili (ordine, ordine con risposta, ordine pre-concordato e documento di trasporto)**
    - Aggiunta una regola con severità “warning” (non bloccante)  per la validazione del formato 
    del “Belgian organisation numbers” (ICD:0208). La severità passerà a “fatal” con la Spring release 2022;
    - Aggiunte delle regole con severità “warning” (non bloccante) per la validazione dei formati degli 
    identifier italani (ICD/EAS:0201, 0210, 0211 and EAS 9906 and 9907). La severità passerà a “fatal” con 
    la Spring release 2022;
    - Aggiunti i codici relativi alle unità di trasporto (tir16-085) e alla tipologia di confezionamento (tir16-090) 
    per allineamento ai codici della lista CEF. (O1, O2, O3, O4, O5, O6, O7, O8, O9, OG, OH, OI, OJ, OL, OM, ON, OP, 
    OQ, OR, OS, OV, OW, OX, OY, OZ, P1, P3, P4, SX);
    - Aggiunti i codici UOM (Unit of Measure) IUG, KWN, KWS, ODG, ODK, ODM, Q41, Q42, XZZ per allineamento ai codici 
    della lista CEF.

Se evidenzia che con la presente release **vengono introdotte anche, negli schematron di OpenPeppol, le regole relative** 
**alla validazione dei codici 0201 (Codice IPA), 0210 (Codice Fiscale) e 0211 (Partita IVA)** già presenti negli schematron 
di rilevanza nazionale con severità “fatal”, pertanto l’introduzione di tali regole non ha nessun impatto operativo. 

Si avvisa infine che le modifiche descritte impattano sui controlli e sulle logiche implementate dal tool di validazione,
**vi invitiamo pertanto a scaricare la versione aggiornata**
