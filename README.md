<div align="center">
  <h1>🏋️‍♀️ AI Gym Coach</h1>
  <p><strong>Your Personal AI-Powered Real-Time Fitness Trainer</strong></p>
  <p>
    <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
    <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" alt="Streamlit" />
    <img src="https://img.shields.io/badge/WebRTC-333333?style=for-the-badge&logo=webrtc&logoColor=white" alt="WebRTC" />
    <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite" />
    <img src="https://img.shields.io/badge/AI_Coaching-F7931E?style=for-the-badge&logo=openai&logoColor=white" alt="AI Coaching" />
  </p>
</div>

---

## 📖 Overview
Welcome to the **AI Gym Coach**! This is a smart, interactive fitness application built to be your personal virtual trainer. By leveraging the power of computer vision and real-time video processing, the app monitors your exercise form through your webcam.

Integrated with **Groq LLM** and a **Text-to-Speech (TTS) pipeline**, the app provides intelligent, real-time voice feedback, counts your reps, tracks your metrics, and helps you maintain perfect form throughout your workout.

---

## 🌟 Key Features
- **🎥 Real-time Form Tracking:** Uses live webcam feed (via Streamlit WebRTC) to analyze your movements.
- **🗣️ AI Voice Coaching:** Powered by Groq, providing dynamic, spoken feedback to correct your form and keep you motivated.
- **📊 Workout Analytics:** Tracks your reps, sets, and progress over time with built-in database persistence.
- **🔒 Secure Authentication:** Built-in login wall to keep user data private.

---

## 📸 Screenshots

### Dashboard UI
![Dashboard Interface](Main%20App/static/images/UI%20Img%201.png)

### Real-time Coaching UI
![Real-time Tracking Interface](Main%20App/static/images/UI%20Img%202.png)

---

## 🚀 Installation & Setup (Windows)

Follow these steps to get the project running locally on your Windows machine:

### 1. Prerequisites
- [Python 3.8+](https://www.python.org/downloads/) installed on your system.
- Git installed.
- A webcam for real-time tracking.
- A [Groq API Key](https://console.groq.com/keys) for the AI voice coaching.

### 2. Clone the Repository
Open PowerShell or Command Prompt and run:
```powershell
git clone https://github.com/Sumit07125/Ai-Gym-Coach.git
cd Ai-Gym-Coach
```

### 3. Set up a Virtual Environment
It is highly recommended to use a virtual environment to manage dependencies.
```powershell
# Create a virtual environment named 'venv'
python -m venv venv

# Activate the virtual environment
.\venv\Scripts\activate
```

### 4. Install Dependencies
Navigate to the `Main App` folder and install the required Python packages:
```powershell
cd "Main App"
pip install -r requirements.txt
```

### 5. Environment Variables
Create a `.env` file in the root of your project and add your Groq API Key:
```env
GROQ_API_KEY=your_groq_api_key_here
```

### 6. Run the Application
Start the Streamlit application:
```powershell
streamlit run main.py
```
The application will automatically open in your default web browser at `http://localhost:8501`.

---

<div align="center">
  <h3>Developed By <code>getch();</code> ❤️</h3>
</div>