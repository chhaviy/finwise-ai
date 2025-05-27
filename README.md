# 🧠 Finwise AI

**Finwise AI** is your personal GenAI-powered finance tutor. It simplifies complex financial topics into beginner-friendly insights using large language models (LLMs), interactive Q&A, and visualizations.

---

## 🚀 Features

- 💬 Ask anything about personal finance (taxes, credit score, budgeting, etc.)
- 🧠 “Explain Like I’m 5” mode for beginners
- 📊 Visualize financial scenarios (SIP returns, loan EMIs, savings growth)
- 📚 Finance Cheat Sheets and TL;DRs
- 🗂️ Chat memory for personalized learning

---

## 🔧 Tech Stack

- [Streamlit](https://streamlit.io/) – for UI
- OpenAI GPT-4 (or 3.5) – for core LLM Q&A
- LangChain – for RAG and memory (planned)
- FAISS – for document-based retrieval
- Matplotlib / Plotly – for interactive finance charts
- Python (Pandas, NumPy) – for financial calculations

---

## 📁 Folder Structure

finwise-ai/
│
├── app/                     # Core app logic
│   ├── __init__.py
│   ├── main.py              # Entry point for Streamlit app
│   ├── llm_engine.py        # OpenAI/GPT integration
│   ├── utils.py             # Utility functions (optional placeholder)
│   ├── financial_tools.py   # EMI/SIP calculator logic (placeholder)
│   ├── visuals.py           # Matplotlib/Plotly charts (placeholder)
│
├── .gitignore               # Files to ignore (e.g., __pycache__, .env)
├── .env.example             # Placeholder for OpenAI API key
├── requirements.txt         # Dependencies list
├── README.md                # Project overview and instructions
