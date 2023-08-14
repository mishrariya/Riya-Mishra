# Twitter Sentiment Analysis
This file contains code that performs sentiment analysis on Twitter data using a Logistic Regression classifier. The goal is to classify the sentiment of tweets into positive, negative, or neutral categories.

## Introduction
Sentiment analysis involves determining the sentiment or emotion expressed in a piece of text. In this project, we use the Natural Language Toolkit (NLTK) and Scikit-learn libraries to preprocess the Twitter data, create TF-IDF vector representations, and train a Logistic Regression classifier for sentiment classification.

## Preprocessing
The text data undergoes several preprocessing steps:

** Tokenization **: Splitting the text into individual words or tokens.
** Lowercasing **: Converting all tokens to lowercase to ensure uniformity.
** Stopword Removal **: Removing common words like "and," "the," etc. that do not carry significant meaning.
** Non-Alphabetic Token Removal **: Removing tokens that are not composed of alphabetic characters.

## Model
A Logistic Regression model is used for sentiment classification. The TF-IDF (Term Frequency-Inverse Document Frequency) vectorizer is employed to convert text data into numerical vectors. These vectors are used as input to the Logistic Regression classifier.

## Results
The accuracy of the model is calculated by comparing the predicted sentiment labels to the true labels of the test data. The accuracy score obtained is approximately 80%.
