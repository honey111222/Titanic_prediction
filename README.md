Titanic Survival Prediction

Overview

This project aims to predict whether a passenger on the Titanic would survive based on various features such as age, gender, ticket class, and other attributes. The model is built using Logistic Regression, a commonly used classification algorithm.

Dataset

The dataset used is the Titanic dataset from Kaggle or other publicly available sources. It contains the following key features:

PassengerId: Unique ID for each passenger

Pclass: Ticket class (1st, 2nd, or 3rd)

Name: Passenger's name

Sex: Gender of the passenger

Age: Age of the passenger

SibSp: Number of siblings/spouses aboard

Parch: Number of parents/children aboard

Ticket: Ticket number

Fare: Fare paid for the ticket

Cabin: Cabin number (if available)

Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

Survived: Target variable (0 = Did not survive, 1 = Survived)

Project Workflow

Data Preprocessing

Handling missing values (e.g., imputation for age and embarked columns)

Encoding categorical variables (e.g., converting 'Sex' and 'Embarked' to numerical form)

Feature selection to improve model performance

Exploratory Data Analysis (EDA)

Visualizing survival rates based on different features

Identifying correlations between variables

Model Building

Splitting the dataset into training and testing sets

Applying Logistic Regression for classification

Evaluating model performance using accuracy, precision, recall, and F1-score

Model Evaluation

Checking the confusion matrix

Analyzing feature importance

Comparing results with baseline models

Dependencies

To run this project, install the following Python libraries:

Running the Project

Run the Python script to train and evaluate the model:

Results & Insights

Women had a higher survival rate compared to men.

1st class passengers had a higher survival rate than those in 2nd and 3rd class.

Children had a higher chance of survival compared to adults.

Future Improvements

Implement advanced classification techniques like Random Forest, XGBoost, or Neural Networks for better accuracy.

Perform hyperparameter tuning for optimized model performance.

Enhance feature engineering by extracting more meaningful insights from existing features.


