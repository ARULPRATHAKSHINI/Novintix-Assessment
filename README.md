Healthcare Data Analysis & Prediction Project

This project is based on a healthcare dataset and includes four major tasks:

Exploratory Data Analysis (EDA)

Supervised Learning (Predicting Test Results)

Unsupervised Learning (Billing Amount Anomaly Detection)

LLM-Based AI Doctor Recommendation

All steps were done in Google Colab using Python.

📌 Dataset Overview

The dataset contains the following columns:

Name, Age, Gender, Blood Type, Medical Condition, Date of Admission, Doctor, Hospital, Insurance Provider, Billing Amount, Room Number, Admission Type, Discharge Date, Medication, Test Results.

🧪 Task 1 — Exploratory Data Analysis (EDA)
Numerical Column Analysis

Age (distribution, min/max, outliers)

Billing Amount (spread, unusual values)

Room Number (range, patterns)

Categorical Column Analysis

Bar charts plotted for:

Medical Condition

Admission Type

Medication

These graphs give a quick view of which conditions and treatments are more frequent.

🤖 Task 2 — Supervised Learning: Predicting Test Results
Steps Completed

Selected features needed for prediction

Encoded categorical variables

Filled missing values

Train-test split: 80% train, 20% test

Trained a Linear Regression model

Evaluation Metrics

Mean Absolute Error (MAE)

RMSE

R² Score

A comparison of predicted vs. actual test results was also displayed.

🕵️ Task 3 — Unsupervised Learning: Anomaly Detection in Billing
Method Used

A simple statistical approach (Z-score) was used to detect extreme billing values.

Output

Marked unusually high and low billing amounts

These anomalies were highlighted for review

Interpretation

High anomalies may indicate complex procedures, surgeries, or long stays.
Low anomalies may indicate short visits or entry mistakes.

🧑‍⚕️ Task 4 — AI Task (LLM-Based Doctor Recommendation)

After predicting a patient’s Test Result, the model output was given to an LLM (Large Language Model) along with important attributes:

Age

Medical Condition

Medication

The LLM generated a short doctor-style recommendation based on these inputs.

Sample LLM Output
Doctor-Style Recommendation:
Patient age: 63
Condition: Obesity
Medication: Aspirin
Predicted test result: 0.0 (normal)

Advice:
- The predicted result appears normal; continue the current medication.
- Maintain balanced meals, proper hydration, and light activity.
- Monitor symptoms and seek medical help if any discomfort increases.
- A follow-up check in a few days can help ensure everything stays stable.


This section demonstrates how LLMs can support simple automated medical guidance (non-clinical).

📁 Project Structure
Healthcare-Project/
│
├── Task 1 - EDA
├── Task 2 - Supervised Learning
├── Task 3 - Anomaly Detection
├── Task 4 - LLM Doctor Recommendation
└── README.md

🛠️ Tools Used

Python

Pandas

NumPy

Matplotlib

Scikit-learn

Google Colab

An LLM (ChatGPT) for doctor recommendation

✔️ Conclusion

This project covers a complete data science pipeline:

Understanding healthcare trends

Building a prediction model

Detecting abnormal financial entries

Using LLMs for automated doctor-style text generation

It demonstrates how traditional ML and modern AI methods can work together on real-world healthcare data.
