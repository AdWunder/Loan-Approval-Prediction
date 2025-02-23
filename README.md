# 🏦 Loan Approval Prediction

## 📌 Project Overview

This project focuses on predicting **loan approval status** using machine learning techniques. By analyzing applicant data, we aim to build an accurate classification model that helps financial institutions automate the decision-making process.  

🔹 **Dataset**: Contains applicant details such as income, loan amount, credit history, and other financial indicators.  
(Source Kaggle : https://www.kaggle.com/datasets/ninzaami/loan-predication/data)
🔹 **Goal**: Predict whether a loan will be approved or rejected based on given features.  
🔹 **Techniques Used**: Data preprocessing, feature scaling, class balancing, hyperparameter tuning, and model evaluation.  

---

## 🚀 Features & Methodology
### **1️⃣ Data Preprocessing**
✔ Handling missing values (Mode Imputation for categorical features).  
✔ Outlier detection and removal using **Interquartile Range (IQR)**.  
✔ Balancing dataset using **SMOTE (Synthetic Minority Over-sampling Technique)** to prevent model bias.  

### **2️⃣ Feature Engineering**
✔ Scaling numerical features using **MinMaxScaler** for better model performance.  
✔ Square root transformation applied to normalize skewed distributions.  

### **3️⃣ Model Training & Optimization**
✔ **Random Forest Classifier** chosen for its robustness in classification tasks.  
✔ Hyperparameter tuning with **GridSearchCV** to optimize performance.  
✔ Evaluation using **Accuracy, Precision, Recall, F1-Score, and Confusion Matrix**.  

---

## 📊 Model Performance
After applying MinMaxScaler and optimizing the Random Forest model, the accuracy equal to 92%**.  

**Final Results:**  
| Metric         | Score  |
|---------------|--------|
| **Accuracy**  | `92%`  |
| **Precision** | `95%`  |
| **Recall**    | `92%`  |
| **F1-Score**  | `92%`  |

---
