# LangChain-Based Information Retrieval System

This repository demonstrates the integration of **LangChain** with **FAISS vector search** and **Ollama LLM ("deepseek-r1:1.5b")** to build an intelligent document retrieval and answering system. The system processes multiple document formats (text, HTML, and PDFs), indexes them using embeddings, and retrieves relevant content based on user queries.

---

## Features

- **Multi-Source Data Ingestion**: Supports loading text, web pages, and PDFs.
- **Efficient Chunking & Indexing**: Uses `RecursiveCharacterTextSplitter` for structured document segmentation.
- **Vector Search with FAISS**: Embeds documents using `OllamaEmbeddings` and stores them in FAISS for fast retrieval.
- **LLM-Powered Responses**: Uses **deepseek-r1:1.5b** to generate intelligent responses.
- **Retrieval-Augmented Generation (RAG)**: Enhances response accuracy by retrieving and using relevant documents.
- **Environment Variable Management**: Secures configurations via a `.env` file.

---

## Setup Instructions

### Prerequisites

- Python 3.8+
- Git installed on your system
- Ollama installed ([Download Ollama](https://ollama.ai))


