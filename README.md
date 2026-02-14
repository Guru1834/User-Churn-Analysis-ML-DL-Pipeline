# 📊 Customer Churn Prediction (End-to-End ML Pipeline)

An end-to-end Machine Learning project focused on predicting customer churn using behavioral and engagement features. The project explores feature engineering, imbalance handling, tree-based models, and neural networks while emphasizing proper evaluation and avoidance of data leakage.

---

## 🚀 Project Overview

Customer churn prediction helps businesses identify users at risk of leaving and enables proactive retention strategies.

This project implements a complete ML workflow:

- Synthetic dataset generation
- Churn definition using behavioral logic
- Feature engineering (recency, frequency, engagement metrics)
- Class imbalance handling
- Model comparison (Random Forest, XGBoost, MLP)
- Evaluation using ROC-AUC and confusion matrices

---

## 🧠 Key Challenges Addressed

- Avoiding **target leakage**
- Handling **class imbalance**
- Understanding why accuracy alone is misleading
- Comparing tree-based models vs neural networks for tabular data
- Identifying weak feature signals in synthetic datasets

---

## 📈 Models Implemented

- Random Forest Classifier
- XGBoost Classifier
- TensorFlow MLP (with EarlyStopping)

Evaluation Metrics:
- Accuracy
- Precision / Recall
- F1-Score
- ROC-AUC
- Confusion Matrix

---

## 📊 Results & Insights

- Accuracy alone was not reliable due to class imbalance.
- ROC-AUC provided better performance interpretation.
- Tree-based models outperformed neural networks for tabular churn data.
- Feature quality had greater impact than model complexity.

---

## 🛠 Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- TensorFlow / Keras
- Matplotlib / Seaborn

---

## 📌 Key Learnings

- Synthetic data must reflect realistic behavioral patterns.
- Feature engineering is more important than model choice.
- Imbalanced datasets require class weighting and proper metrics.
- Overfitting vs underfitting diagnosis using validation curves.
- ROC-AUC is more meaningful than accuracy in churn prediction.
