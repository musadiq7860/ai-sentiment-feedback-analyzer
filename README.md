# 💬 AI Sentiment Feedback Analyzer

An automated feedback analysis pipeline that collects customer reviews via a form, classifies sentiment using Google Gemini AI, logs results to Google Sheets, and sends instant email alerts.

## 🧠 How It Works

1. Customer submits feedback via n8n form
2. Gemini AI classifies sentiment — **Positive / Negative / Neutral**
3. Result is logged to Google Sheets CRM
4. Email alert sent instantly with name, review & sentiment

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| AI Model | Google Gemini (PaLM API) |
| Automation | n8n |
| Storage | Google Sheets |
| Notifications | Gmail |

## ✨ Features

- 📝 Simple feedback form (Name + Review)
- 🎯 One-word sentiment classification via Gemini
- 📊 Auto-logs to Google Sheets with name & sentiment
- 📧 Instant email notification with full details
- ⚡ Fully automated — zero manual work

## 📦 Setup

1. Import `sentiment_analysis.json` into your n8n instance
2. Connect your **Google Gemini API** credentials
3. Connect your **Google Sheets OAuth** credentials
4. Connect your **Gmail OAuth** credentials
5. Update the Google Sheets document ID in the workflow
6. Activate the workflow

## 🔑 Required Credentials

- Google Gemini (PaLM) API Key
- Google Sheets OAuth2
- Gmail OAuth2

---

Built by [Muhammad Musaddaq Qaysir](https://musadiq-portfolio.vercel.app/)
