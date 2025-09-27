# Email Spam Detection using Multinomial Naive Bayes

## Overview
This project demonstrates the use of the **Multinomial Naive Bayes algorithm** for detecting spam emails. The goal is to classify email messages as either **spam** or **not spam** based on their content.

## Dataset
- The dataset includes a collection of email messages labeled as `spam` or `ham` (not spam).  

## Methodology

1. **Model Training**
   - The **Multinomial Naive Bayes classifier** was trained on the training set.  
   - The model learns the frequency of words in spam vs. non-spam emails to make predictions.

2. **Evaluation**
   - The model achieved an **accuracy of 98.39%**, indicating very high correctness of predictions on the selected features.  
   - The **confusion matrix** highlights the types of errors the model makes.  
   - Testing with a custom spam message showed that the model correctly identifies it as **spam**.

used vectorizer=CountVectorizer() to convert text data into a numeric feature matrix so that the machine learning model can understand.
