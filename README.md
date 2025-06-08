# JARVIS---Voice-Assistant
 JARVIS is an intelligent, voice-activated personal assistant that enables users to interact with their systems using  natural language.
# 🤖 JARVIS - Voice Assistant.

JARVIS is an advanced voice assistant built using **Python**, **Eel.js**, **HTML**, and **CSS**, capable of handling real-time tasks and open-ended conversations. It integrates Deep Learning, APIs, and voice interaction to deliver a smart, responsive assistant experience.

---

## 🔧 Features

- 🎤 **Speech Recognition** & 🗣️ **Text-to-Speech**
- 🌦️ Real-time **Weather Information** (OpenWeather API)
- 📰 Latest **News Headlines** by Country (NewsAPI)
- 🎬 **Movie & TV Show Info** (TMDB API)
- 🧮 **Math & GK Q&A** (WolframAlpha API)
- 💬 **Simple Chatbot** using Deep Learning + `intents.json`
- 📱 WhatsApp **Messaging**, **Calling**, and **Video Calling**
- 🌐 Open **Websites** and **Play YouTube** content

---

## 🧠 AI & NLP

- **Custom Intent Handling**:
  - Deep Learning model trained on static queries (e.g. greetings, creator name)
  - Preprocessing: Tokenization, Lemmatization, Bag-of-Words
  - Model: Simple Feedforward Neural Network using Keras
- **General Conversation**:
  - Powered by Hugging Face Transformers for dynamic queries
- **Smart Routing**:
  - Static questions → Custom DL model
  - Dynamic/general questions → Hugging Face
  - Task-related queries → External APIs

---

## 🧱 Tech Stack

**Frontend:**
- HTML, CSS, JavaScript (via Eel interface)

**Backend:**
- Python (modular structure for each functionality)

**Speech:**
- `speech_recognition`, `pyttsx3`

**Machine Learning:**
- Keras, TensorFlow, NLTK

**APIs:**
- TMDB, NewsAPI, WolframAlpha, OpenWeather

**Tools:**
- VS Code, GitHub, SQLite (for WhatsApp contacts)

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/JARVIS-Voice-Assistant.git
   cd JARVIS-Voice-Assistant
