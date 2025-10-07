
---

# 🧠 LegalAssist AI – Contract Drafting and Summarization Tool

**LegalAssist AI** is an advanced **RAG-based (Retrieval-Augmented Generation)** system designed to **summarize and analyze legal documents** efficiently using AI.
It helps lawyers, legal teams, and businesses quickly understand lengthy contracts or policies by generating concise, accurate summaries and clause insights.

---
<img width="600" alt="image" src="https://github.com/user-attachments/assets/1e0225fe-754f-4237-86cc-c6948e6e868c" />


## 🚀 Features

* **Legal Document Summarization** – Extracts and summarizes key points from lengthy legal texts.
* **RAG (Retrieval-Augmented Generation)** – Combines document retrieval and LLM reasoning for accurate, context-aware results.
* **Clause Extraction & Analysis** – Identifies crucial clauses (like confidentiality, liability, payment, etc.).
* **Custom Document Uploads** – Works with uploaded contracts, agreements, and policies.
* **User-friendly Execution** – Run easily with the included `run.bat` file.

---

## 🧩 Tech Stack

* **Python 3.x**
* **LangChain / HuggingFace** for embeddings & vector storage
* **FAISS** for efficient document retrieval
* **LLM (Large Language Model)** for contextual summarization
* **RAG-based pipeline** for enhanced legal understanding

---

## ⚙️ How to Run

1. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```
2. **Run the summarizer:**

   ```bash
   run.bat
   ```
3. Upload or provide legal documents to generate smart summaries.

---

## 🧾 Project Structure

```
.
├── summarizer.py        # Core RAG-based summarization logic
├── requirements.txt     # Project dependencies
├── run.bat              # Quick run script
├── .gitignore           # Ignored files (venv, .env, etc.)
└── README.md            # Project overview
```

---


## 🛡️ Note

* The tool is intended for **legal document understanding and summarization**, not as a substitute for professional legal advice.
* Make sure to include your own `.env` file for API keys (not pushed to GitHub).

---
