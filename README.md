<p align="center">
  <img src="docs/images/demo_facturx_en.png"
       alt="Factur-X invoice example — hybrid PDF with embedded XML (EN16931 compliant)"
       width="600">
</p>

> 🇬🇧 English | [🇫🇷 Français](./README_FR.md)

![License](https://img.shields.io/badge/License-LICENSE.md-lightgreen.svg)
![Factur-X](https://img.shields.io/badge/Invoice-Factur--X-151b1c?style=flat)
![Standard](https://img.shields.io/badge/EN16931-Comfort-0095b1?style=flat)
![Architecture](https://img.shields.io/badge/Type-System-0a5645?style=flat)
[![YouTube](https://img.shields.io/badge/YouTube-@Palks__Studio-FF0000?style=flat&logo=youtube&logoColor=white)](https://www.youtube.com/@Palks_Studio)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-@Palks__Studio-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/palks-studio/)
[![DEV.to](https://img.shields.io/badge/DEV.to-Technical%20Article-7C3AED?style=flat&logo=devdotto&logoColor=white)](https://dev.to/palks_studio/designing-a-factur-x-en16931-generator-from-business-data-to-a-hybrid-pdf-2ec5)
[![Factur-X Invoicing](https://img.shields.io/badge/Factur--X%20Invoicing-0095b1?style=flat)](https://palks-studio.com/en/facturx-invoice-generation)

<p align="center">
  <a href="https://palks-studio.com">
    <img src="https://img.shields.io/badge/Palks%20Studio-Website-0095b1?style=for-the-badge" />
  </a>
</p>

# Electronic Invoicing — Factur-X EN16931

> This repository is a technical presentation and demonstration of the system.  
> It does not contain downloadable source code or production files.

This project presents a real-world implementation of an electronic invoicing system  
capable of generating **Factur-X compliant invoices (EN16931 — Comfort profile)**.

The goal is not to showcase a library or a simple export,  
but to present a **complete, consistent and controlled system**  
for electronic invoice generation.

---

## Overview

The system enables:  

- generation of **hybrid PDF invoices (Factur-X)**  
- integration of a **structured XML compliant with EN16931**  
- full data consistency (lines, VAT, totals)  
- production of a single document, both human-readable and machine-readable

Each generated invoice is:  

- readable by humans (PDF)  
- processable by systems (embedded XML)  
- compliant with European interoperability requirements

[Access the Resource](https://palks-studio.com/en/facturx-invoice-generation)

For a deeper look, a technical article explores the design of the Factur-X generator, its architecture based on a shared data model, automated tax rule management, and the technical choices behind generating EN16931-compliant hybrid PDF/XML invoices without relying on a SaaS platform.

👉 [Designing a Factur-X EN16931 Generator: From Business Data to a Hybrid PDF](https://dev.to/palks_studio/designing-a-factur-x-en16931-generator-from-business-data-to-a-hybrid-pdf-2ec5) (DEV.to)

---

## Tax Compliance – VAT Legal Notices

The system automatically determines and applies the appropriate VAT legal notices based on the issuer's tax regime, the customer's location, their tax status, and the nature of the transaction.

Tax rules are configured according to the characteristics of the business and the types of transactions supported by the system.

The applicable legal notice is included in both the visible PDF and the embedded structured XML.

It is not entered manually: the system determines it based on the configured tax rules and the invoice data.

---

## Approach

This project follows a deliberately different approach compared to common solutions:  

- **no SaaS dependency**  
- **no critical third-party services**  
- **no isolated file export logic**

Factur-X compliance is treated as:  

> **a system-level property**, not as a standalone file output.

This ensures:  

- global data consistency  
- reproducible invoice generation  
- clean integration into real business workflows

---

## Demonstration

The demonstration highlights:  

- the final rendered Factur-X invoice  
- the hybrid structure (PDF + embedded XML)  
- usage within a real invoicing context

Simplified flow:  

```text
Input data → Controlled processing → Factur-X compliant PDF
```


---

## Positioning

This system is designed for:  

- freelancers and independent professionals  
- small and medium-sized businesses (SMEs)  
- internal invoicing systems  
- environments requiring EN16931 compliance

It fits into a broader approach of:  

- **autonomous invoicing systems**  
- **controlled infrastructure**  
- **no reliance on external platforms**

---

## What this repository shows

- a coherent electronic invoicing architecture  
- a system-level approach to Factur-X compliance  
- a real-world example of hybrid invoice generation

---

## What this repository does not show

For security and intellectual property reasons:  

- no XML generation logic  
- no validation pipelines (XSD / Schematron)  
- no internal processing scripts  
- no production architecture details

The purpose is to demonstrate capabilities,  
not to expose implementation.

---

## Compliance

Generated invoices comply with:  

- **EN16931 standard (Comfort profile)**  
- **Factur-X format (PDF with embedded XML)**  
- **PDF/A-3 archival requirements**

---

## Philosophy

This project reflects an engineering approach focused on:  

- simplicity  
- determinism  
- auditability  
- long-term reliability

The objective is not to multiply tools,  
but to build a system that is clear, stable and fully controlled.

---

## Need a compliance solution?

In the context of the ongoing electronic invoicing rollout in France,  
this kind of system can provide a solid foundation for a controlled and progressive compliance approach.

If you need a solution adapted to your business, a Factur-X EN16931 integration,  
or an autonomous invoicing system without SaaS dependencies, Palks Studio can help.

[![Contact](https://img.shields.io/badge/Contact-Palks%20Studio-0095b1?style=flat)](https://palks-studio.com/en/contact)

---

© Palks Studio — see LICENSE.md  
- https://palks-studio.com
