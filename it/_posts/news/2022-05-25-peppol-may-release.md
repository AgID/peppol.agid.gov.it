---
layout: post
title: Peppol May Release 2022
lang: it
ref: peppol-may-release
excerpt_separator: <!--more-->
tags:
categories: news
permalink: /it/news/peppol-may-release/
---
Si comunica che sono pubblicati gli aggiornamenti relativi alla May Release 2022 di OpenPeppol, contenenti una serie di modifiche le cui release notes complete sono disponibili agli indirizzi: 

 - [Ordinazione Semplice](https://peppol-docs.agid.gov.it/docs/docs/ITA/others/guides/release-notes-it/3-order-only/main.html)
 - [Ordinazione Completa](https://peppol-docs.agid.gov.it/docs/docs/ITA/others/guides/release-notes-it/28-ordering/main.html)
 - [Ordinazione Pre-concordata](https://peppol-docs.agid.gov.it/docs/docs/ITA/others/guides/release-notes-it/42-orderagreement/main.html)
 - [Documento di Trasporto](https://peppol-docs.agid.gov.it/docs/docs/ITA/others/guides/release-notes-it/30-despatchadvice/main.html)
 - [Fatturazione](https://peppol-docs.agid.gov.it/docs/docs/ITA/invoice/guide/release-notes-it/main.html)
<!--more-->
Il contenuto originale rilasciato da OpenPeppol relativo alla fatturazione è disponibile [qui](https://docs.peppol.eu/poacc/billing/3.0/release-notes/), mentre il contenuto originale rilasciato da OpenPeppol relativo agli altri processi è disponibile [qui](https://docs.peppol.eu/poacc/upgrade-3/release-notes/).
Tali aggiornamenti avranno efficacia in via obbligatoria dal giorno **30 maggio 2022**.

Di seguito si riportano i cambiamenti effettuati:
 - **Cambiamenti alla specifica (Documentazione)**
     - Corretto un errore che provocava la comparsa di errori in sede di caricamento/utilizzo di file di schematron in alcuni convertitori/tool di file XLS;
     - Modificata da “warning” a “fatal” la severità della regola PEPPOL-COMMON-R043 (ICD 0208) relativa alla validazione del formato del “Belgian organisation numbers", come annunciato nella Fall release 2021;
     - Aggiunta una regola con severità “warning” per la validazione del formato del “Swedish organisation numbers” (ICD/EAS 0007). La severità passerà a “fatal” con la Fall release 2022;
     - Corretta la regola PEPPOL-EN16931-R080 che deve attivarsi solo per la Nota di credito e non per la Fattura;
     - Aggiunti i codici 0214, 0215 e 0216 alla codifica ICD e adeguati gli artefatti di validazione;
     - Aggiunti i codici 0147, 0170, 0188, 0215 e 0216 alla codifica EAS e adeguati gli artefatti di validazione;
     - Corretta la ripetizione del codice TSP presente nella codifica UNCL7143.
     - Inseriti i codici tipo fattura aggiuntivi 71, 102, 218, 219, 331, 382, 553, 817, 870, 875, 876 e 877, in linea con l'aggiornamento effettuato dal 
     TC434/EC-DIGITAL. Aggiunta all’interno della sezione Documentazione l’indicazione che questi codici tipo fattura addizionali possono essere trattati come sinonimi del codice 380 e quindi non richiedono una modifica nell’elaborazione;
     - Inserito il codice tipo fattura 0388. Aggiunta all’interno della sezione Documentazione l’indicazione che questo codice tipo fattura può essere trattato come sinonimo del codice 380 e quindi non richiede una modifica nell’elaborazione.

- **Cambiamenti alle code lists e artefatti di validazione – Altri processi (ordine, ordine con risposta, ordine pre-concordato e documento di trasporto)**
     - Aggiunta una regola con severità “warning” per la validazione del formato del “Swedish organisation numbers” (ICD/EAS 0007). La severità passerà a “fatal” con la Fall release 2022;
     - Corretto un errore che provocava la comparsa di errori in sede di caricamento/utilizzo di file di schematron in alcuni convertitori/tool di file XLS;
     - Modificata da “warning” a “fatal” la severità della regola PEPPOL-COMMON-R043 (ICD 0208) relativa alla validazione del formato del “Belgian organisation numbers”, come annunciato nella Fall release 2021;
     - Corretta la regola PEPPOL-T77-R001 che veniva erroneamente ignorata in casi di omissione dell’indicazione del periodo di validità;
     - Aggiunta una regola con severità “warning” per la validazione del formato del “Australian ABN” (ICD/EAS 0151). La severità passerà a “fatal” con la Fall release  2022;
     - Aggiunti i codici 0214, 0215 e 0216 alla codifica ICD e adeguati gli artefatti di validazione;
     - Aggiunti i codici 0147, 0170, 0188, 0215 e 0216 alla codifica EAS e adeguati gli artefatti di validazione;
     - Rimozione della ripetizione del codice TSP dalla codifica UNCL7143.
