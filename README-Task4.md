##Twitter Sentiment Analysis Project##

This project demonstrates a complete machine learning pipeline to classify the sentiment of tweets as either positive or negative. I used a large public dataset of 1.6 million tweets to train and evaluate the model.

Key Steps
Data Preprocessing: I cleaned the raw text data by removing noise, punctuation, and common words (stopwords) to prepare it for analysis.

Feature Engineering: The cleaned text was converted into a numerical format using the TF-IDF Vectorizer, which assigns a weight to each word based on its importance in the dataset.

Model Training: I trained a Logistic Regression model on the preprocessed data. This model is well-suited for text classification tasks.

Prediction: The trained model was saved and successfully used to predict the sentiment of new, unseen tweets.
