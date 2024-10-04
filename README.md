# Exploring Car Insurance Trends

## Project Overview
This project, *Exploring Car Insurance Trends*, aims to analyze a dataset of 10,000 insurance policyholders and understand the factors contributing to the likelihood of filing an insurance claim. The insights gained are crucial for insurance companies in areas such as risk assessment, policy personalization, claim prediction, and fraud detection.

## Key Objectives:
1. **Risk Assessment**: Identify high-risk drivers for accurate policy pricing.
2. **Policy Personalization**: Tailor insurance policies based on individual risk profiles.
3. **Claim Prediction**: Anticipate claims to manage reserves and resources better.
4. **Fraud Detection**: Detect patterns that may indicate fraudulent claims.

## Data Description
The dataset contains 19 variables, including:
- **Demographics**: Age, gender, race.
- **Driving History**: Years of driving experience, past accidents, speeding violations, DUIs.
- **Vehicle Information**: Ownership, type, year.
- **Insurance History**: Outcome (whether a claim was filed), annual mileage.

## Analysis & Modeling
Exploratory data analysis revealed key relationships between variables (e.g., past accidents, speeding violations) and claim outcomes. Two models were developed to predict claim likelihood:
- **Logistic Regression**: Achieved an accuracy of 84.69% and AUC of 0.82.
- **Random Forest Classifier**: Achieved an accuracy of 83.74%.

### Performance:
- Logistic regression demonstrated slightly better predictive capabilities, making it a strong candidate for this dataset.
- Random forest also performed well, and further optimization or experimentation with other models (e.g., gradient boosting) could enhance results.

## Conclusion
Both models are effective in predicting insurance claims, with logistic regression standing out for its simplicity and accuracy. Future improvements may include feature engineering and model tuning for further optimization.

