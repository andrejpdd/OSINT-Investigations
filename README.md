# OSINT-Investigations
Open-Source Intelligence (OSINT), Financial Crime Analysis &amp; AML/KYB Case Studies | Inteligência de Fontes Abertas, Prevenção a Fraudes e Compliance Financeiro.
# 🛡️ OSINT, Threat Intelligence & Financial Fraud Analysis Portfolio

**Author:** André Almeida — Civil Police Investigator (PCSP - 10+ years) | Law Student (UNICID) | B.A. in Social Communication (USJT)  
**Focus Areas:** Open-Source Intelligence (OSINT), Anti-Money Laundering (AML), Know Your Business (KYB), Digital Forensics & Corporate Risk Mitigation.

---

## 🇺🇸 English Overview

Welcome to my technical repository. This space consolidates forensic case studies on cyber fraud typologies, payment artifact reverse engineering, and KYB/AML onboarding vulnerabilities based on real-world investigations in Brazil.

All whitepapers strictly follow the **Parallel Construction** methodology, relying exclusively on public records and open-source telemetry, with full PII sanitization in compliance with the Brazilian General Data Protection Law (LGPD - Law 13.709/2018) and international investigative ethics (ACFE / INTERPOL).

### 📂 Published Whitepapers & Case Studies

#### 1. [Case Study #01] Low-Complexity Digital Scams: OSINT & Verification Failures in "Money Mule" MEI Accounts
* 📄 **File:** `Case_01_OSINT_Money_Mule_MEI_PT_EN.pdf` *(Bilingual: PT-BR pages 1–2 | EN-US pages 3–4)*
* **Summary:** Investigation of a social engineering attack (ticket scam via sock puppet) where illicit Pix funds (R$ 1,600.00) were routed through a corporate "Money Mule" account (MEI).
* **Technical Highlights:**
  * Cross-referencing corporate registry emails across e-commerce and tech forums (Data Lake to Data Silo funneling).
  * Extraction of Google Account ID metadata and geolocation convergence via public Google Maps reviews in the South Zone of São Paulo.
  * Identification of severe KYB gaps: incompatible R$ 70,000.00 share capital and transactional behavior mismatch (food service CNAE processing entertainment sales).

#### 2. [Case Study #02] Legal Impersonation Fraud (Pretexting), High-Velocity Smurfing & KYB Failures
* 📄 **Files:** `Case_02_OSINT_Legal_Pretexting_AML_EN.pdf` *(English)* | `Case_02_OSINT_Legal_Pretexting_AML_PT.pdf` *(Portuguese)*
* **Summary:** Forensic analysis of an advanced social engineering operation simulating a judicial hearing on Google Meet, coercing the victim into contracting a R$ 50,000.00 bank loan followed by self-to-self transfers and multi-layered money mule dispersion.
* **Technical Highlights:**
  * **Critical KYB Failure:** Identification of a primary shell company (MEI) opened 5 days prior to the attack with a declared share capital of **R$ 90,000,000.00** (vs. R$ 81,000.00 legal cap) at a physically non-existent building number (No. 100,000 on a 130-meter street).
  * **Digital Footprinting:** Operator tracking via immutable Google GAIA ID (`115490095041130798647`) and credential correlation (Epieos / Holehe), plus serial shell company links via shared registration emails.
  * **Payment Reverse Engineering:** Technical decoding of Pix EMV payloads (BR Code Tags 26, 54, 59/60, CRC16), random EVP/UUID keys, Tax Region CPF attribution (9th digit analysis), and FEBRABAN bank slip barcodes.
  * **Velocity, Smurfing & MED Containment:** Analysis of 8 split transfers (R$ 14,889.97 total) executed within 6 minutes (16:00–16:06) to bypass Transaction Monitoring, and full fund preservation via the Central Bank of Brazil's Special Return Mechanism (MED - BCB Resolution No. 103/2021).

---

## 🇧🇷 Visão Geral em Português

Este repositório reúne estudos de caso técnicos sobre tipologias de fraude financeira, engenharia reversa de artefatos de pagamento (Pix/Boletos) e vulnerabilidades de *onboarding* (KYC/KYB), elaborados a partir de investigações reais.

Todos os relatórios adotam a metodologia de **Construção Paralela (*Parallel Construction*)**, utilizando estritamente dados abertos (OSINT) e registros públicos, com pseudonimização completa de dados pessoais em conformidade com a LGPD (Lei 13.709/2018) e padrões éticos da ACFE e INTERPOL.

* **Estudo de Caso #01 (`Case_01_OSINT_Money_Mule_MEI_PT_EN.pdf`):** Mapeamento de pegada digital (Google ID e reutilização de credenciais) e análise de falhas de *Due Diligence* em contas MEI "laranjas" com desvio de finalidade de CNAE e capital social incompatível.
* **Estudo de Caso #02 (`Case_02_OSINT_Legal_Pretexting_AML_PT.pdf`):** Engenharia reversa de fraude de falso advogado/audiência judicial simulada, expondo anomalias críticas na Redesim (MEI com R$ 90 milhões de capital social e endereço inexistente), rastreamento via Google GAIA ID, decodificação de *payloads* EMV de Pix, fracionamento de alta velocidade (*Smurfing*) e contenção via MED do Banco Central.
