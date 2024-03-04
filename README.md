# Credit Score Prediction Project

This repository contains code for a machine learning project that predicts credit scores based on various features.

## Overview

The code in this repository performs the following tasks:

- Data preprocessing
- Model training and evaluation
- Model selection
- Model deployment

## Code Description

The code is implemented in a Jupyter Notebook (`.ipynb` file) and utilizes several Python libraries including:

- pandas
- NumPy
- matplotlib
- seaborn
- sci-kit-learn
- catboost

The main steps in the code include:

1. Importing necessary libraries
2. Loading the dataset
3. Data preprocessing:
    - Handling missing values
    - Encoding categorical variables
    - Scaling numerical features
4. Exploratory data analysis (EDA)
5. Building and evaluating machine learning models:
    - KNeighborsClassifier
    - RandomForestClassifier
    - GradientBoostingClassifier
    - Support Vector Machine (SVM)
    - Logistic Regression
    - Naive Bayes
    - Decision Tree
    - AdaBoost
    - CatBoost
6. Model selection based on performance metrics
7. Model Deployment

## Usage

To run the code:

1. Ensure you have Python installed on your system.
2. Install the required Python libraries using `pip install -r requirements.txt`.
3. Open the Jupyter Notebook file (`ML.ipynb`) and execute each cell sequentially.

## Results

After evaluating various machine learning models based on performance metrics such as accuracy, precision, recall, and F1 score, the GradientBoostingClassifier was selected as the model of choice for predicting credit scores.

## Data Source

The dataset used in this project was obtained from Kaggle. You can find the dataset [here](https://www.kaggle.com/datasets/parisrohan/credit-score-classification).

## Code Source

The code implementation in this project was developed with the assistance of the ChatGPT language model. 

## Files

- `ML.ipynb`: Jupyter Notebook containing the code.
- `requirements.txt`: File listing the required Python libraries.
- `model.pk1`: Serialized model file.

