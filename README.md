# 📚 RAG Document Q&A with Groq & Llama 3

A Retrieval-Augmented Generation (RAG) application built using **Streamlit**, **LangChain**, **Groq Llama 3**, **FAISS**, and **OpenAI Embeddings**. Ask questions from research papers and get accurate context-based answers.

## 🚀 Features

* Load PDF research papers
* Generate embeddings with OpenAI
* Store vectors using FAISS
* Retrieve relevant document chunks
* Answer questions using Groq Llama 3
* Interactive Streamlit UI

## 🛠️ Tech Stack

* Streamlit
* LangChain
* Groq (Llama3-8B-8192)
* OpenAI Embeddings
* FAISS
* Python

## 📂 Project Structure

```text
├── app.py
├── .env
├── research_papers/
│   └── *.pdf
├── requirements.txt
└── README.md
```

## ⚙️ Setup

Install dependencies:

```bash
pip install -r requirements.txt
```

Create a `.env` file:

```env
OPENAI_API_KEY=your_openai_api_key
GROQ_API_KEY=your_groq_api_key
```

Run the application:

```bash
streamlit run app.py
```

## 📖 Usage

1. Add PDF files to the `research_papers` folder.
2. Click **Document Embedding**.
3. Enter your question.
4. Get answers based on the document content.

## 🎯 Example Questions

* What is the main contribution of the paper?
* Summarize the methodology.
* What datasets were used?
* Explain the proposed model.

## 📜 License

MIT License
