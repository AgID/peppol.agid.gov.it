---
layout: page
title: FAQ
description: 
lang: it
ref: faq
order: 2
child_of_ref: chi-siamo
---

**FAQ 1 - Come faccio ad avere un Participant ID PEPPOL?**

Se volete accreditarvi su rete PEPPOL, come prima cosa, dovete scegliere un intermediario PEPPOL. Per intermediario PEPPOL si intende l'Access Point che farà da tramite tra voi e gli Access Point degli altri membri della rete PEPPOL con cui intendete scambiare documenti. È l'intermediario che vi assegnerà un Participant ID PEPPOL, ovvero l'identificativo univoco sulla rete che rappresenta l'indirizzo elettronico a cui vengono associate le tipologie di documento che il soggetto è in grado di ricevere.

Preferibilmente il soggetto (es. Operatore economico o PA) ha uno e un solo Participant Id PEPPOL, ottenuto la prima volta che viene registrato sulla rete.

**FAQ 2 - Qual è il formato di un Participant ID PEPPOL?**

In Italia per i Participant ID PEPPOL sono in uso le seguenti codifiche:

- 0211:ITpartitaIVA (per operatori economici)

- 0210:CodiceFiscale (per operatori economici)

- 0201:CodiceIPA (per Pubbliche Amministrazioni)

Oltre a queste, sono ammesse le codifiche internazionali elencate nella codelist dei Participant Identifier Schemes [pubblicata da PEPPOL](https://docs.peppol.eu/edelivery/codelists/).

**FAQ 3 - Che cos'è un intermediario PEPPOL?**

L'intermediario PEPPOL è il fornitore dei servizi di Access Point, qualificato nella rete PEPPOL, che trasmette e riceve i documenti per conto del Participant nel rispetto delle specifiche di interoperabilità. Nella rete PEPPOL sia il mittente che il destinatario sono connessi ad un proprio Access Point.

**FAQ 4 - Come posso procurarmi un intermediario PEPPOL?**

Per avvalersi di un intermediario PEPPOL è necessario sottoscrivere un contratto di servizio per l'accesso alla rete con un Service Provider tra quelli certificati da PEPPOL ed attivare le modalità di connessione più idonee alle proprie esigenze.

**FAQ 5 - Come posso diventare un intermediario certificato PEPPOL?**

Per diventare intermediario certificato PEPPOL nel dominio italiano, è necessario seguire la procedura di onboarding prevista da AgID e disponibile [qui](/it/qualificazione-ap-smp/).

**FAQ 6 - Dove trovo l'elenco degli intermediari PEPPOL?**

Sono disponibili due elenchi di intermediari certificati:

- [Elenco completo degli intermediari PEPPOL](https://peppol.org/members/full-members-list/)

- [Elenco degli intermediari PEPPOL certificati dalla PEPPOL Authority Italiana (AGID)](https://peppol.agid.gov.it/it/qualificazione-ap-smp/elenco-ap-smp/)

**FAQ 7 - Una volta scelto un Intermediario, posso cambiarlo?**

È sempre possibile cambiare il proprio intermediario. A seguito della scelta, il Participant Id del soggetto deve essere migrato dal vecchio al nuovo intermediario, concordando le modalità e i tempi.

**FAQ 8 - Cos'è un Access Point PEPPOL?**

L’Access Point è il punto di accesso alla rete PEPPOL. E’ il componente infrastrutturale della rete che permette all’Ente/Operatore economico di collegarsi in interoperabilità all’infrastruttura di rete e consentire l’accesso ai servizi offerti da Peppol, sia per la trasmissione che per la ricezione dei documenti informatici.

**FAQ 9 - Cos'è un Service Metadata Publisher Provider?**

Un Service Metadata Publisher Provider è un fornitore, certificato PEPPOL, del servizio che ha il compito di registrare i Participant sulla rete PEPPOL e associa a ciascuno di essi le tipologie di documento che è in grado di ricevere (es. fatture, ordini, etc...).

**FAQ 10 - Come posso diventare Service Metadata Publisher Provider?**

Per diventare Service Metadata Publisher Provider nel dominio italiano è necessario seguire la procedura di onboarding prevista da AgID e disponibile [qui](/it/qualificazione-ap-smp/).

**FAQ 11 - Quale è il vantaggio di iscrivermi a PEPPOL?**

Aderire alla rete PEPPOL consente ai soggetti di poter gestire tutti i documenti del ciclo degli acquisti (Ordine, Documenti di Trasporto e Fattura) utilizzando il medesimo formato e la medesima infrastruttura di trasporto tra cliente e fornitore adoperata sia in ambito nazionale, sia in ambito europeo e internazionale.

**FAQ 12 - Qual è il formato dei documenti PEPPOL?**

I documenti PEPPOL utilizzano il formato UBL XML.

**FAQ 13 - Cos'è il formato UBL XML?**

Si tratta di un [formato standard universale per i documenti commerciali](https://www.oasis-open.org/committees/tc_home.php?wg_abbrev=ubl). L'utilizzo cui è destinato viene suggerito già dal suo nome: **UBL sta per Universal business language, mentre XML individua il formato documentale**. La sua realizzazione è il risultato di una collaborazione a livello internazionale volta proprio a individuare una libreria di documenti standard XML, per facilitare gli scambi e contribuire all'interoperabilità dei sistemi

**FAQ 14 - Di quali elementi si compone PEPPOL?**

PEPPOL si basa su tre elementi fondamentali:

- **eDelivery Network** -- l'infrastruttura di rete vera e propria;

- **PEPPOL BIS**, Business interoperability specifications -- le specifiche tecniche necessarie per garantire l'interoperabilità nello scambio dei documenti commerciali e fiscali;

- **PEPPOL TIA**, Transport infrastructure agreements -- le regole per l'utilizzo dell'infrastruttura di rete.

Per approfondimenti è possibile consultare la pagina [*Cos'è PEPPOL*](/it/chi-siamo/cos-e-peppol/).

**FAQ 15 - Cosa devo comunicare alla Pubblica Amministrazione per ricevere gli ordini?**

L'unico elemento da comunicare è il proprio Participant ID PEPPOL.

**FAQ 16 - Con che cadenza scadono i certificati Peppol per l’ambiente di produzione? Come si possono rinnovare?**

I certificati hanno una validità di due anni. In prossimità della loro scadenza, il punto di contatto tecnico del Service Provider riceverà una comunicazione automatica di avviso e dovrà avviare il processo di rinnovo, seguendo la [procedura per il rinnovo](https://peppol-docs.agid.gov.it/manuali_utente/rinnovo_certificati_peppol) prevista da OpenPeppol.

**FAQ 17 - La fatturazione elettronica Peppol da e verso l'Italia**

Nelle comunicazioni su rete Peppol, il mittente e il destinatario sono individuati da identificativi Peppol (ParticipantID), che devono essere riportati anche sul documento di fatturazione elettronica trasmesso.

Per ottenere un identificativo Peppol è necessario avvalersi di un intermediario che fornisca i servizi di Access Point (AP) Peppol e che effettui la registrazione del participanti ID del destinatario dei documenti su un SMP PEPPOL.

La lista dei Service Provider qualificati come Access Point Provider da AgID è disponibile al seguente [link](https://peppol.agid.gov.it/it/qualificazione-ap-smp/elenco-ap-smp/).

Un mittente straniero può inviare una fattura elettronica ad un destinatario italiano tramite l'infrastruttura di rete Peppol, rispettando le specifiche Peppol specializzate per l’Italia dall'Agenzia dell'Italia Digitale e disponibili al seguente [link](https://peppol-docs.agid.gov.it/docs/my_index_fatt.jsp).

Se il destinatario è una PA, per la ricezione della fattura elettronica tramite la rete Peppol è necessario che la PA si avvalga di un Service Provider che sia contemporaneamente qualificato come Access Point Provider da AgID ed intermediario accreditato del [Sistema di Interscambio dell’Agenzia delle Entrate](https://www.fatturapa.gov.it/it/sistemainterscambio/) e che la PA abbia configurato il canale di ricezione Peppol per gli uffici di fatturazione elettronica sull’Indice delle Pubbliche Amministrazioni (iPA).

Qualsiasi mittente italiano che si avvale di un Service Provider qualificato come Access Point da AgID è in grado di inviare fatture elettroniche verso soggetti esteri registrati sull'infrastruttura di rete Peppol, nel rispetto delle Specifiche Peppol rilevanti nel paese del destinatario del documento.

Non è necessario un ulteriore onboarding  da parte del Service Provider Peppol per l'invio e la ricezione di fatture elettroniche da e verso l'Italia attraverso l'infrastruttura di rete Peppol.