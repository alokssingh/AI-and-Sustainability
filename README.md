# AI-and-Sustainability


# 📄 Information Extraction using Retrieval-Augmented Generation (RAG)

This project demonstrates how to build a **simple Retrieval-Augmented Generation (RAG) pipeline** using **LangChain**, **Ollama**, and an **open-source LLM**. The workflow loads a PDF, converts it into searchable vector embeddings, retrieves relevant chunks, and uses an LLM to answer questions grounded in the document.

---

## 🚀 Features
- PDF ingestion and text extraction  
- Chunking and document preparation using LangChain utilities  
- Embedding generation and vector storage (ChromaDB)  
- Retrieval of semantically similar chunks  
- RAG-based question answering  
- Continuous interactive Q&A loop  
- Optional structured output using LangChain output parsers  

---

## 🧰 Tech Stack
- Python  
- LangChain  
- Ollama (local LLM inference)  
- Chromadb  
- docarray  
- pymupdf4llm  

---

## 📦 Installation

Install all required dependencies:

```bash
pip install langchain
pip install langchain_community
pip install langchain-text-splitters
pip install langchain-pinecone
pip install langchain[docarray]
pip install docarray
pip install chromadb
pip install pymupdf4llm
