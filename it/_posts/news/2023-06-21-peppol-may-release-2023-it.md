---
layout: post
title: Peppol May Release 2023
lang: it
ref: peppol-may-release-2023-it
excerpt_separator: <!--more-->
tags:
categories: news
permalink: /it/news/peppol-may-release-2023-it/
---
Si comunica che sono stati pubblicati gli aggiornamenti relativi alla May Release 2023 di OpenPeppol, contenenti una serie di modifiche le cui release notes complete sono disponibili agli indirizzi:

 - [Ordinazione Semplice](https://peppol-docs.agid.gov.it/docs-next-release/docs/ITA/others/guides/release-notes-it/3-order-only/main.html);
 - [Ordinazione Completa](https://peppol-docs.agid.gov.it/docs-next-release/docs/ITA/others/guides/release-notes-it/28-ordering/main.html);
 - [Ordinazione Pre-concordata](https://peppol-docs.agid.gov.it/docs-next-release/docs/ITA/others/guides/release-notes-it/42-orderagreement/main.html);
 - [Documento di Trasporto](https://peppol-docs.agid.gov.it/docs-next-release/docs/ITA/others/guides/release-notes-it/30-despatchadvice/main.html);
 - [Fatturazione](https://peppol-docs.agid.gov.it/docs-next-release/docs/ITA/invoice/guide/release-notes-it/main.html).

Il contenuto originale rilasciato da OpenPeppol è disponibile [qui](https://peppol.org/may-2023-release-of-the-peppol-post-award-artefact/).
**Tali aggiornamenti avranno efficacia in via obbligatoria dal giorno 07 agosto 2023, ciononostante si consiglia di recepire per tempo tali modifiche e di scaricare gli schematron per la validazione dei documenti aggiornati.**
<!--more-->
Le specifiche tecniche che rimarranno in vigore fino al giorno 06 agosto 2023 sono disponibili agli indirizzi:

 - [Fatturazione](https://peppol-docs.agid.gov.it/docs/my_index_fatt.jsp);
 - [Altri processi (Ordinazione semplice, Ordinazione completa, Ordinazione pre-concordata, Documento di trasporto)](https://peppol-docs.agid.gov.it/docs/my_index.jsp).

Di seguito si riportano i cambiamenti effettuati:
Cambiamenti alla documentazione, alla sintassi e alle code lists e artefatti di validazione - [Altri profili (ordine, ordine con risposta, ordine pre-concordato e documento di trasporto)](https://peppol-docs.agid.gov.it/docs-next-release/my_index.jsp)

**Cambiamenti alla specifica (Documentazione)**
 - BIS Ordinazione Semplice, BIS Ordinazione Completa – Integrata la sezione 6.4. Identificazione del prodotto con l’indicazione dell’identificativo prodotto attribuito dal Produttore; 
 - BIS Ordinazione Semplice, BIS Ordinazione Completa – Integrata la sezione 6.14. Altri riferimenti con l’indicazione del riferimento al catalogo in testata;
- BIS Ordinazione Semplice, BIS Ordinazione Completa – Integrata la sezione 6.16. Consegna (Delivery) con la descrizione della modalità di indicazione della priorità richiesta dall’Acquirente per l’evasione dell’ordine; 
 - BIS Ordinazione Semplice, BIS Ordinazione Completa – Aggiornati gli esempi in funzione delle modifiche alla sintassi.

**Cambiamenti alla sintassi**
- Ordine
    - Aggiunta cac:CatalogueReference – Riferimento al catalogo come struttura opzionale a livello di testata;
    - Aggiunto cbc:ShippingPriorityLevelCode – Priorità di spedizione richiesta come campo opzionale della struttura cac:Shipment;
    - Aggiunti cbc:StartTime – Ora di inizio e cbc:EndTime – Ora di fine come campi opzionali della struttura cac:RequestedDeliveryPeriod a livello di linea;
    - Aggiunta cac:ManufacturersItemIdentification – Identificativo prodotto attribuito dal Produttore come struttura opzionale a livello di linea.
- Risposta all’ordine
    - Aggiunti cbc:StartTime – Ora di inizio e cbc:EndTime – Ora di fine come campi opzionali della struttura cac:PromisedDeliveryPeriod a livello di linea.

**Cambiamenti alle code lists e artefatti di validazione**
 - Aggiunta la codelist Transport service priority code (UNCL4219) per indicare la priorità di spedizione richiesta. Si applica nelle specifiche di Ordinazione Semplice e Ordinazione Completa;
 - Modificata da “warning” a “fatal” la severità della regola PEPPOL-COMMON-R050 per la validazione dell’Australian Business Number (ABN);
 - Aggiunti i codici 0221 (Giappone) e 0230 (Malesia) alla codifica EAS. Rimosso il codice svedese 9955 dalla stessa codifica;
 - Aggiunti i codici 0221 (Giappone), 0222, 0223 (Francia), 0224 (Francia), 0225 (Francia), 0226 (Francia), 0227 (Francia), 0228 (Francia), 0229 (Francia), 0230 (Malesia) alla codifica ICD;
 - Aggiunto il codice EMD nella codelist Item type identification code (UNCL7143) per indicare l’identificativo del Dispositivo Medico secondo l’European Medical Device Nomenclature (EMDN).

 **Cambiamenti alla documentazione, alla sintassi e alle code lists e artefatti di validazione – [Fatturazione](https://peppol-docs.agid.gov.it/docs-next-release/my_index_fatt.jsp)**

**Cambiamenti alle code lists e artefatti di validazione**
 - Modificata da “warning” a “fatal” la severità della regola PEPPOL-COMMON-R050 per la validazione dell’Australian Business Number (ABN);
 - Aggiunti i codici 0221 (Giappone) e 0230 (Malesia) alla codifica EAS. Rimosso il codice svedese 9955 dalla stessa codifica;
 - Aggiunti i codici 0221 (Giappone), 0222, 0223 (Francia), 0224 (Francia), 0225 (Francia), 0226 (Francia), 0227 (Francia), 0228 (Francia), 0229 (Francia), 0230 (Malesia) alla codifica ICD;
 - Aggiunto il codice EMD nella codelist Item type identification code (UNCL7143) per indicare l’identificativo del Dispositivo Medico secondo l’European Medical Device Nomenclature (EMDN). 
 - Corrette specifiche regole di business derivanti dagli aggiornamenti della EN16931 e relativi schematron (per ulteriori informazioni si rimanda al [link](https://github.com/ConnectingEurope/eInvoicing-EN16931/releases/tag/validation-1.3.10).

**Cambiamenti alle regole specifiche per Paese**
 - Rimosse le regole GR-R-007-1, GR-R-007-2 e GR-R-007-3;
 - Aggiornato il contesto di applicazione delle regole GR-R-004-1 e GR-R-004-2 che non si applicano più quando il Rappresentante Fiscale è greco;
 - Aggiunta la regola GR-R-011 che rende obbligatorio il Codice Fiscale per il Fornitore greco;
 - Rinominata la regola GR-R-011 in GR-S-011 e modificata da “fatal” a “warning” la severità. 
