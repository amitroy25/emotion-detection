# 😃 Emotion Classification Pipeline

A robust emotion classification pipeline combining the power of **FastText embeddings**, **character N-grams**, **contextual features**, and **LDA-based dimensionality reduction**—topped off with a **Random Forest classifier** for reliable prediction.

---

## 🚀 Features

- 🌐 FastText-based word embeddings for rich text representation
- 🧱 Character N-gram features for morphology
- 🧠 Contextual feature extraction (e.g., all caps, emojis, length)
- 🔄 Dimensionality reduction using Linear discriminant analysis (LDA)
- 🌲 Random Forest classifier for final emotion prediction

---

## 📊 Architecture Overview

Text Input → Preprocessing → Feature Extraction → LDA Reduction → Random Forest Classifier → Emotion Label


---

## 📦 Tech Stack

- Python
- FastText (Facebook AI)
- scikit-learn
- NLTK
- LDA
- Pandas, NumPy

---

## 🧪 How to Run

```bash
pip install -r requirements.txt
python main.py
```

---

##  Sample Predictions

Input: "I am feeling amazing today!"

Predicted Emotion: Joy

Input: "Why does everything go wrong?"

Predicted Emotion: Sadness

---

## 📊 Results
Accuracy: 64%


---

## Future Improvements
🚀 Deploy model via Flask or FastAPI

💻 Build a Web UI using Streamlit or Next.js

---
