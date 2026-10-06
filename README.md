# Disaster-Tweet-Detection
Analyzed disaster-related tweets using Python and NLP to classify text into Short, Medium, and Long categories. Performed EDA, TF-IDF text vectorization, and built a Multinomial Naive Bayes classification model with performance evaluation.

1. Project Objective: The goal was to analyze disaster-related tweets and classify them based on their text characteristics.
2. Dataset: The dataset contains 6,263 tweets with columns such as tweet text, keyword, location, tweet length, word count, hashtag usage, and text category.
3. Data Analysis: I used Pandas to explore the dataset, check its structure, missing values, and statistical information.
4. Exploratory Data Analysis: I analyzed tweet length, word count, hashtag usage, text categories, and top keywords using visualizations.
5. Text Categories: Tweets were categorized into Short, Medium, and Long based on their text characteristics.
6. Label Encoding: I converted the text categories into numerical values using LabelEncoder so they could be used by the machine learning model.
7. Text Vectorization: I used TF-IDF Vectorization to convert the tweet text into numerical features while removing common English stop words.
8. Model Building: I split the data into 80% training and 20% testing data and trained a Multinomial Naive Bayes classification model.
9. Model Evaluation: I evaluated the model using accuracy, classification report, and confusion matrix to understand its performance.
10. Prediction: Finally, I tested the model with a new tweet such as “Massive fire breaks out in city area” and used the trained model to predict its category.
