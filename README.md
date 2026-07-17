# driver-attrition-predictions
# Driver Attrition Prediction using Ensemble Machine Learning

Predicting driver attrition using supervised machine learning to help ride-hailing platforms proactively identify high-risk drivers and improve retention strategies.

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange)
![XGBoost](https://img.shields.io/badge/XGBoost-Ensemble-success)
![License](https://img.shields.io/badge/License-MIT-green)

---

## Project Overview

Driver attrition is one of the biggest operational challenges for ride-hailing companies. High driver turnover increases recruitment costs, affects customer experience, and reduces operational efficiency.

This project develops a machine learning pipeline to predict whether a driver is likely to leave the platform using demographic, behavioral, and performance-related attributes. The insights can help business teams design targeted retention strategies for high-risk drivers.

---

## Business Problem

Ride-sharing companies invest significant resources in acquiring and onboarding drivers. Losing experienced drivers results in:

- Increased recruitment costs
- Reduced service availability
- Lower customer satisfaction
- Higher operational expenses

The objective of this project is to identify drivers at risk of attrition before they leave, enabling proactive intervention.

---

## Objectives

- Predict driver attrition using supervised machine learning.
- Compare multiple ensemble learning algorithms.
- Handle class imbalance effectively.
- Identify the key factors contributing to driver churn.
- Generate actionable business insights.

---

## Dataset

- **Domain:** Human Resources / Ride Sharing
- **Problem Type:** Binary Classification
- **Target Variable:** Attrition (Yes/No)
- **Features:** Driver demographics, experience, income, performance, tenure, ratings, and other operational metrics.

---

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- SMOTE
- RandomizedSearchCV

---

## Machine Learning Workflow

```
Data Collection
        │
        ▼
Data Cleaning
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Feature Engineering
        │
        ▼
Handling Class Imbalance (SMOTE)
        │
        ▼
Model Training
        │
        ▼
Hyperparameter Tuning
        │
        ▼
Model Evaluation
        │
        ▼
Business Insights
```

---

## Exploratory Data Analysis

Performed extensive EDA to understand:

- Missing values
- Feature distributions
- Class imbalance
- Correlation analysis
- Driver demographic patterns
- Income and experience trends
- Feature importance

---

## Feature Engineering

- Missing value treatment
- Categorical encoding
- Feature scaling
- Outlier handling
- Feature selection

---

## Models Evaluated

- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost

Random Forest and XGBoost delivered the best predictive performance after hyperparameter tuning.

---

## Handling Class Imbalance

The dataset exhibited class imbalance.

To improve model performance:

- Applied **SMOTE (Synthetic Minority Oversampling Technique)**
- Evaluated Precision, Recall, F1 Score, and ROC-AUC instead of relying solely on Accuracy.

---

## Model Performance

| Metric | Score |
|---------|-------|
| Accuracy | 92% |
| Precision | 93% |
| Recall | 95% |
| F1 Score | 94% |
| ROC-AUC | 0.98 |

---

## Key Findings

- Driver income significantly influenced attrition.
- Longer tenure was associated with lower attrition risk.
- Driver performance ratings showed strong predictive power.
- Ensemble learning models substantially outperformed baseline models.

---

## Business Recommendations

- Identify high-risk drivers through predictive scoring.
- Develop targeted retention programs for experienced drivers.
- Review compensation strategies for at-risk driver segments.
- Monitor performance metrics to trigger proactive engagement.

---

## Repository Structure

```
driver-attrition-prediction
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│
├── src/
│
├── models/
│
├── reports/
│
├── images/
│
├── requirements.txt
│
├── README.md
│
└── LICENSE
```

---

## Skills Demonstrated

- Machine Learning
- Classification
- Ensemble Learning
- Feature Engineering
- Hyperparameter Tuning
- Class Imbalance Handling
- Model Evaluation
- Exploratory Data Analysis
- Data Visualization
- Business Analytics

---

## Future Improvements

- Deploy the model using FastAPI.
- Build an interactive Streamlit dashboard.
- Track experiments using MLflow.
- Containerize the application using Docker.
- Automate retraining with CI/CD pipelines.

---

## Author

**Nagarjun CN**
