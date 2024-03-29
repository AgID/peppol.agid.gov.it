---
layout: page
title: FAQ
description: 
lang: en
ref: faq
order: 2
child_of_ref: chi-siamo
---

**FAQ 1 - How can I obtain a PEPPOL Participant ID?**

If you want to be accredited on the PEPPOL network, first of all, you must choose a PEPPOL intermediary. By a PEPPOL intermediary we mean the Access Point that will act as an intermediary between you and the Access Points of the other members of the PEPPOL network with whom you intend to exchange documents. It is the intermediary who will assign you a PEPPOL Participant ID, that is the unique identifier on the network that represents the electronic address to which the types of documents that the subject is able to receive are associated.

Preferably the subject (e.g. the economic operator or the public administration) has one and only one PEPPOL Participant ID, obtained the first time it is registered on the network.

**FAQ 2 - Which is the format of a PEPPOL Participant ID?**

In Italy, the following codes are used for PEPPOL Participant IDs:

-   0211:ITpartitaIVA (for economic operators)

-   0210:CodiceFiscale (for economic operators)

-   0201:CodiceIPA (for Public Administrations)

In addition to these codes, the international codes listed in the Participant IDentifier Schemes codelist [published by PEPPOL](https://docs.peppol.eu/edelivery/codelists/) are allowed.

**FAQ 3 - What is a PEPPOL intermediary?**

The PEPPOL intermediary is the Access Point service provider, qualified in the PEPPOL network, which transmits and receives documents on behalf of the Participant in compliance with the interoperability specifications. In the PEPPOL network, both the sender and the receiver are connected to their own Access Point.

**FAQ 4 - How can I obtain a PEPPOL intermediary?**

To use a PEPPOL intermediary it is necessary to sign a service contract for access to the network with a Service Provider (to be chosen amongst those certified by PEPPOL) and activate the connection methods most suitable for your needs.

**FAQ 5 - How can I become a PEPPOL certified intermediary?**

To become a PEPPOL certified intermediary in the Italian domain, it is necessary to follow the onboarding procedure provided by AgID and available [here](/en/qualification-ap-smp/).

**FAQ 6 - Where can I find the list of PEPPOL intermediaries?**

Two lists of certified intermediaries are available:

-   [Full list of PEPPOL intermediaries](https://peppol.org/members/full-members-list/)

-   [List of PEPPOL intermediaries certified by the Italian PEPPOL Authority (AGID)](https://peppol.agid.gov.it/it/qualificazione-ap-smp/)

**FAQ 7 - Once I have chosen an intermediary, can I change it?**

It is always possible to change one's intermediary. Following the choice, the Participant ID of the subject must be migrated from the old to the new intermediary, by agreeing on the methods and times.

**FAQ 8 - What is a PEPPOL Access Point?**

A PEPPOL Access Point is the access point to the PEPPOL network. It is the infrastructural component of the network that allows the Public Entity or Economic Operator to connect to the network infrastructure and to allow access to the services offered by PEPPOL, both for the transmission and for the receipt of digital documents.

**FAQ 9 - What is a Service Metadata Publisher Provider?**

A Service Metadata Publisher Provider is a PEPPOL-certified service provider who is in charge of registering Participants on the PEPPOL network and associating each of them with the types of documents it is able to receive (e.g. invoices, orders, and so on).

**FAQ 10 - How can I become a Service Metadata Publisher Provider?**

To become a Service Metadata Publisher Provider in the Italian domain it is necessary to follow the onboarding procedure provided by AgID and available [here](/en/qualification-ap-smp/).

**FAQ 11 - Which is the advantage of joining PEPPOL?**

Joining the PEPPOL network allows parties to be able to manage all the documents of the purchasing cycle (Order, Transport Documents and Invoice) using the same format and the same transport infrastructure between customer and supplier both within nation borders and at the European/international level.

**FAQ 12 - Which is the format of PEPPOL documents?**

PEPPOL documents use the UBL XML format.

**FAQ 13 - What is the UBL XML format?**

The UBL XML format is a [universal standard format for business documents](https://www.oasis-open.org/committees/tc_home.php?wg_abbrev=ubl). Its intended use is already suggested by its name: UBL stands for Universal Business Language, whilst XML identifies the document format. Its implementation is the result of an international collaboration aimed at identifying a library of standard XML documents, to facilitate exchanges and contribute to system interoperability.

**FAQ 14 - On which elements is PEPPOL based on?**

PEPPOL is based on three fundamental elements:

-   **eDelivery Network** - the core network infrastructure;

-   **PEPPOL BIS**, Business interoperability specifications - the technical specifications necessary to ensure interoperability in the exchange of commercial and tax documents;

-   **PEPPOL TIA**, Transport infrastructure agreements - the rules for using the network infrastructure.

**FAQ 15 - What do I have to communicate to the Public Administration to receive orders?**

The only thing to communicate is your PEPPOL Participant ID.

**FAQ 16 - How often do Peppol certificates for the production environment expire? How can they be renewed?**

Certificates are valid for two years. As their expiry approaches, the Service Provider's technical contact point will receive an automatic notice and will have to start the renewal process, following the [renewal procedure](https://peppol-docs.agid.gov.it/manuali_utente/rinnovo_certificati_peppol) provided by OpenPeppol

**FAQ 17 - Peppol electronic invoicing to and from Italy**

In Peppol network communications, the sender and the recipient are identified by Peppol identifiers (ParticipantIDs), which must also be reflected on the transmitted electronic billing document .

In order to obtain a Peppol identifier, it is necessary to use an intermediary that provides Peppol Access Point (AP) services and performs the registration of the participant ID of the recipient of the documents on a PEPPOL SMP.

The list of Service Providers qualified as Access Point Providers by AgID is available at the following [link](https://peppol.agid.gov.it/it/qualificazione-ap-smp/elenco-ap-smp/).

A foreign sender can send an electronic invoice to an Italian recipient via the Peppol network infrastructure, respecting the Peppol specifications specialized for Italy by the Agenzia dell'Italia Digitale and available at the following [link](https://peppol-docs.agid.gov.it/docs/my_index_fatt.jsp).

If the recipient is a PA, for the receipt of the e-invoice via the Peppol network it is necessary that the PA uses a Service Provider that is simultaneously qualified as an Access Point Provider by AgID and an accredited intermediary of the [Revenue Agency's Interchange System](https://www.fatturapa.gov.it/it/sistemainterscambio/) and that the PA has configured the Peppol reception channel for e-invoicing offices on the Index of Public Administrations (iPA).

Any Italian sender using a Service Provider qualified as an Access Point by AgID is able to send e-invoices to foreign entities registered on the Peppol network infrastructure, subject to the relevant Peppol Specifications in the country of the document recipient.

No additional onboarding by the Peppol Service Provider is required for sending and receiving e-invoices to and from Italy via the Peppol network infrastructure.