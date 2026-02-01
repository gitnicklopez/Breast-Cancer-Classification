# Breast Cancer Classification (Kaggle Project)
Author: Nicholas Lopez

## Project Overview
This project focuses on predicting whether a breast mass sample is Malignant (M) or Benign (B) using various machine learning classification models. The data is sourced from the Wisconsin Breast Cancer dataset, which contains features extracted from digitized images of fine needle aspirates (FNA) of breast masses.

## Key Features
Exploratory Data Analysis (EDA): Insights into feature distributions and target class balance.

## Data Preprocessing: 
Includes custom functions for target label encoding (M/B to 1/0) and feature scaling using StandardScaler.Multi-Model Comparison: Evaluates six different classification algorithms to find the most accurate predictor.Automated Evaluation Pipeline: A reusable function to train, predict, and score multiple models simultaneously.

## Models Evaluated
The following models were trained and tested on the standardized dataset:
> Support Vector Machine (SVC) - Top PerformerLogistic
> RegressionPerceptronK-Nearest Neighbors (KNN)
> Decision Tree
> Random ForestResults

## Metrics Used:
The models were evaluated based on Accuracy. The Support Vector Classifier (SVC) outperformed the other models with a high degree of precision:
> ModelAccuracy:
> 
> > SVC-98.90%
> > 
> > Logistic Regression-97.80%
> > 
> > Perceptron-96.70%
> >
> > KNN-96.70%
> > 
> > Decision Tree-95.60%
> > 
> > Random Forest-95.60%

# Technologies Used
> Python (Pandas, NumPy)
> 
> Scikit-learn (Machine Learning models and preprocessing)
> 
> Matplotlib (Visualization)
