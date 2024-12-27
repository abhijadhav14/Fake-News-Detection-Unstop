# Fake-News-Detection-Unstop
This project was developed as part of a competition in the Unstop "Serve-Smart Hackathon" organized by the Indian Institute of Technology (Banaras Hindu University). The aim was to build a machine learning model to classify news articles as real or fake based on their textual content.


# Features

Preprocessing:

Tokenization, stopword removal, and special character filtering.

Sentiment analysis and keyword density analysis.

Feature Engineering:

Analysis of title and text length.

Linguistic feature extraction for better model training.

Machine Learning Models:

Implementation of Logistic Regression, Random Forest, SVM, and Gradient Boosting (XGBoost).

Performance Evaluation:

Metrics like Accuracy, Precision, Recall, F1 Score, and AUC-ROC.

Result Output:

Predictions saved in result.txt in the required format.

# Dataset

The dataset contains the following columns:

Title: The headline of the article.

Text: The main body content.

Subject: The category or theme of the article (e.g., Politics, Health).

Date: The publication date.

Label: Binary value indicating if the news is real (1) or fake (0).

# Results

Model Performance:

Metric

Score

Accuracy

0.92

Precision

0.89

Recall

0.91

F1 Score

0.90

AUC-ROC

0.94


