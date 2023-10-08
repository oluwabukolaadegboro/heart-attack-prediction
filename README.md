# heart-attack-prediction

This project was implemented as part of my final capstone project for a program offered by Vector Institute, Introduction to Machine Learning for Black & Indigenous students. 

The goal of this project is to identify if a patient has a heart attack or not. To solve this, the project was scoped into a binary classification problem and evaluated using various machine learning models. The dataset consists of multivariate tabular data containing 303 instances and 14 features with the following attribute characteristics: categorical, integer, and real values. 

As part of the data pre-processing step, the data was normalized and since no missing values were found, no further data cleaning was required. The dataset was split into an 80% train set and a 20% test set. The model was evaluated using the accuracy and the ROC curve. In the end, the Extreme Gradient Boost algorithm gave the highest accuracy of 83.607% when compared to the other models. Further steps were taken to ensemble selected ML models used for training, however, the accuracy of the ensemble results performed similarly to that of the Extreme Gradient Boost algorithm.
