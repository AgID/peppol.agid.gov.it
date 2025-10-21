---
layout: post
title: Update to the PA's Single SMP regarding the registration functionality of Peppol Participant IDs with schemeID 0201 (IndicePA)
lang: en
ref: update-smp-single
excerpt_separator: <!--more-->
tags:
categories: news
permalink: /en/news/update-smp-single/
---
Please note that on September 26, 2025, an update was released on the Single Public Administration SMP (SMP Unico della PA) relating to the registration functionality of Peppol Participant IDs with schemeID 0201 (IndicePA).
<!--more-->
It is now possible to register a Peppol Participant ID for a PA using the Unique Code of an Office of the same registered on the IndicePA with the ability to receive electronic order documents and electronic delivery notes (DDT) via its own Peppol Access Point.

We would like to take this opportunity to remind you that **the method for registering a Participant ID** relating to a Unique Code of an IPA Office **for the receipt of electronic invoicing documents** (invoices and credit notes) **remains unchanged, via association on the IPA index of the Peppol channel** and indication of the code from the chosen Access Point.

Specifically, the steps for associating the Peppol channel with each billing office are:

    -within the IPA modification form, the Entity must set the Intermediary field to “Yes”
    -enter the identification code of the Peppol Access Point used by the Entity in the “CanalePeppol” field.

The identifier consists of four alphanumeric characters, the string “AP” followed by two numeric characters, and is assigned to the Service Provider by the Italian Peppol Authority upon certification by AgID.