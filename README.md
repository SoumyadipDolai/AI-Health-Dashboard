# 🩺 AI-Powered Personal Health Dashboard

A cross-language project that tracks, analyzes, and predicts health trends using **C, Java, Python, and HTML/JS**.

---

## 🚀 Features
- Track calories, workout, sleep, and daily activity.
- Predict wellness score with AI.
- Real-time sensor simulation (steps & heart rate).
- Visual dashboard with charts.
- Secure backend for user login & data storage.

---

## 🏗 Tech Stack
- **Frontend (HTML/CSS/JS):** UI and charts
- **Java:** Backend services & data storage
- **Python:** AI engine for predictions
- **C:** Low-level device simulator

---

## 📂 Folder Structure
---

AI-Health-Dashboard/
│── frontend/
│   ├── index.html
│   ├── dashboard.html
│   ├── style.css
│   └── script.js
│
│── backend-java/
│   ├── src/
│   │   └── Main.java
│   └── README.md
│
│── ai-engine-python/
│   ├── health_predictor.py
│   ├── data_preprocessing.py
│   ├── requirements.txt
│   └── README.md
│
│── c-sensor-simulator/
│   ├── step_counter.c
│   ├── heart_rate.c
│   ├── Makefile
│   └── README.md
│
│── docs/
│   ├── architecture.png   (diagram placeholder)
│   └── README.md
│
│── LICENSE
│── README.md
└── run.sh

## ▶️ Run Instructions

```bash
cd frontend
open index.html   # or run with Live Server in VS Code
cd backend-java
javac src/Main.java
java src.Main
cd ai-engine-python
pip install -r requirements.txt
python health_predictor.py
cd c-sensor-simulator
make
./step_counter
./heart_rate
