# Loan Default Risk Prediction with Business Cost Optimization

## Objective
Predict whether a customer will default on a loan and optimize the decision threshold using business cost analysis.

## Dataset
Home Credit Default Risk Dataset (Kaggle)

## Approach
- Data cleaning and preprocessing
- Logistic Regression model
- Probability prediction
- Custom business cost function
- Threshold optimization to minimize financial loss

## Business Cost Assumptions
- False Positive (reject good customer): $1,000
- False Negative (approve defaulter): $10,000

## Results
Optimal threshold selected based on minimum total business cost.
Cost-based evaluation provided better decision-making than default 0.5 threshold.

## Skills Demonstrated
- Binary classification
- Cost-sensitive learning
- Risk modeling
- Business decision optimization
