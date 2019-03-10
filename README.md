# Stock-market-sentiment-analysis
The main purpose of the following code is prediction of stock market trends using sentiment analysis. 

Data source: Kaggle

All the code is included in the intermidiate_report.ipynb file. It might be necessary to change file paths before running code on local machine 

The project first applies simple neural networks and then more complex models like LSTMs to time series data to see if they are successful in predicting the change in price of stocks.

Then I used sentiment analysis of news to see how news sentiment co-relates to the change in price of stocks. Surprisingly sentiment analysis of doesn't provide a substantial improvement over baseline methods in predicting prices. This suggests that news is merely a after effect of the trend not the cause for it.

Several early papers have suggested sentiment analysis as a excellent method to predict stock prices[2] while several later papers[1] suggest exactly the opposite. The cause of later poor results is usually attributed to spam posts[1] whose sole job is to decieve the sentiment analysis model. This project can a considered a expriment in understanding why prediction models need to keep on evolving and also not to blindly trust models just because they worked in the past.

[1] Stock chatter: Using stock sentiment to predict price direction Michael Rechenthin , W. Nick Street a , and Padmini Srinivasan

[2]Stock Prediction Using Twitter Sentiment Analysis Anshul Mittal, Arpit Goel
 
