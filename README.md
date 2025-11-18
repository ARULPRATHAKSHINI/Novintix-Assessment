# 🏥 Hospital Patient Analytics & AI Doctor Recommendation System

A complete medical data analysis project featuring **EDA**, **Machine Learning**, **Anomaly Detection**, and an **AI-style doctor recommendation generator**.

---

## ⭐ Project Overview

This project analyzes hospital patient data and builds:

✔ **Exploratory Data Analysis (EDA)**  
✔ **Supervised ML model** to predict test results  
✔ **Unsupervised ML model** for billing anomaly detection  
✔ **AI Doctor-style Recommendation Generator** (LLM-style logic but manually written)  

---

## 🚀 Features

### 🔹 Task 1 — Exploratory Data Analysis (EDA)
Includes distribution analysis for:
- Age  
- Billing Amount  
- Room Number  

Frequency plots for:
- Medical Condition  
- Admission Type  
- Medication  

---

### 🔹 Task 2 — Supervised Machine Learning
- Dataset preparation  
- Train–test split  
- Linear Regression model  
- Evaluation metrics:
  - MAE  
  - RMSE  
  - R² Score  
- Predicted vs Actual comparison  

---

### 🔹 Task 3 — Unsupervised Learning (Anomaly Detection)
- Billing Amount anomaly detection  
- Detect extremely high/low bills  
- Identify rare or suspicious cases  
- Automatically flag anomalies for review  

---

### 🔹 Task 4 — AI Doctor Recommendation (LLM-Based Logic)
Uses:
- Patient Age  
- Medical Condition  
- Medication  
- Predicted Test Result  

Generates:
- Short doctor-style note  
- Personalized health advice  
- Follow-up instructions  

---

## 🧠 Tech Stack

### ✔ Python Libraries
- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  

### ✔ Machine Learning
- Linear Regression  
- Isolation Forest  
- Label Encoding  
- Feature Engineering  

---

## 📁 Project Structure
```
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
```

---

## ⚙️ How to Run the Project

### 1️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 2️⃣ Open Google Colab
```bash
Google Colab
```

### 3️⃣ Run `analysis.ipynb`
Executes:
- EDA  
- ML model training  
- Anomaly detection  
- AI doctor recommendation generation  

---

## 📊 Sample Output — AI Doctor Recommendation

```
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
```

---

## 🏁 Conclusion

This project demonstrates:
- ✔ Data Cleaning & EDA  
- ✔ Predictive modeling  
- ✔ Anomaly detection  
- ✔ Doctor-style AI Recommendation System (non-plagiarised)  

A full end-to-end healthcare analytics pipeline.

---

## 📜 License
MIT License  
