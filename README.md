# 📌 Twitter Sentiment Analysis using Logistic Regression (From Scratch)

This project performs **sentiment analysis on Twitter data** using a **Logistic Regression model implemented from scratch** (without scikit-learn).  
It classifies tweets as **positive** or **negative** using NLP preprocessing and frequency-based features.

---

## 🚀 Features
- Logistic Regression implemented **manually using NumPy**
- Achieved **99.5% accuracy** on the test dataset (10,000 tweets)
- Full NLP pipeline using NLTK:
  - Tokenization  
  - Stopword removal  
  - Stemming  
- Frequency-based feature extraction  
- End-to-end ML workflow: preprocessing → training → prediction → error analysis

---

## 🧰 Tech Stack
**Python, NumPy, Pandas, NLTK, Jupyter Notebook**  
**Logistic Regression (from scratch), Gradient Descent**

---

## 🧹 NLP Preprocessing Steps
1. Lowercasing  
2. Remove URLs, RTs, mentions  
3. Tokenization  
4. Stopword removal  
5. Stemming using Porter Stemmer  
6. Word frequency mapping  
7. Convert text → feature vectors  
