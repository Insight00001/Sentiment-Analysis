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
2. Dropped Null and Duplicate Values: Removed all records with null values and duplicates to maintain a clean and accurate     dataset for model training.
3. Convert the Data Type for statement from Object to String:
Changed the data type of the statement column from object to string to ensure more efficient text processing. The string data type is optimized for text manipulation and ensures consistent handling of text data throughout the analysis.
4. Convert the Data Type for status from Object to Category:
Converted the status column from object to category to optimize memory usage and enhance performance for data analysis. The category data type is more efficient for storing categorical data and speeds up operations such as filtering, grouping, and one-hot encoding, which are commonly used in machine learning workflows.
5. Remove Unwanted Characters: Clean the text by removing any non-alphanumeric characters, excluding spaces, to standardize the input and eliminate noise.
6. Remove Stop Words: Eliminate common stop words from the text to focus on meaningful content and improve the model's performance in identifying emotional cues and mental health indicators.

# EXploratory Data Analysis
## Data visualization
![pie](https://github.com/user-attachments/assets/84f417a2-df0e-4b2a-b578-e33b56313663)
![bar](https://github.com/user-attachments/assets/c01e7f17-ae06-4edd-adcd-55d039f5f3fc)

The analysis of the dataset reveals that texts reflecting a normal emotional state constitute the highest percentage of entries. This indicates that the majority of the text data corresponds to individuals who are not exhibiting signs of distress or mental health issues, suggesting a baseline of normalcy in emotional expression within the dataset
## feature engineering
A new feature, text length, was created to analyze the relationship between the length of text and emotional status. This feature helps in understanding which emotional categories are associated with longer or shorter text inputs. By examining the text length, we aim to answer the question: "Which emotional category do people tend to write the most about?" This analysis can provide insights into the verbosity of different emotional states and may indicate that certain emotions prompt more extensive expression in text.
![bar2](https://github.com/user-attachments/assets/80f5edd4-cc3e-483b-9ec6-a61ef62ef4ac)

statement that are bipolar have the longest text indicating people with such disorder might type more

## Vectorization
Convert Text into Numerical Vectors: Transform the preprocessed text into numerical vectors using techniques such as TF-IDF, word embeddings, or contextual embeddings. This step is essential for preparing the text data to be used by machine learning algorithms.
# Modelling
1. Logistic regression: 80 percent accuracy
2. Decision Tree classifier: 100 percent accuracy
3. Random Forest Classifier: 100 percent accuracy
# Conclusion
Random Forest and Decision Tree classifiers are prone to overfitting, which can lead to reduced generalization performance on unseen data. Therefore, the Logistic Regression model is chosen for its ability to generalize well and maintain robust performance across different datasets.
3. the model achieves an accuracy of 76 per cent
