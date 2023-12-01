# amazon-review-sentiment-analysis

This pytorch NLP project explore text representations and the use of text classification for sentiment analysis using the amazon review dataset.

## Table of Contents

- [Data](#data)
- [Feature Extraction](#feature-extraction)
- [Word Embedding](#word-embedding)
- [Models](#models)
- [Evaluation](#evaluation)

## Data
The Amazon reviews dataset which contains real reviews for office products sold on Amazon.

Data can be downloaded [here](https://web.archive.org/web/20201127142707if_/https://s3.amazonaws. com/amazon-reviews-pds/tsv/amazon_reviews_us_Office_Products_v1_ 00.tsv.gz).

### Data Cleaning
- convert all reviews into lowercase.
- remove the HTML and URLs from the reviews
- remove non-alphabetical characters
- remove extra spaces
- perform contractions on the reviews

### Dara Preprocessing
- remove the stop words
- perform lemmatization

## Feature Extraction
- TF-IDF
- Bag of Words (BoW)

## Word Embedding
For the second attempt in train2.py, pretrained “word2vec-google-news-300” Word2Vec model is used.

## Models
- Perceptron
- SVM
- Logistic Regression
- Naive Bayes
- Feedforward Neural Networks
- Recurrent Neural Networks

## Evaluation
Precision, Recall, and F1-score