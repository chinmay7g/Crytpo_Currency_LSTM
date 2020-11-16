# Crytpo_Currency_LSTM

![BTC](https://user-images.githubusercontent.com/55191934/99220330-77cf8100-2804-11eb-8572-9f83dabd323d.jpg)

Following repository aims at understanding and predicting the cryptocurrency using LSTM.
Cryptocurrencies used were BitCoin, Ethereum, LiteCoin.

On analysing from the Buy&Hold point of view, it is observed that LiteCoin has better returns comparitively to BitCoin, Ethereum.

![return_crypto_graph](https://user-images.githubusercontent.com/55191934/99220706-25429480-2805-11eb-85ce-720033147b4d.png)

The below image denotes the Close price for the LiteCoin for the given date and time:

![BTC_LSTM_4](https://user-images.githubusercontent.com/55191934/99221550-cbdb6500-2806-11eb-8a19-59aa3dc4b580.PNG)

The LSTM model is then applied on the dataset for LTE (LiteCoin). LSTM is a recurrent Artificial Neural Network that is here used for time series analysis and 
is powerful in sequencing. 

Loss function when model is tuned to epoch=30:

![BTC_LSTM_5](https://user-images.githubusercontent.com/55191934/99221779-3d1b1800-2807-11eb-9d2b-66724aa72d02.PNG)

From the above, it can be seen model converged somewhere around 5 epochs and loss is maintained below 0.002 thereafter.

Results and Predictions are as below shown:

![BTC_LSTM_6](https://user-images.githubusercontent.com/55191934/99221983-a569f980-2807-11eb-9d03-12def57ee01f.PNG)
