# Credit-riskclassification

Credit Risk Analysis Outcome
1. Overview of the Analysis
The goal of this project was to build a Logistic Regression model to predict the risk of loan default based on historical lending data. Using supervised machine learning, we classified loans as either healthy (0) or high-risk (1) to assist lenders in making informed decisions.

2. Results of the Logistic Regression Model
Model Performance Metrics
Accuracy Score: High (e.g., ~99% depending on dataset distribution)
Precision:
For Class 0 (Healthy Loans): Very high, indicating that most loans predicted as healthy were indeed healthy.
For Class 1 (High-Risk Loans): Lower, meaning some high-risk loans may not be identified correctly.
Recall:
For Class 0: Near perfect, indicating almost all healthy loans were correctly classified.
For Class 1: Moderate, meaning some high-risk loans were missed.
F1-Score: A balance between precision and recall, generally favoring class 0 due to class imbalance.
Confusion Matrix Insights
True Negatives (TN): The number of correctly identified healthy loans.
False Positives (FP): Some healthy loans misclassified as high-risk.
False Negatives (FN): Some high-risk loans misclassified as healthy (critical for lenders).
True Positives (TP): The number of correctly identified high-risk loans.
