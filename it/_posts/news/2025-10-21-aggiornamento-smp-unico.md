---
layout: post
title: Aggiornamento SMP Unico della PA relativo alla funzionalità di registrazione di Participant ID Peppol con schemeID 0201 (IndicePA)
lang: it
ref: aggiornamento-smp-unico
excerpt_separator: <!--more-->
tags:
categories: news
permalink: /it/news/aggiornamento-smp-unico/
---
Si comunica che in data 26 settembre 2025 è stato rilasciato un aggiornamento sull’SMP Unico della PA relativo alla funzionalità di registrazione di Participant ID Peppol con schemeID 0201 (IndicePA).
<!--more-->
È ora possibile registrare un Participant ID Peppol di una PA a partire dal Codice Univoco di un Ufficio della stessa censito sull’IndicePA con la capacità di ricezione dei documenti di ordinazione elettronica e di consegna elettronica (DDT) tramite il proprio Access Point Peppol.

Si coglie l’occasione per ricordare che **resta inalterata la modalità di registrazione di un Participant ID** relativo ad un Codice Univoco di un Ufficio IPA **per la ricezione dei documenti di fatturazione elettronica** (fatture e note di credito) **tramite l'associazione sull'indice IPA del canale Peppol** e l'indicazione del codice dall'Access Point scelto.

Nello specifico, i passi per l'associazione del canale Peppol a ciascun ufficio di fatturazione sono:

    -all’interno della maschera di modifica IPA, l’Ente deve valorizzare il campo Intermediario a “Sì”
    -inserire nel campo “CanalePeppol” il codice Identificativo dell’Access Point Peppol utilizzato dall’Ente.

L’identificativo è composto da quattro caratteri alfanumerici, la stringa “AP” seguita da due caratteri numerici, e viene attribuito al Service Provider dalla Peppol Authority Italiana all’atto della Certificazione da parte di AgID.