# twitter_nlp_classification
Classification of twitter sentiment analysis data using Naive-Bayes Classifier.

## Overview

This is the repository of a small project to classify twitter comments into positive and negative sentiments. In this era of social media it is very easy to spread hate speech and racist remarks online. Different social media platforms have been leveraging the power of Natural Language Processing (NLP) to flag the comments which are related to hate and racism. In this project a twitter sentiment analysis is done from a dataset contatining real world tweets from twitter. The dataset contains 31962 observations. The tweets themselves contain twitter user handles, punctuations and stopwords. Data pre-processing is done to renmove these unwanted features from the data and then the tweets are count vectorized to train a Naive-Bayes classifier model with it. The classifier performance is evaluated using confusion matrix, precision, recall and f1 score.

## Dependencies

| Framework | Version |
|-----------|---------|
| Numpy     | 1.18.5  |
| Pandas    | 1.0.4   |
| Seaborn   | 0.9.0   |
| Sklearn   | 0.21.3    |
| Matplotlib| 3.2.1   |
| Wordcloud  | 1.8.0 |

The code was written and tested on Python 3.7
