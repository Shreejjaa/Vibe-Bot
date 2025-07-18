# 🤖 Vibe Bot (BuddyBot) – Emotion-Aware Chat Companion

Vibe Bot (also known as BuddyBot) is an AI-powered conversational assistant integrated into the Emotion-Based Movie Platform. It provides real-time emotional support, interactive conversations, and personalized responses based on the user's current emotional state, as detected via webcam using Google Teachable Machine.

## 🌟 Features

- 🎭 **Emotion Detection Integration**
  - Connects with the Teachable Machine emotion detection model.
  - Adapts tone and response based on detected mood (Happy, Sad, Angry, Neutral, Surprised).

- 🧠 **Conversational AI**
  - Friendly and empathetic chatbot that engages users.
  - Provides comfort, encouragement, or excitement based on user emotions.

- 📽️ **Movie-Based Mood Engagement**
  - Offers mood-specific movie scenes, genres, or endings.
  - Suggests personalized watchlists depending on how the user feels.

- 📝 **User Mood Logging**
  - Logs conversation summaries and emotional states for future personalization.
  - Supports better recommendation accuracy over time.

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Python with Flask
- **Chatbot Engine:** Python + Rule-Based / NLP-Driven Logic (can be extended with GPT-based APIs)
- **Emotion Detection:** Google Teachable Machine (custom-trained model)
- **Database:** MySQL (for mood logs, conversation history)

## 📁 Project Structure

Vibe-Bot-main/
│
├── static/ # CSS, JS, and model files
├── templates/ # HTML files (register.html, login.html, etc.)
├── app.py # Flask backend script
├── model/ # Teachable Machine exported model
├── requirements.txt # Python dependencies
└── README.md # Project documentation
