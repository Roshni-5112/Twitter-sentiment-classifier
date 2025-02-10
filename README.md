# Twitter-sentiment-classifier

Overview
This project performs entity-level sentiment analysis on Twitter data. Given a tweet and an entity, the task is to determine the sentiment of the tweet towards the entity. The sentiment is classified into three categories:Positive,Negative
,Neutral (includes Irrelevant messages)

Dataset
The dataset consists of labeled Twitter messages with corresponding entities and sentiment labels. Messages that are not relevant to the entity are categorized as Neutral.

Features
Preprocessing: Tokenization, stopword removal, stemming, and lemmatization
Feature Extraction: TF-IDF, word embeddings 
Modeling: LGBM, Random Forest, SVM
Evaluation Metrics: Accuracy, Precision, Recall, F1-Score
