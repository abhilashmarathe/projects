🤖 AI-Powered Client Document Assistant (RAG System)
🚀 Overview

This project implements a Retrieval-Augmented Generation (RAG) pipeline to answer questions from client documents.

It simulates an AI assistant for a digital agency that can retrieve and answer questions from contracts, agreements, and project documentation.

The system uses:

SentenceTransformers for semantic embeddings

FAISS for vector similarity search

HuggingFace Transformers for response generation

🎯 Business Problem

Digital agencies manage multiple client contracts and agreements. Manually searching documents for information such as:

Budget

Deadline

Payment terms

Project type

can be inefficient.

This AI assistant enables semantic search and context-aware question answering over internal documents.

🛠 Tech Stack

Python

SentenceTransformers (all-MiniLM-L6-v2)

FAISS (Vector Database)

HuggingFace Transformers

Google Colab

🧠 How It Works

Client documents are loaded and split into text chunks.

Each chunk is converted into embeddings using SentenceTransformers.

Embeddings are stored in a FAISS vector index.

User queries are embedded and matched against stored vectors.

The most relevant document chunk is retrieved.

Retrieved context is passed to a language model for answer generation.

🔄 RAG Pipeline Architecture

User Query
↓
Embedding Generation
↓
FAISS Vector Search
↓
Context Retrieval
↓
LLM Response Generation

📂 Project Structure

client-document-assistant-rag/
│
├── rag_pipeline.ipynb
├── client_docs.txt
├── requirements.txt
└── README.md

📌 Key Features

Fully local execution (No OpenAI API required)

Semantic search using dense embeddings

Context-aware answer generation

Modular and extensible pipeline

🔮 Future Improvements

Use stronger open-source LLM (Mistral / Llama)

Add PDF ingestion instead of plain text

Deploy using FastAPI or Django

Add Streamlit UI

Implement chunk ranking & re-ranking

👨‍💻 Author

Abhilash R. Marathe
Computer Science Engineer | ML & GenAI Enthusiast
Founder – WebQuicks Technologies

LinkedIn: https://www.linkedin.com/in/abhilash-marathe-aa4331140/
