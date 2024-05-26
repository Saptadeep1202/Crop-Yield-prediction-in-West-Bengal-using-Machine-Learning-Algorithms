# Crop-Yield-prediction-in-West-Bengal-using-Machine-Learning-Algorithms
## Overview
This project focuses on predicting rice yield in the state of West Bengal, India, using machine learning algorithms. With a dataset comprising 11,340 distinct entries, we aim to determine the most accurate model for predicting high crop yields in a specified area during a particular season. The study leverages MATLAB’s Regression Learner application for model training and compares various ML models based on their accuracy between the train and test datasets.

## Dataset
The dataset includes 11,340 entries with features that are significant for predicting rice yield. These features may include:

Climatic conditions (temperature, rainfall, humidity, etc.)
Soil properties (type, pH, nutrient content, etc.)
Agricultural practices (sowing time, fertilizer usage, irrigation methods, etc.)
Historical yield data

## Machine Learning Models
The following machine learning models were evaluated:

Linear Regression
Decision Trees
Support Vector Machines (SVM)
Ensemble Methods (Bagging, Boosting)
Neural Networks

## Methodology
Data Preprocessing: The dataset was cleaned and preprocessed to handle missing values, normalize features, and encode categorical variables.

Model Training: Various machine learning models were trained using MATLAB’s Regression Learner application. The dataset was split into training and testing sets to evaluate model performance.

Model Evaluation: The performance of each model was assessed based on the accuracy between the train and test datasets. Metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R²) were used for evaluation.

## Results
The results of the model comparison are as follows:

Linear Regression: Basic approach with moderate accuracy.
Decision Trees: Provided a good balance between interpretability and accuracy.
Support Vector Machines: High accuracy but computationally intensive.
Ensemble Methods: Bagging and Boosting showed improved accuracy over individual models.
Neural Networks: High accuracy with a more complex model structure.
The most accurate model was determined based on the evaluation metrics, and recommendations for its use in practical scenarios were provided.

## Conclusion
This study demonstrates the application of various machine learning models to predict rice yield in West Bengal, India. The insights gained from this research can aid farmers, agronomists, and policymakers in making informed decisions to enhance crop production.


## Contributor
Saptadeep Choudhury(https://github.com/Saptadeep1202)

## License
This project is licensed under the Apache License.
