# Stock-Sentiment-Analysis-using-News-Headlines

* This article is actually based on Natural Language Processing(NLP), here we will create a model which will actually analyze stock price using News Headline. 
* There are various kinds of news articles and based on that the stock price fluctuates. 
* We will analyze the news heading using sentiment analysis using NLP and then we will predict the stock will increase or decrease. It is all about stock sentiment analysis.

### About the problem and the dataset used.
* The data set in consideration is a combination of the world news and stock price shifts.
* Data ranges from 2008 to 2016 and the data from 2000 to 2008 was scrapped from Yahoo finance.
* There are 25 columns of top news headlines for each day in the data frame.
* Class 1- the stock price increased.
* Class 0- the stock price stayed the same or decreased.
### About the approach.
* Used TF-IDF and Bag of Words for extracting featues from the headlines.
* Used Random Forest Classifier, Multinational Naive Bayes and Passive Aggressive Classifier for analysis.
