Simple RAG Chatbot with LangChain, FAISS, and Hugging Face

This notebook demonstrates a basic Retrieval-Augmented Generation (RAG) pipeline using LangChain, FAISS, and Hugging Face models. It loads a pdf document, splits it into smaller chunks, generates embeddings, stores them in a FAISS vector database, and retrieves relevant information to answer user questions using the Qwen2.5-1.5B-Instruct language model.

Features
📄 Load text documents with pdfLoader
✂️ Split documents into chunks using RecursiveCharacterTextSplitter
🧠 Generate embeddings with all-MiniLM-L6-v2
🔍 Store and retrieve embeddings using FAISS
🤖 Generate context-aware answers with Qwen2.5-1.5B-Instruct
🔗 Build a complete Retrieval-Augmented Generation (RAG) workflow using LangChain
Tech Stack
Python
LangChain
FAISS
Hugging Face Transformers
Sentence Transformers

This project is intended for beginners who want to understand the fundamentals of building a local RAG-based question-answering system using open-source tools.
