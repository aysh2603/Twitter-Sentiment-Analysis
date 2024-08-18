
# Twitter-Sentiment-Analysis

## Overview
The Twitter Sentiment Analysis project employs Natural Language Processing (NLP) techniques to classify tweets into positive or negative sentiments. By analyzing the tone of tweets, this project provides insights into public sentiment on various topics. The project involves several stages, including data preprocessing, model training, and evaluation.

## Features
- **Data Collection:** Utilizes a pre-collected dataset of tweets for analysis.
- **Text Preprocessing:** Applies various NLP techniques to clean and prepare the text data.
- **Model Training:** Compares different machine learning models to identify the best fit for sentiment classification.
- **Prediction:** Uses the selected model to classify the sentiment of tweets.

## Technologies Used
Python, NLTK, Scikit-Learn, Pandas, Matplotlib

## Text Preprocessing
- **Tokenization**
Tokenization involves breaking text into individual words or tokens. We utilized tokenization techniques from NLTK library to prepare the text data for analysis.
- **Stemming**
Stemming reduces words to their root form to standardize variations. This step helps in normalizing the text by reducing words to their base or root form, using stemming algorithms provided by NLTK.
- **TF-IDF**
Term Frequency-Inverse Document Frequency (TF-IDF) converts text into numerical features by evaluating the importance of words in the context of the entire dataset. We applied TF-IDF to transform the tweet text into a format suitable for machine learning models.

## Model Training and Evaluation
- **Models compared**
We compared several machine learning models for sentiment classification, including Logistic Regression, XGBoost, Decision Tree and Random Forest.
- **Evaluation Metrics**
Models were evaluated based on F1 score to determine the best fit for classifying tweets as positive or negative.
- **Best Model**
The model with the highest F1 Score was selected for making predictions.
