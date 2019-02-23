# Titanic-Survival

Titanic: Machine Learning from Disaster

This project is on predicting the number of passengers survived from Titanic Disaster. We are given a dataset that is split into train and test data in csv format.
Each file has many passengers and each passenger has multiple features like the passengerId, gender, Pclass, Age, Name etc. The train.csv has an extra column, 'Survived', indicating whether a person has survived or not, making it a supervised learning.
Whereas test.csv does not have it. Our aim is to train the ML model using the train.csv and test it using the test.csv to find if the passengers survived or not.

Below is the workflow stages followed in this project.

1. Read and Understand the problem
2. Import libraries
3. Import train and test data
4. Data wranging
5. Analyze and identify the pattern and links between data
6. Bulding a suitable model

We are using multiple Ml algorithms to predict the output and are also comparing the accuracy obtained from each model against the other.

Algorithms Used:
1. Random Forest 
2. kNeighbors
3. Support Vector Machines	
4. Decision Tree
5. SVC
6. Logistic Regression
7. XGBoost
8. Stochastic Gradient Decent
9. Linear SVC
