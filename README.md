SMS spam Classifer using AI/ML project with Python.It is based on NLP.

Problem Introduction-SMS Spam Classification is a crucial problem in the field of Natural Language Processing and Machine Learning. The increasing volume of SMS messages sent globally on a daily basis has led to the need for automated methods to classify text messages as spam or non-spam. In this project, a machine learning model is trained to classify SMS messages as either spam or ham(non-spam). The goal is to build a model that can accurately identify spam messages, thereby reducing the amount of unwanted messages that people receive.

Problem Statement-The problem statement in SMS spam classification is to build a machine learning model that can accurately classify whether an incoming SMS message is spam or not. The goal is to create a model that can differentiate between legitimate and spam SMS messages in real-time and with high accuracy.

Kaggle dataset link named as SMS Spam Collection - https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset
The SMS Spam Collection is a set of SMS tagged messages that have been collected for SMS Spam research. It contains one set of SMS messages in English of 5,574 messages, tagged acording being ham (legitimate) or spam. The files contain one message per line.
Each line is composed by two columns: v1 contains the label (ham or spam) and v2 contains the raw text.

Spam or Ham sms is evaluated on the basis of transformed text which is obtained after lowering case,tokenizing the sentence,removing stopwords,punctuation,special characters and steeming of text.

Steps performed-
1.DATA COLLECTION
2.DATA CLEANING
2.EDA
3.TEXT/DATA PREPROCESSING
4.MODEL BUILDING
5.BUILDING PREDICTIVE SYSTEM

Machine learning Model used-
1.Guassian.Multinomial,Bernoulli Naive Bayes Classifier using BoW vectorizer(feature engineering)
2.Guassian.Multinomial,Bernoulli Naive Bayes Classifier using TF-IDF vectorizer
3.SVM Classifier using TF-IDF vectorizer
4.KNN Classifier using TF-IDF vectorizer

Evaluation-I got Highest precision of 100% using Multinomial Naive Bayes Classifer using TF-IDF vectorizer so,it is used in the predictive system. 
