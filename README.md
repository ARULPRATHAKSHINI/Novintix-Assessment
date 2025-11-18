HealthCareML — Patient Analysis & AI Recommendation System

A complete healthcare analytics and machine learning project built in Google Colab, featuring Exploratory Data Analysis (EDA), supervised learning for test result prediction, anomaly detection, and an LLM-based doctor recommendation engine.

Features

Exploratory Data Analysis
Visual analysis of Age, Billing Amount, Room Number, Medical Condition, Admission Type, Medication

Supervised Learning
Predicts patient Test Results using Linear Regression with proper preprocessing

Anomaly Detection
Detects unusually high or low Billing Amount values using statistical methods

AI Doctor Recommendation (LLM-Based)
Generates doctor-style advice based on patient condition, medication, and predicted test result

Clean Visualization
Uses bar charts, histograms, and scatter plots

Beginner-friendly Notebook Structure
Easy to follow and well-organized

Tech Stack
Environment

Google Colab (Primary workspace)

Python 3.x

Libraries Used

Pandas — Data handling

NumPy — Numerical operations

Matplotlib — Data visualization

Scikit-Learn — ML models and evaluation

ChatGPT (LLM) — Doctor-style recommendation generation

Dataset Columns

Name

Age

Gender

Blood Type

Medical Condition

Date of Admission

Doctor

Hospital

Insurance Provider

Billing Amount

Room Number

Admission Type

Discharge Date

Medication

Test Results

Getting Started
1. Open Google Colab

No installation needed — everything runs online.

2. Upload the Dataset

Download the dataset from Kaggle:

https://www.kaggle.com/datasets/prasad22/healthcare-dataset

Then upload it to Colab.

3. Install Required Libraries

Most are pre-installed, but you may install if required:

!pip install pandas numpy scikit-learn matplotlib

4. Run Notebook Cells

Execute each cell section by section:

Data Loading

Cleaning

Encoding

EDA

ML Training

Anomaly Detection

AI Recommendation

Environment Variables

(Not required for this project — added for documentation completeness)

Variable	Description	Required
COLAB_ENV	Google Colab Notebook	No
Project Tasks
Task 1 — Exploratory Data Analysis (EDA)
Visualizations:

Age distribution

Billing Amount distribution

Room Number frequency

Medical Condition frequency

Admission Type frequency

Medication usage patterns

Histograms and bar charts are used for clear interpretation.

Task 2 — Supervised Learning
Steps Performed:

Selected numerical + encoded categorical features

Converted Test Results to numeric

Handled missing values

Train/test split (80:20)

Trained Linear Regression model

Evaluation Metrics:

MAE

RMSE

R² Score

A Predicted vs Actual comparison table is also displayed.

Task 3 — Unsupervised Learning
Anomaly Detection on Billing Amount

Uses Z-Score

Marks values as Anomalies = True if above threshold

Helps detect rare cases, expensive treatments, or incorrect entries

Task 4 — AI Task (LLM-Based)
AI Doctor Recommendation Generator

Takes:

Patient Age

Medical Condition

Medication

Predicted Test Result

Outputs:

Short, doctor-style recommendation

Action steps

Follow-up instructions

Sample Output
Patient age: 63
Condition: Obesity
Medication: Aspirin
Predicted test result: Normal

Advice:
- Continue your current medication as prescribed.
- Maintain hydration and follow a balanced, low-fat diet.
- If any new symptoms develop, visit a doctor immediately.
- Recommend checking again in 3–7 days to confirm stability.

Project Structure
HealthcareML-Project/
│
├── EDA/                       # Distribution & frequency plots
├── Supervised-Learning/       # Prediction model
├── Unsupervised-Learning/     # Billing anomaly detection
├── AI-Recommendation/         # Doctor-style advice
│
├── healthcare.ipynb           # Main Colab Notebook
└── README.md                  # Documentation

Available Scripts (Inside Notebook)

Load dataset

Clean dataset

Encode categorical columns

Plot EDA graphs

Train Regression Model

Detect Anomalies

Generate AI Recommendation

Security Features

(General, since ML projects do not require authentication)

No personal login required

Safe to run locally or in cloud

Dataset is anonymized

Browser Support

Chrome

Firefox

Edge

Safari

Works on any browser supporting Google Colab.

Conclusion

HealthcareML successfully combines:

Data Analysis

Predictive ML

Anomaly Detection

LLM-based doctor assistance

This project demonstrates strong understanding of end-to-end machine learning pipeline and AI-based automation.