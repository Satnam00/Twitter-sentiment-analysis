# Twitter-sentiment-analysis
Social media have received more attention nowadays. Public and private opinion about a wide variety of subjects are expressed and spread continually via numerous social media. Twitter is one of the social media that is gaining popularity. Twitter offers organizations a fast and effective way to analyze customers' perspectives toward the critical to success in the market place. Developing a program for sentiment analysis is an approach to be used to computationally measure customers' perceptions.

Sentiment Analysis on Tweets


Dataset Information
We use and compare various different methods for sentiment analysis on tweets (a binary classification problem). The training dataset is expected to be a csv file of type tweet_id,sentiment,tweet where the tweet_id is a unique integer identifying the tweet, sentiment is either 1 (positive) or 0 (negative), and tweet is the tweet enclosed in "". Similarly, the test dataset is a csv file of type tweet_id,tweet. Please note that csv headers are not expected and should be removed from the training and test datasets.

Requirements
There are some general library requirements for the project and some which are specific to individual methods. The general requirements are as follows.

numpy
scikit-learn
scipy
nltk
The library requirements specific to some methods are:


