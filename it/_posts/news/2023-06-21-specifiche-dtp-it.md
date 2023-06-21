---
layout: post
title: Aggiornamento della Specifica italiana del Documento di Trasporto Peppol
lang: it
ref: specifiche-dtp-it
excerpt_separator: <!--more-->
tags:
categories: news
permalink: /it/news/pecifiche-dtp-it/
---
Si comunica che sono stati pubblicati gli aggiornamenti alla Specifica italiana del Documento di Trasporto Peppol in relazione alle disposizioni contenute nel DPR n. 472/1996, contenenti le modifiche elencate di seguito. La relativa [nota di rilascio](https://peppol-docs.agid.gov.it/docs-next-release/docs/ITA/others/guides/release-notes-it/30-despatchadvice/main.html) è disponibile sul [Portale specifiche (next release)](https://peppol-docs.agid.gov.it/docs-next-release/).

**Tali aggiornamenti avranno efficacia in via obbligatoria dal giorno 07 agosto 2023, ciononostante si consiglia di recepirle per tempo.**

Le specifiche tecniche che rimarranno in vigore fino al giorno 06 agosto 2023 sono disponibili all’indirizzo [Altri processi (Documento di trasporto)](https://peppol-docs.agid.gov.it/docs/my_index.jsp).

Di seguito si riportano i cambiamenti effettuati:

**Cambiamenti alla specifica (Documentazione)**
 - Specificati gli scenari di business in relazione ai quali la specifica fornisce le linee guida per il supporto e l’implementazione del Documento di Trasporto (B2G – Business to Government; G2G – Government to Government);
 - Aggiunta l’obbligatorietà di indicazione delle parti Acquirente (BuyerCustomerParty) e Venditore (SellerSupplierParty);
 - Aggiunta l’obbligatorietà di indicazione degli identificativi (Partita IVA / Codice fiscale) delle parti Speditore/Mittente (DespatchSupplierParty), Destinatario/Consegnatario (DespatchCustomerParty), Acquirente (BuyerCustomerParty), Venditore (SellerSupplierParty) e Vettore (CarrierParty);
 - Specificate le modalità di indicazione degli identificativi (Partita IVA / Codice fiscale) delle parti, attraverso l’utilizzo di specifici schemeID;
 - Aggiunto un paragrafo specifico relativo all’indicazione dell’Indirizzo di consegna dei beni (§ 6.3.2 Indirizzo di consegna) e definita la sua obbligatorietà;
 - Aggiornati gli esempi in funzione delle modifiche alla specifica.

**Cambiamenti alla sintassi**
- Modificata da “0..1” a “1..1” la cardinalità dei campi: 
    - cac:DespatchSupplierParty/cac:Party/cac:PartyIdentification – Identificazione del soggetto Speditore;
    - cac:DeliveryCustomerParty/cac:Party/cac:PartyIdentification – Identificazione del soggetto Consegnatario;
    - cac:BuyerCustomerParty – Acquirente;
    - cac:BuyerCustomerParty/cac:Party/cac:PartyIdentification – Identificazione del soggetto Acquirente;
    - cac:SellerSupplierParty – Venditore;
    - cac:SellerSupplierParty/cac:Party/cac:PartyIdentification – Identificazione del soggetto Venditore;
    - cac:Consignment – Informazioni sul trasporto;
    - cac:CarrierParty/cac:PartyIdentification – Identificazione del soggetto Vettore;
    - cac:Shipment/cac:Delivery – Informazioni sulla consegna;
    - cac:Shipment/cac:Delivery/cac:Despatch – Ulteriori informazioni sulla consegna;
    - cac:Shipment/cac:Delivery/cac:Despatch/cac:DespatchAddress – Indirizzo di consegna.
- Aggiornate  le descrizioni dei campi e i relativi esempi in funzione delle modifiche alla specifica.

Si comunica inoltre che in data 23 giugno 2023 è previsto un ulteriore rilascio ad integrazione del precedente, il cui oggetto riguarda:

**Cambiamenti alle code lists e artefatti di validazione**
 - Aggiornamento delle Regole di business per il Documento di Trasporto Peppol.

**Cambiamenti a fogli di stile ed esempi**
 - Aggiornamento del foglio di stile per il Documento di Trasporto Peppol 3;
 - Aggiornamento dei file di esempio in funzione delle modifiche alla Specifica.  
