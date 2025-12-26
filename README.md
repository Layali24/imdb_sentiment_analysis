# 🎬 IMDB Sentiment Analysis (NLP Project)

A machine learning project that analyzes movie reviews and predicts the sentiment (Positive / Negative).  
This project uses real IMDB data from Kaggle + TF-IDF + Logistic Regression to build a simple and effective NLP sentiment classifier.

---

## 🚀 Project Overview
The goal is to create a model that:
- Takes a movie review as input
- Cleans and preprocesses the text
- Converts the text into numerical features using **TF-IDF**
- Predicts whether the sentiment is **positive** or **negative**

This project is practical, simple, and perfect as a portfolio piece for Machine Learning / NLP beginners.

---

## 📂 Project Structure
```
imdb-sentiment-analysis/
│
├── notebooks/
│ └── imdb_sentiment_analysis.ipynb # Main Google Colab notebook
│
├── models/
│ ├── imdb_sentiment_model.pkl # Saved trained model
│ └── imdb_tfidf_vectorizer.pkl # Saved TF-IDF vectorizer
│
├── data/
│ └── README-data-source.txt # Kaggle dataset link (not the dataset itself)
│
├── requirements.txt
└── README.md
```
---

## 📊 Dataset Information
Dataset used: **IMDB Dataset of 50K Movie Reviews** (Kaggle)

🔗 Dataset link (download only):  
https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews

> ⚠️ Note: The CSV file is **not included** in this repository due to Kaggle license rules.

---

## 🧠 How the Model Works
1. Load and clean movie review text
2. Convert text to numbers using **TF-IDF**
3. Train a **Logistic Regression** classifier
4. Evaluate performance with accuracy & classification metrics
5. Predict sentiment for new reviews

---

## 📎 Example Usage
```python
predict_sentiment("I loved this movie, it was emotional and beautiful!")
# -> positive

predict_sentiment("This was a boring film, I regret watching it.")
# -> negative
```
---
## 🔧 Technologies Used

Python

NLTK

Pandas / NumPy

Scikit-learn

Google Colab

TF-IDF Vectorizer

---
