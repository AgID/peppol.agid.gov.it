---
layout: page
title: About PEPPOL
description: 
lang: en
ref: about-peppol
order: 3
---

The Pan-European Public Procurement Online (PEPPOL) began as a project initiative 
on the subject of digital purchases promoted by the European Commission in the period 
between 2008 and 2012.

At the end of the project the OpenPEPPOL association took over the governance of the fundamental components of the system.
PEPPOL is a set of infrastructural elements and technical specifications promoted by the European Commission in the context 
of the CEF initiatives and which make interoperability between the various e-procurement systems possible, cross-border.
The fundamental components of the system are: the PEPPOL eDelivery Network network infrastructure, the specifications 
for the interoperability of the PEPPOL Business Interoperability Specifications (BIS) business documents, 
the agreements regulating the use of the PEPPOL Transport Infrastructure Agreements (TIA) network .

AGID coordinates the activities aimed at the adoption of e-Procurement in the public sector 
and defines the technical rules for the interoperability of the systems involved.

With the Circular letter n. 3 of 6 December 2016, which defines the additional technical 
rules to guarantee the communication and sharing of data between the electronic purchasing 
and trading systems, AGID has introduced PEPPOL as a reference architecture to guarantee 
interoperability in public e-Procurement.


## How does PEPPOL work?

PEPPOL is based on a 4 corner architecture that interconnects the subjects that exchange documents in one of the phases of e-Procurement. The 4 corners specifically represent:

- Corner 1: the sender of the document
- Corner 2: the PEPPOL Access Point (AP) to which the sender is connected
- Corner 3: the PEPPOL AP to which the recipient is connected
- Corner 4: the recipient of the document

The interactions between the 4 corners are depicted in the image below, where the Service Metadata Publisher (SMP) is the node that allows to identify the Access Point on which the recipient is registered and to verify his real willingness to receive a particular type of document (for example, Order or Invoice in the PEPPOL format).

![How does PEPPOL work]({{ site.baseurl }}/assets/images/come-funziona-peppol.png)