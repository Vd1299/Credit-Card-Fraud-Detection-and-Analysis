# Credit Card Fraud Detection

A machine learning project to detect fraudulent credit card transactions using multiple classification algorithms.

## Dataset
- **550,000** credit card transactions
- **28 anonymized features** (V1-V28) + Amount + Class
- **Binary classification**: 0 (Non-Fraud) vs 1 (Fraud)

## Models
- Random Forest
- Gradient Boosting  
- Decision Tree
- Naive Bayes

## Features
- Feature importance analysis
- Merchant category risk assessment
- Transaction type analysis
- Model performance comparison with confusion matrices

## Results
| Model | Accuracy | AUC |
|-------|----------|-----|
| Gradient Boosting | 99.1% | 0.99 |
| Random Forest | 97.8% | 0.99 |
| Decision Tree | 97.8% | 0.98 |
| Naive Bayes | 93.4% | 0.98 |


## Key Insights
- Top predictive features automatically identified
- Large transactions show higher fraud rates
- Specific merchant categories have elevated risk
- Best model catches 98% fraud transactions

## License
MIT License- https://opensource.org/license/mit
