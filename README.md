📘 Chat with Your PDF Using AI – Python + LangChain + Local LLM (Flask UI)

This project allows you to chat with any PDF file locally using Python, LangChain, FAISS, and a lightweight local LLM (TinyLlama).
You can upload a PDF, ask questions, and get meaningful responses — all offline, without using any external APIs.

🎯 Features

Upload and preview PDF files

Ask questions and get accurate, contextual answers

Works fully offline with a local LLM

Real-time typing effect for replies

Clear chat option

Simple Flask web interface

🛠️ Tech Stack
Backend

Python 3.10+

Flask

LangChain

TinyLlama (local model with ctransformers)

FAISS (vector search)

Sentence Transformers

PyMuPDF

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

🚀 Installation & Setup
1️⃣ Clone or Download the Project
git clone https://github.com/your-username/chat-with-pdf-ai.git
cd chat-with-pdf-ai

2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Add the Local LLM Model

Download the TinyLlama GGUF model:

tinyllama-1.1b-chat-v1.0.Q4_0.gguf

Place it inside the models/ folder:

project/
└── models/
      tinyllama-1.1b-chat-v1.0.Q4_0.gguf

4️⃣ Run the Flask App
python app.py

5️⃣ Open in Browser
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

💡 Why I Built This Project

By doing this project, I am learning how Flask works, how local LLMs run, and how to connect them with LangChain, embeddings, and vector search.
