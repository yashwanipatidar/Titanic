# Titanic
# Titanic Survival Prediction

This project implements a machine learning model to predict the survival of passengers aboard the Titanic based on various features like age, class, and embarkation port. The model uses **Logistic Regression** and **scikit-learn** for data preprocessing and model building.

## Project Overview

The Titanic dataset from Kaggle is used for this project. The goal is to predict whether a passenger survived or not using features such as age, gender, and family size. We will preprocess the dataset, train a machine learning model, and evaluate its performance.

### Key Steps:
1. **Data Preprocessing**: Handle missing values, encode categorical variables (Sex, Embarked), and create new features.
2. **Feature Engineering**: New features such as "FamilySize" were created by combining `SibSp` and `Parch` (family-related columns).
3. **Model Training**: Train a **Logistic Regression** model on the preprocessed dataset.
4. **Model Evaluation**: Evaluate the accuracy of the model using a test set.

## Installation

To run this project, ensure you have the following Python libraries installed:

```bash
pip install pandas numpy scikit-learn matplotlib
