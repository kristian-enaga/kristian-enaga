# Hi, I'm Kristian Jay Eñaga 👋

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kristian-jay-e%C3%B1aga-85345741a/) [![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kchanchan2357@gmail.com)

## GTM Systems & AI Automation Engineer (Clay • HubSpot • Salesforce • n8n • Make)

I audit and build automated lead and revenue engines for B2B sales and marketing teams.

- Diagnose leaks in inbound, outbound, CRM, and RevOps workflows  
- Save 15+ hours/week per rep by automating prospecting, enrichment, routing, and follow‑up  
- Eliminate lost leads with bulletproof error handling, retries, and dead‑letter queues  
- Stack: **Clay**, **Hubspot** **n8n**, **Make**, **REST APIs/Webhooks**, **Postgres/Supabase DLQs**, and **Signal-to-Sequence Pipeline Architecture**.

---

## Core Production Systems

---

### 📥 Inbound Architecture & Defensive Data Engines
> High-throughput real-time ingestion, schema validation, zero-downtime SLA processing, and automated error recovery.

#### 1. [Accounts Payable Automation & Financial Control Engine](https://github.com/kristian-enaga/Accounts-Payable-Automation-Financial-Control)
<img width="1920" height="1079" alt="image" src="https://github.com/user-attachments/assets/e8d972b1-2f29-4eff-8034-5e4d84ee3777" />

- **What it does:** End-to-end automated parsing and verification of vendor invoices using Gemini 1.5 Vision and OpenAI GPT-4o, extracting line items, running strict mathematical checks, and flagging discrepancies before human sign-off.
- **Architecture:** Gmail / Form Webhook Ingestion → Gemini 1.5 Vision OCR → JS Line-Item Math & Duplicate Validation → Supabase DLQ → Slack Triage Alert → ERP / Google Sheets Sync.
- **Outcome:** Eliminates 90%+ of manual accounting data entry, prevents accidental overpayments, and guarantees zero data loss via Supabase DLQ.
- 📺 [Watch 3-min Loom Demo](https://www.loom.com/share/5b4e94ef3be14b9cb90adbe6ef9fa0f0)

#### 2. [Inbound Lead Sanitization, Normalization & Fraud Defense Engine](https://github.com/kristian-enaga/Inbound-Lead-Sanitization-Normalization-Engine)
<img width="1920" height="1079" alt="Inbound Lead Sanitization Architecture" src="https://github.com/kristian-enaga/Inbound-Lead-Sanitization-Normalization-Engine/blob/main/n8n-inbound-lead-sanitization-production-architecture.png?raw=true" />

- **What it does:** Autonomous sanitization layer that blocks spam, fixes invalid formatting, normalizes raw form data, and verifies domain/email health before records reach the CRM.
- **Architecture:** Webhook Ingestion → Regex Data Cleansing → E164 Phone Formatting → Hunter / MX Email Verification → Supabase DLQ → Schema Gate → HubSpot CRM Sync.
- **Outcome:** 100% invalid CRM entries blocked; response SLA from hours → sub-5 seconds.
- 📺 [Watch 4-min Loom Demo](https://www.loom.com/share/c38d37d65eed44129a712e530a8e2446)

#### 3. [AI Lead Scoring & Priority Router](https://github.com/kristian-enaga/AI-Lead-Scoring-Router)
<img width="1920" height="1079" alt="AI Lead Scoring Architecture" src="https://github.com/kristian-enaga/AI-Lead-Scoring-Router/blob/main/n8n-ai-lead-scoring-production-architecture.png?raw=true" />

- **What it does:** Real-time automated triage of inbound leads by budget, company size, and urgency using Google Gemini AI with OpenRouter fallback, instantly splitting VIP enterprise prospects from low-priority inquiries.
- **Architecture:** Webhook intake & payload extraction → Supabase DLQ raw lead backup → Google Gemini AI scoring + OpenRouter fallback → Schema validation & parameter merge → Multi-tier IF router (Slack alerts for VIPs / Automated Gmail replies for standard leads) → Centralized Google Sheets CRM sync.
- **Outcome:** Eliminates 70% of manual lead review time, saves 15+ hours/week of qualification work, guarantees zero lead loss via DLQ persistence, and routes high-value prospects instantly.
- 📺 [Watch 3-min Loom Demo](https://www.loom.com/share/38164c8a840f4076b3ac0ec62a26e3ce)

#### 4. [Instant Speed-to-Lead Alert & CRM Ingestion](https://github.com/kristian-enaga/Speed-to-lead-ingestion-engine)
<img width="1920" height="1079" alt="image" src="https://github.com/user-attachments/assets/93e85a03-7418-4415-a602-1dcdc57bd49a" />

- **What it does:** Ingests webhook leads, normalizes schema, syncs to Google Sheets CRM, and fires instant Slack alerts.
- **Architecture:** Webhook ingestion → schema normalization → Sheets sync → Slack notifications.
- **Outcome:** Lead contact time -95% (5-minute Speed-to-Lead); connection rates up to +391%.
- 📺 [Watch 4-min Loom Demo](https://www.loom.com/share/707c78cf35df44aadf3ee1a04d75b57)

---

### 📤 Outbound Architecture & Automated Enrichment Systems
> Automated lead discovery, waterfall enrichment, and campaign staging with zero manual lift.

#### 5. [Autonomous B2B Prospecting & Waterfall Enrichment Engine](https://github.com/kristian-enaga/b2b-outbound-prospecting-engine)
- **What it does:** Automates prospect discovery, multi-source waterfall enrichment (Apollo/Clay), email verification, and staging to cold outreach sequences.
- **Architecture:** Target Search Query → Scraping/Apollo Ingestion → Clay Enrichment Waterfall → ZeroBounce Verification Gate → Smartlead / Instantly Sequence Staging.
- **Outcome:** Saves 15+ hours/week per sales representative while maintaining deliverability and domain reputation.

---

### 🔄 Nearbound Architecture (Inbound × Outbound Signal Engines)
> Capitalizing on intent signals, CRM history, and company events to trigger targeted outreach.

#### 6. [Intent Signal-to-Sequence Pipeline & Account Intelligence Engine](https://github.com/kristian-enaga/intent-signal-to-sequence-pipeline)
- **What it does:** Intercepts high-intent signals (funding rounds, job hiring posts, tech stack shifts) combined with historical CRM context to launch hyper-personalized outreach campaigns.
- **Architecture:** Intent Webhook Trigger → CRM Account Lookup → Gemini Context Scoring → DLQ Verification → Personalization Engine → Outreach Sequence Trigger.
- **Outcome:** Transforms cold outreach into timely, contextual nearbound conversations with higher response rates.

---

### ⚙️ Production Infrastructure & Operations

#### 7. [Centralized Error Handling & Supabase Dead-Letter Queue (DLQ)](https://github.com/kristian-enaga/n8n-centralized-error-handler-dlq)
- **What it does:** System-wide fault-tolerant architecture that catches workflow execution errors, persists raw payloads to Supabase, and dispatches actionable Slack diagnostics.
- **Architecture:** System-wide Error Trigger → Payload Normalization → Supabase DLQ Storage → Slack Alert Routing → Recovery Execution.
- **Outcome:** Ensures 0% data loss across all GTM automation pipelines and maintains sub-5-second SLA visibility.
