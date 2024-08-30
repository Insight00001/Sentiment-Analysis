# Aim of the Project
The objective is to develop a machine learning model capable of accurately identifying emotional cues and mental health indicators from written text. By leveraging advanced Natural Language Processing (NLP) techniques, the model aims to detect signs of various mental health conditions, such as stress, anxiety, depression, suicidal ideation, bipolar disorder, and personality disorders, from an individual's textual input.
# Overview
This project utilizes Natural Language Processing (NLP) techniques to detect and classify various mental states based on text input provided by individuals. The mental states identified include stress, anxiety, depression, suicidal tendencies, bipolar disorder, and personality disorders. By analyzing textual data, the model aims to provide insights into an individual's mental health condition, enabling early detection and intervention.
# Data Collection
the dataset was collected from Kaggle: https://www.kaggle.com/datasets/suchintikasarkar/sentiment-analysis-for-mental-health
# Features
1. Statement: The textual data or post to analyze.
2. Status: The tagged mental health status of the statement.
# Data cleaning
To ensure the quality and reliability of the data, the following steps were undertaken for data cleaning:
1. Checked for Null and Duplicate Values: Identified any missing (null) and duplicate entries within the dataset.
2. Dropped Null and Duplicate Values: Removed all records with null values and duplicates to maintain a clean and accurate      dataset for model training.
# EXploratory Data Analysis

## Data visualization
## Vectorization
1. converts the text into numerical vectors to be used by machine learning algorithms
2. The data is passed to the logistic regression machine learning algorithm, and the model's performance is evaluated using the accuracy score.
3. the model achieves an accuracy of 76 per cent
