# 📊 Telegram Accountant Bot (n8n Workflow)

## 📌 Overview
This project contains an **n8n workflow (JSON)** that turns **Telegram into your personal accountant**.  
With this bot, you can quickly log expenses, record income, and request financial summaries — all from your Telegram chat.  

Perfect for **freelancers, solopreneurs, and small business owners** who want a lightweight, no-subscription accounting assistant.

---

## 🚀 Features
- ✅ Log expenses directly from Telegram (e.g., `/expense Lunch 20`)
- ✅ Record income transactions (e.g., `/income ClientX 500`)
- ✅ Generate instant balance reports (`/summary`)
- ✅ Data stored securely in Google Sheets / Airtable (configurable)
- ✅ Easy to customize for any accounting category

---

## 🛠️ Tech Stack
- **n8n** (workflow automation)
- **Telegram Bot API**
- **Google Sheets / Airtable** (for data storage)

---

## 📂 Project Structure
```plaintext
telegram-accountant/
│
├── src/
│   └── workflow.json     # n8n workflow file
│
├── docs/
│   ├── images/           # screenshots, diagrams
│   └── setup.md          # extended setup instructions
│
└── README.md
