# Medical_chat_bot
# 🩺 MediChat Bot

An **AI-powered medical chatbot** built with **LangChain** and **Hugging Face embeddings**.  
It can answer medical-related queries by retrieving information from uploaded PDF documents.  
⚠️ **Disclaimer**: This chatbot is for **educational purposes only** and should not replace professional medical advice.

---

## 🚀 Features
- Upload medical PDFs and query them conversationally.
- Uses **LangChain** for document processing and conversational memory.
- Employs **Hugging Face embeddings** with **FAISS** vector store for semantic search.
- Simple **Streamlit** web interface for interaction.
- Provides general health-related answers based on ingested documents.

---

## 🛠️ Tech Stack
- **Python 3.x**
- **LangChain**
- **Hugging Face Transformers / Sentence Transformers**
- **FAISS** (vector database)
- **PyPDF** (document parsing)
- **Streamlit** (UI)

---

## 📂 Project Structure
Medichat_bot/
│-- Medichat_bot.ipynb # Main notebook (development & testing)
│-- app.py # Streamlit app (if exported from notebook)
│-- requirements.txt # Dependencies
│-- data/ # PDF files for knowledge base
│-- vectorstore/ # FAISS index storage
│-- README.md # Project documentation
