# 🚀 Automated Operations Portfolio

This repository contains operational prototypes designed to automate financial workflows and support auditing.

## 📂 Project List

### 1. AI Receipt Parser (Make.com)
**Goal:** Automate expense entry by extracting data from receipt images using GPT-4 Vision.
- **File:** `make-receipt-parser.json`
- **Logic:** Watch OneDrive -> OCR Image -> Parse JSON -> Add to Google Sheets.
- **Tools:** Make.com, OpenAI GPT-4o, OneDrive.

### 2. Smart Triage Bot (Make.com)
**Goal:** Reduce support ticket triage time by 90% using AI sentiment analysis.
- **File:** `make-triage-bot.json`
- **Logic:** Ingest Ticket -> Classify Urgency (1-10) -> Route to Slack/Email.

### 3. Risk Audit Engine (n8n)
**Goal:** Detect potential fraud in real-time transaction streams.
- **File:** `n8n-risk-engine.json`
- **Logic:** Analyze Transaction -> Calculate Risk Score -> Flag for Review.

---
*To view these workflows, import the JSON files directly into Make.com or n8n.*# low-code-automation-

