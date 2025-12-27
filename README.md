📘 Chat with Your PDF Using AI – Python + LangChain + Local LLM (Flask UI)

This project lets you chat with any PDF file locally using Python, LangChain, FAISS, and a lightweight TinyLlama LLM.
You can upload a PDF, ask questions, and get meaningful answers — fully offline and without depending on external APIs.

🎯 Features

Upload and extract text from PDF files

Ask questions and receive context-based answers

Works completely offline with a local LLM

Typing animation for responses

Option to clear chat

Simple Flask-based web interface

🛠️ Tech Stack
Backend

Python 3.10+

Flask

LangChain

TinyLlama (local GGUF model using ctransformers)

FAISS for vector search

Sentence Transformers

PyMuPDF for PDF reading

Frontend

HTML

CSS

JavaScript

📦 Requirements (requirements.txt)
flask
langchain
faiss-cpu
sentence-transformers
PyMuPDF
ctransformers

🚀 Setup Instructions
1️⃣ Install the project dependencies

Create a virtual environment (optional) and install the required packages:

pip install -r requirements.txt

2️⃣ Add the Local LLM Model

Place this model file inside the models folder:

tinyllama-1.1b-chat-v1.0.Q4_0.gguf

Folder structure example:

models/
   tinyllama-1.1b-chat-v1.0.Q4_0.gguf

3️⃣ Run the Flask Application
python app.py

4️⃣ Open in your browser
http://127.0.0.1:5000

📁 Folder Structure
project/
├── app.py
├── uploads/
├── models/
│   └── tinyllama-1.1b-chat-v1.0.Q4_0.gguf
├── static/
│   └── styles.css
├── templates/
│   └── index.html
└── requirements.txt

💡 Personal Note

I built this project to learn how Flask works, how to use local LLMs, and how to connect PDFs, embeddings, and vector search using LangChain.
