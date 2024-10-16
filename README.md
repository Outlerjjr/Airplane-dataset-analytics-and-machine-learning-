# Flight Delay Prediction Project

## Overview
This project uses Data Science and Machine Learning to predict the reasons behind flight delays. We clean and preprocess the dataset, apply multiple classification algorithms, and determine the most accurate model for predicting delay reasons. The final cleaned data is exported into a CSV file for future use.

## Key Features
- Data cleaning and preprocessing to ensure accuracy and reliability.
- Implementation of multiple machine learning models, including:
  - Logistic Regression
  - Support Vector Classifier (SVC)
  - Decision Tree Classifier
  - Random Forest Classifier
- Evaluation of model performance based on accuracy.
- Exporting the cleaned data into a CSV file for further analysis.

## Machine Learning Models
1. **Logistic Regression**: Initially used for binary classification, applied to our multiclass dataset.
2. **Support Vector Classifier (SVC)**: We tested both linear and RBF kernels to evaluate the best fit for our data.
3. **Decision Tree Classifier**: Predicts delay reasons by splitting data into branches based on feature values.
4. **Random Forest Classifier**: Utilizes 300 decision trees to provide the most accurate prediction by taking the mode of predictions.

## Data Preprocessing
- Handled missing data and ensured that only relevant features are used for modeling.
- Encoded categorical variables to make them suitable for machine learning models.
- Cleaned and structured data for improved readability.

## Results
- The Random Forest Classifier yielded the highest accuracy (93-94%), making it the best-performing model for predicting delay reasons.

## Conclusion
This project demonstrates the effective use of various machine learning techniques to predict flight delays. The final processed data is saved in a CSV file, making it available for further analysis or integration into other applications.

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone <repo-url>
