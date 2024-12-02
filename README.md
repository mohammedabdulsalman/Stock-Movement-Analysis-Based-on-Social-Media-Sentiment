# Stock-Movement-Analysis-Based-on-Social-Media-Sentiment
: Develop a machine learning model that predicts stock movements by scraping data from social media platforms like Twitter, Reddit, or Telegram. The model should extract insights from user-generated content, such as stock discussions, pr
project Description:
This project is about analyzing social media data about Apple Inc. and predicting its future stock trend with sentiment classification. We applied sentiment analysis and machine learning principles to discover the possible effect of "public sentiment" on "market trends".

Prediction of stock price is an extremely complex and very challenging task because there are too many factors involved such as economic circumstances, political events, and other environmental factors which may impact the stock price. Due to these factors, it is difficult to find out the dependence of a single factor on future prices and trends.

The popularity and importance of numerous social media platforms has risen to new levels over the past few years, as more people spend time online. One such social media platform that has seen an explosive rise in popularity is Twitter. Twitter is a rich source of real-time information regarding current societal trends and opinions. The "Twittesphere" is a melting pot driving various opinions, emotions and trends and could be a pivotal factor in influencing and shaping perceptions.
Some statistics regarding Twitter:

Twitter has 145 million monetizable daily active users.

30 million (or 20%) of Twitter’s daily users are American.

92% of the U.S. population is familiar with Twitter (even if they don’t use it).

According to a recent survey by Pew Research Center, around one-in-five U.S. adults (22%) say they use Twitter.

Twitter stands out as one of the social media sites with the most news-focused users.

Behavioural economics tell us that people are not rational consumers and individual behaviours and decisions are greatly affected by emotions and indeed by the opinions of others. Twitter sentiment analysis can be extremely helpful for predicting emotions or opinion on a certain stock. So examining the trending mood on Twitter and observing its relationship to the movement in stock price can help predict the future trend in the market.

Data Preprocessing
Twitter data from Kaggle for Apple stock was used for sentiment analysis. The time frame chosen to analyze data is January 01, 2016 to August 31, 2019.

We collected daily Apple stock data for the same time period from Yahoo Finance for historical data analysis and stock price/trend prediction.
Algorithms used for analysis:

Random Forest Classifier

Random Forest Classifier is an ensemble method, meaning that a random forest model is made up of a large number of small decision trees, called estimators, which each produce their own predictions. The random forest model combines the predictions of the estimators to produce a more accurate prediction.
Random Forest Regressor

Random Forest Regression is a supervised learning algorithm that uses ensemble learning method for regression. Ensemble learning method is a technique that combines predictions from multiple machine learning algorithms to make a more accurate prediction than a single model.
Limitations/ What could have been done differently?
Twitter API has limitations on the amount of data that can be accessed. Therefore, a document with Twitter information regarding Apple stock from Kaggle was used.

The Kaggle dataset also had limited data (Jan'16 - Aug'19) which restricted our analysis to limited number of trading days.

NewsAPI headlines besides Twitter could also have been used for sentiment analysis.

Identifying optimum hyperparameters to fine tune the model outputs.
