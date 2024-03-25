# Spam SMS Classifer using AI/ML project with Python.It is based on NLP.

# 1.Problem Introduction- 
Spam SMS Classification is a crucial problem in the field of Natural Language Processing and Machine Learning. The increasing volume of SMS messages sent globally on a daily basis has led to the need for automated methods to classify text messages as spam or non-spam. In this project, a machine learning model is trained to classify SMS messages as either spam or ham(non-spam). The goal is to build a model that can accurately identify spam messages, thereby reducing the amount of unwanted messages that people receive.

# 2.Problem Statement-
The problem statement in SMS spam classification is to build a machine learning model that can accurately classify whether an incoming SMS message is spam or not. The goal is to create a model that can differentiate between legitimate and spam SMS messages in real-time and with high accuracy.

# 3.Kaggle dataset link named as SMS Spam Collection- 
https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset
The SMS Spam Collection is a set of SMS tagged messages that have been collected for SMS Spam research. It contains one set of SMS messages in English of 5,574 messages, tagged acording being ham (legitimate) or spam. The files contain one message per line.
Each line is composed by two columns: v1 contains the label (ham or spam) and v2 contains the raw text.

# 4.Data Preprocessing-
Spam or Ham sms is evaluated on the basis of transformed text which is obtained after lowering case,tokenizing the sentence,removing stopwords,punctuation,special characters and stemming of text.

# 5.Steps performed-
a.DATA COLLECTION
b.DATA CLEANING
c.EDA
d.TEXT/DATA PREPROCESSING
e.MODEL BUILDING
f.BUILDING PREDICTIVE SYSTEM

# 6.Machine learning Model used-
a.Guassian.Multinomial,Bernoulli Naive Bayes Classifier using BoW vectorizer(feature engineering)
b.Guassian.Multinomial,Bernoulli Naive Bayes Classifier using TF-IDF vectorizer
c.SVM Classifier using TF-IDF vectorizer
d.KNN Classifier using TF-IDF vectorizer

# 7.Result-
I got Highest precision of 100% using Multinomial Naive Bayes Classifier using TF-IDF vectorizer so,it is used in the predictive system. 
