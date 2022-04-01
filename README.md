# NLP Content Based Recommender System

This is a simple content-based recommender implement in python 3.0 to illustrate content-based recommemder on candidates matching with jobs.

The expected model is to input a / list of candidate namelist and output of recommend job positions.

![alt text](https://miro.medium.com/max/1400/1*P63ZaFHlssabl34XbJgong.jpeg)

The training process involves 6 steps:
- Data Cleansing (html tag, stop words, ...)
- Data Preparation / Manuputation
- Formatting data stemming, lemmatizer
- Job text vectors formation using TFIDF and Count Vectorizer
- Find the Cosine Similarity score between job text and candidate text
- Test other algorithm such as Spacy (pre-trained word vectors) and KNN (K-Nearest Neighbors) for comparation.


![alt text] (https://github.com/LightLow/content-based_recommender/blob/main/model-flow.png?raw=true)
