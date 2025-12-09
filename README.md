# XAI-Trade-offs-in-Binary-and-Multi-Class-Cancer-Diagnosis

This repository contains the code and experiments for a breast cancer risk prediction study using the **BCSC Risk Factors Dataset**, an open-source clinical dataset widely used in breast cancer research.

We implemented three high-performance machine learning models:

- **Support Vector Machine (SVM)**
- **Artificial Neural Network (ANN)**
- **XGBoost**

Since these models are considered **black-box models**, we added **Explainable AI (XAI)** techniques to make predictions interpretable and trustworthy:

- **SHAP** for ANN and XGBoost
- **LIME** for SVM

The goal of this project is to evaluate and improve the **accuracy–explainability trade-off**, with a particular focus on ensuring strong **recall** for cancer detection and providing clear, meaningful explanations for clinicians.
