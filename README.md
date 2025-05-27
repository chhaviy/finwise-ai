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
├── app/ # Main app code
│ ├── main.py # Streamlit entry point
│ ├── llm_engine.py # Handles LLM interaction
│ ├── utils.py # Utility functions
│ ├── financial_tools.py # SIP, EMI calculators
│ ├── visuals.py # Chart generation
│
├── docs/ # Sample PDFs or scraped content
├── data/ # External data files
├── requirements.txt # Python dependencies
├── README.md
