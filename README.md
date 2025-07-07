# 🔒 Phishing Detector using Classification Models

This project focuses on detecting phishing websites using machine learning classification algorithms. It uses various handcrafted features extracted from URLs to train models that can effectively distinguish between legitimate and phishing websites.

---

## 📌 Project Overview

Phishing is a type of cyberattack where attackers trick users into clicking malicious links, often mimicking trusted sites. In this project, we use URL-based features to build and evaluate classification models that can detect phishing attempts.

---

## 🧠 Key Features

- Feature engineering on URLs (length, presence of special characters, SSL usage, etc.)
- Binary classification: phishing (1) or legitimate (0)
- Models used: Logistic Regression, Random Forest, Decision Tree, and more
- Evaluation using accuracy, confusion matrix, and ROC-AUC score

---

## 🧪 Models & Evaluation

| Model              | Accuracy | AUC Score |
|--------------------|----------|-----------|
| Logistic Regression | 0.92     | 0.98     |
| Random Forest       | 0.96     | 1        |
| XGBoost             | 0.96     | 1        |

- ROC Curve plotted to visualize model performance
- Confusion matrix used for detailed error analysis

---

## 🛠️ Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook
