This project implements an end-to-end Retrieval-Augmented Generation (RAG) pipeline that enables users to query PDF documents using natural language. The system processes documents by splitting them into chunks, generating semantic embeddings, and storing them in a Pinecone vector database. Upon receiving a query, relevant document chunks are retrieved using cosine similarity and passed to a Large Language Model (LLM) to generate accurate, context-aware responses. The application is deployed using Streamlit for an interactive user experience.

** Key Features**
 PDF document ingestion and intelligent text chunking
 Semantic search using embeddings and cosine similarity
 LLM-based context-aware answer generation
 Fast retrieval using Pinecone vector database
 Interactive UI built with Streamlit
 Supports both OpenAI and HuggingFace models
