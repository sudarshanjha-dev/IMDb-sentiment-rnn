# 🎬 IMDb Sentiment Analysis using RNN

This project is a Natural Language Processing (NLP) model that classifies IMDb movie reviews as positive or negative using a Recurrent Neural Network (RNN).

---

## 📌 Project Overview

The goal of this project is to build a deep learning model that can understand movie reviews and predict sentiment.

- Input: Movie review text  
- Output: Positive (1) or Negative (0)  
- Model: Recurrent Neural Network (RNN)  
- Dataset: IMDb movie reviews dataset (Keras)

---

## 🧠 Problem Statement

Given a movie review, predict whether the sentiment is:

- Positive 👍  
- Negative 👎  

This is a binary text classification problem in NLP.

---

## 📂 Dataset

- Dataset: IMDb Reviews Dataset (Keras / TensorFlow)
- Total samples: 50,000 reviews
- Training: 25,000
- Testing: 25,000
- Labels:
  - 0 → Negative review
  - 1 → Positive review

---

## ⚙️ Tech Stack

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- NLP preprocessing (tokenization, padding)

---

## 🏗️ Model Architecture

Embedding Layer  
↓  
SimpleRNN / LSTM Layer  
↓  
Dense Layer (ReLU)  
↓  
Dropout (optional)  
↓  
Dense Layer (Sigmoid)

---

## 🔄 Workflow

1. Load IMDb dataset  
2. Preprocess text (tokenization + padding)  
3. Build RNN model  
4. Train model  
5. Evaluate performance  
6. Make predictions on custom reviews  

---



## 🚀 How to Run This Project

### 1. Clone the repository
```bash
git clone https://github.com/sudarshanjha-dev/IMDb-sentiment-rnn.git
cd IMDb-sentiment-rnn
