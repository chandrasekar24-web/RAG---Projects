# Web-Based RAG Project using LangChain, Gemini, and ChromaDB

## Overview

This project demonstrates a **Retrieval-Augmented Generation (RAG)** pipeline that extracts content from a website, stores it in a vector database, retrieves relevant information based on user queries, and generates accurate answers using Google's Gemini LLM.

The project uses **LangChain** for orchestration, **Google Gemini Embeddings** for vector generation, **ChromaDB** as the vector store, and **Gemini 2.5 Flash** as the language model.

## Features

* Load web content directly from a URL.
* Split large documents into manageable chunks.
* Generate vector embeddings using Gemini Embedding Model.
* Store embeddings in ChromaDB.
* Perform semantic similarity search.
* Retrieve relevant context for user queries.
* Generate context-aware answers using Gemini LLM.
* Simple end-to-end RAG implementation.

## Tech Stack

* Python
* LangChain
* Google Gemini API
* ChromaDB
* WebBaseLoader
* RecursiveCharacterTextSplitter

## Project Workflow

1. **Document Loading**

   * Fetch content from a website using LangChain's WebBaseLoader.

2. **Text Splitting**

   * Break large documents into smaller chunks using RecursiveCharacterTextSplitter.

3. **Embedding Generation**

   * Convert text chunks into vector embeddings using Gemini Embedding Model.

4. **Vector Storage**

   * Store embeddings in ChromaDB for efficient semantic search.

5. **Retrieval**

   * Retrieve the most relevant document chunks based on the user's question.

6. **Prompt Construction**

   * Combine retrieved context with the user's query.

7. **Answer Generation**

   * Use Gemini 2.5 Flash to generate concise and context-aware responses.




* Support multiple websites and PDFs.
* Add conversational memory.
* Implement a web interface using Streamlit.
* Add source citations in responses.
* Deploy as a cloud-based application.
