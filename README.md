# Aim of the Project
The aim is to develop a machine learning model that can accurately identify emotional cues and mental health indicators from written text.
# Overview
This project focuses on using sentiment analysis to detect and classify various mental states, such as stress, anxiety, depression, Suicidal, Stress, Bipolar, Personality disorder
# Data Collection
the dataset was collected from Kaggle: https://www.kaggle.com/datasets/suchintikasarkar/sentiment-analysis-for-mental-health
# Features
unique_id: A unique identifier for each entry.
Statement: The textual data or post to analyze.
Mental Health Status: The tagged mental health status of the statement.
# Methods
### Data cleaning
this involves removing null values, and unwanted characters in the statement column (independent Variable).
### Vectorization
1. converts the text into numerical vectors to be used by machine learning algorithms
2. The data is passed to the logistic regression machine learning algorithm, and the model's performance is evaluated using the accuracy score.
3. the model achieves an accuracy of 76 per cent
