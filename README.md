# 💹 FinLens — Finance Document Intelligence

> A Notebook LM-style AI assistant built specifically for financial documents — contracts, invoices, and financial statements.

Built for the **Build with AI UAE** initiative (Google for Developers × GeeksforGeeks).

🔗 **Live Demo:** `[your-vercel-url].vercel.app`

---

## ✨ Features

| Feature | Description |
|---|---|
| 📄 **Multi-Document Upload** | Upload multiple PDFs (contracts, invoices, financial statements) |
| 🔍 **In-App PDF Viewer** | Browse documents page by page with zoom controls |
| 🤖 **AI Chat Assistant** | Ask anything — get answers with page references (`[Page 3]`) |
| 🔗 **Knowledge Graph** | Extract entities, financial metrics, risks, and insights automatically |
| 📊 **Auto Presentation** | Generate a professional slide deck from your documents |
| ⬇️ **Export Slides** | Download the presentation as a standalone HTML file |
| 🌙 **Dark / Light Mode** | Toggle between themes |
| ⚡ **Quick Prompts** | One-click prompts: Summarize, Risks, Key Metrics, Dates, etc. |

---

## 🚀 How to Run Locally

This is a **single HTML file** — no build step, no dependencies to install.

1. Download `index.html` from this repo
2. Open it in any modern browser (Chrome, Firefox, Edge)
3. Enter your **Gemini API Key** in the top bar and click **Connect**
4. Upload your financial PDFs and start chatting!

---

## 🔑 Getting Your Gemini API Key (Free)

1. Go to [https://aistudio.google.com](https://aistudio.google.com)
2. Sign in with your Google account
3. Click **"Get API Key"** → **"Create API Key"**
4. Copy the key and paste it into FinLens

> The free tier includes generous usage limits — more than enough for testing and demos.

---

## 📁 Project Structure

```
finlens/
└── index.html      ← The entire app (HTML + CSS + JS)
└── README.md       ← This file
```

Everything lives in a **single HTML file** — no frameworks, no npm, no build tools required.

---

## 🛠️ Tech Stack

- **Frontend:** Vanilla HTML, CSS, JavaScript
- **AI Model:** Gemini 2.0 Flash (via Gemini API)
- **PDF Rendering:** PDF.js (CDN)
- **Hosting:** Vercel (free tier)

---

## 💡 Use Cases

- 📋 **Contract Review** — Upload NDAs, service agreements, or lease contracts and instantly identify key clauses, parties, and obligations
- 🧾 **Invoice Analysis** — Extract line items, payment terms, due dates, and vendor details
- 📈 **Financial Statements** — Summarize P&L, balance sheets, and cash flow statements with key metrics
- ⚠️ **Risk Identification** — Automatically flag penalty clauses, liabilities, and red flags

---


## 👤 Author

Made with ❤️ using Gemini Canvas + Gemini API
