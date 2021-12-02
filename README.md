# Mood Detector 😄 😞 😨 😮

Multi-class sentiment analysis problem to classify texts into eight emotion categories: joy, sadness, anger, fear, neutral, disgust, shame, surprise 

## Deployment Link: https://mood123.herokuapp.com/

## Description
Mood detection is a technique used in software that allows a program to predict the emotions of a person by understanding the context of the texts provided bythe same. Companies have been experimenting with combining sophisticated algorithms that have emerged in the past ten years to understand more about the extent of replicating the emotions of a person by just texts or language spoken.

## Here's the Preview:
![App](Images/screencapture-mood123-herokuapp-2021-12-02-14_41_12.png)

## Prediction Preview: 
![App](Images/screencapture-mood123-herokuapp-2021-12-02-14_41_46.png)

## Prediction Probability Graph :
![Graph](Images/download.png)


## Steps followed

- Text Dataset Collection
- Labelling dataset for the class they belong to
- Loading dataset in jupyter
- Cleaning the dataset using NeatText
- Creation of train and test data
- Creating a pipeline
- Using CountVectorizer 
- Using Logistic Regression for Multiple CLasses
- Prediction then chhecking the accuracy
- Saving the model
- Loading the model in pycharm
- Creating an api to run on local system
- Deploying the model


## Technology used
- Python
- Pandas
- Tensorflow/Keras
- NeatText
- Sklearn
- Joblib
- Pycharm
- Streamlit
- Heroku
