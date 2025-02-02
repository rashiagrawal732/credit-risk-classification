# credit-risk-classification
Credit Risk Analysis Report

Overview of the Analysis
This analysis evaluates the effectiveness of a logistic regression model in predicting credit risk associated with loans. The model was trained and tested on financial data, including loan amounts, interest rates, borrower income, debt-to-income ratios, number of accounts, derogatory marks, and total debt. The goal was to classify loans as either low-risk ("0") or high-risk ("1").

The machine learning process followed these key steps:

Splitting the dataset into training and testing sets
Training and fitting a logistic regression model
Assessing model performance using accuracy, precision, recall, and F1 scores
Machine Learning Model Performance
Accuracy, Precision, and Recall Scores

Accuracy: The model achieved an accuracy of 99%, meaning it correctly classified 99% of loan cases.
Precision:
For low-risk loans ("0"), the precision was 1.00, indicating that all identified low-risk loans were indeed low-risk.
For high-risk loans ("1"), the precision was 0.87, showing moderate effectiveness in identifying high-risk loans, with some false positives.
Recall:
For low-risk loans ("0"), the recall was 1.00, meaning the model correctly identified all instances of low-risk loans.
For high-risk loans ("1"), the recall was 0.89, reflecting moderate success in capturing high-risk loans, though some were missed.
Summary
Based on these results, the logistic regression model performed well in distinguishing between low-risk and high-risk loans. The model's strong precision, recall, and F1 scores for high-risk loans make it a valuable tool for lenders in mitigating financial risk and reducing the occurrence of bad loans.
