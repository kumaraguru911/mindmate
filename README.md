# 💬 MindMate – Your AI Mental Health Companion

MindMate is a **Generative AI-powered mental health chatbot** designed to understand your thoughts, detect emotional tone, and offer supportive responses. Built for the Generative AI competition, this project highlights the power of AI to provide safe, smart, and empathetic conversations.

> ⚠️ **Disclaimer**: This project is for educational purposes only. MindMate is **not a substitute for professional mental health services**. If you're in crisis, please contact a certified mental health professional or emergency helpline.

---

## ✨ Features

- 🧠 **Mood Detection** – Understands if the user is feeling positive, neutral, negative, or in an emergency state.
- 🚨 **Violence & Suicide Detection** – Identifies harmful thoughts using NLP and classifies critical messages.
- 🤖 **Smart Responses via Gemini** – Uses Gemini Pro to generate context-aware, compassionate replies.
- 📈 **Visual Mood Tracker** *(optional)* – Track user's emotional patterns with simple charts.
- 🛡️ **Safety-First Responses** – Encourages help-seeking behavior and avoids reinforcing negative thoughts.

---

## 🛠️ Tech Stack

| Component          | Tech Used               |
|--------------------|-------------------------|
| Language           | Python                  |
| Platform           | Google Colab            |
| AI Model           | Gemini (Generative AI)  |
| NLP                | Scikit-learn / Regex    |
| Visualization      | Matplotlib              |


---

## 📸 Example Outputs

```bash
💬 Welcome to MindMate. Type 'exit' to quit.

User: I'm feeling really stressed about my exams.
Mood: 🙁 Negative
MindMate: I understand how exams can be overwhelming. Try to take breaks and talk to someone if you need support. You're doing your best!

User: It makes me want to give up and end everything.
Mood: 🚨 Emergency
MindMate: It sounds like you're going through a lot. Please talk to a mental health professional or contact a suicide prevention helpline. You're not alone. ❤️
