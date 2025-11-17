# PrismCode AI
understands your code and it is powered by Gemini


It is an intelligent developer assistant that lets you upload, explore, and query codebases using natural language.  
Powered by Google Gemini, it performs context-aware reasoning — summarizing, locating endpoints, explaining architecture, and answering deep technical questions.

It’s your personal AI code analyst, designed for speed, clarity, and developer insight.

---

## ✨ Key Features — Already Implemented
- 🧠 **RAG-Powered Q&A** — Retrieves exact code context and line references  
- 💬 **Gemini Summarizer** — Generates detailed project-level summaries  
- 🎨 **Dark / Light Theme Toggle** — Smooth transitions with custom CSS  
- ⚙️ **Demo Mode** — Instantly load sample projects for testing  
- 📂 **Multi-file Upload** — Supports ZIPs or individual code files  
- 🧭 **Recent Questions History** — Sidebar recall with clear option  
- 💡 **Smart Header + Logo** — Animated gradient and brand identity  
- ⚡ **Glowing Footer** — Signature with social icons and gradient animation  

---

## 🧠 Example Insights

**Query:** “Where is the API authentication handled?”  
**Gemini Insight:** Found in `auth/routes.py`, lines 22–58 — defines the `verify_user_token()` function that validates JWTs before accessing protected endpoints.

**Query:** “Summarize this frontend structure.”  
**Gemini Summary:** React-based dashboard app using modular context providers, dynamic routing, and API abstraction hooks for clean scalability.

------

## 🧩 Tech Stack

| Layer           | Technology                                                                 |
|-----------------|---------------------------------------------------------------------------|
| Frontend        | Streamlit (custom CSS, components, theme toggle)                          |
| AI Model        | Gemini 2.5 Pro via Google Generative AI SDK                                |
| RAG / Embeddings| LangChain + HuggingFace + FAISS                                           |
| Backend Logic   | Python (LangChain RAG pipeline, summarization, retriever)                 |
| File Parsing    | Recursive directory + TextSplitter for all major languages                |

---


