# Kindle Review Rating Predictor

## Overview

This project aims to predict the rating of Kindle reviews based on the text provided by users. Various Natural Language Processing (NLP) techniques such as Bag of Words, TF-IDF, and Word2Vec are employed. The highest accuracy of 78% is achieved using Word2Vec in conjunction with Logistic Regression.

## Project Description

Predicting the rating of user reviews can provide insights into customer satisfaction and product performance. This project explores different text representation techniques and machine learning algorithms to determine the most effective method for this task.

## Data

- This is a small subset of dataset of Book reviews from Amazon Kindle Store category. Content 5-core dataset of product reviews from Amazon Kindle Store category from May 1996 - July 2014. Contains total of 982619 entries.
- Acknowledgements This dataset is taken from Amazon product data, Julian McAuley, UCSD website. http://jmcauley.ucsd.edu/data/amazon/


## Methodology

1. **Preprocessing**:
    - Tokenization
    - Removing stop words
    - Lemmatization

2. **Text Representation**:
    - **Bag of Words**: A simple method where the text is represented as the frequency of words.
    - **TF-IDF**: A more sophisticated method that considers the importance of words in the context of the entire dataset.
    - **Word2Vec**: A neural network-based technique that captures semantic relationships between words.

3. **Modeling**:
    - **Logistic Regression**: Chosen for its simplicity and effectiveness in binary classification tasks.
    - **Gaussian Naive Bayes**: Used with Bag of Words and TF-IDF to explore its performance in predicting review ratings.

## Results

- **Bag of Words**: 59%
- **TF-IDF**: 59%
- **Word2Vec**: 78%

The highest accuracy of 78% was achieved using Word2Vec with Logistic Regression.
