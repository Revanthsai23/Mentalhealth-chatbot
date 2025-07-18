# 💬 MoodCraft: A Deep Learning Framework for Context-Aware Emotion Classification

## 🧠 Project Overview
**MoodCraft** is a real-time, deep learning-based emotion classification system designed to assist users with mental health support through chatbot interaction. The system analyzes user input and classifies it into one of six emotions — **joy**, **sadness**, **anger**, **fear**, **love**, and **surprise** — using advanced NLP models such as BiGRU and Transformers. It also provides tools like cognitive assessments and mindfulness exercises.

---

## 🗂️ Project Structure

- `app.py` – Flask-based backend server for web interface and API.
- `moodcraft_emotion_model.ipynb` – Jupyter notebook with data preprocessing, model training, evaluation, and comparisons.
- `emotion_dataset.csv` – Labeled dataset used for emotion classification.
- `bigru_model.pth` – Trained PyTorch model for emotion classification.
- `templates/` – HTML templates for the web app frontend.
- `static/` – Static files including CSS, JavaScript, and media.
- `requirements.txt` – List of Python dependencies.

---

## 🎯 Features

- 🔍 **Emotion Detection** from user text using a BiGRU-based model.
- 💬 **Interactive Chatbot** for real-time emotional conversations.
- 🔐 **User Authentication** with role-based access control.
- 🧘 **Mindfulness Toolkit** with music therapy and guided meditation.
- 🧪 **Cognitive IQ Tests** to assess mental agility.
- 📊 **Feedback Collection** with visualization and analytics.

---

## 🛠️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-repo-name.git
   cd your-repo-name

2. **Install dependencies**
    ```bash
    pip install -r requirements.txt

3. **Launch the Flask application**
    ```bash
    python app.py
