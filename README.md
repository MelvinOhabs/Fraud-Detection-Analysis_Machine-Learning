# Fraud-Detection-Analysis_Machine-Learning

Project Overview

Every festive season, online spending spikes and so does fraud.
People abroad begin sending money home, e-commerce activity increases, and cybercriminals take advantage of the rush.
This project simulates that real-world scenario by building a machine learning model that detects fraudulent transactions with high accuracy and explainability.

The goal is simple: help businesses and fintechs flag suspicious transactions early so they can protect customers without slowing down genuine activity.

Why This Analysis Matters

In today’s digital economy:

Fraud techniques are evolving faster than manual teams can keep up.

Businesses need scalable, data-driven fraud prevention.

A reliable model reduces losses, lowers chargebacks, and improves customer trust.

This project demonstrates how data science can solve a real financial risk problem relevant in 2025 and beyond.

Models Tested

I experimented with multiple algorithms:

1. Logistic Regression

Baseline model

Fast, interpretable

Useful for benchmarking

2. XGBoost

Handles imbalanced data well

Excellent with non-linear relationships

Strong performance

3. Random Forest (Final Choice)

After comparing metrics, Random Forest performed best

Stable, robust, and less prone to overfitting

Feature importance gave strong business-level insights

Why Random Forest Won:

Best balance of precision & recall (critical in fraud detection)

Detected more true fraud cases with fewer false alarms

Clear feature importance for business stakeholders

🔍 Feature Engineering Highlights

This project applied multiple techniques to improve model performance:

Label Encoding & One-Hot Encoding for categorical fields

Scaling of numerical fields

Handling imbalance using SMOTE / class weights (mention what you used)

Correlation analysis to identify redundant features

Feature importance to understand drivers of fraud

These steps significantly improved the model’s robustness.

📝 What I Learned

Fraud datasets are often imbalanced, so recall and F1-score matter more than accuracy

Feature engineering is as important as the model itself

Different algorithms learn fraud patterns differently — ensemble models often win

Business context is crucial: a fraud model must be accurate but not overly aggressive
