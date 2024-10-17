# emails Spam Classifier

This project is a machine learning-based application to classify emails messages as either "Spam" or "Not Spam". It uses Natural Language Processing (NLP) techniques for text preprocessing and a machine learning model for classification. The user inputs an emails message, and the app predicts whether it is spam or not.

## Features

- **NLP Preprocessing**: Tokenization, stopwords removal, and stemming.
- **Spam Detection**: Uses a trained machine learning model to classify messages.

## Tech Stack

- **Python 3.x**: Core programming language.
- **NLTK**: Used for text preprocessing (tokenization, stopwords removal, stemming).
- **Pickle**: For loading the pre-trained machine learning model and TF-IDF vectorizer.
- **Scikit-learn**: For machine learning (training and predicting using models).

## How It Works

1. **Input**: Users provide a text input (emails message) in the Streamlit web interface.
2. **Preprocessing**: The input text is cleaned and preprocessed using NLP techniques like lowercasing, tokenization, stopwords removal, and stemming.
3. **Vectorization**: The cleaned text is transformed into a vector using the TF-IDF vectorizer.
4. **Prediction**: The vectorized text is fed into the pre-trained machine learning model, which outputs a classification (1 for spam, 0 for not spam).
5. **Improving model Perforance** Applied Different Model to check the efficency . TfidfVectorizer and MultinomialNB Algoritham Gives Better efficency and best precision.
6. **Output**: The app displays whether the message is spam or not.
