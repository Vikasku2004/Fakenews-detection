# Fake-News-Detection-Machine-Learning
Developed a Fake News Detection system using Machine Learning with TF-IDF vectorization and Logistic Regression. The model processes and analyzes news text to classify it as real or fake with high accuracy. Built an interactive web interface using Streamlit for real-time predictions.
# 📰 Fake News Detection System

An end-to-end Machine Learning project that detects whether a news article is **Real or Fake** using Natural Language Processing (NLP) techniques and a Streamlit web interface.

---

## 🚀 Project Overview

Fake news has become a major issue in the digital world. This project aims to automatically classify news articles as **real or fake** using machine learning algorithms.

The system processes textual data, applies NLP techniques, and predicts the authenticity of news content in real-time.

---

## 🧠 Features

- 🔍 Real-time news classification (Fake / Real)
- ⚡ Fast and lightweight ML model
- 🧹 Text preprocessing (cleaning, stemming, stopword removal)
- 📊 TF-IDF vectorization for feature extraction
- 🌐 Interactive web app using Streamlit
- 📈 Model accuracy display

---

## 🛠️ Tech Stack

### 👨‍💻 Languages
- Python

### 📚 Libraries & Tools
- Pandas, NumPy
- NLTK (Natural Language Processing)
- Scikit-learn
- Streamlit

### 🤖 Machine Learning
- TF-IDF Vectorizer
- Logistic Regression

---

## 📂 Project Structure

ake-news-detector/
│── app.py # Main Streamlit application
│── train.csv # Dataset
│── requirements.txt # Dependencies
│── README.md # Project documentation


---

## ⚙️ How It Works

1. **Data Loading**
   - Dataset is loaded and cleaned (handling missing values)

2. **Text Preprocessing**
   - Remove special characters
   - Convert text to lowercase
   - Remove stopwords
   - Apply stemming

3. **Feature Extraction**
   - Convert text into numerical format using TF-IDF

4. **Model Training**
   - Logistic Regression is trained on processed data

5. **Prediction**
   - User input is processed and classified as:
     - ✅ Real News
     - 🚨 Fake News

---

## ▶️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/fake-news-detector.git
cd fake-news-detector
