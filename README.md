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
### Model Performance on Test Data
| Vectorization Method  | Classifier               | Accuracy  |
|----------------------|-------------------------|----------|
| **Bag of Words (BoW)**  | Multinomial Naive Bayes | 82.6%    |
| **TF-IDF**             | Multinomial Naive Bayes | 83.3%    |
| **Word Embeddings**    | Logistic Regression     | 79.1%    |

- BoW and TF-IDF performed similarly well with Multinomial Naive Bayes.  
- Word Embeddings were used with Logistic Regression due to computational limitations. While the accuracy is reasonable (79.1%), better performance is expected with neural networks, as they are more compatible with Word Embeddings.  


## 🚀 How to Run the Project
### Requirements:
- Python 3.x
- Libraries: `numpy`, `pandas`, `sklearn`, `nltk`

## 🚀 How to Run
Open `notebook.ipynb` and run the cells in order.


