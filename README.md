# 🚀 Cold_Email_Generation

## 📝 Overview
This project automates **job scraping, semantic search, and personalized cold emailing** using **LangChain, Groq (Mixtral-8x7B), ChromaDB, and Streamlit**.

---

## 🛠 Features
✅ **Web Scraping**: Extracts job postings from LinkedIn.  
✅ **AI-Powered Information Extraction**: Uses LLM to convert scraped job listings into structured JSON (role, experience, skills, etc.).  
✅ **Vector Database (ChromaDB)**: Efficient **semantic search** to match jobs with relevant portfolio projects.  
✅ **Personalized Cold Emails**: Auto-generates professional outreach emails using **Groq LLM**.  
✅ **Streamlit UI**: User-friendly interface for interaction and automation.  

---

## 📌 Tech Stack
- **Python**
- **LangChain**
- **Groq (Mixtral-8x7B)**
- **ChromaDB** (Vector Database for semantic search)
- **Streamlit** (Web UI)
- **Pandas** (Data handling)
- **WebBaseLoader** (Web scraping)

---

## 🚀 How It Works
1. **Scrape Job Listings** → Extract job postings from LinkedIn.
2. **Extract & Structure Data** → LLM processes text into JSON format.
3. **Store & Retrieve Portfolio Projects** → Use ChromaDB for semantic search.
4. **Generate Cold Email** → AI crafts personalized outreach messages.
5. **Streamlit UI** → Provides an easy-to-use dashboard.

---

## 🖥 Setup API Keys
- **Groq API Key**: Obtain from [Groq](https://groq.com/)

---

## 🌐 Running the Web UI (Streamlit App)  
To use the interactive web UI, run the following command in the terminal:  

```bash
streamlit run main.py
```
---

## 📸 UI Screenshot

---

## 🛠 Future Enhancements
✅ Automate email sending via SMTP or LinkedIn API
✅ Improve LLM accuracy for better job parsing
✅ Add more portfolio filtering options
