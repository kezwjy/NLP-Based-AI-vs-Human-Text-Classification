## AI vs Human Text Classifier

This project builds a simple NLP model to classify whether a piece of text is AI-generated or written by a human.

## Overview

The goal of this project is to explore how well basic NLP techniques can capture differences in writing patterns between AI and human text. Instead of using complex deep learning models, this project focuses on a lightweight and interpretable approach.

## Methodology
Performed text preprocessing (cleaning, stopword removal, lemmatization)
Converted text into numerical features using Word2Vec embeddings
Represented each document by averaging word vectors
Trained a Logistic Regression model for binary classification

## Evaluation

The model was evaluated using standard classification metrics such as:

F1-score
Confusion matrix

## It achieved strong performance despite using relatively simple methods.

Tech Stack
Python
scikit-learn
gensim (Word2Vec)
nltk / standard NLP preprocessing tools
Notes

This project focuses on simplicity and interpretability, showing that even basic models can perform well when combined with meaningful text representations.
