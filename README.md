# 🩺 Medical AI Assistant – RAG-based Diagnosis System  

This project is a **Retrieval-Augmented Generation (RAG)** powered **Medical AI Assistant**.  
It extracts structured data from JSON-based medical flowcharts and knowledge bases, processes them into CSV datasets, builds **BM25 + FAISS vector search indices**, and finally integrates with **LLMs (Mistral-7B / HuggingFace models)** to provide **clinically informed answers** to medical queries.  

It also comes with a **Gradio Web UI** for interactive querying.  

---

## 🚀 Features  
- 📂 Extracts and processes **diagnostic flowcharts** and **medical knowledge JSONs** into CSVs  
- 🧹 Cleans and normalizes datasets (symptoms, risk factors, lab results, history, etc.)  
- 🔎 Hybrid retrieval using **BM25** and **SentenceTransformer embeddings + FAISS**  
- 🤖 Generates structured and detailed medical answers using **LLMs**  
- 🎨 Interactive **Gradio-based UI** with dark theme customization  
- 📊 Saves merged and cleaned medical datasets for reusability  

---
## 🛠 Tech Stack

Language: Python
Retrieval: FAISS, BM25 (rank-bm25)
Embeddings: SentenceTransformers (all-MiniLM-L6-v2)
Model: mistralai/Mistral-7B-Instruct-v0.2 (transformers)
Data Processing: pandas, numpy, json
Execution: Google Colab

---
![rag1](https://github.com/user-attachments/assets/4bd433fb-3c7a-4c58-998d-7cf5b50d1729)


