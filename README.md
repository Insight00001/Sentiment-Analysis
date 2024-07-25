# Problem Statement
The project aim is to determine an individual Mental condition from the individual verbal expression
# Data Collection
the dataset was collected from Kaggle: https://www.kaggle.com/datasets/suchintikasarkar/sentiment-analysis-for-mental-health
# Features
unique_id: A unique identifier for each entry.
Statement: The textual data or post.
Mental Health Status: The tagged mental health status of the statement.
# Methods
### Data cleaning
this involves removing null values, and unwanted characters in the statement column (independent Variable).
### Vectorization
1. converts the text into numerical vectors to be used by machine learning algorithms
2. The data is passed to the logistic regression machine learning algorithm, and the model's performance is evaluated using the accuracy score.
3. the model achieves an accuracy of 76 per cent
