# 📈 LSTM Stock Price Predictor

This project uses a Long Short-Term Memory (LSTM) neural network to forecast stock closing prices using historical stock price and volume data. Built and run entirely in Python with Jupyter Notebook.

## 🔍 Overview

The model is trained on historical stock prices, leveraging LSTM’s strength in capturing sequential dependencies in time series data. After training, the model outputs predicted prices alongside actual closing prices for visual comparison.

### 🧠 Key Features

- LSTM-based model built with TensorFlow/Keras
- Uses both stock price and volume features
- Clean, reproducible Jupyter Notebook workflow
- Output visualizations with Matplotlib and Plotly
- Model performance visualized against actual data

## 🗂️ Project Structure

```
.
├── PredictingStockFuture.ipynb    # Jupyter Notebook
├── stock.csv                      # Historical price data
├── stock_volume.csv               # Volume data
├── requirements.txt               # Environment dependencies
└── README.md                      # This file
```

## 📊 Output Sample

![LSTM Prediction vs Actual](301f4a43-ec2b-43bd-abd3-059ac4d68d53.png)

This plot shows a strong visual alignment between actual and predicted stock values — an indicator of successful sequence learning by the LSTM model.

## ⚙️ Installation

### Clone the Repo

```bash
git clone https://github.com/PJEDeveloper/stock-price-lstm.git
cd stock-price-lstm
```

### Set Up Environment

Install required dependencies (recommended in a virtual environment):

```bash
pip install -r requirements.txt
```

## 🚀 How to Run

1. Open the Jupyter notebook:
   ```bash
   jupyter notebook PredictingStockFuture.ipynb
   ```

2. Execute the cells step-by-step to:
   - Load and preprocess data
   - Train the LSTM model
   - Visualize predictions

## 📂 Data Sources

- `stock.csv`: Contains normalized closing price data
- `stock_volume.csv`: Includes associated trading volumes
- Ensure these datasets are in the root directory before running the notebook

## 📝 License

This project is licensed under the Apache 2.0 License.

---

> Developed by Patrick Hill  
> [LinkedIn](https://www.linkedin.com/in/patrick-hill-4b9807178/)
