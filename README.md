# Sentiment-Analysis-of-Tweets

## Introduction

This project was developed as part of the course ***CS 5824 Advanced Machine Learning*** I had enrolled in during my **Masters in Computer Science** at ***Virginia Polytechnic Institute and State University***.

Course Instructor: [Dr. Yue Wang](https://ece.vt.edu/people/profile/ywang.html)

## Problem Statement

Goal of the project was to predict the sentiment behind a users tweet. This was a Supervised Classification problem to train a model to understand the sentiment behind users tweet and predict the user sentiment over unseen test data using a Support Vector Machine.

## Dataset and Research Methods

Dataset included 1.6 Million records of tweets from different users. Just like any other Natural Language Processing task, a lot of effort went into preprocessing the data (tweets). Two main approaches viz. Stemming and Lemmatization were explored to generate tokens and a document term matrix was used to train a Support Vector Machine, in order to predict the users sentiment (positive or negative).


Detailed analysis, approach, implementation and results can be found in the [Jupyter Notebook](./Sentiment_Analysis_Support_Vector_Machine.ipynb)

Also find the [Project Report](./Advance_Machine_Learning_Final_Report.pdf)

## Observation Results and Conclusion

Support Vector Machine was found to be performing decently really well on the dataset with a accuracy of over 75-77%. Performance of the Support Vector Machine developed here, matched and was even slightly outperformed by the Naive Bayes classifier built using same preoprocessing steps.

Hence Naive Bayes Classifier built on Lemmatization as a preprocessing step is recommended for the task of ***Sentiment Analysis of Tweets***.
