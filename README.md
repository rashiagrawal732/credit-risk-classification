# credit-risk-classification
Analysis Overview

This report assesses the performance of a logistic regression model in predicting credit risk for loans. The model was trained on financial data that included loan amounts, interest rates, borrower income, debt-to-income ratios, number of accounts, derogatory marks, and total debt. The goal was to classify loans as either low-risk, labeled as "0," or high-risk, labeled as "1."

The machine learning process involved dividing the dataset into training and testing sets, developing and fitting a logistic regression model, and evaluating its performance based on accuracy, precision, recall, and F1 scores.

Model Performance Evaluation

The model achieved an accuracy rate of 99%, indicating that it correctly classified the vast majority of loan cases. In terms of precision, it perfectly identified low-risk loans with a score of 1.00, ensuring no false positives in that category. For high-risk loans, the precision score was 0.87, meaning the model was moderately effective but still produced some false positives. The recall score for low-risk loans was also 1.00, successfully capturing all instances in that category. For high-risk loans, the recall was 0.89, reflecting the model’s ability to correctly identify most high-risk cases, though some were missed.

Conclusion

The logistic regression model demonstrates strong predictive performance, particularly in distinguishing high-risk loans. Its high precision and recall scores make it a valuable tool for lenders seeking to mitigate financial risk by reducing the occurrence of defaulted loans.
