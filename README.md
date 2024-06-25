# Bias Identification Application
This project aims to detect bias in textual data. 
Detecting bias is crucial in various fields like social media analysis, news reporting, and content moderation.
Here we are using different NLP techniques, BERT Embeddings and several ML agorithms to classify text into different bias categories.
This application is deployed on streamlit and you can access and test it using the given link : https://bias-identification-dawnjo.streamlit.app/

## Key Features:
*  BERT Embeddings: Utilizes BERT (Bidirectional Encoder Representations from Transformers) for contextual word embeddings, capturing nuanced semantic information.
*  Machine Learning Models: Implements several ML models (Logistic Regression, Decision Trees, Random Forest, SVM, MLP) to classify text based on BERT embeddings.
*  Bias Categories: Detects biases such as Country Bias, Gender Bias, Religion Bias, etc., based on predefined classification labels.
*  Data Preprocessing: Handles data cleaning, tokenization, and preprocessing using Python libraries.
*  Visualization: Includes visualizations of label distributions and model performance metrics.

## Installations
* Numpy
* Pandas
* Matplotlib
* scikit-learn
* imblearn
* torch
* transformers
* joblib
