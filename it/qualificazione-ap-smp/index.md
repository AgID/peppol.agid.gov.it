---
layout: page
title: Qualificazione AP/SMP
description:
lang: it
ref: qualificazione-ap-smp
order: 1
---
Procedura da seguire per sottoscrivere il Peppol Service Provider Agreement:

1. Eseguire l’iscrizione obbligatoria all’Associazione OpenPeppol AISBL, come indicato all’interno della sezione [Join](https://peppol.org/join/), compilando e **firmando digitalmente** il documento OpenPeppol Membership Application Form specificando il ruolo che si intende assumere: **Access Point (AP)** Provider o anche **Service Metadata Publisher (SMP) Provider**.;

      _Per ricoprire il ruolo di AP Provider è necessario registrarsi per il Post-Award Procurement Service Domain._
      _Per ricoprire il ruolo di SMP Provider è necessario registrarsi per il Addressing and Capability Lookup Service Domain._

2. Inviare via email il documento di cui al punto precedente all’indirizzo [membership@peppol.eu](mailto:membership@peppol.eu)

3. Compilare e firmare digitalmente il documento [Peppol Service Provider Agreement](https://peppol.agid.gov.it/attachments/PeppolServiceProviderAgreement_v4.0.1.pdf) e la Visura Camerale della società, o in alternativa la [Dichiarazione sostitutiva del certificato di iscrizione alla CCIAA](https://peppol.agid.gov.it/attachments/dichirazione_rea_compilabile_rev201812.pdf)

4. Inviare via PEC i documenti di cui al punto precedente all’indirizzo [protocollo@pec.agid.gov.it](mailto:protocollo@pec.agid.gov.it) specificando l’oggetto come segue: _[PEPPOL] richiesta di \*nomeSocietà\* per sottoscrizione accordo Peppol_

5. La Peppol Authority AGID svolge le verifiche sulla documentazione inviata e comunica l’esito delle stesse al contatto del Service Provider indicato nel Peppol Service Provider Agreement per ricevere le comunicazioni formali (Annex 3, pag. 23)

6. Inviare richiesta al Peppol Service Desk relativa al rilascio dei certificati digitali per lo svolgimento dei test, compilando il relativo [form](https://openpeppol.atlassian.net/servicedesk/customer/portal/1/group/1/create/13).

      _L’indirizzo mail indicato nel campo “Email confirmation to” della richiesta sarà censito da OpenPeppol come indirizzo di contatto del SP per le comunicazioni relative ai Certificati PKI di AP/SMP (es. notifica di scadenza dei certificati). Si consiglia di indicare l’indirizzo di contatto tecnico indicato nel Peppol Service Provider Agreement per ricevere le segnalazioni di support e security issue (Annex 3, pag. 23 dell’Agreement) e di utilizzare una mail di gruppo._

7. La Peppol Authority autorizza il rilascio dei certificati digitali per l’ambiente di test.

8. Effettuare il download e l’installazione dei certificati di test.

      _In caso di necessità di indicazioni relative alle modalità di recupero dei certificati di test è possibile fare riferimento alle informazioni fornite nel paragrafo 5. Recupero dei nuovi certificati della [Procedura per il rinnovo dei certificati Peppol](https://peppol-docs.agid.gov.it/manuali_utente/rinnovo_certificati_peppol)_

9. Eseguire i test e le verifiche di interoperabilità secondo le seguenti FASI sequenziali:
    - **FASE 1**: Qualificazione dei servizi base, da eseguire attraverso il completamento della suite “Accreditation” del [Peppol Testbed](https://www.testbed.peppol.org/). Al termine dei test, il SP comunica il relativo esito attraverso l’invio di una richiesta al Peppol Service Desk, compilando il relativo [form](https://openpeppol.atlassian.net/servicedesk/customer/portal/1/group/1/create/16)
    - **FASE 2**: (dopo il superamento della FASE1): Qualificazione dei servizi specifici per il contesto italiano, da eseguire attraverso l’esecuzione di una sessione completa di tutti i casi di test previsti dal processo di accreditamento degli Access Point afferenti alla Peppol Authority AGID. La sessione di test viene eseguita sulla [Piattaforma di Onboarding](https://peppol.agid.gov.it/it/qualificazione-ap-smp/piattaforma-onboarding/), la cui interfaccia viene descritte nel [manuale utente della Piattaforma di Onboarding](https://peppol-docs.agid.gov.it/manuali_utente/onboarding). Una volta completata con successo la sessione di test , il SP invia il documento contenente l’esito dei test alla Peppol Authority direttamente attraverso la <a href="https://peppol-onboarding.agid.gov.it/piattaforma-onboarding/" data-proofer-ignore>Piattaforma di Onboarding</a>.

10. La Peppol Authority svolge le verifiche sulla documentazione inviata e autorizza l’emissione dei certificati digitali per l’ambiente di produzione.

11. Effettuare il download e l’installazione dei certificati di produzione.

12. La Peppol Authority trasmette al Service Provider il documento Peppol Service Provider Agreement controfirmato digitalmente.

Si segnala che i certificati Peppol per l’ambiente di produzione hanno validità di due anni. Alla loro scadenza, il Service Provider dovrà procedere al loro rinnovo, seguendo la specifica [procedura per il rinnovo dei certificati Peppol](https://peppol-docs.agid.gov.it/manuali_utente/rinnovo_certificati_peppol) prevista da OpenPeppol.

In caso di necessità, è possibile richiedere ad OpenPeppol la modifica dell’indirizzo di contatto per le comunicazioni relative ai certificati PKI inviando una richiesta al Peppol Service Desk, compilando il relativo [form](https://openpeppol.atlassian.net/servicedesk/customer/portal/1/group/1/create/12) e indicando nel campo _Summary_ l’oggetto “Request for update of the email address for PKI Certificate”.

### Documenti allegati

- [PEPPOL Service Provider Agreement](/attachments/PeppolServiceProviderAgreement_v4.0.1.pdf)
- [Dichiarazione sostitutiva del certificato di iscrizione alla CCIAA](/attachments/dichirazione_rea_compilabile_rev201812.pdf)
- [Guida alla firma del nuovo Service Provider Agreement](/attachments/Guide_signing_agreement_V_1_0.pdf)