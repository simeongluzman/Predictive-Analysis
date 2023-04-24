# LSTM Neural Network for Predicting User Actions
LSTM Neural Network for Predicting User Actions is a machine learning project aimed at predicting user actions on a learning platform based on the history of their interactions. Utilizing a Long Short-Term Memory (LSTM) neural network, this project helps to gain insights into user behavior and potentially enhance the user experience.

# Features

Data Preprocessing:
- Extracts features from timestamp columns, encodes categorical columns, and normalizes non-categorical columns for optimal input data.

LSTM Neural Network:
- Implements a Long Short-Term Memory neural network to predict user actions based on their interaction history with a learning platform.

Training and Testing:
- Splits data into training and testing sets and trains the model to achieve an accuracy of 63.4%.

Prediction Functions:
- Includes a function to predict the next n actions for a given user and another function to predict the next n actions for each unique user in the dataset.

# Getting Started
To get started with the LSTM Neural Network for Predicting User Actions, follow these simple steps:

1. Clone the repository to your local machine.
2. Ensure that you have Python and the required dependencies installed, such as TensorFlow, Keras, Pandas, and NumPy.
3. Run the data preprocessing script to prepare the input data for the neural network.
4. Train the LSTM model using the provided training script.
5. Use the prediction functions to predict user actions for a given user or all unique users in the dataset.
