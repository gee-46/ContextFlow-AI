# 🧠 ContextFlow AI

### Intelligent Conversational Q&A Chatbot with Context Retention

---

## 🏷️ Badges

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge\&logo=python)
![Streamlit](https://img.shields.io/badge/Streamlit-App-red?style=for-the-badge\&logo=streamlit)
![Google Gemini](https://img.shields.io/badge/LLM-Gemini%20Pro-black?style=for-the-badge\&logo=google)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active-success?style=for-the-badge)

---

## 🚀 Overview

**ContextFlow AI** is a conversational question-answering chatbot that delivers intelligent, context-aware responses using **Google Gemini Pro**.

Unlike basic chatbots that forget previous inputs, ContextFlow AI maintains conversation flow, allowing users to ask follow-up questions naturally without repeating information.

Built with **Streamlit**, this project offers a clean interface and real-time interaction, making it ideal for demos, hackathons, and AI experimentation.

---

## ✨ Key Features

### 💬 Context-Aware Conversations

* Maintains chat history using Streamlit session state
* Enables multi-turn conversations
* Understands follow-up queries without re-explaining context

### ⚡ Streaming Responses

* Real-time response generation using Gemini streaming
* Faster and more interactive user experience

### 🧠 Powered by Gemini Pro

* High-quality natural language understanding
* Accurate and structured responses

### 🖥️ Simple & Interactive UI

* Built with Streamlit
* Minimal and user-friendly interface

### 🔐 Secure API Handling

* Uses `.env` file for managing API keys securely

---

## 🏗️ Tech Stack

* **Frontend**: Streamlit
* **Backend**: Python
* **LLM**: Google Generative AI (Gemini Pro)
* **Environment Management**: python-dotenv

---

## 📂 Project Structure

```
├── app.py              # Main Streamlit application
├── .env                # API keys (not pushed to GitHub)
├── requirements.txt    # Dependencies
└── README.md
```

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/contextflow-ai.git
cd contextflow-ai
```

### 2. Create Virtual Environment (Recommended)

```bash
conda create -n contextflow python=3.10
conda activate contextflow
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure Environment Variables

Create a `.env` file in the root directory:

```env
GOOGLE_API_KEY=your_api_key_here
```

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

---

## 🧩 How It Works

1. User enters a question in the input field
2. Input is sent to the Gemini Pro model
3. Model processes input along with previous chat history
4. Response is streamed back in real time
5. Conversation history is stored and displayed

---

## 📸 Demo Screenshots



### 🖥️ Chat Interface

![Chat UI](https://via.placeholder.com/800x400?text=Chat+Interface+Screenshot)

### ⚡ Streaming Response Example

![Streaming](https://via.placeholder.com/800x400?text=Streaming+Response)

### 🧠 Context Awareness Demo

![Context](https://via.placeholder.com/800x400?text=Context+Retention+Example)

---

## 📌 Use Cases

* 🤖 Personal AI assistant
* 📚 Study helper for students
* 💼 Hackathon and demo projects
* 🧪 Experimenting with LLMs
* 🔄 Multi-turn conversational systems

---

## 🚧 Future Enhancements

* 🔍 Retrieval-Augmented Generation (RAG)
* 🗄️ Database integration (SQLite / MongoDB)
* 🔐 User authentication system
* 🎙️ Voice-based interaction
* ☁️ Cloud deployment (AWS / Streamlit Cloud)

---

## 🤝 Contributing

Contributions are welcome! Fork the repository and submit a pull request.

---

## 📜 License

This project is licensed under the **Apache License 2.0.**

---

## 👨‍💻 Author

**Gautam N Chipkar**

---

> "Context isn’t memory — it’s continuity."
