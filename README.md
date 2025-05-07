# EVA – Offline AI Assistant for Android

EVA is an AI-powered personal assistant designed for Android devices that operates both offline and online. It offers voice recognition, text-to-speech, and a simple GUI to handle everyday tasks like opening apps, setting reminders, and fetching weather updates.

## 🔧 Features

- Voice Command Recognition (Offline & Online)
- Text-to-Speech Interaction
- Open Applications via Voice
- Set Reminders and Alarms
- Play Local Music
- Get Weather Info (via OpenWeatherMap API)
- Offline Functionality for Core Tasks
- GUI built with Python (Tkinter or PyQt)

## 🛠️ Tech Stack

- Python
- Tkinter / PyQt5 (for GUI)
- Vosk / SpeechRecognition (for voice input)
- pyttsx3 (text-to-speech)
- OpenWeatherMap API (for weather)
- Kivy (for Android deployment)

## 📁 Project Structure

```
eva/
├── main.py
├── gui.py
├── voice_engine.py
├── commands/
│   ├── weather.py
│   ├── open_app.py
│   └── reminder.py
├── assets/
│   └── icons, audio
├── requirements.txt
└── README.md
```

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/yourusername/eva-ai-assistant.git
cd eva-ai-assistant
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the assistant:

```bash
python main.py
```

## 👥 Authors

- Akhil Singh  
- Yash  
- Jai Kaushik  
- Anshul Tiwari  
  Faculty: Dr. Pankaj Aggarwal  
K.R. Mangalam University

## 📃 License

This project is licensed under the MIT License.
