# 📄 AI PDF Question Answering System (RAG Project)

## 🚀 Project Overview

This project is an **AI-powered PDF Question Answering System** built using the **RAG (Retrieval-Augmented Generation)** approach.

It allows users to:

* Upload PDF documents 📑
* Extract and process text
* Ask questions based on the document
* Get intelligent answers using AI 🤖

---

## 🎯 Features

✅ Load and process PDF files
✅ Convert text into embeddings
✅ Store embeddings using FAISS
✅ Retrieve relevant content
✅ Generate accurate answers using LLM
✅ Modular and scalable code structure

---

## 🛠️ Tech Stack

* Python 🐍
* LangChain
* FAISS (Vector Database)
* LLM (Ollama / Open Source Models)
* PDF Loader

---

## 📂 Project Structure

```
project/
│── main.py              # Main execution file
│── pdf_loader.py       # PDF loading & processing
│── document.py         # Document handling
│── data/               # Sample PDFs
│── requirements.txt    # Dependencies
│── README.md           # Project documentation
```

---

## ⚙️ Installation

### 1️⃣ Clone the Repository

```
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2️⃣ Create Virtual Environment

```
python -m venv .venv
```

### 3️⃣ Activate Environment

* Windows:

```
.venv\Scripts\activate
```

* Mac/Linux:

```
source .venv/bin/activate
```

### 4️⃣ Install Dependencies

```
pip install -r requirements.txt
```

---

## ▶️ How to Run

```
python main.py
```

---

## 🧠 How It Works (Simple Explanation)

1. Load PDF 📄
2. Extract text
3. Convert text → embeddings
4. Store in FAISS index
5. User asks question ❓
6. System retrieves relevant content
7. LLM generates answer 🤖

---

## 📌 Example Use Case

* Study notes Q&A
* Research paper analysis
* Document-based chatbot
* AI assistant for PDFs

---

## 🔮 Future Improvements

* Web interface (Streamlit / React)
* Multi-PDF support
* Chat history
* Voice input (optional)
* Deployment (Cloud)

---

## 👨‍💻 Author

**Your Name**

* GitHub: https://github.com/your-username
* LinkedIn: (Add your profile)

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!

---
