# Credit-riskclassification

Credit Risk Analysis Outcome
1. Overview of the Analysis
The goal of this project was to build a Logistic Regression model to predict the risk of loan default based on historical lending data. Using supervised machine learning, we classified loans as either healthy (0) or high-risk (1) to assist lenders in making informed decisions.

![image](https://github.com/user-attachments/assets/83a80bd4-4831-49a2-93d3-89f2ab2039b7)


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

![image](https://github.com/user-attachments/assets/44ee7f03-1aec-428d-a389-5e5f4dd23b9e)

Classification Report for the Model: 

Key Insights from the Results

Class 0 (Majority Class)

✔ Precision = 1.00 → All instances predicted as 0 were actually 0 (no false positives).

✔ Recall = 1.00 → All actual 0s were correctly classified (no false negatives).

✔ F1-Score = 1.00 → Perfect classification for class 0.

Class 1 (Minority Class)

✔ Precision = 0.87 → 87% of the predictions for class 1 were correct. Some false positives exist.

✔ Recall = 0.95 → 95% of actual 1s were correctly classified. Some false negatives exist.

✔ F1-Score = 0.91 → Strong but not perfect performance, indicating some trade-off between precision and recall.

Overall Performance
✔ Accuracy = 99% → The model is highly accurate, correctly classifying 99% of instances.

✔ Macro Avg (0.94 Precision, 0.97 Recall, 0.95 F1-Score) → Balanced performance across both classes.

✔ Weighted Avg (0.99 Precision, 0.99 Recall, 0.99 F1-Score) → Dominated by Class 0, since it's the majority.

![image](https://github.com/user-attachments/assets/8ae890ef-9a07-496e-8dbd-7222d91a4143)

