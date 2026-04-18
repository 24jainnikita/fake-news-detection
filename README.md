# Fake News Detection using Logistic Regression

## Dataset 
link:(https://www.kaggle.com/datasets/bhavikjikadara/fake-news-detection)

## Overview
This project implements a **Logistic Regression** model to classify news articles as **fake or real** using **Natural Language Processing (NLP)** techniques.

## Dataset
The dataset consists of labeled news articles with text content, which are preprocessed for classification.

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
To run this project, install the necessary dependencies:

```bash
pip install numpy pandas scikit-learn nltk re

## Setup Instructions

1. Clone the repository:
git clone https://github.com/24jainnikita/fake-news-detection.git

2. Install dependencies:
pip install -r requirements.txt

3. Run the notebook:
news-detection.ipynb
