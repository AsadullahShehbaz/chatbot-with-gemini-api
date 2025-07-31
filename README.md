# 🤖📄 Gemini DocChat App

Welcome to the **Gemini DocChat App** — a sleek and modern AI-powered web app built with **Streamlit** that allows users to:
- 💬 **Chat with Gemini AI** like ChatGPT  
- 📑 **Upload and summarize PDFs** with instant answers  
- 📚 **Preserve chat history**, use multi-page navigation  
- 🔐 **Secure API keys with `secrets.toml`**  

---

## 🚀 Features

### 🔹 Gemini ChatBot Page
- Ask any general questions using Gemini 1.5 Flash
- Clean UI with bottom-aligned prompt box (like ChatGPT)
- Chat history saved for each session

### 🔹 Document Reader Page
- Upload and read PDF files with pagination
- Ask questions from the document
- Export AI-generated summary

### 🔹 Built with:
- `LangChain` + `Gemini 1.5 API`
- `Streamlit` for frontend
- `PyPDF2` for PDF reading
- `streamlit-option-menu` for navigation

---

## 📸 Screenshots

| Chat Page | Document Reader |
|-----------|-----------------|
| ![Chat Screenshot](https://via.placeholder.com/400x200.png?text=Chat+UI) | ![Doc Screenshot](https://via.placeholder.com/400x200.png?text=Doc+Reader) |

---

## 🛠️ Installation

```bash
git clone https://github.com/yourusername/gemini-docchat-app.git
cd gemini-docchat-app
pip install -r requirements.txt
