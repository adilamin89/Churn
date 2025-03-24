Churn Prediction AI Project

A full-stack machine learning project that predicts customer churn using classical ML, deep learning, and model explainability (SHAP). The system is end-to-end, with deployment via Flask API and Docker containerization, and integrated tools including MLflow, PostgreSQL, and cloud support (AWS/GCP/Azure).

1. Project Overview

This project aims to:

Predict customer churn using various ML models

Compare performance using MLflow

Explain model predictions with SHAP

Serve predictions through a RESTful Flask API

Deploy in Docker containers, optionally on cloud platforms

Store and retrieve data using PostgreSQL (hosted on AWS RDS)

2. Features & Tools

Machine Learning:

Logistic Regression, Random Forest, XGBoost, LightGBM

Keras-based deep learning models

PyTorch neural networks

Hyperparameter tuning (GridSearchCV)

Model evaluation (accuracy, precision, recall, F1, ROC-AUC)

Visual plots: Confusion matrix, ROC curve, SHAP

MLOps:

MLflow: Experiment tracking, model registry, artifact logging

SHAP: Model interpretability (summary, waterfall, force plots)

PDF Reports: Auto-generated with performance summary and visuals

Deployment:

Flask API to serve models

Docker for containerization

PostgreSQL for relational data management

AWS RDS for cloud-hosted database

Google Colab / GCP / Azure for training and experimentation

3. Project Structure
Churn_Prediction_Project/ │ ├── data/ # Raw and processed datasets │ └── WA_Fn-UseC_-Telco-Customer-Churn.csv │ ├── notebooks/ # Jupyter or Colab notebooks │ └── EDA_and_Modeling.ipynb │ ├── src/ # All source code │ ├── training/ # Model training scripts │ ├── evaluation/ # Metrics, plots, MLflow logging │ ├── deployment/ # Flask API code │ ├── shap_analysis/ # SHAP visualization & interpretation │ ├── database/ # SQL setup scripts (PostgreSQL) │ └── utils.py # Utility functions │ ├── reports/ # Auto-generated PDFs with plots, metrics, SHAP │ └── final_model_report.pdf │ ├── Dockerfile # Containerization setup ├── requirements.txt # Dependencies ├── README.md # Project documentation └── app.py # Flask app for serving predictions

4. Getting Started

Requirements

Python 3.8+

pip or conda

Docker

PostgreSQL (local or RDS)
