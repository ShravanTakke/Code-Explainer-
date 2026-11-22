
# 🧠 Code Explainer

A beginner-friendly AI-powered web application that explains programming code using the Google Gemini API.

## 📌 Project Overview

Code Explainer helps beginners understand source code by providing a simple overview, line-by-line explanations, important programming concepts, and suggestions for improvement.

Users can select a programming language, paste their code, and receive an AI-generated explanation through an easy-to-use web interface.

## ✨ Features

- Supports multiple programming languages.
- Simple and interactive Streamlit interface.
- AI-generated code overview.
- Line-by-line code explanation.
- Explanation of important programming concepts.
- Suggestions for code improvement.
- Stop generation control.
- Error handling for API failures and timeouts.

## 🛠️ Technologies Used

- **Python** – Main programming language.
- **Streamlit** – Web application interface.
- **Google Gemini API** – AI-powered code explanation.
- **Google GenAI SDK** – API integration.

## 🤖 AI Model

`gemini-3.8-flash`

## 📂 Project Structure

```text
Code_Explainer/
│
├── app.py
├── requirements.txt
├── README.md
└── .gitignore
```

## ⚙️ Installation and Setup

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Open the project folder

```bash
cd Code_Explainer
```

### 3. Install dependencies

```bash
py -m pip install -r requirements.txt
```

### 4. Configure the Gemini API key

Get an API key from:

https://aistudio.google.com/app/apikey

Set it in PowerShell:

```powershell
$env:GEMINI_API_KEY="YOUR_API_KEY"
```

### 5. Run the application

```bash
py -m streamlit run app.py
```

Open the local URL provided by Streamlit, usually:

`http://localhost:8501`

## 📖 How to Use

1. Launch the application.
2. Select the programming language.
3. Paste your source code into the editor.
4. Click **Explain my code**.
5. View the generated explanation.

## ⚠️ Limitations

- Requires an internet connection.
- Requires a valid Gemini API key.
- API availability and usage limits may affect response generation.
- AI-generated explanations should be reviewed for accuracy.
- Stopping generation prevents the result from being displayed, but may not cancel a request already processing on Google's servers.

## 🎓 Academic Project

**Project:** Code Explainer  
**Student:** Shravan Takke  
**Class:** LY AIA9  
**Roll Number:** 71  
**Enrollment Number:** MITU21IBCS0011

---

*Developed using Python, Streamlit and Google Gemini API.*
