# 📚 Celebal_Technology_Assignment8  
## Advanced AI-Driven Legal Document Summarization and Risk Assessment

A cutting-edge Streamlit-powered AI tool designed to analyze legal documents, identify risks, and generate structured summaries using state-of-the-art AI models.

---

## 📌 Overview

This project uses advanced AI techniques including **Groq API**, **SentenceTransformer**, and **FAISS** to extract insights from legal PDFs. The application identifies potential compliance, financial, and operational risks and provides structured, downloadable summaries to support legal professionals.

The user-friendly **Streamlit** interface allows easy document uploads, real-time risk analysis, and semantic search.

---

## 🚀 Features

- 📄 **PDF Extraction**  
  Extracts and processes text from uploaded legal documents using PyPDF2.

- 🧠 **AI-Powered Summarization**  
  Uses Groq API to generate coherent and structured summaries of lengthy legal texts.

- 🔍 **Risk Assessment**  
  Identifies and classifies risks into compliance, financial, and operational categories.

- 🎯 **Semantic Search**  
  Retrieves relevant sections from documents using SentenceTransformer embeddings and FAISS indexing.

- 📊 **Visualization**  
  Displays pie charts representing the distribution of detected risks.

- 📩 **Download & Email Reports**  
  Allows users to download the summary and optionally email the assessment report.

---

## 🛠️ Tech Stack

- **Python**
- **Streamlit** – for the web interface
- **Groq API** – for AI-driven summarization
- **SentenceTransformer** (`all-MiniLM-L6-v2`) – for text embeddings
- **FAISS** – for fast semantic search
- **PyPDF2** – for PDF parsing and text extraction
- **Matplotlib / Plotly** – for risk visualizations

---

## 📁 Project Structure
📁 celebal_assignment8/
├── app.py # Main Streamlit application
├── summarizer.py # Summarization logic using Groq API
├── risk_assessor.py # Risk extraction and classification logic
├── utils.py # Helper functions (e.g., PDF parsing, embedding, etc.)
├── requirements.txt # Python dependencies
├── README.md # Project documentation
└── 📁 data/
└── sample_doc.pdf # Example PDF for testing
