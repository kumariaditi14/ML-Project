# Customer Churn Prediction

## Overview

This project focuses on analyzing customer churn and building a machine learning
model to identify customers who are more likely to leave the company.

The project includes exploratory data analysis, feature analysis, data preprocessing,
handling of class imbalance, model comparison and hyperparameter tuning.

## Project Workflow

- Data loading and preprocessing
- Exploratory Data Analysis
- Churn analysis by customer characteristics
- Feature selection
- One-hot encoding of categorical variables
- Feature scaling
- Handling class imbalance using SMOTE
- Model comparison using recall
- Gradient Boosting model development
- Hyperparameter tuning
- Final model evaluation

## Models Used

- Decision Tree
- K-Nearest Neighbors
- Random Forest
- Logistic Regression
- Gradient Boosting

## Key Analysis

Some important patterns explored in the project include:

- Churn behaviour across different states
- Impact of international plans on churn
- Customer service calls and churn
- Relationship between day charges and churn
- Comparison of churn across area codes

## Final Model

Gradient Boosting was selected for the final model after comparing multiple
classification algorithms and tuning its hyperparameters.

The final model achieved a **recall score of 0.80 on the test data**.

Recall was used as an important evaluation metric because identifying customers
who are likely to churn is more important than simply maximizing overall accuracy.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Imbalanced-learn
- Jupyter Notebook

## Dataset

The dataset used for this project is included in this repository as:

`churn-bigml-20.csv`

## Project Files

- `Customer_Churn.ipynb` — Complete analysis and machine learning workflow
- `churn-bigml-20.csv` — Dataset used for the analysis
