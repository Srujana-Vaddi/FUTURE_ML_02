# FUTURE_ML_02
Support Ticket Classification
# AI-Based Support Ticket Classification System

## Future Interns - Machine Learning Task 2

## Overview

This project use NLP(Natural Language Processing) and Machine Learning.This project builds a system with mix of these two technologies..

This system erases the conflicts faced by the customer support tickets by classifying tickets based on categories and predicts the priority

---

# Features

- Text preprocessing using NLP(access the ticket text)
- Stopwords removal
- TF-IDF Vectorization(converts text to numbers)
- Ticket category prediction
- Priority tagging system(assigning priority)
- Data visualization
- Machine Learning model training and evaluation

---

# Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK(Natural Language ToolKit
- Matplotlib

---

# Machine Learning Concepts Used
- Natural Language Processing (NLP)
- Text Cleaning
- Stopwords Removal
- TF-IDF Vectorization
- Train-Test Split
- Naive Bayes Classification
- Accuracy Evaluation

---

# Dataset

Customer Support Ticket Dataset from Kaggle.

Dataset contains:
- Ticket descriptions
- Ticket categories
- Customer support related issues

---

# Project Workflow

## 1. Data Loading
The dataset is loaded using Pandas.

## 2. Text Preprocessing
- Convert text to lowercase
- Remove special characters
- Remove stopwords

## 3. Feature Extraction
TF-IDF Vectorizer is used to convert text into numerical vectors.

## TF-IDF Formula

\[
TF\text{-}IDF(t,d) = TF(t,d) \times \log\left(\frac{N}{DF(t)}\right)
\]

## 4. Train-Test Split
Dataset is divided into:
- Training data
- Testing data

## 5. Model Training
Multinomial Naive Bayes algorithm is used for ticket classification.

## 6. Prediction
The model predicts:
- Ticket Category
- Ticket Priority

## 7. Model Evaluation
Accuracy score and classification report are used for evaluation.

---

# Model Used
## Multinomial Naive Bayes

Naive Bayes performs well for text classification and NLP-related tasks.

---

# Example Prediction

## Input
```text
"Payment failed and money deducted"
```

## Output
```text
Predicted Category: Billing
Predicted Priority: High
```

---

# Files Included

```text
support_ticket_classification.ipynb
customer_support_tickets.csv
ticket_classifier.pkl
vectorizer.pkl
requirements.txt
README.md
```

---

# Output
- Automatic ticket classification
- Priority prediction system
- NLP-based text analysis

---

# Limitations
Currently, the model predicts only one category for each ticket using single-label classification.

Some real-world customer support tickets may belong to multiple categories simultaneously.

Example:
"Payment failed and unable to login"

This ticket may belong to:
- Billing
- Login

The current model predicts the most probable category only.

---

# Future Improvements
- Multi-label ticket classification
- Deep Learning based NLP models
- Confidence score prediction
- Real-time ticket routing system

---


# Conclusion
This project demonstrates how NLP and Machine Learning can be used to automate customer support ticket classification and priority prediction systems.
