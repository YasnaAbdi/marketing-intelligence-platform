# marketing-intelligence-platform
An open-source machine learning platform for customer churn prediction, marketing analytics, explainable AI, and intelligent business decision support.

# Open Marketing Intelligence Platform (OMIP)

> An open-source end-to-end machine learning platform for customer churn prediction and marketing decision intelligence.

![Python](https://img.shields.io/badge/Python-3.12-blue)
![Status](https://img.shields.io/badge/Status-In%20Development-orange)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-red)

---

# Overview

Open Marketing Intelligence Platform (OMIP) is an open-source machine learning platform designed to help businesses analyze customer behavior, predict customer churn, and support marketing decision-making through explainable artificial intelligence.

Unlike traditional churn prediction projects that stop after generating predictions, OMIP focuses on transforming predictions into actionable business decisions by integrating machine learning, explainability, statistical evaluation, and decision intelligence into one unified framework.

The long-term vision of this project is to become a reusable framework that can be adapted to various marketing datasets rather than a solution limited to a single dataset.

---

# Motivation

Customer churn is one of the most important business challenges across industries such as telecommunications, banking, insurance, SaaS, retail, and e-commerce.

Accurate prediction alone is not enough.

Organizations need to understand

- Why customers leave
- Which customers should receive marketing campaigns
- Which customers generate the highest expected profit
- How marketing budgets should be allocated

OMIP aims to answer these questions using modern machine learning techniques.

---

# Objectives

The project has four primary goals.

- Predict customer churn accurately.
- Explain model decisions using Explainable AI.
- Estimate business impact and expected marketing profit.
- Recommend optimal marketing actions.

---

# Key Features

## Data Processing

- Data validation
- Missing value detection
- Duplicate detection
- Data quality analysis
- Feature type identification

---

## Exploratory Data Analysis

- Statistical summaries
- Distribution analysis
- Correlation analysis
- Customer segmentation
- Business insights

---

## Feature Engineering

- Encoding
- Scaling
- Feature selection
- Feature importance
- Derived features

---

## Machine Learning

- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost
- LightGBM
- CatBoost

---

## Model Evaluation

- Accuracy
- Precision
- Recall
- F1 Score
- ROC AUC
- Precision-Recall Curve
- Calibration Curve
- Lift Chart
- Gain Chart

---

## Explainable AI

- SHAP
- Feature Importance
- Partial Dependence
- Permutation Importance

---

## Decision Intelligence

Instead of simply predicting churn probability, OMIP recommends business actions.

Examples:

- Offer Discount
- Send Promotion
- Contact Customer
- No Action

Recommendations are generated based on business rules and expected marketing profit.

---

## Dashboard

Interactive dashboards will be developed using

- Power BI
- Streamlit

---

## API

REST API using FastAPI

Example endpoints

POST /predict

POST /decision

---

# Project Architecture

```

Dataset

↓

Data Validation

↓

Data Cleaning

↓

Exploratory Data Analysis

↓

Feature Engineering

↓

Model Training

↓

Hyperparameter Optimization

↓

Model Evaluation

↓

Explainable AI

↓

Decision Engine

↓

Dashboard / API

```

---

# Technology Stack

| Category | Technologies |
|-----------|-------------|
| Programming | Python |
| Data Processing | Pandas, NumPy |
| Machine Learning | Scikit-learn, XGBoost, LightGBM |
| Explainability | SHAP |
| Visualization | Matplotlib, Plotly |
| Dashboard | Power BI, Streamlit |
| API | FastAPI |
| Version Control | Git |
| Containerization | Docker |

---

# Repository Structure

```

OMIP/

├── data/

├── docs/

├── notebooks/

├── src/

│ ├── data/

│ ├── features/

│ ├── models/

│ ├── evaluation/

│ ├── explainability/

│ ├── decision/

│ ├── visualization/

│ └── utils/

├── tests/

├── examples/

├── config/

└── assets/

```

---

# Development Roadmap

## Version 0.1

- Project initialization
- Data loading
- Data validation
- Exploratory data analysis

---

## Version 0.2

- Feature engineering
- Baseline machine learning models

---

## Version 0.3

- Hyperparameter optimization
- Advanced evaluation

---

## Version 0.4

- Explainable AI

---

## Version 0.5

- Decision Engine

---

## Version 1.0

- Dashboard
- REST API
- Docker support
- Documentation
- Deployment

---

# Dataset

The initial implementation uses the IBM Telco Customer Churn dataset.

The architecture is intentionally designed to support multiple marketing datasets in future versions.

---

# Future Improvements

- AutoML
- Time-series forecasting
- Customer Lifetime Value prediction
- Campaign optimization
- Recommendation systems
- MLOps integration
- Cloud deployment
- Real-time prediction

---

# License

This project is released under no License.

---

# Author

Yasna Abdi

Computer Engineering Student

Interested in Artificial Intelligence, Data Science, Machine Learning and Decision Intelligence.
