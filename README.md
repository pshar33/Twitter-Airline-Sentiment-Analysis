# Twitter-Airline-Sentiment-Analysis

### Code requirements

* Numpy
* Pandas
* matplotlib
* os
* re,nltk
* sklearn

**If you are using anaconda you need to :-**
- install wordcloud in the anaconda prompt using the command **python -m pip install wordcloud** (for visualization purposes)
- install mlxtend using the command **pip install mlxtend** (for plotting the confusion matrix)
- install nltk using **pip install nltk** ( toolkit for nlp data)

### Description
This **KAGGLE dataset** is a csv file of tweets for 6 different airlines over a period of **2015-02-17 to 2015-02-24**.
I found some interesting results by visualizing and cleaning the data and then by later trying to predict the twitter sentiments by the tweets data.

### Breakdown of the notebook:

1. Loading the dataset: Load the data and import the libraries.
2. Data Preprocessing:
    - Analysing missing data
    - Removing redundant columns.
3. Visualising and counting sentiments of tweets for each airline
4. Wordcloud plots for positive and negative tweets to visualise most frequent words for each.
5. Analysing the reasons for negative tweets for each airline.
6. Visualising negative tweet-sentiment relationship with dates.
7. Predicting the tweet sentiments with tweet text data with:
    - Decision Tree Classifier
    - Random Forest Classifier
8. Calculating accuracies, plotting the confusion matrix and comparing the models.
