# 📰 Auto-Newsletter Builder using Gemini API, n8n & Airtable

Built an own automated newsletter pipeline using AI.
This project pulls articles from RSS feeds, summarizes them with **Google Gemini API**, stores them in **Airtable**, and sends weekly digests via email using **n8n**.

---

## ✨ Features

- 🔗 **RSS Feed Integration** – Auto-fetch articles from any public feed (e.g., TechCrunch, IndieHackers)
- 🧠 **Gemini-Powered Summarization** – Summarizes articles into 3-sentence briefs using Google’s Gemini Pro LLM
- 📊 **Airtable Storage** – Stores title, URL, summary, and date in Airtable base
- 📬 **Automated Weekly Email** – Sends a beautifully formatted digest using Gmail every Friday
- 💡 **No-Code Stack** – Built entirely using n8n, Gemini API, and Airtable

---

## 📁 Tech Stack

| Tool       | Purpose                          |
|------------|----------------------------------|
| [n8n](https://n8n.io/) | Workflow automation |
| [Gemini API](https://makersuite.google.com/) | LLM-based summarization |
| [Airtable](https://airtable.com/) | Lightweight database |
| [Gmail API / SMTP](https://developers.google.com/gmail/api) | Email delivery |
