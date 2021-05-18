# Stock_Prediction_Sentiment_Analysis
This is a project of Forecasting DJIA index trend with news headlines using BERT and LSTM

The pipeline involves two steps, first step is preprocessing the two raw dataset,'Gaurdian_news' and 'Reuters', and combine into a single csv file containing all headlines 'Data.csv'.

After preprocess, there are two approaches for doing sentiment analysis, BERT or LSTM. They are independent to each other containing the whole pipeline. The reason to have two is because variables tends to mess up between two models.

You may run either/all of them to see the result. Make sure the 'data.csv' and 'DJIA.csv' are placed in the same folder as ipynb file.
