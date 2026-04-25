# Crypto Price Prediction

This project predicts **Cryptocurrency Prices** using machine learning and time-series concepts.
In this project, I used Bitcoin historical data and tried to predict future prices based on past values.

------
## What I did in this project

- Collected crypto data using yfinance  
- Applied basic time-series techniques  
- Created lag features (used past values for prediction)  
- Calculated Moving Averages (MA20, MA50)  
- Implemented RSI 
- Trained a Random Forest model  
- Compared predicted values with actual prices  
-  RMSE,MAE, MAPE evaluation.

---

## How it works

The model uses previous price data (lag values) to predict the next values.  
It follows a time-based approach, so data is not shuffled.

---

## Output

- Graph of Actual vs Predicted prices  
- Market trend using Moving Averages  

---

## Tools & Libraries

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Scikit-learn  
- yfinance  

---

## How to run

1. Open the notebook in Google Colab  
2. Install libraries if needed  
3. Run all cells  

---

## Note

crypto market is voiatile ,so predictions may not always be accurate..

---
## Author
Harshal Ramteke(pea-hen)
