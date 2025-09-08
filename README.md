# JARVIS – Personal Voice Assistant 🎙️🤖

Jarvis is a **Python-based voice assistant** inspired by Iron Man’s J.A.R.V.I.S.  
It can **listen, respond, and perform tasks** such as sending WhatsApp messages, taking screenshots, opening apps, and playing music — all through **voice commands**.

---

## ✨ Features
- 🎤 **Voice Recognition** – Listen and process speech commands
- 🔊 **Text-to-Speech** – Respond with a natural voice
- 📷 **Screenshot & Camera** – Capture screen or open webcam
- 💬 **WhatsApp Automation** – Send scheduled messages via PyWhatKit
- 🎵 **Music Player** – Play songs via command
- 📝 **Task Manager** – Read tasks from `tasks.txt`
- 🎮 **Mini-Game & Utilities** – Calculator, file operations, and more

---

## 🛠️ Tech Stack
- **Language**: Python 3.12  
- **Libraries**:  
  - `pyttsx3` – Text to Speech  
  - `SpeechRecognition` – Voice input  
  - `pyaudio` – Microphone input  
  - `pyautogui` – Screenshots & GUI automation  
  - `opencv-python` – Camera features  
  - `pywhatkit` – WhatsApp messages & automation  
  - `requests` – Fetch APIs & online data  
  - `pillow` – Image handling  
  - `numpy` – Math & image operations  

---

## 📦 Installation

### 1. Clone the repository
```bash
git clone https://github.com/abhi3114-glitch/JARVIS-.git
cd JARVIS-
python -m venv .venv

# Activate it:
# On Windows:
.venv\Scripts\activate
# On Linux/Mac:
source .venv/bin/activate
pip install -r requirements.txt
python jarvis_main.py
Example commands:

"Open YouTube"

"Send WhatsApp message"

"Take screenshot"

"Play music"

"What’s the time?"
