# Gen-AILLM-Capstone-project
IMDB Movie Review Sentiment Analysis
Overview

This project builds a sentiment analysis model on the IMDB movie reviews dataset, classifying reviews as positive or negative and comparing different text representation methods.

Problem Statement

To develop a system that predicts the sentiment (positive/negative) of movie reviews and evaluate how different text representations affect classification performance.

Objectives

Preprocess IMDB movie review text.

Represent text using:

Bag of Words (BoW)

TF-IDF

GloVe-style dense embeddings (SVD on TF-IDF)

Word2Vec-style dense embeddings (SVD on BoW)

BERT-style deep model (MLP on TF-IDF)

Train sentiment classification models for each representation.

Evaluate models using Accuracy, Precision, Recall, and F1-score.

Compare all representations in a single results table and identify the best-performing one.

Data

Dataset: IMDB Dataset.csv

Samples: 50,000 reviews (balanced: 25k positive, 25k negative)

Columns:

review – text of the movie review

sentiment – "positive" or "negative"

Methods (Short)

Text cleaning (lowercasing, removing HTML, URLs, special characters).

Feature extraction: BoW, TF-IDF, SVD-based dense embeddings, MLP-based deep model.

Models: Logistic Regression and MLPClassifier.

Evaluation: Accuracy, Precision, Recall, F1-score.

Output

A comparison table (comparison_table_no_extra_installs.csv / .xlsx)
with metrics for each representation: BoW, TF-IDF, GloVe-style, Word2Vec-style, BERT-style.
