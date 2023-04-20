# Predictive-Analysis
Predictive Analysis Project

# Project Summary
This code trains a Long Short-Term Memory (LSTM) neural network to predict the next user 
action based on the user's history of interactions. The input data is taken from a CSV file 
and consists of a set of user interactions with a learning platform, where each interaction 
is associated with a user ID, a timestamp, and an action performed by the user. The code pre-processes 
the input data by extracting features from the timestamp column, one-hot encoding the categorical columns, and normalizing the non-categorical columns. The target variable 'action' is also one-hot encoded. The preprocessed data is then split into training and testing sets, and an LSTM model is trained on the training set to predict the next user action. The model is evaluated on the test set and the accuracy is printed to the console. Additionally, the code provides a function to predict the next n actions for a given user, as well as a function to predict the next n actions for each unique user in the dataset.
