# 🏥 Hospital Readmission Risk Prediction

This project predicts the likelihood of a patient being readmitted within 30 days of discharge, focusing on chronic condition cases. Built as part of Learnathon 4.0 (MedTech Domain – Problem Statement 1).

---

## 🚀 Problem Statement

Predict hospital readmission risk for patients with chronic conditions using clinical and demographic data.

---

## ✨ Team ID and Members

=>ID : 

Team(MB5)_3_NO:12

=>Members :
-Anamu Yashwant (23CSE046)
-Pichika Rajeev (23CSE079)
-Aditya Jena (23CSEAIML187)
-Suraj Meher (23LECSE004)

---
## Presentation 

📂 [Predicting-Hospital-Readmission-Risk-for-Patients-with-Chronic-Conditions.pptx](https://github.com/user-attachments/files/21431369/Predicting-Hospital-Readmission-Risk-for-Patients-with-Chronic-Conditions.pptx)

## 📁 Dataset

- Provided healthcare dataset (CSV)
- Columns include patient name, admission/discharge dates, age, gender, medical condition, admission type, and more.

---

## 🔍 Phase 1: Data Preprocessing

- Converted dates to datetime format.
- Normalized names to lowercase.
- Engineered `Length_of_Stay` feature.
- Created `Readmitted` label:
  - If a patient is readmitted within 30 days of discharge → `Readmitted = 1`
  - Otherwise → `0`
- Removed helper columns post feature creation.

---

## 📊 Phase 2: Exploratory Data Analysis (EDA)

- Visualized:
  - Most common medical conditions
  - Readmission patterns by age
  - Admission types and their impact on readmission

---

## 🤖 Phase 3: Model Building & Evaluation

- **Model Used**: Random Forest Classifier
- **Preprocessing**: Label encoding of categorical features
- **Train-Test Split**: 80-20
- **Metrics Evaluated**:
  - Accuracy
  - Classification Report (Precision, Recall, F1)
  - Confusion Matrix
  - ROC AUC Score

---

## 🧠 Results

- The model demonstrates reliable performance on unseen data.
- Key influencing factors include:
  - Age group
  - Medical condition
  - Type of admission

---

## 📌 Technologies Used

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn
- Google Colab

---


## 📎 Note

This is a basic implementation. Future improvements may include:
- Handling class imbalance
- Hyperparameter tuning
- Feature selection
- Model comparison

---

## 📂 How to Run

1. Upload dataset to your Colab environment.
2. Run all cells in the notebook (`TEAM-118.ipynb`).
3. All outputs, visualizations, and model metrics will be generated automatically.

---

# Hospital-Risk-Predictions
Learnathon 4.0 
