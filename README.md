AI-powered Interview Practice Web App built with Streamlit that helps candidates practice interviews with role-based questions, follow-ups, and AI-generated feedback. Supports voice input, text input, and provides a final evaluation.

🚀 Features

Role-based interviews: Engineer, Sales, Retail Associate

Dynamic follow-up questions: 5-question interview (starter + 4 follow-ups)

Voice & text input: Speak your answers or type them

Candidate name support: Personalized interview experience

AI-generated feedback: Strengths, weaknesses, score, and improvement tips

Local model support: Uses a CapybaraHermes-2.5-Mistral-7B GGUF model for offline inference

AI feedback summary

⚡ Requirements

Python 3.10+

Packages: streamlit, pyttsx3, speechrecognition, pyaudio, llama-cpp-python

Local model: CapybaraHermes-2.5-Mistral-7B GGUF (≤ 2GB version recommended)

💻 Installation

Install dependencies

pip install streamlit pyttsx3 speechrecognition pyaudio llama-cpp-python

Download the local GGUF model Place your model in a folder (e.g., models/) and update model_path in interview_app.py:

model_path = r"D:\praveen\models\CapybaraHermes-2.5-Mistral-7B\capybarahermes-2.5-mistral-7b.Q4_K_S.gguf"

Run the app

streamlit run interview_app.py

📝 Usage

Open the app in your browser.

Enter candidate name and select role.

Click Start Interview.

Answer questions using voice or text.

Click Next to proceed through 5 questions.

At the end, view AI-generated feedback.

Restart anytime using Start Again 🔁.

💡 Future Enhancements

Adaptive AI follow-ups personalized to answers

Answer scoring: communication, technical depth, clarity

Export transcript + feedback to PDF

Multi-role support: HR, Behavioral, Technical, System Design

📜 License

This project is licensed under MIT License.# Interview-Bot
