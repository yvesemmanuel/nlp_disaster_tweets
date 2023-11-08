# NLP with Disaster Tweets - Kaggle Competition

This repository contains machine learning models and analyses for the Kaggle competition ["Natural Language Processing with Disaster Tweets"](https://www.kaggle.com/c/nlp-getting-started). The goal of the competition is to build a machine learning model that predicts which tweets are about real disasters and which ones are not.

## Overview

The task is to create a machine learning model that can accurately classify text data—in this case, tweets—into two categories: tweets about real disasters and tweets that are not. This is a classic binary text classification problem with a real-world application of understanding how social media can play a crucial role in effective disaster response.

## Models

Here are the results of the models implemented so far:

- [**Logistic Regression**](https://github.com/yvesemmanuel/nlp_disaster_tweets/blob/main/Tweet_Disaster_Classification_logistic_regression.ipynb): A simple yet powerful linear model used as a baseline for binary classification tasks. The model performed with an accuracy score of 0.73143 on the competition's test set.

- [**Naive Bayes**](https://github.com/yvesemmanuel/nlp_disaster_tweets/blob/main/Tweet_Disaster_Classification_naive_bayes.ipynb): A probabilistic classifier based on applying Bayes' theorem with strong (naive) independence assumptions between the features. It is particularly suited for high-dimensional data, and it performed better than logistic regression with an accuracy score of 0.77873.

### Performance Summary

| Model            | Accuracy Score |
|------------------|----------------|
| Logistic Regression | 0.73143        |
| Naive Bayes         | 0.77873        |

_**Note:** The accuracy scores are reflective of the model's performance on the Kaggle competition's test dataset._
