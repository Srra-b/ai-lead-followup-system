# 🔄 Automated Smart Follow-up System

An automated lead engagement and re-engagement workflow built with **n8n**, **Google Sheets API**, and **Gmail API**. It monitors prospect interactions, tracks follow-up cadences, logs lead activity into a central Google Sheets database, and delivers personalized follow-up outreach via email to maximize conversion rates.

---

## 📽️ System Live Demo
📺 **[Click Here to Watch the Live Demo Video](https://www.loom.com/share/677e0a7ede3c4fc3b08d1dd11deaf02b)**

---

## 📸 System Screenshots & Visual Proof

| n8n Workflow Canvas | Google Sheets Database | Gmail Follow-up Email |
| :---: | :---: | :---: |
| ![Workflow](./Workflow-screenshot.png) | ![Database](./sheet-screenshot.png) | ![Email](./email-screenshot.png) |

---

## 🔑 Key Features
* **Automated Cadence Tracking**: Triggers scheduled follow-ups based on prospect response status and timestamps.
* **Structured Interaction Audit**: Updates Google Sheets dynamically with follow-up dates, interaction history, and lead status.
* **Personalized Dynamic Outreach**: Generates customized follow-up emails sent directly through Gmail OAuth 2.0 integration.

---

## 🛠️ Tech Stack
* **Workflow Engine**: n8n
* **Database / CRM**: Google Sheets API
* **Email Engine**: Gmail API (OAuth 2.0)

---

## 🎯 Business Impact & Value
* **Zero Latency (Speed-to-Lead)**: Eliminates manual follow-up delays by maintaining consistent communication with prospects.
* **Higher Re-engagement**: Prevents leads from turning cold through systematic, automated outreach sequences.
* **Full Audit Trail**: Centralizes all follow-up interactions and status updates inside Google Sheets for complete operational transparency.

* ---

## ⚙️ How It Works

1. A lead submits their information through a form.
2. n8n receives the lead data and sends it to the AI model.
3. Google Gemini generates a personalized follow-up message based on the lead's information.
4. The personalized email is automatically sent through Gmail.
5. The lead information and follow-up details are recorded in Google Sheets.
