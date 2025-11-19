credit_risk_ML
Interpretable Machine Learning for Credit Risk Modeling using SHAP

This project builds a *credit risk prediction model*using a *Gradient Boosting Classifier*and explains its behavior using *SHAP (SHapley Additive exPlanations)*.  
The goal is not only to achieve good predictive performance, but also to provide *transparent, interpretable, and fair* model decisions for loan approval or rejection.

1. Project Objectives

- Predict the *loan status* (e.g., approved/paid vs default) using a credit risk dataset.
- Use a *non-linear model* (Gradient Boosting) suitable for complex patterns.
- Apply *SHAP* to:
  - Understand global feature importance**.
  - Explain *individual (local) predictions**.
  - Analyze feature interactions*.
  - Perform a simple *fairness analysis* based on a categorical feature (e.g., home ownership
  
  -   2. Tech Stack

- Language: Python
- Environment: Jupyter Notebook / Google Colab
- Libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `scikit-learn`
  - `shap`

Install SHAP :

```bash
pip install shap
