
# Twitter sentiment analysis of Bitcoin

Stock and Crypto prices are influenced by the supply and demand of those assets. To find out if the rise in demand can be displayed by the sentiment on Twitter, I started this project which is about the sentiment analysis of bitcoin in a given timeframe and comparing the sentiments with the price of bitcoin.
## Objectives

The task is to query tweets from Twitter and predict the sentiment of those tweets.


## Methodology

- Data fetching - Get the date
- Data Wrangling - Clean the Text column 
- Running the model - Run the model
- Compare and graph the results with bitcoin price quote


## Roadmap

- First to fetch the date I used the unofficial twitter api from the Twint library.

- Secondly I sorted and cleaned the data. The importnt part was to remove the @mentions, special characters and retweets.

- For the sentiment analysis I used a pretrained transformers model from the Hugging Face library.

- Subsequently, I fetched the price data of bitcoin for the same timeframe to find out if there is a correlation between those two variables.

## Observation

It seems that the Twitter sentiment and the close price of bitcoin are correlated during these past few hours. Of course, a larger timespan would provide greater confidence — but this provides us with an initial positive outcome to investigate further.
