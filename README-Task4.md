## Task 4: Sentiment Analysis

Drive link-colab file
https://colab.research.google.com/drive/16tUgE0wC6buBn39ztw3JkyIp7OyoHRt2?usp=sharing

This project demonstrates a complete machine learning pipeline to classify the sentiment of a tweet as either positive or negative. I used a large public dataset of 1.6 million tweets to train and evaluate the model.

### Key Steps

* **Data Preprocessing:** I cleaned the raw text data by removing noise, punctuation, and common words (stopwords) to prepare it for analysis.
* **Feature Engineering:** The cleaned text was converted into a numerical format using the TF-IDF Vectorizer, which assigns a weight to each word based on its importance in the dataset.
* **Model Training:** I trained a Logistic Regression model on the preprocessed data. This model is well-suited for text classification tasks.
* **Prediction:** The trained model was saved and successfully used to predict the sentiment of new, unseen tweets.


Importing libraries
<img width="1415" height="789" alt="Screenshot 2025-08-30 201835" src="https://github.com/user-attachments/assets/ac464d7c-a3d1-45e5-b22d-744acaa95994" />

Model training
<img width="1190" height="818" alt="Screenshot 2025-08-30 201931" src="https://github.com/user-attachments/assets/e6eb67a7-c472-4ab5-9784-bfd7ada20dbc" />

Model prediction
<img width="1000" height="587" alt="Screenshot 2025-08-30 202025" src="https://github.com/user-attachments/assets/c7d78dc3-972e-409a-9bed-af0960f5d753" />



