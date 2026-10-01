# 💬 Sentiment Analysis

A Natural Language Processing (NLP) project that classifies text as positive or negative using Python and scikit-learn.

## 🎯 Project Overview

This project demonstrates a basic text-classification workflow by converting text into numerical features and training a machine learning model to predict sentiment.

## ⚙️ How It Works

The project:

- Uses labeled positive and negative text examples
- Converts text into numerical features using CountVectorizer
- Trains a Multinomial Naive Bayes classifier
- Accepts new text as input
- Predicts whether the sentiment is positive or negative

## 🛠 Technologies Used

- Python
- scikit-learn
- Natural Language Processing (NLP)
- Jupyter Notebook

## 🧠 Model

### Multinomial Naive Bayes

Multinomial Naive Bayes is used to classify the vectorized text into positive or negative sentiment categories.

### CountVectorizer

CountVectorizer converts text into numerical feature vectors based on word occurrence counts, allowing the classifier to process textual data.

## 📊 Example

The trained model can receive a new sentence, transform it using the same vectorizer, and predict its sentiment.

## 🚀 Future Improvements

- Train on a larger dataset
- Add train/test evaluation
- Compare CountVectorizer with TF-IDF
- Compare multiple classification algorithms
- Add preprocessing for more complex text
