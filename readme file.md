# Credit Scoring Model Solution

## Overview
This project builds and evaluates machine learning models to predict creditworthiness based on customer financial data. The solution compares three classification algorithms to identify the most effective model for credit scoring.

## Dataset Features
- **Income** – Annual income
- **Age** – Age of applicant
- **LoanAmount** – Requested loan amount
- **DebtRatio** – Debt-to-income ratio
- **CreditHistory** – Length/quality of credit history
- **MissedPayments** – Number of missed payments
- **EmploymentYears** – Years employed
- **ExistingLoans** – Number of existing loans
- **Creditworthy** – Target variable (1 = creditworthy, 0 = not)

## Models Implemented
1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier

## Key Steps
- Missing value handling (median imputation)
- Train-test split (80/20)
- Feature scaling with StandardScaler
- Performance evaluation using:
  - Accuracy
  - Precision
  - Recall
  - F1 Score
  - ROC-AUC

## Results Summary

| Model                  | Accuracy | Precision | Recall | F1 Score | ROC-AUC |
|------------------------|----------|-----------|--------|----------|---------|
| Logistic Regression    | 0.9900   | 0.9831    | 1.0000 | 0.9915   | 0.9996  |
| Random Forest          | 0.9100   | 0.8889    | 0.9655 | 0.9256   | 0.9885  |
| Decision Tree          | 0.8700   | 0.8571    | 0.9310 | 0.8926   | 0.8584  |

## Best Performing Model
**Logistic Regression** achieved the highest overall performance with 99% accuracy and near-perfect ROC-AUC (0.9996), making it the most reliable choice for credit scoring in this dataset.

## Requirements