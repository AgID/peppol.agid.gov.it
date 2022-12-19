---
layout: post
title: Peppol November Release 2022
lang: it
ref: peppol-november-release
excerpt_separator: <!--more-->
tags:
categories: news
permalink: /it/news/peppol-november-release/
---
Si comunica che sono stati pubblicati gli aggiornamenti relativi alla November Release 2022 di OpenPeppol, contenenti una serie di modifiche le cui release notes complete sono disponibili agli indirizzi:
 - [Ordinazione Semplice](https://peppol-docs.agid.gov.it/docs-next-release/docs/ITA/others/guides/release-notes-it/3-order-only/main.html);
 - [Ordinazione Completa](https://peppol-docs.agid.gov.it/docs-next-release/docs/ITA/others/guides/release-notes-it/28-ordering/main.html);
 - [Ordinazione Pre-concordata](https://peppol-docs.agid.gov.it/docs-next-release/docs/ITA/others/guides/release-notes-it/42-orderagreement/main.html);
 - [Documento di Trasporto](https://peppol-docs.agid.gov.it/docs-next-release/docs/ITA/others/guides/release-notes-it/30-despatchadvice/main.html);
 - [Fatturazione](https://peppol-docs.agid.gov.it/docs-next-release/docs/ITA/invoice/guide/release-notes-it/main.html).
Il contenuto originale rilasciato da OpenPeppol è disponibile [qui](https://peppol.org/post-award-november-release-publication/).
Tali aggiornamenti avranno efficacia in via obbligatoria dal giorno **06 febbraio 2023**, ciononostante si consiglia di recepire per tempo tali modifiche e di scaricare gli schematron per la validazione dei documenti aggiornati.
Le specifiche tecniche che rimarranno in vigore fino al giorno 05 febbraio 2023 sono disponibili agli indirizzi:
 - [Fatturazione](https://peppol-docs.agid.gov.it/docs/my_index_fatt.jsp);
 - [Altri processi](https://peppol-docs.agid.gov.it/docs/my_index.jsp) (Ordinazione semplice, Ordinazione completa, Ordinazione pre-concordata, Documento di trasporto).
<!--more-->
Di seguito si riportano i cambiamenti effettuati:
**Cambiamenti alla documentazione, alla sintassi e alle code lists e artefatti di validazione – Altri profili (ordine, ordine con risposta, ordine pre-concordato e documento di trasporto)**

**Cambiamenti alla specifica (Documentazione)**
- BIS Ordinazione Semplice, BIS Ordinazione Completa – Inserite le nuove tipologie di Ordinazione, 221 Ordinazione a budget e 226 Ordinazione di regolazione; 
- BIS Ordinazione Semplice, BIS Ordinazione Completa – Modificata la modalità di indicazione del CUP a livello di testata;
- BIS Ordinazione Completa – Corretto il secondo esempio di risposta all’ordine nella sezione 7.1.1 della documentazione;
- BIS Ordinazione Pre-Concordata – Modificata la modalità di indicazione di Partita IVA e Codice Fiscale di Fornitore/Venditore e Cliente/Acquirente; 
- BIS Ordinazione Semplice, BIS Ordinazione Completa, BIS Ordinazione Pre-Concordata, BIS Documento di Trasporto – Aggiornati gli esempi in funzione delle modifiche alla sintassi; 
- Eliminata indicazione del “Last updated” nel piè di pagina.

**Cambiamenti alla sintassi**
- Ordine
    - Aggiunti cbc:StartTime – Ora di inizio e cbc:EndTime – Ora di fine come campi opzionali della struttura cac:RequestedDeliveryPeriod;
    - Aggiunta cac:ProjectReference – Riferimento al progetto come struttura opzionale a livello di testata.
- Risposta all’ordine
    - Aggiunti cbc:StartTime – Ora di inizio e cbc:EndTime – Ora di fine come campi opzionali della struttura cac:PromisedDeliveryPeriod.
- Ordine pre-concordato
    - Aggiunto cbc:DocumentTypeCode come campo opzionale della struttura cac:ItemSpecificationDocumentReference a livello di riga;
    - Aggiunto cbc:CompanyID come campo opzionale della struttura cac:PartyLegalEntity sia per il Fornitore (cac:SellerSupplierParty) che per il Cliente (cac:BuyerCustomerParty). 
- Documento di trasporto
    - Aggiunto cbc:SalesOrderLineID - Identificativo linea d’ordine di vendita come campo opzionale a livello di riga di DDT;
    - Aggiunto cac:CommodityClassification – Classificazione prodotto come struttura opzionale a livello di riga di DDT;
    - Aggiunta cac:AdditionalDocumentReference – Documenti addizionali come struttura opzionale a livello di testata. Aggiunta cac:DocumentiReference – Riferimento a documento addizionale come struttura a livello di riga;
    - Aggiunta cac:ShipmentStage – Informazioni sullo stato della spedizione come struttura opzionale a livello di testata. Il relativo campo cbc:TransportModeCode – Modalità di trasporto è opzionale e valorizzabile tramite codelist UN/ECE Recommendation 19;
    - Recepita la richiesta della Peppol Authority italiana di inserire la struttura cac:PartyIdentification del Vettore (cac:CarrierParty), che ora non risulta più un’estensione della sintassi italiana;
    - Recepita la richiesta della Peppol Authority italiana di rendere obbligatorio il campo cbc:DeliveredQuantity della struttura cac:DespatchLine.

**Cambiamenti alle code lists e artefatti di validazione**
- Rimosse le seguenti regole di validazione relative alla categoria fiscale:
    - Ordine - regola PEPPOL-T01-B20301 applicata al campo cac:AllowanceCharge/cac:TaxCategory/cbc:ID e regola PEPPOL-T01-B28701 applicata al campo cac:Item/cac:ClassifiedTaxCategory/cbc:ID;
    - Risposta all’ordine – regola PEPPOL-T76-B07701 applicata al campo cac:SellerSubstitutedLineItem/cac:Item/cac:ClassifiedTaxCategory/cbc:ID;
    - Ordine Pre-Concordato – regola PEPPOL-T110-B13301 applicata al campo cac:AllowanceCharge/cac:TaxCategory/cbc:ID e regola PEPPOL-T110-B14601 applicata al campo cac:TaxTotal/cac:TaxSubtotal/cac:TaxCategory/cbc:ID e regola PEPPOL-T110-B22301 applicata al campo cac:Item/cac:ClassifiedTaxCategory/cbc:ID.
    - Integrata la codelist Order Type Code (UNCL1001 subset) con due nuovi tipi di ordinazione: 221 Ordinazione a budget e 226 Ordinazione di regolazione. Si applica nelle specifiche di Ordinazione Semplice e Ordinazione Completa;
    - Modificata da “warning” a “fatal” la severità della regola PEPPOL-COMMON-R049 (ICD 0007) per la validazione del formato della “Swedish organisation number”, come annunciato nella May Release 2022;
- Corretta la regola PEPPOL-COMMON-R050 per la validazione del “Australian Business Number (ABN)”;
- Aggiunto il codice statunitense 9959 alla codifica EAS. Rimossi i codici italiani 9906 e 9907 dalla stessa codifica. Adeguati gli artefatti di validazione;
- Aggiunti i codici 0217 (Paesi Bassi), 0218, 0219 e 0220 (Lettonia) alla codifica ICD e adeguati gli artefatti di validazione.

**Cambiamenti alla documentazione, alla sintassi e alle code lists e artefatti di validazione – Fatturazione**

**Cambiamenti alla specifica (Documentazione)**
- Eliminata indicazione del “Last updated” nel piè di pagina;

**Cambiamenti alle code lists e artefatti di validazione**
- Modificata da “warning” a “fatal” la severità della regola PEPPOL-COMMON-R049 (ICD 0007) per la validazione del formato della “Swedish organisation number”, come annunciato nella May Release 2022;
- Corretta la regola PEPPOL-COMMON-R050 per la validazione del “Australian Business Number (ABN)”;
- Aggiunto il codice statunitense 9959 alla codifica EAS. Rimossi i codici italiani 9906 e 9907 dalla stessa codifica. Adeguati gli artefatti di validazione;
- Aggiunti i codici 0217 (Paesi Bassi), 0218, 0219 e 0220 (Lettonia) alla codifica ICD e adeguati gli artefatti di validazione.
- Corrette specifiche regole di business derivanti dagli aggiornamenti della EN16931 e relativi schematron (per maggiori informazioni si rimanda al segunete [link](https://github.com/ConnectingEurope/eInvoicing-EN16931/releases/tag/validation-1.3.9))

**Cambiamenti alle regole specifiche per Paese**

- Aggiornate le regole GR-S-008-1, GR-R-008-2 e GR-R-008-3, prevedendo la stringa ##INVOICE|URL## invece di ##INVOICE-URL## (POAC-518);
- Eliminata la regola DK-R-015;
- Corretto il testo delle regole DK-R-004 PEPPOL UBL & CII;
- Corretto il testo della regola DK-R-003 PEPPOL CII.
