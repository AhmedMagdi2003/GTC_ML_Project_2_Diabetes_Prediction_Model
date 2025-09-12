# 🩺 Diabetes Classification with Machine Learning

## 📌 Overview
This project predicts diabetes using the Pima Indians dataset.  
It covers correlation analysis, feature engineering, handling imbalance with SMOTE, and classification with **SVM** and **Gradient Boosting**, tuned via GridSearchCV.

---

## 📊 Dataset
- Features: Glucose, Insulin, BMI, Age, Blood Pressure, etc.  
- Target: `Outcome` (0 = Non-diabetic, 1 = Diabetic).

---

## 🔎 Workflow
1. **EDA & Correlation Analysis**  
   - Glucose and Insulin show the strongest correlation with Outcome.  

2. **Feature Engineering**  
   - Handling zero-like values.  
   - Binning Age & BMI.  
   - Feature scaling for SVM.  

4. **Modeling & Tuning**  
   - **SVM** and **Gradient Boosting**.  
   - Hyperparameter tuning with GridSearchCV + StratifiedKFold.  

5. **Evaluation**  
   - Confusion Matrix  
   - Precision, Recall, F1-score  
   - ROC-AUC  

---

## 🚀 Results
- SVM achieved higher recall, critical for medical prediction.  
- Cross-validation reduced overfitting.  
- Correlation findings guided effective feature engineering.  

---

## 🛠️ Tech Stack
- Python, pandas, numpy, matplotlib, seaborn  
- scikit-learn, imbalanced-learn  
