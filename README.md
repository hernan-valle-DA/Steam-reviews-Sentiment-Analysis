# Steam Reviews Sentiment Analysis

## 📌 Project Overview
This project focuses on sentiment analysis of Steam game reviews using Natural Language Processing (NLP). It applies three tokenization techniques and trains machine learning models to classify reviews as positive or negative.

## 🔍 Dataset
The dataset consists of user reviews from Steam, labeled as **positive** or **negative**.

## 🛠 Methods & Models
### 1. **Text Preprocessing**
- Tokenization
- Stopword removal
- Lemmatization

### 2. **Feature Engineering**
Three tokenization techniques were used:
- **Bag of Words (BoW)** → Multinomial Naive Bayes
- **TF-IDF** → Multinomial Naive Bayes
- **Word Embeddings** → Logistic Regression

### 3. **Model Training**
The data was split into **training (70%)** and **testing (30%)** sets. Each model was trained and evaluated using accuracy and other performance metrics.

## 📊 Results
- BoW and TF-IDF performed well with Naive Bayes.
- Word Embeddings combined with Logistic Regression provided promising results.

## 🚀 How to Run the Project
### Requirements:
- Python 3.x
- Libraries: `numpy`, `pandas`, `sklearn`, `nltk`

## 🚀 How to Run
Open `notebook.ipynb` and run the cells in order.


