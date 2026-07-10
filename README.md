# personality-prediction-machine-learning
## Overview
This project predicts whether an individual is an introvert or an extrovert using behavioral and social preference data. Multiple supervised machine learning models were developed and compared to identify the most accurate classifier.

## Problem Statement
The objective was to determine how effectively behavioral indicators such as stage fear, time spent alone, social event attendance, and social media activity can predict personality type.

## Dataset
- Source: Kaggle – Extrovert vs. Introvert Behavior Dataset
- Records: 2,400+ survey responses
- Target Variable: Personality Type (Introvert / Extrovert)

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Machine Learning Workflow
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Yeo-Johnson Transformation
- Standardization
- PCA
- SMOTE
- Model Training
- Hyperparameter Tuning (GridSearchCV)
- Cross Validation
- Model Evaluation

## Models Evaluated
- Logistic Regression
- Random Forest
- k-Nearest Neighbors (kNN)
- Linear Discriminant Analysis (LDA)
- Quadratic Discriminant Analysis (QDA)
- Gaussian Naive Bayes

## Results
- Best Model: Random Forest
- Accuracy: ~90%
- ROC-AUC: ~0.93
- Cross Validation: 5-Fold

## Business Applications
- Customer Segmentation
- Recruitment & Talent Analytics
- Personalized User Experience
- Behavioral Analytics

## Repository Contents
- Jupyter Notebook
- Dataset
- Project Presentation

## Project Visualizations

### Correlation Matrix

The correlation matrix shows the relationships between behavioral variables and personality type.

[Correlation Matrix](images/correlation_matrix.png)

### Random Forest Confusion Matrix

The confusion matrix shows how accurately the Random Forest model classified introverts and extroverts.

[Random Forest Confusion Matrix](images/confusion_matrix.png)

### Random Forest ROC Curve

The ROC curve demonstrates the model's ability to distinguish between the two personality classes, achieving an ROC-AUC of approximately 0.93.

[Random Forest ROC Curve](images/roc_curve.png)

## Author
Vassu Patel
