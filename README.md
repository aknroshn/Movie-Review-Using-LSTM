# Movie-Review-Using-LSTM
Movie Review Using LSTM Sentiment Analysis

This project is a sentiment analysis model for movie reviews. It uses a Long Short-Term Memory (LSTM) neural network to classify movie reviews as either positive or negative based on the text of the review. The project involves the following steps:

Setup Dependencies and Load Data: Installing necessary libraries like Kaggle, pandas, numpy, matplotlib, seaborn, scikit-learn, and TensorFlow/Keras. It then loads a dataset of 50,000 movie reviews from Kaggle.
Data Preprocessing: Converts the sentiment labels ("positive" and "negative") into numerical values (1 and 0) and splits the data into training and testing sets. It also tokenizes the review text and pads the sequences for consistent input length for the LSTM model.
LSTM Model Building, Compile, and Train: Defines, compiles, and trains an LSTM model using the preprocessed data.
Evaluation & Metrics: Evaluates the trained model's performance using metrics such as accuracy, confusion matrix, classification report, and AUC score.
Prediction: Provides a function to take a new movie review as input and predict its sentiment using the trained model.
