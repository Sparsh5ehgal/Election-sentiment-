# Election sentiment Analysis using Glove and RNN
Twitter sentiment analysis for elections using Twitter database and glove and rnn model
The repository contains 5 ipython notebooks. The steps involved in the implementation of this project are as follows:

portfolio notebook gives the over view of the project.
Election_datascapre (code for fetching tweets using the twitter api tweepy)
Data_Labeling (code for labeling tweets as positive or negative based on the sentiment score. Resampling procedure for the data)
Exploratory Data Analysis
Glove model
Bidirectional RNN
Tweet_prediction
The data.7z contains all the data files(Election.csv is the final dataset that was used for the analysis)
The SavedModel.7z contains the models weights for Glove model

Contributions:

Generated the tweet datasets, combined data from different months.
Cleaned the tweets, labeled and resampled the dataset.
Performed exploratory data analysis
Created word embeddings using Glove. Built a model on top of the embeddings. Fine tuned the model by varing the nodes and architecture of the model.
References:

1.http://docs.tweepy.org/en/v3.5.0/
2.https://towardsdatascience.com/another-twitter-sentiment-analysis-bb5b01ebad90
3.https://www.analyticsvidhya.com/blog/2015/06/quick-guide-text-data-cleaning-python/
4.https://machinelearningmastery.com/tactics-to-combat-imbalanced-classes-in-your-machine-learning-dataset/
5.https://www.datacamp.com/community/tutorials/wordcloud-python
6.https://github.com/stanfordnlp/GloVe
