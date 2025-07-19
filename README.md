# 🚀 Resume Analyzer based on Job Description

This project is an **AI-powered Resume Analyzer** that evaluates how well a candidate's resume matches a given job description (JD). It uses OCR and NLP techniques to extract skills from the resume, compares them against the JD, and provides an ATS (Applicant Tracking System) match score along with role suggestions.

## 🔍 Features

- 📄 Extracts text from PDF resumes using OCR
- 🧠 Identifies keywords from job descriptions using NLP
- 🧰 Matches resume skills to predefined job roles
- 📊 Visualizes ATS match score using pie charts
- 💡 Gives personalized suggestions and best-fit roles
- 🖥️ Built with a user-friendly Gradio interface

## 🛠️ Tech Stack

- Python
- Gradio
- Tesseract OCR
- NLTK (Natural Language Toolkit)
- Matplotlib
- PyMuPDF (`fitz`)
- PDF2Image
- PIL (Pillow)

## 🚀 Getting Started

### 1. Install Dependencies

```bash
pip install gradio pdf2image pytesseract nltk matplotlib PyMuPDF
sudo apt-get install -y poppler-utils

