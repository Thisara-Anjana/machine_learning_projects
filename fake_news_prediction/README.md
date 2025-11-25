# 📰 Fake News Prediction Model

## 📌 Overview
This project predicts whether a news article is **real or fake** using machine learning.  
It was built and tested on **Google Colab** for easy reproducibility.

---

## 📂 Dataset
- Source: [Kaggle Fake News Dataset]
- Contains labeled news articles with text and target labels (`1 = fake`, `0 = real`).

---

## ⚙️ Steps
1. **Data Preprocessing**
   - Removed stopwords, punctuation, and applied tokenization
   - Converted text into numerical features using **TF-IDF**

2. **Model Training**
   - Tried multiple classifiers:
     - Logistic Regression
     - Naive Bayes
     - Random Forest
   - Selected the best-performing model based on accuracy

3. **Evaluation**
   - Metrics: Accuracy, Precision, Recall, F1-score
   - Confusion matrix for visualization

---

## 📊 Results
- Best model: **Logistic Regression**
