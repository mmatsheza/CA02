# CA02: A demonstration of Naives Bayes Algorithm in Text Analytics.

## Summary

This notebook is a demonstration of how to employ feature engineering on email format text to prepare it for the Machine Learning (ML) algorithm, 
Naives Bayes. The data set included pre-defined train and test data sets. After linking the directory paths to the notebook and loading 
both train and test email sets, functions were created to carry out a number of processes within the text cleaning and feature engineering 
stages in the Natural Language Pipeline (NLP). After the data sets were made digestible for the ML algorithm, they were trained and 
applied on the test data. Next, the trained model was applied on the test data and the performance of the model was evaluated. 

## Required Libraries for CA02

Below is a list of the required libraries to replicate this analysis.

1. nltk.tokenize: This function is used to tokenize text into individual words.
2. pos_tag: Used for Parts of Speech tagging
3. stopwords: provides a list of english words that mainly serve a grammatical function rather than provide meaning on their own.
4. WordNetLemmatizer: performs word lemmatization which maps all the different forms of a word to its base form.
5. LabelEncoder: Encodes the text into numerical variables that are digestible by the machine learning algorithms.
6. defaultdict: useful in counting and aggregating data by using methods such as place holders for null key values.
7. wordnet: used for clarifying meaning in words and finding appropriate synonyms.
8. TfidfVectorizer: used for feature engineering, particularly on converting words into a numerical score using Term Frequency-Inverse Document Frequency (TF-IDF), to calculate the score of a word based on its frequency and rarity in appearance. The more frequent it is, the higher the score. The more rare it is, the higher the score. Words with high TF and IDF are ranked highest in a document.
9. model_selection, naive_bayes, svm: importaing the machine learning algorithms to be used in training and testing the data. Naive Bayes is a probability based algorithm founded on Bayes principles that assumes each word is an independent event and assigns a probability to each word of its likelhood of belonging to a certain class. Support Vector Machines (SVM) find the most ideal between text categories that maximizes the distance from the boundary to enhance accuracy.
10. accuracy_score: Determines the accuracy of the applied machine learning algorithms

**NB If you are using Jupyter Notebook, ensure you install the libraries in the Anaconda environment, or by using the !pip function. See the code below for reference.**

## Software Versions in use

1. Jupyter Notebook Python: 6.5.2
2. Windows 11 opersting system

## Data sets in use and source

1. PDF instructions: CA02: Spam eMail Detection using Naive Bayes Classification Algorithm
2. test-mails
3. train-mailes

The Data Sets were provided by Dr. Brahma for use in a computer assignment 2 on Naives Bayes Machine Learning Algorithm. Additioanlly, the source code was 
provided by Dr. Brahma with the students main focus to carry out an end to end analysis.
