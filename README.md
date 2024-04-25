# sp500_LSTM_predict
SP500 stock prediction using Bidirectional LSTM recurrent neuronal network.

Model has been trained with the last 10 years SP500 data (2481 samples)

### Train data: 
  - 80% samples
### Test data:
  - 20% samples
### Evaluation data:
  - Last 250 sp500 days

### Features: 
  - Open
  - High
  - Low
  - Volume
  - Technical indicators:
      - RSI
      - PCT
  - Energy sp500 sector close value
  - VIX volatibility
  - Crude Oil stock close value

### Label:
  - sp500 close 


### Model evaluation:

MAPE: 0.006201656116299953

Mean squared error: 1001.3350514867699

Root mean squared error: 31.643878578435512

Mean absolute error: 28.43005812311747

R2: 0.9909222432243882

<img src="https://github.com/dbeniteze/sp500_LSTM_predict/blob/main/images/sp500_close_vs_predict.png" width="420">


### References:

<a href="https://finance.yahoo.com/quote/%5EGSPC/" target="_blank"> S&P 500 - Yahoo Finance </a>
