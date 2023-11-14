# Deep Learning Homework: Charity Funding Predictor

## Background

The non-profit foundation Alphabet Soup wants to create an algorithm to predict whether or not applicants for funding will be successful. Leveraging our knowledge of deep learning, we are tasked with creating a binary classifier able to predict whether applicants will be successful if funded by Alphabet Soup.

We have received a data file containing historic data on 34,000+ organizations that have received funding from Alphabet Soup. W

## Instructions

### Step 1: Preprocess the data

We'll first preprocess the dataset, using  Pandas and the Scikit-Learn’s `StandardScaler()`, in order to compile, train, and evaluate the neural network model.

### Step 2: Compile, Train, and Evaluate the Model

We then design deep learning model, using TensorFlow, to create the binary classification model.

### Step 3: Optimize the Model

Using TensorFlow, we then optimize the model to achieve a target predictive accuracy >/= 75%, repeating the optimization up to 3 times if we are unsuccessful.


3. **Summary**: None of the optimization attempts achieved an improvement in accuracy sufficient enough to meet the 75% accuracy target. Improved accuracy could have been achieved by removing variables from the model that were / are less associated with “success”. In addition, because much of this data was categorical, it might make sense to try a decision tree or a random forest model.


- - -

## Rubric

[Unit 21 - Deep Learning Homework Rubric - Charity Funding Predictor](https://docs.google.com/document/d/1SLOROX0lqZwa1ms-iRbHMQr1QSsMT2k0boO9YpFBnHA/edit?usp=sharing)

___
© 2021  Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.	
