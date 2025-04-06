# Titanic-Machine-Learning-Dataset

## Overview
This project builds a machine learning classifier to predict the survival of passengers aboard the Titanic based on historical data. Using the famous Titanic dataset from Kaggle, the goal is to explore, preprocess, and model the data to achieve high accuracy in predicting whether a passenger survived (1) or not (0). This project showcases skills in data analysis, feature engineering, and classical machine learning techniques.

## Dataset
- **Source**: [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)
- **Files**:
  - `train.csv`: Training data with features and target (`Survived`).
  - `test.csv`: Test data for predictions.
- **Features**:
  - `PassengerId`, `Pclass`, `Name`, `Sex`, `Age`, `SibSp`, `Parch`, `Ticket`, `Fare`, `Cabin`, `Embarked`
- **Target**: `Survived` (0 = No, 1 = Yes)
- **Size**: 891 rows (train), 418 rows (test).

## Requirements
- Python 3.8+
- Libraries:
  ```bash
  pip install pandas numpy scikit-learn matplotlib seaborn xgboost lightgbm
  ```
- Optional: Jupyter Notebook for exploration.



