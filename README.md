# **Stock Market Prediction for Apple Using Random Forest**

This repository contains a Python-based project that predicts Apple's stock price movements using historical data and a **Random Forest Classifier**. The goal is to forecast whether Apple's stock price will go up or down the next day, helping investors make informed decisions.

---

## **Project Overview**

- **Objective**: Predict the direction of Apple's stock price (up or down) using historical stock data.
- **Model**: Random Forest Classifier.
- **Features**: Historical stock prices (Open, High, Low, Close, Volume) and engineered features like rolling averages and trends.
- **Evaluation**: Precision, Accuracy, and Backtesting.

---

## **Key Features**

- **Data Collection**: Historical Apple stock data from 1980 to 2025 using Yahoo Finance (`yfinance`).
- **Feature Engineering**: Created target variables and added momentum/trend features like rolling averages and close ratios.
- **Model Training**: Used a Random Forest Classifier to predict stock price movements.
- **Backtesting**: Implemented walk-forward validation to simulate real-world trading scenarios.
- **Improvements**: Added probability thresholding and additional predictors to enhance model performance.

---

## **Repository Structure**

```
stock-market-prediction/
├── data/                    # Contains the historical stock data
├── notebooks/               # Jupyter notebooks for analysis and prediction
├── README.md                # This file
├── requirements.txt         # List of Python dependencies
└── src/                     # Source code for data processing and model training
```

---

## **Getting Started**

### **Prerequisites**
- Python 3.x
- Libraries: `yfinance`, `pandas`, `numpy`, `scikit-learn`, `matplotlib`

### **Installation**
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/stock-market-prediction.git
   ```
2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

### **Usage**
1. Open the Jupyter notebook in the `notebooks/` directory.
2. Run the cells to load data, train the model, and evaluate predictions.

---

## **Results**
- **Precision**: 0.5105
- **Accuracy**: Moderate, with room for improvement.
- **Insights**: The model performs reasonably well in predicting stock price movements but can be further enhanced with more advanced techniques.

---

## **Future Work**
- Explore advanced models like **XGBoost** and **LightGBM**.
- Add more technical indicators (e.g., MACD, RSI).
- Perform hyperparameter tuning and ensemble methods for better accuracy.

---

## **Contributing**
Feel free to contribute to this project by opening issues or submitting pull requests. Any suggestions for improving the model or adding new features are welcome!

---

## **License**
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Happy predicting! 🚀
