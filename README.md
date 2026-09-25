# Personal AI Assistant using RAG

A personal AI assistant that answers questions about my background,
education, skills, projects, experience, and professional interests.

## 🚀 Live Demo

https://abinaya-ai-assistance-amgvqhgcfv8f4wcfyfwnnz.streamlit.app/

## 📌 Project Overview

This project implements a Retrieval-Augmented Generation (RAG)
based AI assistant using Python and Streamlit.

The assistant retrieves relevant information from a prepared
knowledge base and uses an LLM to generate natural-language
responses.

## 🛠️ Technologies Used

- Python
- Streamlit
- Groq
- FAISS
- FastEmbed
- BGE Embeddings
- NumPy
- Retrieval-Augmented Generation (RAG)

## 🔄 How It Works

1. Personal information is stored as text chunks.
2. BGE embeddings are generated for the text.
3. FAISS is used to create a vector index.
4. User questions are converted into embeddings.
5. Relevant information is retrieved from the index.
6. Retrieved context is provided to the language model.
7. The AI assistant generates the final response.

## ✨ Features

- Personal AI assistant
- Context-aware question answering
- Semantic information retrieval
- Chat history
- Streamlit web interface
- Hosted online using Streamlit

## 📂 Project Structure

```text
personal-ai-assistant-rag/
│
├── streamlit_app.py
├── chunks_data.pkl
├── requirements.txt
├── .gitignore
└── README.md
