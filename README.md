CryptoPricePredictor

This project is aimed at predicting price movements in the cryptocurrency market using machine learning. 

Overview
Using historical data and technical indicators (e.g., moving averages and RSI), this project builds a predictive model that anticipates price direction. The metric optimized in this project is the macro-averaged F1 score, balancing both precision and recall.



Libraries Used
- **pandas**
- **numpy**
- **sklearn** (for preprocessing, metrics, and model selection)
- **xgboost** (XGBoostClassifier)
- **imbalanced-learn** (SMOTE for oversampling)
- **matplotlib** and **seaborn** (for visualization)

Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/moe0009/CryptoPricePredictor.git
   cd CryptoPricePredictor
