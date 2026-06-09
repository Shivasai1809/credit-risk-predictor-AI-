# Credit Risk & Loan Default Prediction

## Overview
This project predicts whether a loan applicant is likely to default using Machine Learning and Explainable AI techniques.

The solution combines:
- Random Forest Classifier
- SHAP Explainability
- FAISS Vector Search
- Gemini API
- Streamlit Deployment

The goal is to help financial institutions make faster and more transparent lending decisions.

---

## Business Problem

Banks and financial institutions face significant losses due to loan defaults.

This project helps:
- Identify high-risk applicants
- Reduce bad loans
- Improve decision transparency
- Support compliance requirements

---

## Project Architecture

Data Collection
↓
Data Cleaning & Preprocessing
↓
Feature Engineering
↓
Random Forest Model
↓
SHAP Explainability
↓
FAISS + Gemini RAG System
↓
Streamlit Deployment

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Random Forest
- XG Boost
- SHAP
- FAISS
- Gemini API
- Streamlit
- GitHub

---

## Model Performance

| Metric | Value |
|----------|----------|
| Accuracy | 92% |
| Model | Random Forest | XG boost|
| Explainability | SHAP |
| Deployment | Streamlit |

---

## Key Features

### Credit Risk Prediction
Predicts whether a customer is likely to default.

### Explainable AI
SHAP explains why a prediction was made.

### RAG Pipeline
Uses FAISS and Gemini API to generate policy-grounded explanations.

### Real-Time Scoring
Users can enter applicant information and receive instant risk predictions.

---

## Project Structure

Credit-Risk-Prediction/

├── CreditRiskAI.ipynb

├── app.py

├── requirements.txt

├── README.md

├── model.pkl

└── dataset.csv

---

## Installation

```bash
git clone https://github.com/yourusername/Credit-Risk-Prediction.git

cd Credit-Risk-Prediction

pip install -r requirements.txt

streamlit run app.py
```

## Results

- Achieved 92% prediction accuracy.
- Improved decision transparency using SHAP.
- Automated applicant scoring process.
- Reduced manual review effort.

---

## Future Improvements

- LightGBM implementation
- Hyperparameter optimization
- Model monitoring
- Advanced explainability dashboard
- Cloud deployment

---

## Author

Shiva Sai

GitHub:
https://github.com/Shivasai1809

LinkedIn:
( linkedin.com/in/chipla-shiva-sai-82204b306 )
