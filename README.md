# Sentiment Analysis of Words Project

## Project Overview

This project aims to classify words into different sentiment classes using Natural Language Processing (NLP) and Machine Learning techniques. The primary algorithm used for classification is the Naive Bayes classifier.

## Dataset

The dataset is stored in an Excel file named `nlp_words.xlsx` and contains the following columns:
- `words`: The words or phrases to be classified.
- `class`: The sentiment class associated with each word or phrase.

## Requirements

- Python 3.x
- pandas
- scikit-learn
- openpyxl (for reading Excel files)

## Installation

1. Clone the repository or download the project files.
2. Install the required Python packages using pip:
    ```bash
    pip install pandas scikit-learn openpyxl
    ```

## Project Files

- `nlp_words.xlsx`: The dataset containing words and their sentiment classes.
- `sentiment_analysis.py`: The main script to run the sentiment analysis.
- `ML.ipynb`: Jupyter notebook containing the project code and analysis.

## Steps

1. **Data Loading and Preprocessing:**
    - Load the dataset from the Excel file.
    - Check for and handle duplicate and missing values.

2. **Feature Extraction:**
    - Extract features from the text using `CountVectorizer`.

3. **Model Training and Evaluation:**
    - Split the data into training and testing sets.
    - Train a Naive Bayes classifier on the training set.
    - Evaluate the model on the testing set and print the accuracy and classification report.
