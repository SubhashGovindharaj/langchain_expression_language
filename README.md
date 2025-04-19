# 🧠 LangChain Expression Language App (FastAPI + Ollama + LangSmith)

This project demonstrates the use of **LangChain Expression Language (LCEL)** to build a local LLM app using **FastAPI** and **Ollama's llama3** model. It includes **LangSmith** integration for experiment tracking and chain observability.

---

## 🚀 Features

- 🧩 LangChain Expression Language (LCEL)
- 🤖 Local LLM with Ollama (`llama3`)
- 🔍 LangSmith tracing enabled
- ⚡ FastAPI backend with LangServe
- 🔐 Environment variable management using `python-dotenv`

---

## 🛠️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/SubhashGovindharaj/langchain_expression_language.git
cd langchain_expression_language

---

### ✅ `requirements.txt`

```txt
langchain
langchain-core
langchain-community
langserve
ollama
fastapi
uvicorn
sse-starlette
python-dotenv
