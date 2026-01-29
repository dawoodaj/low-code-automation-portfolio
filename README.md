# ⚡ Automated Operations Portfolio

**"The best code is no code."**

This repository contains operational prototypes designed to demonstrate **AI Enablement**, **Process Optimization**, and **FinTech Compliance Automation**.

I specialize in connecting business logic with AI agents to build tools that help teams move faster and stay compliant.

---

## 📂 Project Portfolio

I have categorized these prototypes into **Operational Efficiency** (Speed) and **Risk & Compliance** (Control), mirroring the core needs of a modern FinTech environment.

### 🔹 Operational Efficiency & Automation

#### **1. AI Receipt Vision Parser**
**Goal:** Eliminate manual data entry for expenses by processing receipt images with Computer Vision.
- **File:** `make-receipt-parser.json`
- **Tech Stack:** Make.com, OpenAI GPT-4o (Vision), OneDrive, Google Sheets.
- **Workflow:** Watches OneDrive for new images → OCRs the receipt → Standardizes JSON (Date/Merchant/Amount) → Updates Financial Ledger automatically.

#### **2. Smart Support Triage Bot**
**Goal:** Reduce L1 support ticket volume by 90% through automated sentiment analysis and routing.
- **File:** `make-triage-bot.json`
- **Tech Stack:** Make.com, OpenAI, Slack API, Gmail.
- **Workflow:** Ingests ticket → Analyzes Sentiment & Urgency (1-10) → Routes "High Priority" to Slack #ops → Drafts empathetic auto-replies for routine queries.

#### **3. GDPR Auto-Anonymizer**
**Goal:** Automate "Right to be Forgotten" requests to ensure full legal compliance without human intervention.
- **File:** `make-gdpr-anonymizer.json`
- **Tech Stack:** Make.com, CRM API (Simulated), Internal Database.
- **Workflow:** Listens for deletion webhook → Validates legal eligibility (EU Art. 17) → Wipes PII from marketing & logistics DBs → Generates compliance audit log.

---

### 🔹 Risk, Fraud & Compliance (RegTech)

#### **4. Real-Time Risk Audit Engine**
**Goal:** Detect suspicious transactions in real-time streams to prevent fraud before settlement.
- **File:** `n8n-risk-engine.json`
- **Tech Stack:** n8n, Python (Script Node), Slack Webhooks.
- **Workflow:** Monitors transaction stream → Calculates Risk Score based on velocity & amount → Flags anomalies (> Score 7) to Compliance Team.

#### **5. KYC Identity Validator**
**Goal:** Automate "Know Your Customer" checks by cross-referencing new user IDs with sanctions lists.
- **File:** `n8n-kyc-validator.json`
- **Tech Stack:** n8n, REST API, Postgres.
- **Workflow:** Daily batch fetch of new signups → Checks against simulated AML/Sanctions database → Auto-approves clear users → Locks suspicious accounts for manual review.

---

## 🛠 Technical Stack

* **Orchestration:** Make.com (Advanced), n8n (Self-Hosted/Cloud)
* **AI & LLMs:** OpenAI API (GPT-4o), Computer Vision
* **Scripting:** Python (for custom logic nodes), JSON/Data Structures
* **Integrations:** Google Workspace, Slack API, REST Webhooks, SQL

---

## 📸 Workflow Visuals

### AI Receipt Parser (Make.com)
![Receipt Parser Screenshot](image_300d3c.png)
*(Automated extraction of structured data from raw images)*

### Risk Audit Engine (n8n)
![Risk Engine Screenshot](image_172f3e.png)
*(Real-time logic flow for fraud detection)*

---

## 🚀 How to Run These Prototypes

Since these are Low-Code blueprints, you do not need to compile them.

1.  **Download** the `.json` file from the file list above.
2.  **Import** it into your Make.com or n8n dashboard.
3.  **Connect** your own API keys (OpenAI, Google, etc.).
4.  **Run** the scenario.

---

*Built by Dawood Javvad - 2026*
