# 📚 RAG Pipeline for Coursera Course Scraping

This repository demonstrates a Retrieval-Augmented Generation (RAG) pipeline built in Google Colab. It scrapes the Coursera course page for "Deep Neural Networks", extracts relevant course details, stores them using ChromaDB, and leverages **Gemini AI** as the LLM for answering queries.

---

## 🚀 Features

- Scrapes course data from Coursera using Python.
- Stores processed information in a ChromaDB vector store.
- Uses Gemini AI for natural language understanding and responses.
- Combines retrieval and generation for intelligent question answering.

---

## 🛠️ Technologies Used

- **Google Colab**
- **BeautifulSoup / Requests** - for web scraping
- **ChromaDB** - vector database for storing embeddings
- **Gemini AI** - for LLM-based response generation
- **Langchain** -  for text to vectors, agumentation, generating context using llm

---

## 📌 How It Works

1. **Scraping Phase**: Course page content is extracted using Python scraping tools.
2. **Embedding & Storage**: Text data is chunked and stored in ChromaDB as embeddings.
3. **Query Handling**: User queries are interpreted by Gemini AI, and the most relevant course segments are retrieved via Chroma.
4. **Response Generation**: Gemini formulates context-aware answers combining retrieved facts with reasoning.
