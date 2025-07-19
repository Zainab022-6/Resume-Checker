# Resume-Checker
This script is a Resume Analyzer Web App built using Python and Gradio, designed to help users check how well their resume matches a job description (JD) using ATS (Applicant Tracking System) logic.
💼 Key Features:

    📄 Accepts resume PDFs and extracts their content using OCR.

    🧠 Uses NLTK to process job descriptions and extract keywords.

    🧩 Matches resume content against a predefined skill set for various roles like Data Scientist, Web Developer, DevOps Engineer, etc.

    📊 Generates a pie chart showing the ATS match percentage.

    🤖 Provides personalized suggestions and role recommendations.

    🌐 Hosted with a simple and user-friendly Gradio web interface.

📦 Dependencies:

    gradio, pdf2image, pytesseract, nltk, matplotlib, PyMuPDF, PIL, and system utility poppler-utils.
# Resume Checker (ATS Match Scorer)

A simple yet powerful web app that helps you evaluate how well your resume matches a specific job description (JD). Built using Python and Gradio.

## 🚀 Features

- 📥 Upload your resume in PDF format.
- 📋 Paste any job description (JD).
- 🧠 Intelligent keyword matching using NLTK.
- 📊 Visual ATS Score (pie chart).
- 🔍 Role recommendations based on your skills.
- 💬 Smart suggestions to improve your resume.

## 🛠️ Requirements

```bash
pip install gradio pdf2image pytesseract nltk matplotlib PyMuPDF
sudo apt-get install -y poppler-utils
