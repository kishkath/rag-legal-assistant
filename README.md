# 📚 RAG Legal Assistant (Streamlit UI)

**Business Overview:**  
The RAG Legal Assistant is an AI-powered solution designed for law firms, legal researchers, and compliance teams. It leverages a hybrid retrieval system combining dense embeddings and BM25 sparse search to provide **accurate, context-driven legal answers**. The assistant ensures **faithful responses with inline citations** from your document corpus and evaluates answer reliability. By integrating a Streamlit UI, it provides a **user-friendly interface for quick legal question answering**, reducing time spent on manual research and improving decision-making efficiency.

---

## Streamlit App URL

**Access the app here:** [Your Streamlit App URL](https://your-streamlit-app-link.com)  

*(Replace with your deployed Streamlit URL once live)*

---

## Features

- Hybrid retrieval using **Chroma embeddings** (dense) + **BM25** (sparse).  
- Automatic embedding storage in Chroma on first launch.  
- Answers include **inline citations** and sources.  
- LLM-based **evaluation of answer faithfulness**.  
- Streamlit-based **interactive web interface**.  

---

## Tech Stack

- Python 3.10+  
- [Streamlit](https://streamlit.io/) for the UI  
- [LangChain](https://www.langchain.com/) for LLM pipelines  
- [Chroma](https://www.trychroma.com/) for vector storage  
- [SentenceTransformers](https://www.sbert.net/) for embeddings  
- [rank_bm25](https://github.com/dorianbrown/rank_bm25) for sparse retrieval  
- OpenAI Chat models for LLM responses  

---

## Folder Structure


