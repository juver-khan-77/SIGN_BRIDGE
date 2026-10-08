# SIGN_BRIDGE

> Real-time sign language → text & speech using computer vision.

Sign Bridge is a browser-based system that uses a webcam, Google MediaPipe, and WebAssembly to recognize hand gestures and facial expressions and convert them into text or speech.

## Features

- 🖐️ Real-time hand gesture recognition
- 🙂 Facial expression detection
- 🔊 Text-to-speech output
- ⚡ Runs directly in the browser
- 🔒 Video processing stays on-device
- 📱 Responsive interface

## Tech Stack

- HTML5
- CSS3
- JavaScript
- Google MediaPipe
- WebAssembly
- Web Speech API
- Netlify

## How It Works

**Webcam → MediaPipe → Gesture & Expression Analysis → Sign Dataset → Text / Speech**

The system reads hand landmarks, converts finger positions into sign patterns, and maps them to predefined signs and phrases.

## Run Locally

```bash
git clone https://github.com/<your-username>/SIGN_BRIDGE.git
cd SIGN_BRIDGE
python -m http.server 8000
```

Open:

```text
http://localhost:8000
```

## Live Demo

https://sign-bridge-backup.netlify.app

## Status

🟢 In active development

## Author

**Juver Khan**

Built with curiosity, code, and a lot of experimentation. 🚀
