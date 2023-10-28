# YouTube Comments Sentiment Analysis 

## Project Overview

This YouTube Comments Sentiment Analysis project is designed to analyze the sentiments expressed in comments on YouTube videos. Sentiment analysis, also known as opinion mining, involves using natural language processing (NLP) techniques to determine the emotional tone of a piece of text. In this project, we will focus on identifying whether comments are positive, negative, or neutral in sentiment.

## Data Collection through YouTube API

- **Data Collection**: We start by collecting YouTube comments data from various video sources using the YouTube Data API. The API allows us to fetch comments from specific videos or channels. Refer to the API documentation for more details on data collection.

## Sentiment Labeling using VADER

- **Sentiment Labeling**: The sentiment of the collected comments is determined using the VADER (Valence Aware Dictionary and sEntiment Reasoner) tool. VADER is a lexicon and rule-based sentiment analysis tool specifically designed for social media text sentiment analysis.

## Preprocessing using NLTK

- **Data Preprocessing**: The collected data is preprocessed to clean and prepare it for sentiment analysis. This preprocessing may include text tokenization, removing special characters, and handling missing or irrelevant data.

## RNN-LSTM Model using TensorFlow and Keras

- **Model Architecture**: For sentiment analysis, we utilize a deep learning model based on an RNN-LSTM architecture, implemented using TensorFlow and Keras.

## Model Evaluation using Matplotlib

- **Model Evaluation**: After running your project, assess your RNN-LSTM model's performance on a validation dataset and visualize the results using Matplotlib as mentioned in the project README.
