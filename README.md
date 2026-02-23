# 🩺 Liver Disease Prediction using Machine Learning

## 📌 Project Overview
This project focuses on analyzing a liver patient dataset and building predictive
machine learning models to classify whether a patient has liver disease or not.

The study combines:
✔ Exploratory Data Analysis (EDA)  
✔ Data Preprocessing  
✔ Multiple ML Classifiers  
✔ Model Comparison  
✔ Streamlit Deployment  

---

## 🎯 Problem Statement
Liver disease cases are increasing due to factors such as alcohol consumption,
contaminated food intake, drug toxicity, and environmental exposure.

The objective of this project is to:

1️⃣ Perform a complete data analysis  
2️⃣ Build predictive classification models  
3️⃣ Justify model design decisions  
4️⃣ Compare model performances  
5️⃣ Deploy the best model  

---

## 📊 Dataset Information

**Dataset:** Indian Liver Patient Dataset (ILPD)  
**Records:** 583 patients  

• Liver Disease Patients → 416  
• Non-Liver Disease Patients → 167  

**Features Include:**
- Age_of_the_patient
- Gender_of_the_patient
- Total_Bilirubin
- Direct_Bilirubin
- Alkaline_Phosphotase
- Alamine_Aminotransferase
- Aspartate_Aminotransferase
- Total_Protiens
- Albumin
- Albumin_and_Globulin_Ratio
- Target

---

## 🧪 Exploratory Data Analysis (EDA)

EDA included:

✔ Class distribution analysis  
✔ Age & gender analysis  
✔ Outlier detection  
✔ Feature correlation study  
✔ Clinical interpretation  

**Key Insights:**
- Bilirubin strongly associated with liver disease  
- ALT & AST indicate liver cell damage  
- Albumin reduction linked to liver dysfunction  

---

## ⚙️ Data Preprocessing

Techniques applied:

✔ Missing value imputation (Median)  
✔ Gender encoding  
✔ Target transformation (Binary)  
✔ Outlier handling (Retained)  
✔ Feature scaling (RobustScaler)  

---

## 🤖 Machine Learning Models Implemented

The following classifiers were evaluated:

- Logistic Regression  
- Decision Tree  
- Random Forest  
- Support Vector Machine (SVM)  
- K-Nearest Neighbors (KNN)  

---

## 🏆 Best Model Selection

KNN classifier was selected based on:

✔ Highest accuracy (tied)  
✔ Balanced confusion matrix  
✔ Reliable clinical predictions  

---

## 📈 Evaluation Metrics

Models evaluated using:

✔ Accuracy  
✔ Confusion Matrix  
✔ Precision  
✔ Recall  
✔ F1-score  
✔ ROC Curve  

---

## 🖥️ Deployment

The final KNN model was deployed using **Streamlit**:

Features:

✔ Interactive UI  
✔ Real-time prediction  
✔ Probability confidence  

Run app:

```bash
streamlit run streamlit_app.py
