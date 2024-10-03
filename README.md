In this project i created a simple LSTM Model in Order to predict the AAPL stock (APPLE). Through this project i also experimented with different batch sizes and
epoch in order to calculate the best model. To calculate the best model i used RMSE and MAE error values. 

Here are some of the experimented values i used:

epoch | batch_size | training RMSE error | training MAE error | testing RMSE error | training MAE error
-------------------------------------------------------------------------------------------------------
100   |     12     |      2.5928         |       1.7869       |       7.3518       |       4.9659      
-------------------------------------------------------------------------------------------------------
100   |     15     |      2.5180         |       1.7266       |       7.6148       |       4.7558      
-------------------------------------------------------------------------------------------------------
50    |     12     |      3.3461         |       2.4062       |       7.0068       |       4.7510      
-------------------------------------------------------------------------------------------------------
50    |     15     |      3.3507         |       2.5358       |       7.8915       |       5.6807      
-------------------------------------------------------------------------------------------------------
100   |     9      |      2.5836         |       1.7789       |       8.3035       |       5.4088      
-------------------------------------------------------------------------------------------------------
100   |     20     |      2.7537         |       1.9311       |       7.3102       |       4.5591      
-------------------------------------------------------------------------------------------------------
200   |     12     |      2.4789         |       1.6719       |       7.4321       |       4.6648      
-------------------------------------------------------------------------------------------------------
200   |     15     |      2.6982         |       1.9625       |       8.3915       |       5.9822      
-------------------------------------------------------------------------------------------------------
200   |     5      |      2.7296         |       2.0643       |       11.9279      |       8.9169      


Using that table of results the model concludes with average RMSE error = 8.8033 and MAE error = 5.5205 in testing.
I can conclude that the model had success rate at 91% predicting AAPL (Apple stock).

The database was used from https://www.kaggle.com/datasets/suyashlakhani/apple-stock-prices-20152020
