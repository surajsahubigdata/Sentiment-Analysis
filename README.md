# IMDB Movie Review Sentiment Classifier

## Overview
This project implements a sentiment analysis model using a pre-trained Simple RNN model on the IMDB movie reviews dataset. The model classifies user-provided movie reviews as either positive or negative based on the sentiment expressed in the text. The model is integrated into a user-friendly web interface using Streamlit.

## Features
+ **Sentiment** Prediction: Classifies movie reviews as either positive or negative sentiment.
+ **User Input**: Users can input any movie review into the interface, and the application will return the sentiment along with the prediction score.
+ **Interactive Web Interface**: Built using Streamlit for ease of use and accessibility.

## Technologies Used
+ **TensorFlow/Keras**: For loading and running the pre-trained Simple RNN model.
+ **IMDB Dataset**: A dataset of 50,000 movie reviews used for training the sentiment analysis model.
+ **Streamlit**: For creating the web application that allows user interaction with the model.