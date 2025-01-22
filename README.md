# NLP with Disaster Tweets - Kaggle Competition

This repository contains a series of machine learning models and analyses for the Kaggle competition ["Natural Language Processing with Disaster Tweets"](https://www.kaggle.com/c/nlp-getting-started). The goal of this competition is to predict whether a given tweet describes a real disaster or not.

## Models Implemented

Below are the models that have been implemented and evaluated for this task:

- **[DistilBERT](https://github.com/yvesemmanuel/nlp_disaster_tweets/blob/main/Tweet_Disaster_Classification_distilbert_lora_tuning.ipynb)**: A transformer-based model fine-tuned using the LoRA (Low-Rank Adaptation) approach to efficiently adjust model weights for tweet classification.
- **[Naive Bayes](https://github.com/yvesemmanuel/nlp_disaster_tweets/blob/main/Tweet_Disaster_Classification_naive_bayes.ipynb)**: A probabilistic classifier that uses word frequencies to classify tweets as disaster-related or not.
- **[Logistic Regression](https://github.com/yvesemmanuel/nlp_disaster_tweets/blob/main/Tweet_Disaster_Classification_logistic_regression.ipynb)**: A linear model that applies the sigmoid function to classify tweets based on extracted features.
- **[XGBoost](https://github.com/yvesemmanuel/nlp_disaster_tweets/blob/main/Tweet_Disaster_Classification_xgboost.ipynb)**: A gradient boosting algorithm designed for performance and scalability, used here to classify tweets as disaster-related or not.

## Performance Summary

Below is a summary of the performance of each model based on their accuracy scores on the Kaggle competition's test dataset:

| Model              | Accuracy Score |
|--------------------|----------------|
| **DistilBERT**      | 0.79650        |
| **Naive Bayes**     | 0.79007        |
| **Logistic Regression** | 0.73827    |
| **XGBoost**         | 0.73797        |

_**Note:** The accuracy scores are reflective of the model's performance on the Kaggle competition's test dataset._

## Conclusion

- **DistilBERT** outperforms other models with the highest accuracy, making it a strong candidate for disaster tweet classification.
- **Naive Bayes** and **Logistic Regression** are competitive, with Naive Bayes showing slightly better performance than Logistic Regression.
- **XGBoost**, despite being a powerful algorithm, yields a slightly lower accuracy compared to the other models tested.

Each model has its advantages, and the choice of model depends on the trade-offs between performance, interpretability, and computational cost.
