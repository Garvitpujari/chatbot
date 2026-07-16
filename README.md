# 🤖 LangGraph Chatbot

A conversational AI chatbot built using **LangGraph**, **LangChain**, **Groq Llama 3.3**, and **Streamlit**. The application supports persistent conversation history using LangGraph's `MemorySaver` checkpointer and provides an interactive chat interface.

## 🚀 Live Demo

**Streamlit App:** https://chatbot-4qyvmnxvyw6haq7gcupcun.streamlit.app/

---

## ✨ Features

- 💬 Interactive chat interface with Streamlit
- 🧠 Conversation memory using LangGraph MemorySaver
- ⚡ Powered by Groq's Llama 3.3-70B Versatile model
- 🔄 Persistent chat history during a session
- 🏗️ Modular frontend and backend architecture
- ☁️ Easily deployable on Streamlit Community Cloud

---

## 🛠️ Tech Stack

- Python
- Streamlit
- LangGraph
- LangChain
- LangChain Groq
- Groq API
- Pydantic
- Python Dotenv

---

## 📂 Project Structure

```text
chatbot/
│
├── streamlit_frontend.py      # Streamlit UI
├── langgraph_backend.py       # LangGraph workflow
├── requirements.txt
├── .gitignore
└── README.md
```

---

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/Garvitpujari/chatbot.git
cd chatbot
```

### Create a virtual environment

```bash
python -m venv venv
```

Activate it

**Windows**

```bash
venv\Scripts\activate
```

**Linux/macOS**

```bash
source venv/bin/activate
```

### Install dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Environment Variables

Create a `.env` file in the project root.

```env
GROQ_API_KEY=your_groq_api_key
```

---

## ▶️ Run Locally

```bash
streamlit run streamlit_frontend.py
```

---

## 🧠 LangGraph Workflow

```
START
   │
   ▼
chat_node
   │
   ▼
 END
```

The chatbot:

1. Receives the user message.
2. Sends it to the Groq LLM.
3. Stores conversation state using LangGraph's `MemorySaver`.
4. Returns the AI response to the Streamlit interface.

---

## 📸 Demo

Add screenshots or a GIF here.

Example:

```
assets/demo.png
```

---

## 📦 Requirements

Main libraries used:

- streamlit
- langgraph
- langchain
- langchain-core
- langchain-groq
- python-dotenv
- pydantic

---

## 👨‍💻 Author

**Garvit Pujari**

GitHub: https://github.com/Garvitpujari

---

## ⭐ If you found this project helpful

Please consider giving it a ⭐ on GitHub.
