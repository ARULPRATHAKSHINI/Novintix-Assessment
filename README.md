🏥 Hospital Patient Analytics & AI Doctor Recommendation System

A complete medical data analysis project featuring EDA, machine learning, anomaly detection, and an AI-style doctor recommendation generator.

🎥 Demo Video

(Add your demo link here)
https://drive.google.com/...

⭐ Project Overview

This project analyzes hospital patient data and builds:

✔ Exploratory Data Analysis (EDA)

✔ A Supervised ML model to predict test results

✔ An Unsupervised ML model for billing anomaly detection

✔ An AI Doctor-style Recommendation Generator (LLM-style but manually written to avoid plagiarism)

🚀 Features
🔹 Task 1 — Exploratory Data Analysis (EDA)

Distribution analysis for:

Age

Billing Amount

Room Number

Frequency plots for:

Medical Condition

Admission Type

Medication

🔹 Task 2 — Supervised Machine Learning

Dataset preparation

Train–test split

Linear Regression model (simple & explainable)

Evaluation metrics:

MAE

RMSE

R² Score

Predicted vs Actual comparison

🔹 Task 3 — Unsupervised Learning

Billing Amount Anomaly Detection

Detect extremely high / low hospital bill values

Identify rare or suspicious medical cases

Flag anomalies for manual review

🔹 Task 4 — AI Doctor Recommendation (LLM-based logic)

Uses:

Patient Age

Medical Condition

Medication

Predicted Test Result

Generates:

Short doctor-style note

Health advice

Follow-up instructions

🧠 Tech Stack
✔ Python Libraries

pandas

numpy

matplotlib

seaborn

scikit-learn

✔ Machine Learning

Linear Regression

Isolation Forest

Feature Encoding

📁 Project Structure
├── data/
│   └── patient_records.csv
├── notebooks/
│   └── analysis.ipynb
├── src/
│   ├── eda.py
│   ├── model_training.py
│   ├── anomaly_detection.py
│   └── ai_recommendation.py
└── README.md

⚙️ How to Run the Project
1. Install Dependencies
pip install -r requirements.txt

2. Open Jupyter Notebook
jupyter notebook

3. Run analysis.ipynb to execute all tasks
📊 Sample Output — AI Doctor Recommendation
Doctor-style Recommendation:
Patient age: 63
Condition: Obesity
Current medication: Aspirin
Predicted test result: 0.0 (normal)

Advice:
- The predicted result is normal. Continue prescribed medication unless advised otherwise.
- Ensure rest, proper hydration and balanced diet.
- Monitor symptoms closely. If condition is 'high' or 'critical', arrange immediate clinical review and further tests.
- Schedule follow-up check in 3-7 days and repeat tests to confirm trend.

🏁 Conclusion

This project demonstrates:

Data Cleaning & EDA

Predictive modeling

Anomaly detection

A doctor-style AI recommendation system without plagiarism
