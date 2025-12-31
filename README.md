# 🎭 AI Face Emotion HUD

A real-time **AI-powered face emotion detection HUD** built with **Python, OpenCV, and DeepFace**.  
The application captures live webcam video, analyzes facial expressions, and displays emotion confidence scores in a clean, futuristic HUD interface.

---

## ✨ Features

- 🎥 Live webcam feed using OpenCV  
- 🧠 Real-time facial emotion recognition  
- 😊 Tracks **5 emotions**:
  - Angry
  - Happy
  - Sad
  - Surprise
  - Neutral
- 📊 Confidence bars for each emotion  
- ⚡ Optimized analysis for smooth performance  
- 🎨 HUD-style overlay with dynamic updates  

---

## 🧠 How It Works

1. The webcam captures live frames using **OpenCV**.
2. Every **0.6 seconds**, a frame is analyzed using **DeepFace**.
3. DeepFace returns confidence scores (0–100%) for facial emotions.
4. The system:
   - Identifies the dominant emotion
   - Displays it with confidence percentage
   - Shows all tracked emotions as progress bars
5. The HUD updates continuously until the user exits.

---

## 🛠️ Tech Stack

| Category | Technology |
|--------|------------|
| Language | Python |
| Computer Vision | OpenCV |
| Emotion Detection | DeepFace |
| Deep Learning Backend | TensorFlow / Keras |
| UI Overlay | OpenCV drawing utilities |

---

## 📂 Project Structure

```text
AI-Face-Emotion-HUD/AI-Face-Emotion-HUD/
│
├── emotion_hud.py      # Main application script
└── README.md           # Project documentation
│
├── emotion_hud.py      # Main application script
└── README.md           # Project documentation
