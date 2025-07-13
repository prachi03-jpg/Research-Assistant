# 🧠 Research Assistant

A smart research assistant that automates web browsing, reads articles, extracts relevant information, and generates structured reports — all powered by cutting-edge LLMs.

![Banner](https://via.placeholder.com/1200x400.png?text=Research+Assistant) <!-- (Replace with a real screenshot or demo GIF) -->

---

## 🚀 Features

- 🔍 Web browsing with intelligent scraping
- 📑 Summarization of research papers/articles
- 🧾 Auto-generated structured reports
- 🗣️ LLM-powered Q&A over gathered data
- 💾 Download/export reports
- ⚡ FastAPI backend + React frontend

---

## 🛠️ Tech Stack

| Frontend | Backend | ML/LLM | Tools |
|----------|---------|--------|-------|
| React.js | FastAPI | GPT-4 / OpenAI | SQLite |
| Tailwind | Python  | LangChain (optional) | Git & GitHub |

---

## 📸 Screenshots

| Dashboard | Summary View |
|-----------|--------------|
| ![1](https://via.placeholder.com/300x200.png?text=Dashboard) | ![2](https://via.placeholder.com/300x200.png?text=Summary+View) |

---

## 🧪 How to Run Locally

```bash
# Clone the repo
git clone https://github.com/prachi03-jpg/Research-Assistant.git
cd Research-Assistant

# Backend
cd backend
pip install -r requirements.txt
uvicorn main:app --reload

# Frontend (in a new terminal)
cd frontend
npm install
npm run dev

