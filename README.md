# StockPricePredictions
This project implements Recurrent Neural Network (RNN) and Long Short-Term Memory (LSTM) models for forecasting stock prices using synthetic data generated via stochastic processes. Includes autoregressive prediction, sequence length ablation studies, evaluation metrics, and visualization.

## Key Features

- RNN and LSTM-based time series forecasting models
- Synthetic data generation using a simplified Geometric Brownian Motion (GBM)
- Evaluation using MAE, RMSE, R², and MAPE
- Autoregressive prediction support
- Ablation study with modifiable `seq_length` input sequence length
- You can modify the seq_length variable to experiment with different historical lookback windows:
  `seq_length = 7` # try 10, 20 or 30 for ablation study

---

## Repository Contents

- `MCS_StockPrice_RNN_7_v3.ipynb`: Implements the RNN model
- `MCS_StockPrice_LSTM_7_v4.ipynb`: Implements the LSTM model

---

## Requirements

Install dependencies with:

```bash
pip install torch numpy pandas matplotlib scikit-learn
```

---

## How to Run

1. Clone the repository
```bash
git clone https://github.com/aniketbhaumik/StockPricePredictions.git
cd StockPricePredictions
```

2. open the notebook using Jupyter or Google Colab

`jupyter notebook MCS_StockPrice_LSTM_7_v4.ipynb`
# or
`jupyter notebook MCS_StockPrice_RNN_7_v3.ipynb`


3. Run all the cells step by step:
  a) Simulate synthetic stock prices
  b) Train RNN/LSTM models
  c) Evaluate and visualize results

---

## License

This project is licensed under the MIT License.

---

## Acknowledgements

Developed as part of an academic project on financial time series modeling with deep learning 
