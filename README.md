# Titanic_Survival_Prediction
The Titanic Survival Prediction project is a machine learning project that aims to predict the survival of passengers aboard the Titanic based on a dataset of passenger information.


## DATASET

We had used a dataset from Kaggle Site for creating our prediction model. The data has been split into two groups:

• training set (train.csv)

• test set (test.csv)

The training set should be used to build your machine learning models. For the training set, we provide the outcome (also known as the “ground truth”) for each passenger. Your model will be based on “features” like passengers’ gender and class. You can also use feature engineering to create new features. 

The test set should be used to see how well your model performs on unseen data. For the test set, we do not provide the ground truth for each passenger. It is your job to predict these outcomes. For each passenger in the test set, use the model you trained to predict whether or not they survived the sinking of the Titanic.


### DATA DICTIONARY

![image](https://github.com/naincy-n/Titanic_Survival_Prediction/assets/78255083/2b36665d-d694-43ea-b9cd-6947512c0fbf)


## VARIABLE NOTES

### pclass
A proxy for socio-economic status (SES)

1st = Upper

2nd = Middle

3rd = Lower

### age
Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5

sibsp: The dataset defines family relations-

Sibling = brother, sister, stepbrother, stepsister

Spouse = husband, wife (mistresses and fiancés were ignored)

### parch
The dataset defines family relations-

Parent = mother, father

Child = daughter, son, stepdaughter, stepson

Some children travelled only with a nanny, therefore parch=0 for them.


## IMPLEMENTATION

Implementation of the Titanic Survival Prediction project using logistic regression as the
machine learning algorithm is done by using following steps:

❖ Step- 1 Import the required libraries

❖ Step- 2 Load the Titanic dataset into a pandas data frame

❖ Step- 3 Pre-process the data by handling missing values and converting categorical variables to numerical ones

❖ Step- 4 Perform exploratory data analysis to gain insights into the data

❖ Step- 5 Engineer relevant features to improve the performance of the model

❖ Step- 6 Split the data into training and testing sets

❖ Step- 7 Train a logistic regression model on the training data

❖ Step- 8 Evaluate the performance of the model on the testing data


## Conclusion

In this project, we used logistic regression as the machine learning algorithm to train a model on the Titanic dataset, and achieved an accuracy of around 80%. We also performed exploratory data analysis, feature engineering, and model evaluation to improve the performance of the model.

This project demonstrates the importance of data pre-processing, feature engineering, and model selection in machine learning. It also highlights the potential of machine learning to solve real-world problems and make predictions based on historical data. Overall, the Titanic Survival Prediction project provides a valuable learning experience for those interested in machine learning and data science.


## 
~Naincy Naiyar
