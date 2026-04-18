# Fake News Detection using Logistic Regression

## Dataset 
link:(https://www.kaggle.com/datasets/bhavikjikadara/fake-news-detection)

## Overview

A machine learning project that classifies news articles as Fake or Real using NLP preprocessing and a Logistic Regression model trained on TF-IDF features.

## Example

Input: "Government announces new economic reforms to boost growth."
Output: REAL

## Dataset

Source: https://www.kaggle.com/datasets/bhavikjikadara/fake-news-detection

The dataset consists of labeled news articles with text content used for classification.

## Model & Approach
- **Text Preprocessing**:  
  - Removed special characters and punctuation using **Regular Expressions (re)**.  
  - Tokenized text and removed stopwords using **NLTK**.  
  - Lemmatized words for better feature extraction.  
- **Feature Engineering**:  
  - Converted text into numerical features using **TF-IDF (Term Frequency-Inverse Document Frequency)**.  
- **Algorithm**: Logistic Regression for binary classification.  
- **Evaluation**: Accuracy, Precision, Recall, F1-score, and Confusion Matrix.

## Installation & Requirements

Install dependencies:
pip install -r requirements.txt

## Setup Instructions

1. Clone the repository:
git clone https://github.com/24jainnikita/fake-news-detection.git

2. Navigate to the project folder:
cd fake-news-detection

3. Install dependencies:
pip install -r requirements.txt

4. Run the notebook:
news-detection.ipynb

## Saved Model

- model2.pkl → trained Logistic Regression model  
- tfidfvec2.pkl → TF-IDF vectorizer used for feature extraction  
