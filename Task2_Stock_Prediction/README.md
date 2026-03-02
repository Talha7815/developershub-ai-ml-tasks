# Task 2: Stock Price Prediction

## 📌 What I Did
I built a model that predicts tomorrow's stock price for Apple (AAPL) using historical data.

## 📊 Dataset
- **Source**: Yahoo Finance (yfinance library)
- **Stock**: Apple Inc. (AAPL)
- **Time Period**: Last 2 years of daily data
- **Features Used**: Open, High, Low, Close, Volume

## 🛠️ Tools Used
- Python
- yfinance (data fetching)
- pandas (data handling)
- scikit-learn (machine learning)
- matplotlib/seaborn (charts)

## 🤖 Models Used
1. **Linear Regression** - R² Score: 0.8164, MAE: $2.94
2. **Random Forest** - R² Score: -1.6253, MAE: $13.33

## 📈 Results
- **Best Model**: Linear Regression
- **Prediction Accuracy**: ±$2.94 on average
- **Most Important Features**: 
  - High-Low Ratio (volatility)
  - Open-Close Ratio (price gap)
  - Current Close price

## 📁 Files in this Folder
- `Task2_Stock_Prediction.ipynb` - My complete analysis notebook

