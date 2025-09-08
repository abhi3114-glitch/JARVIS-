# JARVIS  — Personal Voice Assistant

**JARVIS** is a Python-based voice assistant inspired by Iron Man’s J.A.R.V.I.S.  
This repository contains the Jarvis project files, utilities, assets, and demo media.

## Features
- Voice recognition (SpeechRecognition)
- Text-to-speech (pyttsx3)
- Screen capture & GUI automation (pyautogui)
- WhatsApp automation via `pywhatkit`
- Mini-games and utilities (calculator, task reader)
- Notification and custom sounds

## Quick start
```bash
# clone
git clone https://github.com/abhi3114-glitch/JARVIS-.git
cd JARVIS-

# recommended: create virtualenv
python -m venv .venv
# Windows:
.venv\Scripts\activate
# Linux/Mac:
source .venv/bin/activate

# install deps
pip install -r requirements.txt

# run jarvis
python jarvis/jarvis_main.py
