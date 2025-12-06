# Twitter-Sentiment-Analysis
# "𝕏" Twitter Sentiment Analysis — Project Summary

This project focuses on performing **Sentiment Analysis on Twitter data** using Machine Learning and Natural Language Processing (NLP). It processes tweets from two datasets — `twitter_training.csv` and `twitter_validation.csv` — and classifies them as **Positive** or **Negative**. The project is designed to understand public opinion, analyze reactions to events, and study user sentiment across different topics.

---

## 📌 Project Overview
The workflow includes:
- Loading and preparing the datasets  
- Cleaning and preprocessing tweet text  
- Transforming text into numerical features using TF-IDF  
- Training multiple ML models  
- Evaluating and comparing results  
- Visualizing sentiment distribution and model performance  

This allows effective analysis of public sentiment trends, reactions to brands, products, or social issues.

---

## 📂 Dataset Description
Each dataset contains:
- Tweet ID  
- Topic (e.g., Borderlands, Facebook)  
- Sentiment label  
- Raw tweet text  

Only **Positive** and **Negative** tweets are used for binary classification (Irrelevant/Neutral entries are removed).

---

## 🧹 Data Processing Summary
Text preprocessing includes:
- Lowercasing  
- Removing URLs, punctuation, special characters  
- Removing numbers and extra spaces  
- Tokenization  
- Stopword removal  
- Optional lemmatization  

Processed text is vectorized using **TF-IDF n-grams**, enabling the ML models to learn meaningful patterns.

---

## 🤖 Models Used
Three models are trained and evaluated:
- **Bernoulli Naive Bayes** – A simple, fast baseline classifier  
- **Linear SVM** – Best-performing model for sparse text features  
- **Logistic Regression** – Strong and well-balanced classifier  

Performance is measured using accuracy, precision, recall, and F1-score.

---

## 📊 Visualizations Included
The notebook includes useful visualizations such as:
- Positive vs Negative **sentiment distribution**
- **Accuracy comparison** between models
- **Confusion matrix** for each classifier
- Optional **word frequency visualizations**
- Optional **word cloud replacements** or bar graphs for top words

These graphs help understand dataset structure and model behavior.

---

## 📈 Results Summary
- **Linear SVM performs the best (~94% accuracy)**  
- Logistic Regression performs strongly (~93%)  
- Bernoulli Naive Bayes serves as a solid baseline (~87%)  

Sample predictions show consistent results across all classifiers.

---

## 🏁 Conclusion
This project provides a complete end-to-end **Twitter Sentiment Analysis pipeline** with data cleaning, feature extraction, model building, evaluation, and visualization. It is well-suited for academic purposes, research, or real-world applications such as brand monitoring and social media analytics.

---
