# Improving Singapore Airlines (SIA) Customer Satisfaction with Topic Modeling and Sentiment Classification

## Introduction
This is a group project for CS610 Applied Machine Learning Course.   

The objective of the project is to leverage machine learning (ML) to automate sentiment classification and topic discovery of reviews
* Support triaging of feedback through theme and sentiment detection, enabling the organisation to make informed decisions
* Consolidation of feedback into a regular report for analysis (e.g., weekly pain points and compliments)

## Dataset Used
* Singapore Airlines dataset from Kaggle
* https://www.kaggle.com/datasets/kanchana1990/singapore-airlines-reviews/versions/1

## Technologies Used
Programming language
* Python

Machine learning models tested   
Sentiment classification
* Logistic regression (with finetuned DistilBERT embeddings)
* XGBoost (with finetuned DistilBERT embeddings)

Topic modelling
* BERTopic
* Latent Dirichlet Allocation (LDA)

## Final ML Pipeline Created
Best sentiment classifier and best topic modeller combined into a manual pipeline
* Logistic Regression (DistilBERT embeddings) + BERTopic
* Logistic Regression used to predict sentiment
* BERTopic used to extract topics from review text

Refer to Jupyter notebooks for details on the ML models.
