# Local-RAG-Pipeline-llama-3-3b-instruct-

This project implements a **local Retrieval-Augmented Generation (RAG) pipeline** using a quantized version of **Meta Llama 3.2 3B Instruct** and **all-mpnet-base-v2** as the embedding model — all without relying on LangChain or LlamaIndex. The system performs semantic search over embedded documents and passes relevant context to the LLM for answer generation.

---

## 🔧 Requirements

Install the required packages using:

```bash
pip install -r requirements.txt
