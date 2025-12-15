#    Generative AI with LangChain

This repository contains **basic practice implementations of LangChain** using **Ollama** and **OpenAI API**.  
It covers core concepts such as **data ingestion, data transformation, embeddings, and vector stores**.

This repository showcases my hands-on experience with **LLM pipelines, embeddings, vector databases, and Retrieval-Augmented Generation (RAG)** — key skills required for modern AI/ML and GenAI roles.

---

## 👨‍💻 Why This Practice Matters

Large Language Models are powerful, but real-world applications require:
- Efficient data ingestion
- Semantic search using vector databases
- Context-aware question answering
- Flexible LLM integration (local & cloud)

This project demonstrates how to **design and implement these systems end-to-end** using industry-standard tools like **:contentReference[oaicite:0]{index=0}**, **:contentReference[oaicite:1]{index=1}**, and **:contentReference[oaicite:2]{index=2}**.

---

## ✨ Key Features

- 📥 **Data Ingestion**
  - Load and manage unstructured text data

- 🔄 **Data Transformation**
  - Text chunking and preprocessing for optimal embeddings

- 🧠 **Embeddings**
  - Convert text into high-dimensional vectors for semantic search

- 🗂️ **Vector Stores**
  - Store and retrieve embeddings using **FAISS** and **Chroma**

- 🤖 **LLM Integration**
  - Local inference using Ollama
  - Cloud-based inference using OpenAI API

- ❓ **Question Answering (RAG)**
  - Ask natural language questions over your own data

---

## 🛠️ Tech Stack

- **Python**
- **:contentReference[oaicite:3]{index=3}**
- **:contentReference[oaicite:4]{index=4}**
- **:contentReference[oaicite:5]{index=5} API**
- **FAISS / Chroma** (Vector Databases)
- **Virtual Environment (venv)**

---

## 📂 Project Structure

```bash
.
├── data/                 # Sample documents
├── ingestion/            # Data loading modules
├── transformation/       # Text splitting & preprocessing
├── embeddings/           # Embedding generation logic
├── vectorstores/         # FAISS / Chroma setup
├── .env.example          # Environment variable template
├── requirements.txt      # Dependencies
└── README.md             # Documentation

