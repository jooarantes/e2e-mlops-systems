# End-to-End Machine Learning Systems

This repository is a portfolio hub for end-to-end machine learning projects developed across different domains. Each project is maintained in its own repository and focuses on the complete path from data and experimentation to model serving, reproducibility, testing, and operationalization.

## Projects

### 1. Telco Customer Churn Prediction

An end-to-end MLOps project for predicting customer churn in telecommunications.

The project includes:

- Exploratory data analysis and feature engineering;
- Model experimentation with Scikit-Learn, MLP, and Optuna;
- MLflow experiment tracking;
- FastAPI batch inference;
- Docker and Docker Compose workflows;
- Automated tests with pytest;
- Prometheus and Grafana monitoring.

**Repository:** [telco-customer-churn-prediction](https://github.com/jooarantes/telco-customer-churn-prediction)

### 2. E-Commerce Product Recommendation System

An end-to-end recommendation system built with the RetailRocket e-commerce dataset.

The project includes:

- A DVC pipeline for data preparation, feature engineering, training, evaluation, and model promotion;
- A neural collaborative filtering model based on PyTorch and MLP embeddings;
- Scikit-Learn baselines for comparison;
- Ranking evaluation with metrics such as Hit Rate@K, Precision@K, Recall@K, and NDCG@K;
- MLflow experiment tracking and model registry;
- FastAPI serving with cold-start fallback to popularity-based recommendations;
- Docker, Docker Compose, and AWS ECS/Fargate deployment;
- Automated tests and reproducibility controls.

**Repository:** [e-commerce-product-recommendation-system](https://github.com/jooarantes/e-commerce-product-recommendation-system)

### 3. Automated Triage of Medical Reports

An NLP and MLOps system for classifying public medical abstracts into medical condition categories.

This project is a technical demonstration for categorization and prioritization support. It is not a clinical validation study, does not provide medical diagnoses, and does not replace human review.

The project includes:

- Configurable text preprocessing with Strategy and Factory patterns;
- TF-IDF features and optional biomedical embeddings;
- A configurable One-vs-Rest multi-label classification pipeline;
- Model comparison and hyperparameter tuning;
- FastAPI serving with `/predict`, `/health`, `/metrics`, and interactive demo endpoints;
- MLflow experiment tracking and model registry;
- Airflow orchestration;
- ONNX Runtime export and latency benchmarking;
- Prometheus and Grafana observability;
- GitHub Actions CI/CD, Docker, and automated tests.

**Repository:** [automated-triage-of-medical-reports](https://github.com/jooarantes/automated-triage-of-medical-reports)

## Engineering Focus

Across these projects, the portfolio emphasizes:

- Reproducible data and training workflows;
- Experiment tracking and model lifecycle management;
- Modular and testable machine learning code;
- API-based model serving;
- Containerization with Docker;
- Monitoring and operational observability;
- CI/CD and automated quality checks;
- Domain-specific evaluation and explicit model limitations.

## Repository Organization

The projects remain in separate repositories so that each system can be developed, tested, documented, and deployed independently. This repository serves as the entry point for navigating the portfolio.

## Author

Built by [João Arantes](https://github.com/jooarantes).
