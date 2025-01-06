# 📈 StockPrediction with Machine Learning

**StockPrediction** is a machine learning-based project that predicts stock prices using various regression models. The project utilizes data from the S&P500 index and implements models such as Support Vector Machine (SVM), Bayesian Ridge Regression, Linear Regression, XGBoost Regressor, and Kernel Ridge Regression to analyze and predict future stock prices.

---

## 📋 Abstract

Stock prediction plays a critical role in the financial sector for investors seeking high returns while managing risks. This project uses historical stock market data and machine learning techniques to predict stock prices accurately. It demonstrates the comparative effectiveness of various regression models and highlights the importance of robust prediction systems for investment decision-making.

---

## 🔧 Features

- **Data Source**: S&P500 historical data (2001-2021) from Yahoo Finance.
- **Visualization**: Trends in adjusted closing prices, volumes, and moving averages.
- **Regression Models**:
  - Linear Regression
  - XGBoost Regressor
  - Kernel Ridge Regression
  - Bayesian Ridge Regression
  - Support Vector Machine (SVM)
- **Performance Metrics**: Root Mean Square Error (RMSE) for evaluating model performance.

---

## 📊 Results

- **Linear Regression**: RMSE = 4.7128
- **XGBoost Regressor**: RMSE = 4.8147
- **Kernel Ridge Regression**: RMSE = 4.5646
- **Bayesian Ridge Regression**: RMSE = 4.4437
- **Support Vector Machine Regression**: RMSE = 6.8800

---

## 🛠️ Installation and Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/ChethanKacham/StockPrediction.git
   cd StockPrediction

2. **Install Dependencies**: Ensure you have Python installed (3.8+). Install the required packages:
   ```bash
   pip install -r requirements.txt

3. **Run the Notebook**: Launch the Jupyter Notebook:
   ```bash
   jupyter notebook Stock_Prediction.ipynb

---

## 📈 Dataset

   - S&P500 daily trading data (2001-2021).
   - Training data: 70% of the dataset.
   - Testing data: Remaining 30% of the dataset.

## 🔮 Future Enhancements

   - Implement deep learning models like LSTM and GRU for time series prediction.
   - Integrate financial news sentiment analysis to improve prediction accuracy.
   - Add real-time data fetching and prediction capabilities.
   - Develop an interactive dashboard for users.
