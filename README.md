# GlowScanAI 🌟

AI-powered mobile skincare application built as a Final Year Project. GlowScanAI analyzes skin conditions using computer vision and provides personalized skincare recommendations for Pakistani users.

## 🎯 Overview

GlowScanAI helps users identify and understand skin issues through AI-powered image analysis, then delivers tailored skincare routines and product recommendations — all wrapped in a clean, mobile-first experience.

## ✨ Features

- 🔍 AI-based skin issue detection using deep learning
- 💡 Personalized skincare recommendations
- 📊 Scan history tracking
- 🔐 Secure user authentication (Firebase)
- 💬 AI chatbot for skincare guidance (powered by Gemini API)
- 📱 Cross-platform Flutter mobile app

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | Flutter, Dart |
| Backend | Python, Flask |
| AI/ML | PyTorch, EfficientNet, Hugging Face, SigLIP |
| AI Assistant | Google Gemini API |
| Database | Firebase Authentication, Cloud Firestore |

## 📁 Project Structure

```
GlowScanAI/
│
├── frontend/          # Flutter mobile application
│   └── lib/
│       ├── screens/    # UI screens (auth, dashboard, scan, chat, etc.)
│       ├── services/   # API, auth, firestore integration
│       └── widgets/    # Reusable UI components
│
├── backend/           # Flask API + AI model
│   ├── models/         # Skin analysis model logic
│   ├── routes/         # API endpoints
│   ├── services/       # Gemini chatbot integration
│   └── recommendation/ # Recommendation engine
│
└── README.md
```

## 🚀 Getting Started

### Backend
```bash
cd backend
pip install -r requirements.txt
python app.py
```

### Frontend
```bash
cd frontend
flutter pub get
flutter run
```

> **Note:** Firebase credentials, environment variables, and the trained model file are excluded from this repository for security and size reasons. Contact for setup details if you'd like to run this locally.

## 👥 Authors

This project was built as a Final Year Project by a team of three:

- **Muhammad Asad Arshad** — [GitHub](https://github.com/asad3212)
- **Laraib Hamid** — [GitHub](https://github.com/LaraibHamid) ([original repo](https://github.com/LaraibHamid/GlowScanAI))
- **Samavia Tanveer**

Supervised by **Sir Adeel Shehzad**, University of Gujrat.
# sampledatatest
