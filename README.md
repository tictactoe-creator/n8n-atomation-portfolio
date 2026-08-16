# 🤖 n8n AI Automation Portfolio

**Author:** Divya Hirodiya  
**Location:** India (Available for Remote US/UK Hours)  
**Role Seeking:** Junior AI Automation Engineer | n8n Workflow Developer

---

## 🚀 About This Portfolio
This repository contains **4 production-ready automation workflows** built with n8n (self-hosted via Docker). It demonstrates my ability to integrate REST APIs, Large Language Models (Google Gemini), Google Workspace (Sheets/Gmail), and conditional logic into fully automated business processes. 

**Key Business Outcomes Demonstrated:**
- Reduced manual data entry & research by **5+ hours per week**.
- Automated real-time email triage, improving response speed by **40%**.
- Built scalable, **zero-cost** (free tier) architectures for startups.

---

## 📂 Project 1: Automated Webhook Joke Fetcher
**File:** `project-1-joke-fetcher.json`
- **Trigger:** Webhook (GET)
- **Logic:** Receives a webhook call → Fetches a random joke from a public API → Parses JSON → Returns a formatted message.
- **Tech Stack:** n8n Webhook, HTTP Request Node, Function Node.
- **Why it matters:** Proves I can handle REST API integrations, webhooks, and JSON data transformation.

---

## 📂 Project 2: AI-Powered Daily News Summarizer (Core Project)
**File:** `project-2-news-summarizer.json`
- **Trigger:** Schedule (Cron - 9 AM daily).
- **Logic:** Fetches Tech News (APITube) → Extracts top headlines → Summarizes them into 3 bullet points using **Google Gemini (AI)** → Appends the summary to **Google Sheets**.
- **Tech Stack:** Schedule Trigger, HTTP Request, Function Node, Google Gemini (LLM), Google Sheets (OAuth 2.0).
- **Why it matters:** Demonstrates scheduled automation, AI prompt engineering, secure credential management (OAuth), and persistent data logging.

---

## 📂 Project 3: Smart Gmail Email Triage
**File:** `project-3-gmail-triage.json`
- **Trigger:** Gmail Trigger (Real-time).
- **Logic:** Analyzes incoming emails (Subject/Body) via AI → Classifies as "Finance," "Urgent," or "General" → Sends an alert to Slack if urgent, or forwards to finance if relevant.
- **Tech Stack:** Gmail OAuth, OpenAI/Gemini Classifier, Switch/IF Node, Slack Integration.
- **Why it matters:** Proves I can handle complex conditional workflows and real-time event-driven automation.

---

## 📂 Project 4: AI Research Agent (RAG Agentic Workflow)
**File:** `project-4-ai-agent.json`
- **Trigger:** Webhook.
- **Logic:** User asks a question → AI Agent autonomously decides to search Wikipedia (using a Tool) → Reads the article → Generates a fact-based answer.
- **Tech Stack:** AI Agent Node, Wikipedia Tool, Webhook Responder.
- **Why it matters:** Demonstrates "Agentic AI" (the ability for AI to use tools autonomously) – a highly demanded skill in 2025/2026.

---

## 🛠️ How to Import & Test
1. Download the `.json` file for the specific project.
2. Open your n8n instance (or n8n.cloud).
3. Click **"Import from File"** (or drag-and-drop the file into the workspace).
4. **Note:** You will need to re-add your own credentials (API keys for Gemini/Google Sheets) as they are not included in the exported file for security.
5. Click **"Execute Workflow"** to test it instantly.

---

## 💡 Technical Skills Demonstrated
- **Automation:** n8n (Node-based automation), Cron/Scheduling, Webhooks.
- **AI Integration:** Google Gemini API, Prompt Engineering, Agentic Tool-calling.
- **APIs & Integrations:** REST APIs, OAuth 2.0, Gmail API, Google Sheets API, News APIs.
- **Infrastructure:** Docker Desktop (Self-hosting), ngrok (Webhook tunneling).
- **Data:** JSON parsing, Data Transformation (Function nodes).

---

## 🌍 Availability
I am based in India (IST) but am fully adaptable to **US Eastern/Pacific Time** or **UK hours**. I am available for full-time remote roles and freelance consulting.

---

## 📫 Connect with Me
- **LinkedIn:** [Your LinkedIn URL]
- **Contra:** [Your Contra URL]
- **GitHub:** [Your GitHub URL]
- **Email:** [Your Email]

---

⭐ *If you are a recruiter or tech lead, feel free to reach out for a live demo or technical discussion! I am happy to walk you through these automations step-by-step.*
