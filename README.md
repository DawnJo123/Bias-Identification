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
* Scikit-learn
* Imblearn
* Torch
* Transformers
* Joblib

## How to try this application..?
1. If you just want to try this bias detection application, then just go to the given streamlit link and try it. Link: https://bias-identification-dawnjo.streamlit.app/
2. If you want to try it from scratch, follow the below steps:
    * Clone this repository.
      ```git clone https://github.com/DawnJo123/Bias-Identification.git ```
    * Install the required libraries
      ```pip install -r requirements.txt```
    * Run the file named ```bias_detection.ipynb```
    * Running this file will generate pickle files of the five models that we used in this project( Logistic Regression, Decision Tree, Random Forest, SVM and MLP).
    * Place these models into the model folder. NOTE: The model files are already available in the model folder. If u don't want to make any changes in the code or in the data, you can skip the last two steps
    * You can start the application by running the ```app.py``` file using the below command in the terminal.
      ```streamlit run app.py```
   
