# Text Classification for Spam Detection and Comparison Analysis
This project aims to develop a Text Classification Model using Bag of Words (BoW), TF-IDF, Word2Vec, and advanced BERT embeddings

## Data: 
The SMS Spam Collection is a set of SMS tagged messages that have been collected for SMS Spam research. It contains one set of SMS messages in English of 5,574 messages, tagged acording being ham (legitimate) or spam. 

This corpus has been collected from free or free for research sources at the Web.

The SMS Spam Collection (text file: spam) has a total of 4,827 SMS legitimate messages (86.6%) and a total of 747 (13.4%) spam messages.

# Problem Statement:
The proliferation of spam messages in communication channels poses a significant challenge, leading to user inconvenience, privacy concerns, and potential security threats. The aim of this project is to develop an efficient text classification model for spam detection, leveraging various techniques, including Bag of Words (BoW), TF-IDF, Word2Vec, and advanced BERT embeddings.

# Criteria for Success:
Achieve high accuracy in distinguishing between ham and spam messages.
Develop interpretable models for analysis and insights.
Implement three different models for performance analysis.
Compare and contrast the effectiveness of Naive Bayes, Random Forest, and Neural Network models.

## We will follow the following tasks in this notebook:
Data Cleaning
Data Preprocessing and EDA
Modeling

## We will train following Models:
Naive Bayes Model using BOW & TF-IDF
Random Forest Model using Word2vec & AvgWord2vec
Tensorflow Bert Pretrained Model with a single layer neural network


# Conclusion:
In this Capstone project, Text Classification for Spam Detection we worked through a series of tasks such as Data Collection, Data Preprocessing, EDA and Modeling. We performed different NLP techniques and created three models:

### Naive Bayse
We Created a Naive Bayse model using Bag of Words (BoW), Multinomial Naive Bayes model using CountVectorizer with Max_features = 3000 gave the best results with an Accuracy of 98% and Precision of 99%.

### Random Forest
We Got some amazing results from our Random Forest model by training a word2vec from scratch. We got an Accuracy of 99% and a Precision of 99%.

### Neural Network
We created a single layer neural network using Bert embedding ( pre-trained model ). Didn't get very good Precision score as we're looking for precision here.

So our best model with a Precision and Accuracy of 99% is Random Forest using Word2vec.
