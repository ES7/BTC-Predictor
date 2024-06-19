## Disclaimer
### Important Warning
Predicting the stock market or cryptocurrency prices, such as Bitcoin (BTC), is inherently uncertain and involves significant risk. The models and methodologies used in this project are based on historical data and machine learning techniques, which may not accurately predict future market movements. This project is intended for **educational purposes only**. The insights and predictions generated by this model should not be considered financial advice or a recommendation to invest. Users are advised to conduct their own research and consult with a professional financial advisor before making any investment decisions. The creator of this project is not responsible for any financial losses that may occur as a result of using this model or any predictions it generates.

# BTC-Predictor
Bitcoin (BTC) is a digital currency that operates on a decentralized network using blockchain technology. It was introduced in 2008 by an anonymous person or group of people using the pseudonym Satoshi Nakamoto and was released as open-source software in 2009.

In this project, I am developing a Bitcoin (BTC) price prediction model utilizing Long Short-Term Memory (LSTM) networks. LSTM, a type of recurrent neural network (RNN), is particularly well-suited for sequence prediction problems due to its ability to capture temporal dependencies. Given the highly volatile nature of cryptocurrency markets, accurately forecasting BTC prices can provide significant insights for traders and investors. This model aims to analyze historical price data and predict future BTC price movements, helping users make more informed trading decisions.

I have collected BTC price data from May 2016 to May 2024, spanning **8 years**, using the `Historic_Crypto` library. The code to scrape the data is inside **`Data_Collection.ipynb`** file.<br>
The size of this data is **0.265 GB**, which made it difficult to upload to GitHub. Therefore, I broke down the data file into four parts and uploaded their zip files. All the required explaination is provided inside **`BTC_Prediction.ipynb`**.
