# Logistic Regression: Ad Click Prediction
## ARTI 308: Machine Learning - Assignment 7

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit_Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-444876?style=for-the-badge&logo=seaborn&logoColor=white)

### Overview
This repository contains a Logistic Regression Assignment aimed at predicting whether an internet user will click on an advertisement based on their user profile and behavior features. 

### Workflow & Tasks Completed
1. **Exploratory Data Analysis (EDA):** - Visualized the age distribution of users.
   - Analyzed relationships between features like `Age`, `Area Income`, `Daily Time Spent on Site`, and `Daily Internet Usage` using Seaborn's `jointplot` and `pairplot`.
2. **Data Preparation:** - Selected relevant numerical features for the model.
   - Split the dataset into training (67%) and testing (33%) sets.
3. **Model Training:** - Initialized and trained a **Logistic Regression** model using the training data.
4. **Evaluation:** - Generated predictions on the test set.
   - Evaluated the model's performance using a **Classification Report**, achieving an accuracy of **91%**.

### Files in this Repository
* `Logistic-Regression-Assignment.ipynb`: The Jupyter Notebook containing the full EDA and machine learning pipeline.
* `advertising.csv`: The dataset used for training and testing the model.
