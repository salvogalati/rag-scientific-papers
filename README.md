# 🔍 RAG on Scientific Publications

This project demonstrates a full pipeline for **Retrieval-Augmented Generation (RAG)** applied to a personal collection of scientific papers in PDF format.  
It allows for **semantic search** and **question answering** over your own research using modern LLMs and vector-based retrieval.

---

## 📌 Objective

Build an intelligent system that can:
- Ingest and segment PDF research papers into semantic sections
- Generate embeddings of each section using a transformer-based model
- Index those embeddings with FAISS for fast similarity search
- Enable natural language questions to retrieve relevant document chunks
- (Optional) Feed those chunks to a language model for grounded answer generation

---

## 🛠️ Technologies Used

- **LangChain** – Document loaders, chunking, and orchestration
- **FAISS** – Fast similarity search index
- **Sentence Transformers** – Embedding models (e.g. MiniLM, BGE, E5)
- **PyMuPDF** – Robust PDF parsing (via `PyMuPDFLoader`)
- **Hugging Face** – Pretrained embedding models
- **PyTorch** – With CUDA for GPU acceleration

---
