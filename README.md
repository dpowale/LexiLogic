# 📚 LexiLogic – Symbolic Multilingual Document Analyzer

**LexiLogic** is a Streamlit-based application that combines **symbolic reasoning** and **LLMs** (via LangChain) to analyze multilingual PDF documents. It is especially useful for understanding religious, ideological, legal, and cultural texts written in non-English languages such as Arabic.

---

## 🔍 Features

- 🈶 **Language Detection** – Identify the language of the input PDF
- 🌐 **Translation** – Convert non-English text to English
- 🧠 **Named Entity Extraction** – Find people, ideologies, and organizations
- 📚 **Topic Classification** – Identify themes discussed in the document
- 📝 **Contextual Summarization** – Generate meaningful, structured summaries
- 📄 **PDF Parsing** – Extract content using `PyMuPDF`

---

## 🚀 Getting Started

### 🖥️ Local Setup

1. **Install dependencies**:

```bash
pip install streamlit langchain_community openai sympy langdetect deep-translator PyMuPDF
