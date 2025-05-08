# 🇹🇳 IndabaX Tunisia 2025 – 5G AI Challenge

This repository contains the submission of **Team DATA MASTADONS** for the **IndabaX Tunisia 2025 AI Challenge**.

**Team Members**:
- Zakaria M'HEMED  
- Nidhal BEN REJEB  
- Yassine ALLALA  
- Omar KAMMOUN

---

## 🚩 Challenge 1 – KPI-Based Anomaly Detection

### 🎯 Objective
Detect anomalies in Orange KPIs using a supervised machine learning approach.

### 🧠 Methodology
- We used the **XGBoost classifier**, known for its performance on structured data.
- KPI data was **preprocessed** by filling missing values and applying **standard scaling**.
- The model was evaluated using the **Hamming Loss**, which penalizes multi-label misclassification.
- After training, the model was exported for use in downstream tasks.

---

## 🤖 Challenge 2 – LLM-Based Diagnostic Suggestions

### 🎯 Objective
Provide corrective recommendations based on KPI values and anomaly detection results.

### 🧠 Methodology
- We used **Facebook's BART (Bidirectional and Auto-Regressive Transformers)** model via the Hugging Face Transformers library.
- KPI test data was first processed and passed through the trained **XGBoost model** to detect anomalies.
- Based on the anomaly status and KPI features, we generated **optimized prompts** to query the LLM.
- The **BART model** produced concise and relevant **diagnostic suggestions** tailored to each anomaly scenario.

---



"# INDABAX_Tunisia_2025_Submission" 
"# INDABAX_Tunisia_2025_Submission" 
