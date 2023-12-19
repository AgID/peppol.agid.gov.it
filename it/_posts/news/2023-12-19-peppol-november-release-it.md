---
layout: post
title: Peppol November Release 2023 e altre modifiche italiane
lang: it
ref: peppol-november-release-2023-it
excerpt_separator: <!--more-->
tags:
categories: news
permalink: /it/news/peppol-november-release-2023-it/
---
Si comunica che sono stati pubblicati gli aggiornamenti relativi alla November Release 2023 di OpenPeppol e ad ulteriori modifiche relative al contesto italiano, le cui release notes complete sono disponibili agli indirizzi:

•	[Ordinazione Semplice](https://peppol-docs.agid.gov.it/docs-next-release/docs/ITA/others/guides/release-notes-it/3-order-only/main.html);
•	[Ordinazione Completa](https://peppol-docs.agid.gov.it/docs-next-release/docs/ITA/others/guides/release-notes-it/28-ordering/main.html);
•	[Ordinazione Pre-concordata](https://peppol-docs.agid.gov.it/docs-next-release/docs/ITA/others/guides/release-notes-it/42-orderagreement/main.html);
•	[Documento di Trasporto](https://peppol-docs.agid.gov.it/docs-next-release/docs/ITA/others/guides/release-notes-it/30-despatchadvice/main.html);
•	[Fatturazione](https://peppol-docs.agid.gov.it/docs-next-release/docs/ITA/invoice/guide/release-notes-it/main.html).

Il contenuto originale rilasciato da OpenPeppol è disponibile [qui](https://peppol.org/post-award-artefacts-for-november-2023-release-published/).

**Tali aggiornamenti avranno efficacia in via obbligatoria dal giorno 26 febbraio 2024, ciononostante si consiglia di recepire per tempo tali modifiche e di scaricare gli schematron per la validazione dei documenti aggiornati.**

Le specifiche tecniche che rimarranno in vigore fino al giorno 25 febbraio 2024 sono disponibili agli indirizzi:

•	[Fatturazione](https://peppol-docs.agid.gov.it/docs/my_index_fatt.jsp);
•	[Altri processi (Ordinazione semplice, Ordinazione completa, Ordinazione pre-concordata, Documento di trasporto)](https://peppol-docs.agid.gov.it/docs/my_index.jsp).

Di seguito si riportano i cambiamenti effettuati:
**Cambiamenti alla documentazione, alla sintassi e alle code lists e artefatti di validazione – [Altri processi (ordine, ordine con risposta, ordine pre-concordato e documento di trasporto)](https://peppol-docs.agid.gov.it/docs-next-release/my_index.jsp)**

Cambiamenti alla specifica (Documentazione)
•	BIS Ordinazione Semplice, BIS Ordinazione Completa, BIS Ordinazione Pre-concordata, BIS Documento di Trasporto – Correzione di un errore nella sezione *4. Tipi di dato semantici*, in cui l’indicatore booleano era caratterizzato dal tipo primitivo “String” invece che “Boolean”. Modifica puramente editoriale; 
•	BIS Documento di Trasporto – Integrazione della sezione 6.3.2. Indirizzo di consegna con la modalità di indicazione della consegna di tipo domiciliare in analogia con la specifica dell’ordine;
•	BIS Ordinazione Semplice, BIS Ordinazione Completa, BIS Ordinazione Pre-concordata, BIS Documento di Trasporto – Piccole modifiche editoriali.

Cambiamenti alla sintassi
•	Ordine
    o	Aggiornata la denominazione inglese del campo cbc:OrderTypeCode, da "Consignment Order" a "Order Type" per evitare confusione. Nessuna modifica alla specifica italiana;
    o	Piccole modifiche editoriali.
Cambiamenti alle code lists e artefatti di validazione
•	Aggiunti i codici 105 "Purchase order" e 402 "Intermediate handling cross docking order alla codifica Order Type Code;
•	Aggiunto il codice 0218 (Lettonia) alla codifica EAS; 
•	Aggiunta correlazione tra codice CEL e l’unità di misura °C [grado Celsius] nella codifica Recommendation 20, including Recommendation 21 codes - prefixed with X (UN/ECE).
•	Modifica del livello di severità delle Regole di business per il Documento di Trasporto Peppol da WARNING a FATAL, come anticipato con la pubblicazione in data 07/08/2023 dell’Entrata in vigore della Peppol May Release 2023.

**Cambiamenti alla documentazione, alla sintassi e alle code lists e artefatti di validazione – [Fatturazione](https://peppol-docs.agid.gov.it/docs-next-release/my_index_fatt.jsp)**

Cambiamenti alla specifica (Documentazione)
•	Aggiornamento della sezione *4.6 Fatture negative e note di credito*, e rimozione del riferimento al formato BIS2. Modifica puramente editoriale; 
•	Inserimento di esempi specifici nelle sezioni *4.9.1. Rivalsa del bollo e 4.9.2. Restituzione del bollo*;
•	Aggiunta della nuova sezione *4.11 Indicazione acconto in fattura* contenente le modalità operative previste per l’indicazione di un acconto nella fattura di saldo;
•	Aggiornamento delle sezioni *15.1. Regole di business Peppol per le transazioni e 15.2. Regole di business EN 16931 per le transazioni* per allineamento degli schematron all’aggiornamento derivante dalla norma EN 16931;
•	Aggiornamento delle sezioni dell’*Appendix C: Regole Nazionali* per allineamento alle Regole tecniche dell’Agenzia delle Entrate relative alla gestione delle fatture europee - versione 2.3 e modifica delle seguenti regole:
    o	*C.1. CIUS*: BR-IT-120; BR-IT-180; BR-IT-200; BR-IT-230;
    o	*C.4. Estensioni Domestiche*: BR-IT-DE-011; BR-IT-DE-046; BR-IT-DE-049.
•	Integrazione delle sezioni dell’*Appendix C: Regole Nazionali* per allineamento ai controlli svolti da SDI sui documenti e inserimento delle seguenti nuove regole:
    •	*C.1. CIUS*: BR-IT-071; BR-IT-081; BR-IT-100; BR-IT-130; BR-IT-221; BR-IT-361;
    •	*C.2. CIUS Domestiche*: BR-IT-DC-120; BR-IT-DC-141; BR-IT-DC-160; BR-IT-DC-170; BR-IT-DC-180; BR-IT-DC-190; BR-IT-DC-300; BR-IT-DC-310; BR-IT-DC-320; BR-IT-DC-330; BR-IT-DC-340; 
    •	*C.4. Estensioni Domestiche*: BR-IT-DE-050; BR-IT-DE-051; BR-IT-DE-052; BR-IT-DE-053.
•	Aggiornamento della regola BR-IT-DC-480* relativa al controllo della presenza del bollo sui documenti di importo superiore a 77,47 euro; 
•	Piccole modifiche editoriali.

Cambiamenti alle code lists e artefatti di validazione
•	Rimozione della regola PEPPOL-EN16931-R006 dalle *Regole di business Peppol BIS Fatturazione 3.0* in quanto ridondante rispetto alla regola UBL-SR-04 presente tra le *Regole di business EN 16931 Fatturazione*;
•	Revisioni di specifiche **Regole di business CIUS italiana* (CIUS ID BR-IT-120; BR-IT-180; BR-IT-200; BR-IT-230; BR-IT-520*; BR-IT-DC-203) e *Regole di business estensione italiana* (CIUS ID BR-IT-DE-009NC1*; BR-IT-DE-011) per allineamento alle Regole tecniche dell’Agenzia delle Entrate relative alla gestione delle fatture europee - versione 2.3;
•	Integrazione delle *Regole di business CIUS italiana* e delle *Regole di business estensione italiana* per allineamento ai controlli svolti da SDI sui documenti e inserimento delle seguenti nuove regole:
    •	*Regole di business CIUS italiana*: BR-IT-071; BR-IT-081; BR-IT-100; BR-IT-130; BR-IT-221; BR-IT-361; BR-IT-DC-120; BR-IT-DC-141; BR-IT-DC-160; BR-IT-DC-170; BR-IT-DC-180; BR-IT-DC-190; BR-IT-DC-300; BR-IT-DC-310; BR-IT-DC-320; BR-IT-DC-330; BR-IT-DC-340; 
    •	*Regole di business estensione italiana*: BR-IT-DE-050; BR-IT-DE-051; BR-IT-DE-052; BR-IT-DE-053.
•	Aggiunto il codice 0218 (Lettonia) alla codifica EAS;
•	Aggiunta correlazione tra codice CEL e l’unità di misura °C [grado Celsius] nella codifica Recommendation 20, including Recommendation 21 codes - prefixed with X (UN/ECE).

Aggiornamento schematron EN 16931
•	Adozione della versione 1.3.11 degli artefatti di validazione derivanti dall’aggiornamento della EN 16931.

Cambiamenti nella sezione Downloads
•	Inserimento di un nuovo file di esempio relativo alla fatturazione acconto – saldo.


