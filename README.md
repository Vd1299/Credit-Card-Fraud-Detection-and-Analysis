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
| Random Forest | 99.2% | 0.987 |
| Gradient Boosting | 99.1% | 0.985 |
| Decision Tree | 98.8% | 0.979 |
| Naive Bayes | 97.5% | 0.968 |

## Key Insights
- Top predictive features automatically identified
- Large transactions show higher fraud rates
- Specific merchant categories have elevated risk
- Best model achieves 89% fraud detection rate

## License
MIT License- https://opensource.org/license/mit
