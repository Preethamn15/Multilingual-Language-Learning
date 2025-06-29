# VakyaAI — Multilingual AI Language Learning Platform

## 🌍 Overview
**VakyaAI** is a multilingual language learning platform integrated with an AI-powered chatbot designed to enhance user engagement, accessibility, and personalized learning in education.

Leveraging state-of-the-art **Natural Language Processing (NLP)**, **LangGraph-based conversational memory**, and low-latency inference with the **Groq-hosted LLaMA 3.2B model**, VakyaAI facilitates real-time, interactive conversations with grammar correction, vocabulary assistance, and contextual feedback.

A unique feature of VakyaAI is its seamless support for both **text and voice-based interactions**, enabling learners to practice **speaking, listening, reading, and writing** skills in multiple languages.

---

##  Features
-    **Multilingual AI Chatbot** — Supports multiple languages with contextual understanding.
-    **Voice & Text Interaction** — Speak or type; receive both audio and text responses.
-    **Grammar & Vocabulary Assistance** — Instant corrections and suggestions.
-    **Conversational Memory** — Context-aware, coherent dialogues powered by LangGraph.
-    **Lightweight Deployment** — Built using Streamlit for web-based interaction.
-    **Low Latency AI Inference** — Powered by Groq-hosted LLaMA 3.2B for real-time responses.
-    **Self-paced Learning** — Adaptive, interactive, and user-centric educational environment.

---

##  Use Cases
-   Language learning for students, travelers, and professionals.
-   Pronunciation practice through speech-to-text and audio feedback.
-   Conversational AI for educational institutions.
-   AI-assisted tutoring in multilingual settings.

---

| Component            | Technology/Library                     | Purpose                                       |
| -------------------- | -------------------------------------- | --------------------------------------------- |
| Frontend/UI          | **Streamlit**                          | Simple web app interface                      |
| AI Model             | **Groq (Llama 3 70B via Groq API)**    | Generates AI chat responses                   |
| Text-to-Speech (TTS) | **gTTS (Google Text-to-Speech)**       | Converts text responses to speech             |
| Speech-to-Text (STT) | **SpeechRecognition + Google API**     | Converts voice input to text (local only)     |
| Environment Vars     | **python-dotenv**                      | Loads API keys from `.env` securely           |
| Audio Encoding       | **base64**                             | Embeds audio players in the web page          |
| Utilities            | **uuid, datetime, re**                 | Manage session IDs, time stamps, text cleanup |
| Deployment           | **Streamlit Community Cloud / GitHub** | Host app online                               |


---

## 🎥 Demo Video

### 📱 Mobile App Demo
This is how it works when you use VakyaAI as a mobile app.

[![Watch the Demo](Video-demo/thumbnail.jpg)](Video-demo/Mobile-app.mp4)

Click the image above to watch the demo video showcasing the multilingual language learning mobile app in action.

---

### 💻 Local Deployment Demo
This is how it works when this repository is cloned into your local system and run.

[![Watch the Demo](Video-demo/thumbnail.jpg)](Video-demo/Voice%20AI%20Chatbot.mp4)

Click the image above to watch the demo video showcasing the AI-powered voice chatbot running locally.

## 🚀 Installation & Setup

1. Clone the repository:
```bash
git clone https://github.com/your-username/VakyaAI.git
cd VakyaAI

pip install -r requirements.txt

streamlit run app/main.py
```

How to Use VakyaAI
  Open the web interface.
  Select your preferred language.
  Choose Text Chat or Voice Chat.
  Start interacting with the AI — get grammar corrections, vocabulary suggestions, and pronunciation feedback.


contributions: Nandeesh C M nandeeshel2023@gmail.com

**Contact** 
📧 preetham159@gmail.com
📧 preethamn2004@gmail.com
