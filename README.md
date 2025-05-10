
# GenAI-Powered Document Query System (Syllabus Chatbot)

This project demonstrates how to build an intelligent document-based Question Answering (QA) system using NLP techniques. The system allows users to upload PDF documents (such as academic syllabi), ask questions in natural language, and get contextually relevant answers extracted from the documents.

## 🔍 Project Overview

- **Input**: PDF documents + natural language question from user
- **Output**: Answer(s) extracted from relevant chunks in the document using semantic search

## 💡 Features

- PDF text extraction using PyPDF2
- Chunking of extracted text with overlapping windows
- Sentence embedding using `all-MiniLM-L6-v2` from HuggingFace
- Fast vector similarity search using FAISS
- Natural language querying interface (via Google Colab or Streamlit)

## 🛠️ Technologies Used

- Python 3.x
- [Sentence-Transformers](https://www.sbert.net/)
- [FAISS](https://faiss.ai/)
- [PyPDF2](https://pypdf2.readthedocs.io/)
- [NLTK](https://www.nltk.org/)
- Google Colab / Streamlit

## 🚀 How to Run

1. Clone the repository or open the Colab notebook.
2. Install required dependencies:

    ```bash
    pip install faiss-cpu sentence-transformers nltk pypdf2
    ```

3. Upload PDF(s) using Colab widgets or Streamlit.
4. Ask questions and get relevant answers from the document.

## 📁 File Structure

- `Gen_AI_Project.ipynb`: Main Jupyter notebook with all code
- `Dataset`: Some Sample Curriculum PDF
- `README.md`: Project description and usage instructions

## 📌 Use Cases

- Academic syllabus search
- Policy document exploration
- E-learning and intelligent tutoring systems
- Internal documentation Q&A

## 📚 References

- [Sentence Transformers](https://www.sbert.net/)
- [all-MiniLM-L6-v2 on Hugging Face](https://huggingface.co/sentence-transformers/all-MiniLM-L6-v2)
- [FAISS by Facebook AI](https://faiss.ai/)
- [PyPDF2 Documentation](https://pypdf2.readthedocs.io/)
- [NLTK Project](https://www.nltk.org/)

---

© Mohammad Shaikh - VIT Bhopal University
