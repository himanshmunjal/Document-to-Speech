# 📖 File-to-Speech Converter

A simple and lightweight **Streamlit web application** that converts documents into speech.  
Upload your file, extract text, choose a language, and listen instantly. The app also generates a **shareable MP3 link** via AWS S3.

---

## 🚀 Features
- 📂 **Supports multiple file formats** → PDF, Word (DOCX), PowerPoint (PPTX), and Text (TXT).  
- 🌐 **Language selection** → Convert text to speech in English, Hindi, Spanish, and French.  
- 🎧 **Audio playback** → Listen directly inside the app.  
- 🔗 **Shareable link** → Uploads MP3 to AWS S3 with a public download link.  
- ⚡ **Lightweight** → Works on Mac/Windows/Linux without heavy dependencies.  

---

## 🛠️ Tech Stack
- [Streamlit](https://streamlit.io/) → UI framework  
- [gTTS](https://pypi.org/project/gTTS/) → Text-to-Speech  
- [PyPDF2](https://pypi.org/project/PyPDF2/) → PDF text extraction  
- [python-docx](https://pypi.org/project/python-docx/) → Word document parsing  
- [python-pptx](https://pypi.org/project/python-pptx/) → PowerPoint parsing  
- [boto3](https://pypi.org/project/boto3/) → AWS S3 integration  

---

## 📦 Installation

1. **Clone the repo**
   ```bash
   git clone https://github.com/himanshmunjal/file-to-speech.git
   cd file-to-speech
