# Flight Delay Prediction Project

## Overview
This project uses Data Science and Machine Learning to predict the reasons for flight delays. The dataset is cleaned and prepared, and different machine learning algorithms are applied to find the most accurate model for predicting the delay reasons.

## Key Features
- Data cleaning and preparation to make sure the data is accurate and usable.
- Implementing several machine learning models:
  - Logistic Regression
  - Support Vector Classifier (SVC)
  - Decision Tree Classifier
  - Random Forest Classifier
- Comparing the accuracy of different models to find the best one.

## Machine Learning Models
1. **Logistic Regression**: A model typically used for binary classification, but here we used it for multiclass data.
2. **Support Vector Classifier (SVC)**: We tested both linear and RBF kernels to find which one works best for our data.
3. **Decision Tree Classifier**: This model splits the data into branches to predict the delay reasons.
4. **Random Forest Classifier**: Uses 300 decision trees to predict the most common delay reason by taking the majority vote.

## Data Preparation
- Fixed missing data and focused on the most important features for the models.
- Converted categorical data into a format that the machine learning models could understand.
- Ensured the data was well-prepared for the modeling process.

## Results
- The Random Forest Classifier gave the best accuracy (around 93-94%), making it the top-performing model for predicting flight delay reasons.

## Conclusion
This project shows how machine learning can be used to predict flight delays. The models tested, especially the Random Forest, provided useful insights for the problem at hand.
