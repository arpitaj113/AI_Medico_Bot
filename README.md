# 🩺 AI Medico Bot

An AI-powered Medical Document Question Answering System built using **Retrieval-Augmented Generation (RAG)**.

The application allows users to upload medical PDF documents and ask questions in natural language. It retrieves the most relevant document chunks using vector search and generates context-aware responses using Large Language Models (LLMs).

---

## 🚀 Features

- 📄 Upload one or multiple PDF documents
- 🔍 Automatic PDF text extraction
- ✂️ Intelligent document chunking
- 🧠 Embedding generation
- 💾 Vector Database (FAISS / ChromaDB)
- 🤖 AI-powered Question Answering
- 💬 Interactive Streamlit Chat Interface
- ⚡ Fast semantic search
- 🔒 Environment variable support using `.env`

---

## 🛠️ Tech Stack

- Python
- Streamlit
- LangChain
- Ollama
- Llama 3.2
- Google Gemini
- FAISS
- ChromaDB
- Sentence Transformers
- PyPDF
- dotenv

---

## 📂 Project Structure

```text
AI_Medico_Bot/
│
├── app.py
├── requirements.txt
├── README.md
├── .gitignore
├── .env
│
├── assets/
├── data/
├── database/
│
├── utils/
│   ├── __init__.py
│   ├── loader.py
│   ├── splitter.py
│   ├── embeddings.py
│   ├── vectorstore.py
│   ├── llm.py
│   ├── prompts.py
│   └── rag_chain.py
│
├── test_loader.py
├── test_embedding.py
├── test_splitter.py
├── test_faiss.py
├── test_chroma.py
├── test_ollama.py
├── test_gemini.py
└── test_rag.py
```

---

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/arpitaj113/AI_Medico_Bot.git
cd AI_Medico_Bot
```

### Create Virtual Environment

```bash
python -m venv medico_env
```

### Activate Environment

Windows

```bash
medico_env\Scripts\activate
```

Linux/Mac

```bash
source medico_env/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Environment Variables

Create a `.env` file inside the project folder.

Example:

```env
GOOGLE_API_KEY=YOUR_API_KEY
```

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

---

## 💡 How It Works

1. Upload PDF documents.
2. Extract text from PDFs.
3. Split documents into chunks.
4. Generate embeddings.
5. Store embeddings in a vector database.
6. Retrieve relevant chunks.
7. Generate answers using an LLM.
8. Display responses through Streamlit.

---

## 📸 Screenshots

### Home Page

<img width="1357" height="566" alt="image" src="https://github.com/user-attachments/assets/1df2d9df-5058-46fa-a378-ceaece2693c5" />


---

### Upload PDF

<img width="1352" height="560" alt="image" src="https://github.com/user-attachments/assets/22722b8d-fd10-4cc6-b1bb-15ee3393ae0c" />


---

### Chat Interface

<img width="1117" height="555" alt="image" src="https://github.com/user-attachments/assets/d434ee2f-0c2e-497d-ad20-4dd310423a1d" />
<img width="1087" height="556" alt="image" src="https://github.com/user-attachments/assets/2d3e494f-aa4e-4d8a-9660-51e15e270641" />


---

## 🔮 Future Improvements

- Multiple LLM support
- Medical report summarization
- Voice interaction
- Chat history
- Authentication
- Docker deployment
- Cloud deployment

---

## 👩‍💻 Author

**Arpita Jaiswal**

M.Sc. Data Science

GitHub: https://github.com/arpitaj113

LinkedIn: www.linkedin.com/in/arpita-jaiswal-cse

---

## ⭐ If you like this project

Please consider giving it a ⭐ on GitHub.
