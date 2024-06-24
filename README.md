# Deep Learning based Emotion Detection Model on Twitter (X) Conversations

## About the Project

This project was submitted as a final year project for my B. Tech degree in Information Technology. It focuses on developing a deep learning model to detect emotions from Twitter (X) conversations. By analyzing text data from social media, this model aims to classify the emotions conveyed in tweets into predefined categories.

## Introduction

With the proliferation of social media, understanding the emotional tone of conversations can provide valuable insights for businesses, researchers, and individuals. This project leverages the power of deep learning to analyze and classify emotions in tweets. The model can help in sentiment analysis, customer feedback analysis, and various other applications where understanding human emotions is crucial.

## Features

- **Emotion Classification**: Classifies tweets into various emotion categories such as joy, sadness, anger, surprise, love, fear.
- **Data Preprocessing**: Cleans and preprocesses tweet text for optimal model performance.
- **Deep Learning Model**: Utilizes a state-of-the-art neural network architecture for emotion detection.
- **Scalable**: Designed to handle large volumes of data from Twitter.

## Technologies Used

- **Programming Language**: Python
- **Deep Learning Framework**: TensorFlow
- **Natural Language Processing**: NLTK
- **Dataset Collection**: Kaggle, ntscrape
- **Data Visualization**: Matplotlib, Seaborn

## Dataset

The dataset for this project was collected from Kaggle and Twitter using the ntscrape. It includes a large number of tweets labeled with emotions. The data was preprocessed to remove noise and irrelevant information.

## Model Architecture

The deep learning model is built using a combination of LSTM (Long Short-Term Memory) layers and Dense layers to capture the sequential nature of the text data and perform emotion classification. The architecture includes:

- **Embedding Layer**: Converts words into dense vectors.
- **LSTM Layers**: Captures temporal dependencies in the text.
- **Dense Layers**: Fully connected layers for classification.
- **Output Layer**: Softmax activation for multi-class classification.

## Installation

To install and run the project, follow these steps:

## Usage

1. **Data Collection**:
    - Configure and run the script to collect data from Twitter.

2. **Data Preprocessing**:
    - Run the preprocessing script to clean and prepare the data for training.

3. **Model Training**:
    - Execute the training script to train the model on the preprocessed data.
    - Adjust hyperparameters as needed.

4. **Emotion Detection**:
    - Use the trained model to classify emotions in new tweets.
    - Run the prediction script with the input tweet text.

## Results

The model achieved an accuracy of 93% on the test dataset. The performance metrics indicate its ability to accurately classify various emotions. Detailed results and visualizations are provided in the results directory.
