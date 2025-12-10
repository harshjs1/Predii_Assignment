# Predii_Assignment

# 🚗 Vehicle Specification Extraction using RAG (LangChain + Llama-3)

This project implements a **Retrieval-Augmented Generation (RAG)** pipeline to extract structured vehicle specifications (e.g., torque values, part numbers, fluid capacities) from an automotive service manual PDF using **Llama-3 via Ollama**.

---

## ✅ Features
- 📄 PDF text extraction using **PyMuPDF**
- ✂️ Text chunking using **LangChain text splitters**
- 🔎 Semantic embeddings using **Sentence Transformers**
- 🧠 Vector storage & retrieval using **ChromaDB**
- 🤖 Local LLM inference using **Llama-3 via Ollama**
- 📊 Output in structured **JSON format**

---

## 🛠 Tech Stack
- **Python**
- **LangChain**
- **PyMuPDF**
- **Sentence Transformers**
- **ChromaDB**
- **Ollama + Llama-3**

---

## 📂 Project Workflow
1. **PDF Parsing** – Extracts raw text from `/content/service_manual.pdf`.
2. **Chunking** – Splits large text into overlapping chunks.
3. **Embedding** – Converts chunks into vector embeddings.
4. **Vector Store** – Stores embeddings in ChromaDB.
5. **RAG Pipeline** – Retrieves relevant chunks for a query.
6. **LLM Inference** – Llama-3 extracts structured specifications.
7. **JSON Output** – Returns clean structured data.

---

## ▶️ How to Run
1. Clone the repository.
2. Open the notebook in **Google Colab or Jupyter**.
3. Upload your PDF as `/content/service_manual.pdf`.
4. Run cells **in order (Cell 1 → Cell 8)**.
5. Enter your query in the final cell, for example:
