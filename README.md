# Titanic Survival Prediction Using Logistic Regression
This project implements a logistic regression machine learning model to predict passenger survival on the RMS Titanic using key demographic and socioeconomic attributes.
(Target: 0 = Deceased, 1 = Survived)

## Features

The dataset contains many features, but the ones used in the model are:  
**Pclass:** Passenger class (1st, 2nd, or 3rd)  
**Sex:** Passenger's gender (male or female)  
**Age:** Passenger's age  
**SibSp:** Number of siblings/spouses aboard  
**Parch:** Number of parents/children aboard 
**Fare:** Passenger fare  

## Labels

**Survived:** is the label of the target variable, which indicates whether the passenger survived.

## Data Preprocessing
Before training the model, the data was preprocessed to ensure that it was suitable for machine learning.

### Handling Missing Values: 
Some passengers had missing values in the Age column. These missing values were replaced with the median age of the passengers.

### Converting Categorical Data: 
The Sex column contained categorical values such as "male" and "female". Since Logistic Regression requires numerical input, these values were converted into numerical values, where male was represented by 0 and female by 1.

## Model Evaluation

Following Evaluation Metrics were used:
1. Accuracy
2. Classification Report
3. Confusion Matrix

## Tools Used

1. Python
2. Pandas
3. Scikit-Learn




