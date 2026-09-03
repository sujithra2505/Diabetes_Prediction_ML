# Diabetes Prediction Using Machine Learning

## Project Overview

This project uses machine learning classification algorithms
to predict whether a person is likely to have diabetes based
on demographic and health-related features.

## Dataset

The dataset contains information including:

- Gender
- Age
- Hypertension
- Heart Disease
- Smoking History
- BMI
- HbA1c Level
- Blood Glucose Level

The target variable is:

- 0 = No Diabetes
- 1 = Diabetes

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Machine Learning Models

Three classification algorithms were implemented:

1. Logistic Regression
2. Decision Tree
3. Random Forest

## Data Preprocessing

The following preprocessing steps were performed:

- Checked for missing values
- Removed duplicate records
- Encoded categorical variables using one-hot encoding
- Split the dataset into training and testing sets
- Applied feature scaling where appropriate

## Results

| Model | Accuracy |
|---|---:|
| Logistic Regression | 88.46% |
| Decision Tree | 95.07% |
| Random Forest | 96.88% |

Random Forest achieved the highest overall accuracy
among the three evaluated models.

## Feature Importance

The Random Forest model showed the highest feature
importance for:

1. HbA1c Level
2. Blood Glucose Level
3. Age
4. BMI

## Evaluation

Model performance was evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

## Limitations

This project is intended for educational purposes.
It is not a medical diagnostic system and should not
be used for clinical decision-making.

## Author

Sugithra C S
