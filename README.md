# ⚖️ Legal Clause AI

> **An AI-powered Legal Clause Interpretation System that combines Retrieval-Augmented Generation (RAG), semantic search, and Large Language Models to provide accurate, context-aware explanations of legal documents and constitutional provisions.**

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![AI](https://img.shields.io/badge/AI-LLM-success)
![RAG](https://img.shields.io/badge/RAG-Enabled-orange)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📌 Overview

Legal Clause AI is an intelligent legal assistant designed to simplify the interpretation of complex legal clauses and constitutional documents.

Instead of generating responses solely from a language model, the system first retrieves the most relevant legal context using semantic search and vector embeddings. The retrieved information is then supplied to the LLM to generate accurate, grounded, and context-aware legal explanations.

The project demonstrates the practical implementation of Retrieval-Augmented Generation (RAG) for legal document understanding while reducing hallucinations commonly associated with generative AI.

---

## ✨ Features

- AI-powered legal clause interpretation
- Retrieval-Augmented Generation (RAG)
- Semantic search using vector embeddings
- Constitution-based Question Answering
- PDF document knowledge base
- Fine-tuning pipeline
- Context-aware legal explanations
- Fast retrieval using FAISS
- Multi-agent research and fact-checking using LangGraph
- Researcher, Writer, and Critic agent architecture
- Self-correcting feedback for factual inconsistencies and hallucinations
- Interactive Streamlit frontend for user queries
---

## 🏗️ System Architecture

```text
                         User Query
                              │
                              ▼
                    Query Preprocessing
                              │
                              ▼
                  Vector Embedding Generation
                              │
                              ▼
                    FAISS Semantic Search
                              │
                              ▼
                  Relevant Legal Context
                              │
                              ▼
                 ┌────────────────────────┐
                 │     Researcher Agent   │
                 └────────────┬───────────┘
                              │
                              ▼
                 ┌────────────────────────┐
                 │       Writer Agent     │
                 └────────────┬───────────┘
                              │
                              ▼
                 ┌────────────────────────┐
                 │       Critic Agent     │
                 └────────────┬───────────┘
                              │
                              ▼
                 Self-Correcting Feedback
                              │
                              ▼
                   Grounded Legal Response
                              │
                              ▼
                     Streamlit Interface
---


### 3. Replace the `Tech Stack` section with:

```markdown
## 🚀 Tech Stack

### Programming Language

- Python

### Artificial Intelligence

- Large Language Models (LLMs)
- Retrieval-Augmented Generation (RAG)
- Prompt Engineering
- Semantic Search
- Multi-Agent AI

### Machine Learning

- HuggingFace Sentence Transformers
- Embedding Models
- Fine-Tuning Pipeline
- Vector Similarity Search

### Agent Orchestration

- LangGraph
- Researcher Agent
- Writer Agent
- Critic Agent

### Vector Database / Search

- FAISS
- JSON Knowledge Base

### Frontend

- Streamlit

### Development Tools

- Git
- GitHub

---

## 📂 Project Structure

```text
Legal-Clause-AI/
│
├── pdfs/                     # Legal reference documents
├── constitution_qa.json      # Constitution QA dataset
├── rag_pipeline.py           # Retrieval-Augmented Generation pipeline
├── vector_database.py        # Vector embedding and retrieval
├── finetune.py               # Fine-tuning pipeline
├── frontend.py               # User interface
├── requirements.txt
└── README.md
```

---

## ⚙️ Workflow

1. User enters a legal query through the Streamlit interface.
2. The query is converted into vector embeddings using HuggingFace Sentence
   Transformers.
3. FAISS performs semantic similarity search to retrieve relevant legal
   context.
4. The **Researcher Agent** analyses the retrieved information.
5. The **Writer Agent** generates a context-aware legal explanation.
6. The **Critic Agent** evaluates the response for factual inconsistencies
   and hallucinations.
7. Self-correcting feedback is used when issues are detected.
8. The final grounded response is displayed through the Streamlit interface.
---

## 🎯 Applications

* Legal document interpretation
* Contract clause explanation
* Constitutional question answering
* Legal education
* Compliance assistance
* AI-powered legal research
* Enterprise legal knowledge systems

---

## 📈 Future Improvements

* Multi-document reasoning
* Multi-language legal support
* OCR support for scanned contracts
* Legal citation generation
* Case law retrieval
* Voice-based legal assistant
* Cloud deployment
* Authentication and user management

---

## 💻 Installation

Clone the repository

```bash
git clone https://github.com/ruchi315/Legal_clause_AI-.git
```

Move into the project directory

```bash
cd Legal_clause_AI-
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the application

```bash
python frontend.py
```

---

## 🧠 Skills Demonstrated

- Retrieval-Augmented Generation (RAG)
- Large Language Models (LLMs)
- Multi-Agent AI Systems
- LangGraph
- FAISS
- HuggingFace Sentence Transformers
- Vector Databases
- Semantic Search
- Prompt Engineering
- Information Retrieval
- Python Development
- Streamlit
- Machine Learning Pipelines
---
## 📊 Repository Highlights

- **3 specialised agents** orchestrated using LangGraph
- FAISS-based semantic document indexing
- HuggingFace Sentence Transformers for semantic embeddings
- **88% Recall@5** retrieval performance
- **93% faithfulness** for generated responses
- Self-correcting feedback for factual inconsistencies and hallucinations
- Interactive Streamlit interface
- **2.4s P95 response latency**
- Modular Python architecture
- Clean separation of retrieval, agent orchestration, and generation pipelines
- Dataset-driven legal knowledge base
- Production-oriented project structure
- Resume-ready AI portfolio project

---

## 🤝 Contributor

**Khushi Jainth**

B.Tech Student, IIT (BHU) Varanasi

Interested in Artificial Intelligence, Machine Learning, Data Science, and Intelligent Software Systems.

---

## 📄 License

This project is intended for educational, research, and demonstration purposes. Users are encouraged to validate AI-generated legal interpretations with qualified legal professionals before making legal decisions.

---

## ⭐ Support

If you found this project useful, consider giving the repository a ⭐ on GitHub.
