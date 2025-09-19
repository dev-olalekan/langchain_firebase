# LangChain + Firebase Firestore Chatbot

This project integrates **LangChain**, **Google Firestore**, and **OpenAI** to build a chatbot that saves conversation history into **Firebase Firestore**.

---

## 🚀 Features

- Stores chat history in Firestore
- Uses `langchain-google-firestore` for persistence
- Chat with AI using `gpt-4o-mini`
- Authentication via **Google Cloud CLI**
- Easy re-run instructions

---

## 🛠 Tech Stack

<p align="left">
  <img src="https://www.python.org/static/community_logos/python-logo.png" height="40" alt="Python"/>
  <img src="https://firebase.google.com/static/downloads/brand-guidelines/PNG/logo-logomark.png" height="40" alt="Firebase"/>
  <img src="https://firebase.google.com/static/images/brand-guidelines/logo-vertical.png" height="40" alt="Firestore"/>
  <img src="https://avatars.githubusercontent.com/u/1342004?s=200&v=4" height="40" alt="Git"/>
  <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" height="40" alt="GitHub"/>
  <img src="https://img.shields.io/badge/LangChain-000000?style=flat-square&logo=LangChain&logoColor=white" height="40" alt="LangChain"/>
  <img src="https://cloud.google.com/_static/cloud/images/social-icon-google-cloud-1200-630.png" height="40" alt="Google Cloud"/>
  
</p>

---

## 📂 Project Setup

### 1️⃣ Clone the repository

git clone https://github.com/your-username/langfirebase.git
cd langfirebase

python -m venv .venv

# Windows PowerShell

.\.venv\Scripts\activate

# Mac/Linux

source .venv/bin/activate

---

# install python packages

pip install -r requirements.txt

---

# Authenticate Google Cloud

gcloud auth application-default login

---

### Check your access token: run this in code terminal vsc

gcloud auth application-default print-access-token

---

# Running the Project

python chat_model/chat_model_with_firebase.py

---

# Terminal or Cli Response

Initializing Firestore Client...<br>
Setting up Firestore Chat Message History...<br>
Chat History Initialized.<br>
Current Chat History: [ ]<br>
Start chatting with the AI. Type 'exit' to quit.<br>

---

User: Hello <br>
AI: Hi there! How can I help you today?

---

# The image screen shot from terminal

![screenshot](img/screenshot.png)
