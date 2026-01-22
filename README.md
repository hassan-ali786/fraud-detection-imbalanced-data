# Fraud Detection using Machine Learning

## 📌 Project Overview
This project detects fraudulent credit card transactions using machine learning on a highly imbalanced dataset. The focus is on precision-recall evaluation and real-world fraud detection trade-offs.

## 📊 Dataset
- Source: Kaggle – Credit Card Fraud Detection Dataset
- Features:
  - Time
  - Amount
  - PCA-transformed anonymized features (V1–V28)
- Target:
  - Class (0 = Legit, 1 = Fraud)

## 🛠 Tools & Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

## 🔍 Methodology
- Analyzed class imbalance
- Used stratified train-test split
- Applied class weighting
- Trained:
  - Logistic Regression
  - Random Forest Classifier
- Evaluated using Precision, Recall, and F1-score

## ⚖ Trade-offs Discussion
- Accuracy is misleading for fraud detection
- Precision reduces false fraud alerts
- Recall ensures fraudulent transactions are caught
- Logistic Regression is interpretable
- Random Forest captures complex patterns but is less explainable

## 🚀 How to Run
1. Download `creditcard.csv` from Kaggle
2. Place it in the project folder
3. Run the Jupyter Notebook

## 👤 Author
Hassan Ali
