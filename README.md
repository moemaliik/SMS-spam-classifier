# Project Overview
This project develops a machine learning model to accurately classify SMS messages as spam or ham (non-spam). Using the SMS Spam Collection Dataset from the UCI Machine Learning Repository, this implementation demonstrates practical application of machine learning techniques for text classification problems.

# Project Scope
The primary goal is to showcase competence in machine learning through a complete pipeline from data loading to model evaluation. This project serves as a demonstration of skills in data science and machine learning implementation.

# Technical Skills Demonstrated
Python Programming (pandas, scikit-learn)

- Data Preprocessing
- Feature Extraction
- Model Training
- Model Evaluation
- Scikit-learn Usage
- Text Classification
- Version Control with Git

# Dataset
The project uses the SMS Spam Collection Dataset, which contains SMS messages labeled as either "spam" or "ham" (legitimate messages). The dataset is loaded from a tab-separated file with two columns: Label and Message.

# Implementation Details
## Data Preprocessing

- Conversion of text labels to binary values (spam: 1, ham: 0)
- Train-test split with 70-30 ratio
- Text vectorization using CountVectorizer to convert messages into numerical features

#Model Selection
Algorithm: Multinomial Naive Bayes

Rationale: Selected for its efficiency and effectiveness in text classification tasks

#Model Performance
Accuracy: 99.04%

Evaluation Metrics: Comprehensive classification report including precision, recall, and F1-score for both spam and ham classifications

#Project Structure
The implementation follows a standard machine learning workflow:

- Data loading and exploration
- Data preprocessing and feature engineering
- Model training
- Model evaluation and performance analysis

# Technical Requirements

- Python 3.x
- pandas
- numpy
- scikit-learn
