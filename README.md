This repository contains Jupyter notebooks that process a large dataset of tweets related to abortion discourse. It includes Natural Language Processing (NLP) techniques such as topic modeling using BERTopic, 
sentiment analysis using VADER, and statistical data analysis including logistic regression and Random Forest classification models to predict abortion stance based on moral foundations and sentiment.

## Features

- **Data Filtering**: Filters large datasets in chunks to identify tweets related to certain abortion stances and moral foundations.
- **Text Cleaning**: Cleans tweet text by removing URLs, special characters, and converting text to lowercase.
- **Embedding Computation**: Uses BERTweet to compute tweet embeddings.
- **Topic Modeling**: Implements BERTopic to extract and analyze dominant themes within the filtered tweet dataset.
- **Sentiment Analysis**: Uses VADER to classify tweets as positive, negative, or neutral based on sentiment.
- **Predictive Modeling**: Uses Logistic Regression and Random Forest models to predict abortion stance (pro-life, pro-choice, neutral) based on moral foundations and sentiment.
- **Cross-Validation**: Implements cross-validation with grid search to tune hyperparameters and optimize model performance.
- **Visualization**: Provides visualizations of the topics, sentiment distributions, and feature importance using Plotly and Matplotlib.

