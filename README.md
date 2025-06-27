# 🧠 RAG with Local Ollama

This project demonstrates a simple Retrieval-Augmented Generation (RAG) pipeline using a **locally running Ollama model** (`llama3`, `mistral`, etc.), **FAISS** for vector search, and **HuggingFace** sentence embeddings.

## 🚀 Features
- Local LLM via [Ollama](https://ollama.com/)
- Dense embeddings via `sentence-transformers/all-MiniLM-L6-v2`
- Vector similarity search with FAISS
- Two versions:
  - `rag_using_local_ollama.ipynb`: Simple, step-by-step implementation
  - `new_version_rag_notebook.ipynb`: Modular version using LangChain

## 🧱 Tech Stack
- Python
- HuggingFace Transformers
- Ollama (local)
- LangChain (modular version)
