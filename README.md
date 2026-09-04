# Hi, I'm Kristian Jay Eñaga 👋

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kristian-jay-e%C3%B1aga-85345741a/) [![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kchanchan2357@gmail.com)

## GTM Engineer (n8n • Make • AI Agents)

I build automated lead and revenue engines for B2B sales and marketing teams.

- Save 15+ hours/week per rep by automating prospecting, enrichment, routing, and follow‑up. 
- Eliminate lost leads with bulletproof error handling, retries, and dead‑letter queues. 
- Stack: **n8n**, **Make**, **Gemini/OpenAI**, **AI Agents**, **REST APIs**, **webhooks**, and **defensive data engineering**.

---

## Core Production Systems

###1 🧾 Accounts Payable Automation & Financial Control

#### [Enterprise Autonomous AP Invoice Reconciliation & Fraud Protection Engine](https://github.com/kristian-enaga/enterprise-ap-invoice-reconciliation-engine)
<img width="1920" height="1079" alt="image" src="https://github.com/user-attachments/assets/e8d972b1-2f29-4eff-8034-5e4d84ee3777" />

- **What it does:** Ingests vendor invoices across Gmail and webhooks, runs autonomous line-item math checks, traps billing discrepancies, blocks duplicate payouts, and posts clean invoices to QuickBooks Online with Slack human-in-the-loop exception control.
- **Architecture:** Gmail/Webhook trigger → Multi-format document parser → Dual AI model fallback (Gemini/OpenAI) → Automated math verification gate → Supabase zero-data-loss exception vault → Slack interactive approval card → QuickBooks Online ERP sync.
- **Outcome:** Reclaims 10+ hours/week of manual bookkeeping, prevents duplicate/fraudulent disbursements, and ensures 100% audit readiness with immutable failure tracking.
- 🎬 [Watch 4-min Loom Demo](https://www.loom.com/share/595e7e48d6ab4a1f89263d23496f9d67)


---


### 📥 B2B Inbound Lead Acceleration & Qualification

#### 2. [Enterprise Inbound Lead Sanitizer & Outreach Engine](https://github.com/kristian-enaga/Inbound-Lead-Sanitizer-Engine)

<img width="1920" height="1079" alt="image" src="https://github.com/user-attachments/assets/6364334f-f66b-45db-9b89-3bf2e34e49d0" />

- **What it does:** Sanitizes inbound leads, filters bots, scores intent, syncs to HubSpot, and routes to Slack/WhatsApp.  
- **Architecture:** Sub‑5s E.164 phone normalization, bot filtering, Gemini AI intent scoring, HubSpot sync, dynamic Slack/WhatsApp routing.  
- **Outcome:** 100% invalid CRM entries blocked; response SLA from hours → sub‑5 seconds.
- 🎬 [Watch 4‑min Loom Demo](https://www.loom.com/share/c38d37d65eed44129a712e530a8e2446)

#### 3. [AI Lead Scoring & Priority Router](https://github.com/kristian-enaga/AI-Lead-Scoring-Router)

<img width="1920" height="1079" alt="image" src="https://github.com/user-attachments/assets/9fee8045-3258-4968-bd11-8208278c4c0d" />

- **What it does:** Real‑time triage of inbound leads by budget, company size, and urgency.  
- **Architecture:** Google Gemini AI scoring + priority routing to reps/channels.  
- **Outcome:** Saves 15+ hours/week of manual qualification; high‑value prospects routed instantly. 
- 🎬 [Watch 3‑min Loom Demo](https://www.loom.com/share/38164c8a840f4076b3ac0ec62a26e3ce)

#### 4. [Instant Speed‑to‑Lead Alert & CRM Ingestion](https://github.com/kristian-enaga/Speed-to-lead-ingestion-engine)

<img width="1920" height="1079" alt="image" src="https://github.com/user-attachments/assets/93e85a03-7418-4415-a602-1dcdc57bd49a" />

- **What it does:** Ingests webhook leads, normalizes schema, syncs to Google Sheets CRM, and fires instant Slack alerts.  
- **Architecture:** Webhook ingestion → schema normalization → Sheets sync → Slack notifications.  
- **Outcome:** Lead contact time −95% (5‑minute Speed‑to‑Lead); connection rates up to +391%. 
- 🎬 [Watch 4‑min Loom Demo](https://www.loom.com/share/707c78cf35df44a4adf3ee1a04d75b57)

---

### 📤 B2B Outbound Prospecting & Engagement

#### 5. [Automated B2B Outbound Prospecting Engine](https://github.com/kristian-enaga/Automated-B2B-Outbound-System)

<img width="1920" height="1079" alt="image" src="https://github.com/user-attachments/assets/f8bae866-2e23-453a-969b-00af5d0125f5" />

- **What it does:** End‑to‑end outbound: scraping → AI copy → HITL approval → send → logging.  
- **Architecture:** Apify scraping, Gemini email copy, Slack Human‑in‑the‑Loop (HITL) approvals, fault‑tolerant logging.  
- **Outcome:** Reclaims ~70% of rep prospecting time; protects domain deliverability with HITL gates. 
- 🎬 [Watch 4‑min Loom Demo](https://www.loom.com/share/5d3416feda7148bbbd60704ab9b5976e)

#### 6. [Autonomous Job Intelligence & High‑Intent Outreach Engine](https://github.com/kristian-enaga/autonomous-job-lead-engine)

<img width="1920" height="1079" alt="image" src="https://github.com/user-attachments/assets/45d2710a-a5f8-4711-a56d-227eeda4fb19" />

- **What it does:** Finds high‑intent job leads, validates pages, extracts tokens, drafts outreach, and sends via HITL.  
- **Architecture:** SerpAPI ingestion, pre‑flight 404/duplicate checks, JS RegEx HTML token optimization (~70% cost reduction), Gemini + Groq failover, Zod schema validation, DLQ, Telegram HITL 1‑click approvals.  
- **Outcome:** Automates 10+ hours/week of manual sourcing/audits; zero CRM data corruption via strict schema gates.  
- 🎬 [Watch 4‑min Loom Demo](https://www.loom.com/share/7792580657284a58a7e1dabf99365087)

---

### 🛒 E‑Commerce & Revenue Operations

#### 7. [Autonomous Revenue Recovery Engine (E‑Commerce)](https://github.com/kristian-enaga/autonomous-revenue-recovery-engine)

<img width="1920" height="1079" alt="image" src="https://github.com/user-attachments/assets/25dbdf59-5569-42aa-9370-9723ec378d1d" />

- **What it does:** Recovers lost revenue (e.g., abandoned cart/checkout) with smart, non‑spammy email sequences.  
- **Architecture:** Make.com scenario, webhook ingestion, stateful delay gates, Supabase purchase evaluation, Gemini AI email copy, custom Gmail dispatch.  
- **Outcome:** No redundant outreach to converted buyers; protects sender reputation; recovers lost revenue automatically. 
- 🎬 [Watch 3‑min Loom Demo](https://www.loom.com/share/311bfc94eee1429080f6fe5ed3cf62c0)

---

### 🛡️ Infrastructure & System Resilience

#### 8. [n8n Centralized Error Handler & Fail‑Safe](https://github.com/kristian-enaga/n8n-Centralized-Error-Handler)

<img width="1920" height="1079" alt="image" src="https://github.com/user-attachments/assets/0a6e86a9-b257-4635-868d-f1abcce5d33b" />

- **What it does:** Captures n8n execution failures, logs audit trails, and sends instant alerts with 1‑click debug links.  
- **Architecture:** Centralized error handler, Google Sheets audit logs, Gmail/Slack alerts, execution debug links.  
- **Outcome:** Prevents silent downtime; cuts triage time from hours → under 2 minutes per incident. 
- 🎬 [Watch 3‑min Loom Demo](https://www.loom.com/share/ea1602f3bd8a4086983c96590e49136f)

---

## How I work (engagement model)

- **Discovery:** map GTM process, tools, and data flows. 
- **Data model:** define schemas, identity keys, and quality rules.
- **MVP workflow:** ship a minimal end‑to‑end automation in 1–2 weeks. 
- **Production hardening:** add retries, monitoring, docs, and handover.
- **Iterate:** expand to more use cases (onboarding, CS, attribution, etc.).

Open to **B2B contract** and **fractional GTM Engineer** engagements.

---

## Contact

- GitHub: [@kristian-enaga](https://github.com/kristian-enaga)
- Email: [kchanchan2357@gmail.com](mailto:kchanchan2357@gmail.com)
- LinkedIn: [kristian-jay-eñaga](https://www.linkedin.com/in/kristian-jay-e%C3%B1aga-85345741a/)
