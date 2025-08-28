# Stock Market Prediction Using Ensemble Machine Learning Models

This project explores stock market prediction using four machine learning models:
- Linear Regression
- Decision Tree
- Random Forest
- Multi-Layer Perceptron (MLP)

The models were trained on **Yahoo Finance data** via the `yfinance` package and combined using **accuracy-weighted and average-weight ensembles**.  
Results showed that **accuracy-weighted ensembles consistently outperformed single models and average ensembles** in terms of Mean Squared Error (MSE).

---

## Method
- Data: 5 years of daily opening prices from Yahoo Finance (`yfinance`).
- Input: Past 3 days of opening prices.
- Output: Prediction of the 4th day's opening price.
- Evaluation: Mean Squared Error (MSE).
- Simulation: Trading experiments comparing cash outcomes using average vs accuracy-weighted ensembles.

---

## Dependencies
```bash
pip install numpy pandas scikit-learn matplotlib yfinance
