---
layout: post
title: Peppol May Release 2026
lang: it
ref: Peppol May Release 2026
excerpt_separator: <!--more-->
tags:
categories: news
permalink: /it/news/Peppol May Release 2026/
---

Si comunica che sono stati pubblicati gli aggiornamenti relativi alla May Release 2026 di OpenPeppol, le cui release notes complete sono disponibili agli indirizzi:
- [Fatturazione](https://peppol-docs.agid.gov.it/docs-next-release/docs/ITA/invoice/guide/release-notes-it/main.html)
- [Ordinazione Semplice](https://peppol-docs.agid.gov.it/docs-next-release/docs/ITA/others/guides/release-notes-it/3-order-only/main.html)
- [Ordinazione Completa](https://peppol-docs.agid.gov.it/docs-next-release/docs/ITA/others/guides/release-notes-it/28-ordering/main.html)
- [Ordinazione Pre-Concordata](https://peppol-docs.agid.gov.it/docs-next-release/docs/ITA/others/guides/release-notes-it/42-orderagreement/main.html)
- [Documento di Trasporto](https://peppol-docs.agid.gov.it/docs-next-release/docs/ITA/others/guides/release-notes-it/30-despatchadvice/main.html)
Tali aggiornamenti avranno efficacia in via obbligatoria dal giorno **17 agosto 2026**, ciononostante si consiglia di recepire per tempo tali modifiche e di scaricare gli schematron per la validazione dei documenti aggiornati.
<!--more-->
Le specifiche tecniche che rimarranno in vigore fino al giorno 16 agosto 2026 sono disponibili agli indirizzi:
- [Fatturazione](https://peppol-docs.agid.gov.it/docs/my_index_fatt.jsp)
- [Altri processi (Ordinazione semplice, Ordinazione completa, Ordinazione pre-concordata, Documento di trasporto)](https://peppol-docs.agid.gov.it/docs/my_index.jsp)

Di seguito si riportano i cambiamenti effettuati con la May Release 2026:

**Cambiamenti alla sintassi, code lists e artefatti di validazione - [Altri processi (ordine, ordine con risposta, ordine pre-concordato e documento di trasporto)](https://peppol-docs.agid.gov.it/docs-next-release/)**

Cambiamenti alla sintassi

Ordine:
- Aggiunta la nuova struttura cac:QuotationLineReference contenente l’elemento cbc:LineID all’interno della struttura cac:OrderLine per indicare il riferimento ad una specifica riga del documento di preventivo.

Cambiamenti alle code lists e artefatti di validazione

Ordine, Risposta all’Ordine, Ordine Pre-Concordato, Documento di Trasporto:
-	Electronic Address Scheme (EAS)
    - Aggiunti: 0242,0245,0246,0248
    - Rimossi: 0037,0177,0193,0212,0213,0215,0147,0154,0170,0194,0203,0217
    - Modificati: 0088,0096,0184,0190,0191,0192,0195,0196,0198,0204,9959
    
 -  ISO 6523 ICD list
    - Aggiunti: 0245,0246,0247,0248
    - Modificati: 0096,0158,0241,0243

    - ISO 4217 Currency codes
        - Rimossi: ANG, BGN, STD
        - Aggiunti: STN, XCG
    
    - UNCL7161
    - Aggiunti: CAX, CAY, CAZ, DAC, DAF, DAG, DAH, DAI, DAJ, DAK, DAL, DAM, DAN, DAO, DAP, DAQ, PRV

- Modifica da “warning” a “fatal” la severità delle regole PEPPOL-COMMON-R052 (Danimarca) e PEPPOL-COMMON-R053 (Danimarca).

- Inserimento delle nuove regole PEPPOL-COMMON-R054 (Paesi Bassi), PEPPOL-COMMON-R055 (Paesi Bassi), PEPPOL-COMMON-R056-1 (Paesi Bassi), PEPPOL-COMMON-R056-2 (Paesi Bassi), PEPPOL-COMMON-R057 (Paesi Bassi) con severità “warning”. Le regole saranno poste a severità “fatal” in una successiva release.

Aggiornamento schematron
- Aggiornamento schematron

**Cambiamenti alla documentazione, alle code lists e artefatti di validazione – [Fatturazione](https://peppol-docs.agid.gov.it/docs-next-release/my_index_fatt.jsp)**

Cambiamenti alla documentazione
- Inserito nuovo profilo opzionale Profilo 02 – Fatturazione con risposta che consente di gestire un processo in cui a seguito della ricezione della fattura, è richiesto l’invio di una risposta alla fattura. Questo profilo richiede una registrazione separata nell’SMP e utilizza il documento di Invoice Response BIS. Le specifiche di questo documento sono disponibili sul portale specifiche di OpenPeppol [Other BIS](https://docs.peppol.eu/poacc/upgrade-3/upcoming/).

Cambiamenti alle code lists e artefatti di validazione
- Electronic Address Scheme (EAS)
    -	Rimossi: 0037,0147,0154,0170,0177,0193,0194 ,0203 ,0212,0213,0215,0217
    -	Modificati: 0088,0184,0190,0191,0192,0195,0196,0198,0199,0204,9959
	
- ISO 6523 ICD list
    -	Aggiunti: 0246,0247,0248
    - Modificati: 0096,0158,0208,0241,0243

- ISO 4217 Currency codes
    - Rimossi: ANG, BGN
    - Aggiunti: XCG
    
 -   Modifica da “warning” a “fatal” della severità delle regole PEPPOL-COMMON-R052 (Danimarca) e PEPPOL-COMMON-R053 (Danimarca).
 - Inserimento delle nuove regole PEPPOL-COMMON-R054 (Paesi Bassi), PEPPOL-COMMON-R055 (Paesi Bassi), PEPPOL-COMMON-R056-1 (Paesi Bassi), PEPPOL-COMMON-R056-2 (Paesi Bassi), PEPPOL-COMMON-R057 (Paesi Bassi) con severità “warning”. Le regole saranno poste a severità “fatal” in una successiva release.

Aggiornamento schematron EN 16931
-	Aggiornamento schematron EN 16931
-	Eliminazione regola BR-CO-25
-	Aggiornamento regola PEPPOL-EN16931-R004.
-	Aggiunta nella regola PEPPOL-EN16931-R007 (Francia) di due nuovi profili temporanei per Fattura UBL e Nota di Credito

