# 🧠 Saarthi — Bharat: AI Voice Assistant for the Visually Impaired

**Saarthi** is an AI-powered voice assistant project with a vision — helping visually impaired users navigate and interact with the world using voice commands, real-time object detection, emotion analysis, and web tools.

> 🗣️ Powered by Bharat — a smart, always-listening assistant.

---

## ✨ Features

- 🎙️ Continuous voice command recognition using SpeechRecognition
- 🧠 YOLOv8-powered object detection and navigation guidance
- 😊 Emotion recognition via DeepFace
- 🔍 Google Search + Wikipedia summary
- 📺 YouTube music/video playback via voice
- 📷 Mobile phone as wireless camera via IP Webcam
- 💻 Modern frontend with Next.js + Tailwind CSS
- ♿ Accessibility-focused UI with instructions

---

## 🚀 Getting Started

### 🧩 Prerequisites

- Python 3.9+
- Node.js 18+
- IP Webcam App on your Android phone
- YOLOv8 model: `yolov8n.pt` (in root)

---

### ⚙️ Backend Setup (FastAPI + YOLOv8 + DeepFace)

```bash
cd saarthi_backend

# Create and activate virtual environment
python -m venv venv
venv\Scripts\activate     # Windows
# source venv/bin/activate  # macOS/Linux

# Install Python dependencies
pip install -r requirements.txt

# Start the backend server
uvicorn main:app --reload --port 8000
