# **Stock News Headlines Sentiment Analysis using NLP Techniques**

## 🎫**Introduction** 
This project is a demonstration of how Natural Language Processing (NLP) techniques can be used to perform sentiment analysis on stock news headlines. The aim of the project is to classify whether the news headlines are positive, negative, or neutral.


## 🗃️**Dataset** 

The dataset used in this project is Stock News Dataset. It contains news headlines in 25 different columns and 1 Label column. You can access the dataset from [here](https://drive.google.com/file/d/1dXqHOgn8JRM88euhNlK-QywlqMs-mZOB/view?usp=sharing)


## 🎏**Methodology**

The sentiment analysis is performed using Natural Language Toolkit (NLTK) library.

Firstly, the distribution of the target variable is checked and the unwanted columns are dropped. Then all the 25 columns headlines are merged. Then news headlines are preprocessed by
- Removal of numbers
- Lowercase conversion
- Replacing Next line by white space
- Replacing currency sign by 'money'
- Replacing large white space by single white space
- Replacing special characters by white space
- Tokenization
- Stemming & Stopward Removal
- Lemmatization <br>

After pre-processing feature extraction is implemented on the headlines column. Feature Extraction techniques that are implemented are:
- Bag of Words
- Tf-Idf
- Word2Vec
- POS-Tagging


## 📋**Model Training and Classifier**

For model training, Bow(Bag of words) and tfidf(Tf-IDF) is used. The two classifiers that I have used is <br>
1) Multinomial Naive Bayes 
2) Random Forest Classifier


## 📍**Contributing**
Contributions are always welcome! Please feel free to open an issue or submit a pull request.


## ⚖️**License**
This project is licensed under the MIT License.
