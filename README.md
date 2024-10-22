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

## Installation
+ Clone the repository:

    Inline `code`

    git clone https://github.com/surajsahubigdata/RAG-Q-A-Chatbot-using-Groq-and-LLama3.git

+ Create virtual environment and install the required packages:

    Inline `code`

    conda create -p venv python==3.10

    pip install -r requirements.txt

+ Download the simple_rnn_imdb.h5 model file and place it in the project root directory. You can find or train the model using the IMDB dataset, if necessary.

## Usage

+ Run the streamlit application:

    Inline `code`

    streamlit run app.py

+ Open your web browser and navigate to http://localhost:8501
+ Enter your movie review in the text area provided and click the Classify button to get the sentiment prediction.

## Model Overview
+ **Simple RNN Model**: This model is trained on the IMDB dataset to classify reviews into positive or negative categories based on their content.
+ **Preprocessing**: Reviews are tokenized, converted to sequences using a word index, and padded to a length of 500 before being passed to the model for prediction.