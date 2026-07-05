# 📚 Mini RAG Studio

A lightweight **Retrieval-Augmented Generation (RAG)** application that allows users to upload PDF documents, retrieve relevant information using semantic search, and generate context-aware answers with Large Language Models (LLMs).

## 🚀 Features

* 📄 Upload and process PDF documents
* ✂️ Automatic text chunking
* 🔍 Semantic document retrieval using vector embeddings
* 🧠 AI-powered question answering
* 💬 Interactive chat interface
* ⚡ Fast and lightweight architecture
* 🔒 Secure API key management using `.env`

---

## 🛠️ Tech Stack

* **Python**
* **Streamlit**
* **LangChain**
* **Google Gemini / Ollama**
* **Hugging Face Embeddings**
* **FAISS / ChromaDB**
* **PyPDF**
* **Sentence Transformers**

---

## 📂 Project Structure

```
Mini_RAG_Studio/
│
├── app.py
├── requirements.txt
├── .env
├── README.md
│
├── data/
│   └── PDFs
│
├── vector_store/
│
├── utils/
│
└── assets/
```

## ▶️ Run the Application

```bash
streamlit run app.py
```

The application will open in your browser.


## 🤝 Contributing

Contributions are welcome. Feel free to fork the repository, open issues, and submit pull requests.

---

## 📄 License

This project is intended for educational and learning purposes. You are free to modify and extend it for personal or academic use.
