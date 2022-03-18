# Sentiment_Analysis_of_Tweets

## Introduction

This project was developed as part of the course ***CS 5824 Advanced Machine Learning*** I had enrolled in during my **Masters in Computer Science** at ***Virginia Polytechnic Institute and State University***.

Course Instructor: [Dr. Yue Wang](https://ece.vt.edu/people/profile/ywang.html)

## Problem Statement

Goal of the project was to predict the sentiment behind a users tweet. This was a Supervised Classification problem to train a model to understand the sentiment behind users tweet and predict the user sentiment over unseen test data using a Naive Bayes Classifier.

## Dataset and Research Methods

Dataset included 1.6 Million records of tweets from different users. Just like any other Natural Language Processing task, a lot of effort went into preprocessing the data (tweets). Two main approaches viz. Stemming and Lemmatization were explored to generate tokens and a document term matrix was used to train a Naive Bayes Classifier, in order to predict the users sentiment (positive or negative).


Detailed analysis, approach, implementation and results can be found in the [Jupyter Notebook](./Sentiment_Analysis_Naive_Bayes.ipynb)

Also find the [Project Report](./AML_Final_Project_Report_Dvijen_Mahesh_Trivedi.pdf)

## Observation Results and Conclusion

Naive Bayes classifier was found to be performing really well on the dataset with a accuracy of over 78-79%. Performance of the Naive Bayes Classifier developed here, matched and even slightly outperformed SVM classifier built using same preoprocessing steps as the Naive Bayes classifier. 

Hence Naive Bayes Classifier built on Lemmatization as a preprocessing step is recommended for the task of ***Sentiment Analysis of Tweets***.