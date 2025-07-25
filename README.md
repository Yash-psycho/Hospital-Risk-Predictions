🏥 Hospital Readmission Risk Prediction
ML-powered System to Predict Patient Readmission within 30 Days

"Built with purpose during Learnathon 4.0 – MedTech Domain, Problem Statement 1"

🚀 Problem Statement
Predict the likelihood of hospital readmission for patients with chronic conditions using clinical and demographic data — enabling early intervention and smarter care planning.

✨ Team Info
👥 Team ID: MB5_3_NO:12
👨‍🔬 Members:

Anamu Yashwant (23CSE046)

Pichika Rajeev (23CSE079)

Aditya Jena (23CSEAIML187)

Suraj Meher (23LECSE004)

📽️ Presentation: [Predicting-Hospital-Readmission-Risk-for-Patients-with-Chronic-Conditions.pptx](https://github.com/user-attachments/files/21432474/Predicting-Hospital-Readmission-Risk-for-Patients-with-Chronic-Conditions.pptx)


📁 Dataset Details
Healthcare dataset (CSV format) containing:

🧑‍⚕️ Patient Name

📅 Admission & Discharge Dates

🎂 Age, ⚥ Gender

🩺 Medical Condition

🏥 Type of Admission

...and more.

🔍 Phase 1: Data Preprocessing
🔄 Converted admission/discharge dates to datetime format

🧹 Normalized patient names to lowercase

🏥 Engineered Length_of_Stay feature

🧾 Created Readmitted label:

Readmitted within 30 days → 1

Else → 0

🗑️ Removed intermediate columns post feature creation

📊 Phase 2: Exploratory Data Analysis (EDA)
Key insights visualized:

🔁 Most common chronic conditions

📊 Readmission patterns by age groups

🧭 Influence of admission types on readmission likelihood

🤖 Phase 3: Model Building & Evaluation
Model Used: Random Forest Classifier
Preprocessing: Label Encoding for categorical features
Data Split: 80% Train / 20% Test

Metrics Evaluated:

✅ Accuracy

📄 Classification Report (Precision, Recall, F1-score)

🔁 Confusion Matrix

📈 ROC AUC Score

🧠 Key Results
Model effectively predicts risk on unseen data.
Top Influencing Factors:

🎂 Age Group

🩺 Medical Condition

🏥 Type of Admission

⚙️ Tech Stack
🔧 Tools	📚 Libraries
Python	Pandas, NumPy
Google Colab	Scikit-learn
Jupyter Notebook	Seaborn, Matplotlib

📎 Notes & Future Scope
This is a foundational implementation. To level it up:

⚖️ Handle class imbalance (e.g., SMOTE)

🎯 Perform hyperparameter tuning

🧠 Try alternative ML models (XGBoost, SVM, etc.)

🔍 Feature selection via mutual info or SHAP

💻 How to Run
📂 Upload the dataset to your Google Colab environment

▶️ Open and run TEAM-118.ipynb

📊 View all visualizations and model metrics auto-generated

# Hospital-Risk-Predictions
Learnathon 4.0 
