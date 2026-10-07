# Hi, I'm Kristian Jay Eñaga 👋

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kristian-jay-e%C3%B1aga-85345741a/) [![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kchanchan2357@gmail.com)

## GTM Systems & AI Automation Engineer
**Location:** Zamboanga Sibugay, Philippines (UTC+8) | **Email:** [kchanchan2357@gmail.com](mailto:kchanchan2357@gmail.com) | **GitHub:** [@kristian-enaga](https://github.com/kristian-enaga) | **LinkedIn:** [kristian-jay-eñaga](https://www.linkedin.com/in/kristian-jay-e%C3%B1aga-85345741a/)


---

## 📑 Table of Contents
- [Professional Summary](#professional-summary)
- [Technical Skills Matrix](#technical-skills-matrix)
- [Professional Experience](#professional-experience)
- [Quick Recruiter Audit](#quick-recruiter-audit)
- [Core Production Systems](#core-production-systems)
  - [📤 B2B Outbound Prospecting & Engagement](#-b2b-outbound-prospecting--engagement)
    - [1. Automated B2B Outbound Prospecting Engine](#1-automated-b2b-outbound-prospecting-engine)
    - [2. Autonomous Job Intelligence & High-Intent Outreach Engine](#2-autonomous-job-intelligence--high-intent-outreach-engine)
  - [📥 B2B Inbound Lead Acceleration & Qualification](#-b2b-inbound-lead-acceleration--qualification)
    - [3. Fault-Tolerant Lead Triage & Self-Healing CRM Pipeline](#3-fault-tolerant-lead-triage--self-healing-crm-pipeline)
    - [4. Enterprise Inbound Lead Sanitizer & Outreach Engine](#4-enterprise-inbound-lead-sanitizer--outreach-engine)
    - [5. AI Lead Scoring & Priority Router](#5-ai-lead-scoring--priority-router)
    - [6. Instant Speed‑to‑Lead Alert & CRM Ingestion](#6-instant-speedto-lead-alert--crm-ingestion)
  - [🧾 Accounts Payable Automation & Financial Control](#-accounts-payable-automation--financial-control)
    - [7. Automated Accounts Payable Invoice Parsing & ERP Sync](#7-automated-accounts-payable-invoice-parsing--erp-sync)
  - [🛒 E‑Commerce & Revenue Operations](#-ecommerce--revenue-operations)
    - [8. Autonomous Revenue Recovery Engine (E‑Commerce)](#8-autonomous-revenue-recovery-engine-ecommerce)
  - [🛡 Infrastructure & System Resilience](#-infrastructure--system-resilience)
    - [9. n8n Centralized Error Handler & Fail‑Safe](#9-n8n-centralized-error-handler--fail-safe)

---
## Professional Summary

Architect and Systems Integration Engineer specializing in Go-To-Market (GTM) execution, RevOps automation, and production-grade AI pipeline infrastructure. Expert in designing fault-tolerant data pipelines that seamlessly integrate CRMs, enrichment engines, and multi-channel outreach platforms. 

- **Data Integrity & Systems Resilience:** Eliminate dropped leads and silent execution crashes by enforcing Zod schema gates, Dead-Letter Queues (DLQs), automated exponential retries, and rate-limit buffers.
- **Operational Efficiency:** Reclaim 15+ hours per rep weekly by automating multi-step prospecting, inbound lead scoring, data normalization, and accounts payable workflows.
- **AI & Cost Optimization:** Implement JS/RegEx payload cleansing and dual-LLM fallback architectures (Gemini / Groq / OpenAI / OpenRouter) to reduce LLM API spend by up to 70%.

---

## Technical Skills Matrix

| Category | Skills & Technologies |
| :--- | :--- |
| **Automation Platforms** | n8n (Self-Hosted/Cloud), Make.com, Zapier |
| **GTM & CRM Stack** | Clay, HubSpot CRM, QuickBooks Online, Slack, WhatsApp Business API |
| **AI Models & Orchestration** | Google Gemini API, OpenAI API, Groq, OpenRouter, Prompt Engineering, Structured Outputs (Zod) |
| **Data & Infrastructure** | REST APIs, Webhooks, PostgreSQL, Supabase (DLQ), JavaScript (ES6+), JSON, RegEx |
| **Scraping & Ingestion** | Apify, SerpAPI, Webhook Listeners, E.164 Phone Normalization |
| **Reliability & Monitoring** | Dead-Letter Queues (DLQs), Idempotency Keys, Error Handling, Human-In-The-Loop (HITL) Gates |

---

## Professional Experience

### GTM Systems & AI Automation Engineer (Contract & Independent Projects)
*June 2026 – Present*

- **Designed & Deployed Production GTM Engines:** Built 9 end-to-end self-healing automation workflows for lead acquisition, CRM enrichment, speed-to-lead routing, revenue recovery, and accounts payable reconciliation.
- **Enforced Fault-Tolerant Data Pipelines:** Implemented Supabase/Postgres Dead-Letter Queues (DLQs) and failover logic to capture unhandled exceptions, guaranteeing 100% lead and transaction logging during 5xx server downtime or API rate-limit errors.
- **Optimized Speed-to-Lead Operations:** Decreased inbound lead contact time from hours to under 5 seconds by normalizing schema payloads, qualifying lead intent via AI scoring, and auto-dispatching high-priority alerts to sales teams via Slack.
- **Built Cost-Effective Token Optimization Strategies:** Engineered client-side JS RegEx payload cleansers prior to LLM processing, reducing API token usage and operational overhead by ~70%.


## ⚡ Quick Recruiter Audit
- **Role Target:** GTM Systems & AI Automation Engineer (RevOps / Pipeline Infrastructure)
- **Core Stack:** Clay, HubSpot CRM, n8n, Make, REST APIs/Webhooks, PostgreSQL/Supabase, Gemini/OpenAI APIs
- **Architecture Standards:** Zod Schema Gates, Dead-Letter Queues (DLQs), Dual-LLM Fallbacks, Rate-Limit Buffers
- **Location & Shift:** Zamboanga Sibugay, Philippines (UTC+8) | Full US Overlap (8 PM–12 AM PST / Flexible)
- **Availability:** Open for Full-Time Remote Roles, Contract Engagements, & Fractional GTM Systems Work

  
---

## Core Production Systems

### 📤 B2B Outbound Prospecting & Engagement

#### 1. [Automated B2B Outbound Prospecting Engine](https://github.com/kristian-enaga/Automated-B2B-Outbound-System)

<img width="1920" height="1079" alt="image" src="https://github.com/user-attachments/assets/f8bae866-2e23-453a-969b-00af5d0125f5" />

- **What it does:** End‑to‑end outbound: scraping → AI copy → HITL approval → send → logging.  
- **Architecture:** Apify scraping, Gemini email copy, Slack Human‑in‑the‑Loop (HITL) approvals, fault‑tolerant logging.  
- **Outcome:** Reclaims ~70% of rep prospecting time; protects domain deliverability with HITL gates. 
- 🎬 [Watch 4‑min Loom Demo](https://www.loom.com/share/5d3416feda7148bbbd60704ab9b5976e)

#### 2. [Autonomous Job Intelligence & High‑Intent Outreach Engine](https://github.com/kristian-enaga/autonomous-job-lead-engine)

<img width="1920" height="1079" alt="image" src="https://github.com/user-attachments/assets/45d2710a-a5f8-4711-a56d-227eeda4fb19" />

- **What it does:** Finds high‑intent job leads, validates pages, extracts tokens, drafts outreach, and sends via HITL.  
- **Architecture:** SerpAPI ingestion, pre‑flight 404/duplicate checks, JS RegEx HTML token optimization (~70% cost reduction), Gemini + Groq failover, Zod schema validation, DLQ, Telegram HITL 1‑click approvals.  
- **Outcome:** Automates 10+ hours/week of manual sourcing/audits; zero CRM data corruption via strict schema gates.  
- 🎬 [Watch 4‑min Loom Demo](https://www.loom.com/share/7792580657284a58a7e1dabf99365087)

---

### 🤝 Nearbound & Partner Signal Operations

*Section ready for upcoming Nearbound & Ecosystem Integration workflows.*

---

### 📥 B2B Inbound Lead Acceleration & Qualification

#### 3. [Fault-Tolerant Lead Triage & Self-Healing CRM Pipeline](https://github.com/kristian-enaga/fault-tolerant-lead-triage-pipeline)

<img width="1920" height="1079" alt="Fault-Tolerant Lead Triage Pipeline" src="https://raw.githubusercontent.com/kristian-enaga/fault-tolerant-lead-triage-pipeline/main/fault-tolerant-lead-triage-architecture.png" />

- **What it does:** Zero-downtime inbound lead processing engine that cleanses raw webhooks, scores intent via dual-LLM (Gemini/Groq) routing, updates HubSpot, and alerts Slack instantly.
- **Architecture:** Webhook intake → Payload sanitization & regex cleansing → Gemini AI / Groq fallback scoring → Idempotent HubSpot CRM upsert → Supabase DLQ failover backup → Real-time Slack priority alert.
- **Outcome:** Eliminates dropped leads from API rate limits or 5xx crashes, guarantees 100% data retention via DLQ, and drives sub-60s speed-to-lead for high-priority prospects.
- 🎬 [Watch 3-min Loom Demo](https://www.loom.com/share/5d9a49197b574216894cc00822f0069f)

#### 4. [Enterprise Inbound Lead Sanitizer & Outreach Engine](https://github.com/kristian-enaga/Inbound-Lead-Sanitizer-Engine)

<img width="1920" height="1079" alt="image" src="https://github.com/user-attachments/assets/6364334f-f66b-45db-9b89-3bf2e34e49d0" />

- **What it does:** Sanitizes inbound leads, filters bots, scores intent, syncs to HubSpot, and routes to Slack/WhatsApp.  
- **Architecture:** Sub‑5s E.164 phone normalization, bot filtering, Gemini AI intent scoring, HubSpot sync, dynamic Slack/WhatsApp routing.  
- **Outcome:** 100% invalid CRM entries blocked; response SLA from hours → sub‑5 seconds.
- 🎬 [Watch 4‑min Loom Demo](https://www.loom.com/share/c38d37d65eed44129a712e530a8e2446)

#### 5. [AI Lead Scoring & Priority Router](https://github.com/kristian-enaga/AI-Lead-Scoring-Router)

<img width="1920" height="1079" alt="AI Lead Scoring Architecture" src="https://github.com/kristian-enaga/AI-Lead-Scoring-Router/blob/main/n8n-ai-lead-scoring-production-architecture.png?raw=true" />

- **What it does:** Real-time automated triage of inbound leads by budget, company size, and urgency using Google Gemini AI with OpenRouter fallback, instantly splitting VIP enterprise prospects from low-priority inquiries.
- **Architecture:** Webhook intake & payload extraction → Supabase DLQ raw lead backup → Google Gemini AI scoring + OpenRouter fallback → Schema validation & parameter merge → Multi-tier IF router (Slack alerts for VIPs / Automated Gmail replies for standard leads) → Centralized Google Sheets CRM sync.
- **Outcome:** Eliminates 70% of manual lead review time, saves 15+ hours/week of qualification work, guarantees zero lead loss via DLQ persistence, and routes high-value prospects instantly.
- 🎬 [Watch 3-min Loom Demo](https://www.loom.com/share/38164c8a840f4076b3ac0ec62a26e3ce)

#### 6. [Instant Speed‑to‑Lead Alert & CRM Ingestion](https://github.com/kristian-enaga/Speed-to-lead-ingestion-engine)

<img width="1920" height="1079" alt="image" src="https://github.com/user-attachments/assets/93e85a03-7418-4415-a602-1dcdc57bd49a" />

- **What it does:** Ingests webhook leads, normalizes schema, syncs to Google Sheets CRM, and fires instant Slack alerts.  
- **Architecture:** Webhook ingestion → schema normalization → Sheets sync → Slack notifications.  
- **Outcome:** Lead contact time −95% (5‑minute Speed‑to‑Lead); connection rates up to +391%. 
- 🎬 [Watch 4‑min Loom Demo](https://www.loom.com/share/707c78cf35df44a4adf3ee1a04d75b57)

---

### 🧾 Accounts Payable Automation & Financial Control

#### 7. [Enterprise Autonomous AP Invoice Reconciliation & Fraud Protection Engine](https://github.com/kristian-enaga/enterprise-ap-invoice-reconciliation-engine)

<img width="1920" height="1079" alt="image" src="https://github.com/user-attachments/assets/e8d972b1-2f29-4eff-8034-5e4d84ee3777" />

- **What it does:** Ingests vendor invoices across Gmail and webhooks, runs autonomous line-item math checks, traps billing discrepancies, blocks duplicate payouts, and posts clean invoices to QuickBooks Online with Slack human-in-the-loop exception control.
- **Architecture:** Gmail/Webhook trigger → Multi-format document parser → Dual AI model fallback (Gemini/OpenAI) → Automated math verification gate → Supabase zero-data-loss exception vault → Slack interactive approval card → QuickBooks Online ERP sync.
- **Outcome:** Reclaims 10+ hours/week of manual bookkeeping, prevents duplicate/fraudulent disbursements, and ensures 100% audit readiness with immutable failure tracking.
- 🎬 [Watch 4-min Loom Demo](https://www.loom.com/share/595e7e48d6ab4a1f89263d23496f9d67)

---

### 🛒 E‑Commerce & Revenue Operations

#### 8. [Autonomous Revenue Recovery Engine (E‑Commerce)](https://github.com/kristian-enaga/autonomous-revenue-recovery-engine)

<img width="1920" height="1079" alt="image" src="https://github.com/user-attachments/assets/25dbdf59-5569-42aa-9370-9723ec378d1d" />

- **What it does:** Recovers lost revenue (e.g., abandoned cart/checkout) with smart, non‑spammy email sequences.  
- **Architecture:** Make.com scenario, webhook ingestion, stateful delay gates, Supabase purchase evaluation, Gemini AI email copy, custom Gmail dispatch.  
- **Outcome:** No redundant outreach to converted buyers; protects sender reputation; recovers lost revenue automatically. 
- 🎬 [Watch 3‑min Loom Demo](https://www.loom.com/share/311bfc94eee1429080f6fe5ed3cf62c0)

---

### 🛡 Infrastructure & System Resilience

#### 9. [n8n Centralized Error Handler & Fail‑Safe](https://github.com/kristian-enaga/n8n-Centralized-Error-Handler)

<img width="1920" height="1079" alt="image" src="https://github.com/user-attachments/assets/0a6e86a9-b257-4635-868d-f1abcce5d33b" />

- **What it does:** Captures n8n execution failures, logs audit trails, and sends instant alerts with 1‑click debug links.  
- **Architecture:** Centralized error handler, Google Sheets audit logs, Gmail/Slack alerts, execution debug links.  
- **Outcome:** Prevents silent downtime; cuts triage time from hours → under 2 minutes per incident. 
- 🎬 [Watch 3‑min Loom Demo](https://www.loom.com/share/ea1602f3bd8a4086983c96590e49136f)

---

## Education & Certifications

- **Bachelor of Science in Criminology** – *Graduated March 2026*
- **Make Advanced Certification** – *Make Academy (2026)*
- **AI Automation Explorer** – *Credentials in n8n & Generative AI Systems Integration (2026)*

---

## How I work (engagement model)

- **Discovery:** map GTM process, tools, and data flows. 
- **Data model:** define schemas, identity keys, and quality rules.
- **MVP workflow:** ship a minimal end‑to‑end automation in 1–2 weeks. 
- **Production hardening:** add retries, monitoring, docs, and handover.
- **Iterate:** expand to more use cases (onboarding, CS, attribution, etc.).

Open to **Full-time Remote Roles**, **B2B contract**, and **fractional GTM Engineer** engagements.

---

## Remote engagement

- Location: Zamboanga Sibugay, Philippines (PHT, UTC+8)
- Overlap: Comfortable with 8 PM–12 AM PST (9 AM–1 PM PHT next day) for standups/handoffs
- Contractor-ready: invoice via Wise / Payoneer / Deel
- Engagement model: 2-week pilot → monthly retainer / Full-time employment
- Production standards: centralized error handling, retries, DLQ, audit logs, Loom demos for every workflow

---

## Contact

- GitHub: [@kristian-enaga](https://github.com/kristian-enaga)
- Email: [kchanchan2357@gmail.com](mailto:kchanchan2357@gmail.com)
- LinkedIn: [kristian-jay-eñaga](https://www.linkedin.com/in/kristian-jay-e%C3%B1aga-85345741a/)
