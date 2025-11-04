# 💳 Credit Card Fraud Detection using Machine Learning (Scikit-learn & XGBoost)

## Project Overview
This project focuses on detecting fraudulent credit card transactions using multiple **machine learning classification algorithms**.  
Since the dataset is highly imbalanced, the **SMOTE (Synthetic Minority Over-sampling Technique)** method is used to balance the data.  
The models are evaluated based on **Precision**, **Recall**, **F1-Score**, and **ROC-AUC Score** to ensure reliable fraud detection performance.

---

## 🎯 Objectives
- Analyze and preprocess the credit card dataset  
- Handle class imbalance using **SMOTE**  
- Train multiple models for fraud detection  
- Tune hyperparameters for optimal performance  
- Compare models to identify the best one  

---

## 🧠 Algorithms Used
- Logistic Regression  
- K-Nearest Neighbors (KNN)  
- Random Forest Classifier  
- XGBoost Classifier  

---

## ⚙️ Technologies & Libraries
- **Python 3**
- **Scikit-learn**
- **XGBoost**
- **Imbalanced-learn (SMOTE)**
- **NumPy, Pandas**
- **Matplotlib, Seaborn**

---

## 📊 Model Performance Summary

| Model | Precision | Recall | F1-Score | ROC-AUC |
|:------|:----------:|:------:|:---------:|:--------:|
| Logistic Regression | 0.149 | 0.873 | 0.254 | 0.969 |
| K-Nearest Neighbors | 0.606 | 0.822 | 0.698 | 0.911 |
| Random Forest | 0.876 | 0.780 | 0.825 | 0.976 |
| **XGBoost (Tuned)** | **0.855** | **0.797** | **0.825** | **0.978** |

---

## 🏆 Final Model Result
After training and fine-tuning all models, **XGBoost** delivered the best results with:
- **Precision:** 0.855  
- **Recall:** 0.797  
- **F1-Score:** 0.825  
- **ROC-AUC:** 0.978  

✅ **XGBoost** was chosen as the final model for its strong balance between recall and precision, ensuring fewer false positives while effectively catching fraudulent transactions.

---

## 📈 Workflow Summary
1. Data Loading and Cleaning  
2. Exploratory Data Analysis (EDA)  
3. Feature Scaling using **StandardScaler**  
4. Balancing Classes with **SMOTE**  
5. Model Building and Evaluation  
6. Hyperparameter Tuning (for XGBoost)  
7. Final Comparison and Visualization  

---




