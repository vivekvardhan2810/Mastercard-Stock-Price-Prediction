# Mastercard Stock Price Prediction using LSTM, SVM, and K-Nearest Neighbors (KNN)

## Overview

This project focuses on predicting Mastercard's stock prices using three different machine learning models:

- **Long Short-Term Memory (LSTM)**

- **Support Vector Machines (SVM)**

- **K-Nearest Neighbors (KNN)**

Each model is trained and tested on historical stock data provided in the `Mastercard_stock_history.csv` dataset. The models' performance is compared based on Root Mean Squared Error (RMSE).

## Features

- **Exploratory Data Analysis (EDA)**: Visualizes stock trends and checks for missing values.

- **Preprocessing**: Normalizes the data and prepares it for model training.

- **Training Models**: Trains LSTM, SVM, and KNN models on the stock price data.

- **Stock Analysis Chart**: Plots the actual and predicted stock prices for each model.

- **Model Evaluation**: Evaluates model performance using RMSE.
  
## Dataset

The dataset `Mastercard_stock_history.csv` contains the following columns:
- `Date`: The date of the stock price.
- `Close`: The closing price of the stock.
- Other columns like Open, High, Low, Volume are ignored for this prediction task.

## Prerequisites

- Python 3.x
- Libraries: 
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `scikit-learn`
  - `keras`
  
Install the required libraries using the following command:

```
pip install numpy pandas matplotlib scikit-learn keras
```

## How to Run

1. **Clone the Repository**:

```
git clone https://github.com/yourusername/Mastercard-Stock-Prediction.git
cd Mastercard-Stock-Prediction
```

2. **Run the Prediction Script**:

```
python stock_price_prediction.py
```

The script will:

- Perform data preprocessing.

- Train the LSTM, SVM, and KNN models.

- Plot the actual vs predicted stock prices for each model.

- Print the RMSE of each model.

## Project Structure

```
Mastercard-Stock-Prediction/
├── Mastercard_stock_history.csv   # Historical stock data
├── stock_price_prediction.py      # Main Python script for stock prediction
├── README.md                      # Project documentation
└── requirements.txt               # List of required Python libraries
```

## Results

After running the script, you will see the actual and predicted stock prices plotted on the graph for each model (LSTM, SVM, KNN). Additionally, the RMSE (Root Mean Squared Error) for each model will be printed in the console.

