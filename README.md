![Banner](https://static.coindesk.com/wp-content/uploads/2019/04/bitcoin-btc-chart-1200x600.jpg)

# BitCoin(BTC) Price - A Predictive Analysis 

In this project, I utilize historical BTC price data pulled from the Binance API client to explore and analyze its predictibility as an asset using rather traditional indicators as model features. 

**Approach**

In order to derive predicted prices from the original BTC dataset from Binance I use supervised regression techniques. The supervised learning includes a simple *Linear Regression (LR)* model as well as a *Random Forest Regression (RFR)* model that will use the previous close price from the dataset as our “prediction target”. Along with those two models, I use a unique time-series forecasting architecture called *Long Short Term Memory (LSTM)*. 

You can read a more detailed explantion [here](https://github.com/jra333/BTC-Price-Prediction/blob/main/Capstone%20Project%202%20Proposal.pdf).

**Table of Contents:**
- [Stage 1: Data Wrangling](https://github.com/jra333/BTC-Price-Prediction/tree/main/Data%20Wrangling)
- [Stage 2: Exploratory Data Analysis (EDA)](https://github.com/jra333/BTC-Price-Prediction/tree/main/Exploratory%20Data%20Analysis%20(EDA))
- [Stage 3: Preprocessing and Training](https://github.com/jra333/BTC-Price-Prediction/tree/main/Preprocessing-Training)
- [Stage 4: Modeling](https://github.com/jra333/BTC-Price-Prediction/tree/main/Modeling)
