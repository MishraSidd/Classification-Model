# Titanic: Machine Learning from Disaster
This repository contains the notebook used for predicting the survival of passengers aboard the Titanic. The dataset is sourced from the popular Kaggle competition, and multiple machine learning models are explored to evaluate their performance.

## Project Overview
The goal of this project is to apply various machine learning models to predict the survival of Titanic passengers based on different features such as age, gender, passenger class, and more. Several models were implemented to compare their effectiveness and accuracy.

## Models Used
The following models were employed to predict passenger survival:

Decision Trees
Support Vector Machine (SVM)
Random Forest
Multi-Layer Perceptron (MLP) Classifier
KNeighbors Classifier
Each model's performance was assessed, and hyperparameters were tuned to improve accuracy where possible.

## Feature Engineering
To make the data analysis-ready, extensive feature engineering was performed, including:

Dropping irrelevant or redundant columns
Handling missing values
Plotting correlations to understand feature relationships
Creating new features (e.g., family size, title extraction from name)
Converting categorical variables into numerical formats
Normalizing and scaling features where necessary
Dataset
The dataset is provided by the Kaggle Titanic Competition. It contains information on 891 passengers, including their demographics, ticket information, and survival status.

## Visualizations
Visualizations, including correlation heatmaps and survival distributions, were used to gain insights into the relationships between variables and the target outcome (survival).

## Results
The results from each model were compared, with accuracy scores and confusion matrices provided. Random Forest and SVM showed the best overall performance based on cross-validation results.

## License
This project is licensed under the MIT License.
