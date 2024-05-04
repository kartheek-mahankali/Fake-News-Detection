# Fake-News-Detection
This repository contains the Jupyter Notebook to implement fake news detection using multiple techniques.

## Problem Statement
The problem is to build a model that can effectively detect whether a piece of news is fake or real. This involves distinguishing between authentic news and misinformation or disinformation, which is crucial in maintaining informed public discourse and preventing the spread of inaccuracies.

## Project Overview
The project develops a Fake News Detection system utilizing various machine learning and natural language processing techniques. The main steps involve data preprocessing, exploratory data analysis, feature engineering, model training using several classifiers, and evaluating these models to identify the most effective one.

## Steps Involved in the Project
1. Importing Libraries: Necessary libraries for data handling, processing, and visualization are imported.
2. Data Importation: Load the dataset containing news items with their labels indicating whether they are real or fake.
3. Data Cleaning: Cleaning the data by handling null values and converting data types where necessary.
4. Exploratory Data Analysis (EDA): Analyzing the dataset to understand the distribution of real and fake news and the characteristics of the news titles and text.
5. Data Preprocessing: Text data is preprocessed by removing special characters and numbers, converting to lowercase, and tokenizing.
6. Model Training: Various classification models like Logistic Regression, Decision Tree, Random Forest, KNN, Naive Bayes, and a Neural Network are trained on the processed data.
7. Model Comparison and Evaluation: Comparing the performance of different models based on their accuracy and other metrics to select the best performing model.

## Contributions and Results
- Data Preprocessing: Implemented functions to clean and preprocess the text data, preparing it for modeling.
- Feature Engineering: Transformed the text data into a format suitable for model input using tokenization and padding.
- Model Training and Testing: Trained multiple models and evaluated their performance on the test data. Implemented a neural network with TensorFlow and Keras to classify news articles.
- Results Visualization: Visualized the results using Matplotlib to compare the performance across different models.
- Outcome: The models achieved varying levels of accuracy, with detailed metrics plotted and discussed in the notebook. Insights into which models performed better and how different preprocessing steps affected outcomes were provided.

