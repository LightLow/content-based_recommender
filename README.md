# NLP Content Based Recommender System

This is a simple content-based recommender implement in python 3.0 to illustrate content-based recommemder on candidates matching with jobs.

The expected model is to input a candidate name and output a list of recommend job positions.

![alt text](https://miro.medium.com/max/1400/1*P63ZaFHlssabl34XbJgong.jpeg)

The training process involves 6 steps:
- Data Cleansing (html tag, stop words, ...)
- Data Preparation / Manuputation
- Formatting data stemming, lemmatizer
- Job text vectors formation using TFIDF and Count Vectorizer
- Find the Cosine Similarity score between job text and candidate text
- Test other algorithm such as Spacy (pre-trained word vectors) and KNN (K-Nearest Neighbors) for comparation.

# Logic behind the model

The logic behind the model is to prepared the job dataset and candidate dataset (Data cleansing, feature engineering transfrom), collect the features from both side, using similarity function to connect and recommend the top-N selection.
![alt text](https://github.com/LightLow/content-based_recommender/blob/main/model-flow.png?raw=true)
