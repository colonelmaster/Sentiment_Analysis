# Sentiment Analysis using NLTK and Sklearn

## Overview

Sentiment analysis is a natural language processing (NLP) technique used to determine the sentiment or emotion expressed in a piece of text. This project demonstrates the basics of sentiment analysis using Python and popular NLP libraries such as NLTK (Natural Language Toolkit) and Sklearn.

## Project Steps

### Step 1: Modules Downloading

Ensure that you have the required Python modules installed. You can install them using the following commands:

```bash
pip install numpy pandas seaborn re contractions scikit-learn nltk
```

### Step 2: Data Preprocessing

- Load the dataset from 'Twitter_Data.csv'.
- Perform data cleaning, including removing special characters, usernames, hashtags, and URLs.
- Remove duplicate entries and convert text to lowercase.
- Expand contractions and remove stop words.
- Tokenize the sentences and save the preprocessed data back to 'Twitter_Data.csv'.

### Step 3: Exploratory Data Analysis (EDA)

- Visualize the distribution of sentiments using a countplot.
- Analyze the distribution of text length with a histogram.
- Explore the most common words in each sentiment category using frequency distribution plots.

### Step 4: Feature Extraction, Model Selection, Training, and Evaluation

- Use the CountVectorizer to transform tokenized and preprocessed text into a feature matrix.
- Split the data into training and testing sets.
- Train a logistic regression model using cross-validation and evaluate its accuracy.

### Step 5: Cross-validation

- Display a confusion matrix to visualize the model's performance on the test set.

## Files

- **Jupyter Notebook**: The main notebook containing the code for sentiment analysis.
- **Twitter_Data.csv**: The dataset used for analysis.
- **README.md**: This file, providing an overview of the project and instructions.

## Usage

1. Install the required Python modules using the provided commands.
2. Run the Jupyter Notebook in the specified order to perform sentiment analysis on the Twitter dataset.

## Dependencies

- Python 3.x
- Numpy
- Pandas
- Seaborn
- Scikit-learn
- NLTK

## Acknowledgments

- The project uses the NLTK and Scikit-learn libraries for natural language processing and machine learning tasks.

## License

This project is licensed under the [MIT License](LICENSE).

---
