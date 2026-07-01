# 🩺 AI Medico Bot

An AI-powered medical document assistant built using:

- Python
- Streamlit
- LangChain
- Ollama (Llama 3.2)
- ChromaDB / FAISS
- Google Gemini (optional)

## Features

- 📄 Upload medical PDFs
- 🔍 Semantic search
- 🤖 AI-powered question answering
- 💾 Vector database
- 🖥️ Streamlit interface

## Installation

```bash
git clone https://github.com/<your-username>/AI_Medico_Bot.git
cd AI_Medico_Bot

python -m venv medico_env
medico_env\Scripts\activate

pip install -r requirements.txt
```

Create a `.env` file:

```env
GOOGLE_API_KEY=your_api_key
```

Run:

```bash
streamlit run app.py
```