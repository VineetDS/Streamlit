Chat with Multiple PDFs using RAG, LLM, and VectorDB

Overview
This project implements a chatbot that allows users to interact with multiple PDF documents. It uses a Retrieval-Augmented Generation (RAG) system with GooglePalm LLM and FAISS vector store for efficient document retrieval and response generation.

Features
- Extract text from multiple PDF documents.
- Split text into manageable chunks.
- Convert text chunks into numerical vectors using GooglePalm embeddings.
- Store and retrieve embeddings using FAISS vector store.
- Generate conversational responses using GooglePalm LLM.
- User-friendly interface built with Streamlit.

Setup Instructions
1. Clone the Repository
git clone <repository_url>
cd <repository_directory>