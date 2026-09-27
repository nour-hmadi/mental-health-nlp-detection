# 🧠 Mental Health Detection from Reddit Posts

A multi-model NLP classification system to automatically detect mental health conditions from Reddit posts.

## 📌 Project Overview

This project compares **6 machine learning models** across 3 categories to classify Reddit posts into 5 mental health categories: **ADHD, OCD, Aspergers, Depression, and PTSD**.

## 📊 Results

| Model | Accuracy | F1 Score |
|-------|----------|----------|
| RoBERTa 🏆 | 83.91% | 83.89% |
| SVM (Tuned) | 79.09% | 78.93% |
| Logistic Regression | 78.31% | 78.23% |
| DistilBERT | 77.88% | 77.97% |
| Naive Bayes (Tuned) | 73.41% | 72.89% |
| LSTM | 53.79% | 53.20% |

## 🗄️ Dataset

- **Source:** HuggingFace — `solomonk/reddit_mental_health_posts`
- **Total posts:** 151,288 → sampled 10,000 → 5,810 after cleaning
- **Categories:** ADHD, OCD, Aspergers, Depression, PTSD

## 🤖 Models Used

- **Classical ML:** Logistic Regression, Naive Bayes, SVM
- **Deep Learning:** Bidirectional LSTM
- **Transformers:** DistilBERT, RoBERTa

## 🔬 Advanced Techniques

- 5-Fold Cross Validation
- Hyperparameter Tuning (Grid Search)
- Learning Curves
- Statistical Significance Testing (p-value = 0.0000)

## 🛠️ Tools & Technologies

Python · PyTorch · HuggingFace Transformers · Scikit-learn · Pandas · Matplotlib · Google Colab (GPU)

## 👩‍💻 Authors

Jad Bayda, Nour Hmadeh, Hayfa Rustom
*MSc Data Science — Université Saint-Joseph de Beyrouth*
