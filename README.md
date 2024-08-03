# Titanic Survival Logistic Regression

## Overview

This repository contains a logistic regression model that predicts the likelihood of survival for Titanic passengers. The model utilizes features such as age, gender, passenger class, and fare to provide probabilistic assessments of a passenger's chance of survival. The project demonstrates key data science and machine learning techniques, including data preprocessing, feature engineering, model training, and performance evaluation.

## Features

- Logistic Regression model for survival prediction
- Data preprocessing and cleaning
- Feature engineering and encoding
- Model training and evaluation
- Probabilistic survival assessments

## Data

The dataset used for this project is the Titanic passenger data, which includes the following features:

- `PassengerId`: Unique identifier for each passenger
- `Pclass`: Passenger class (1, 2, or 3)
- `Name`: Passenger's name
- `Sex`: Passenger's gender
- `Age`: Passenger's age
- `SibSp`: Number of siblings/spouses aboard
- `Parch`: Number of parents/children aboard
- `Ticket`: Ticket number
- `Fare`: Ticket fare
- `Embarked`: Port of embarkation (C, Q, S)
- `Survived`: Whether the passenger survived (0 = No, 1 = Yes)

## Installation

To run this project, clone the repository and install the required dependencies:

```bash
git clone https://github.com/Sunithakarri/titanic-survival-logistic-regression.git
cd titanic-survival-logistic-regression
pip install -r requirements.txt

Evaluation
The model's performance can be evaluated using metrics such as accuracy, precision, recall, and the F1 score. Results are printed to the console after running the model.

Contributing
Contributions are welcome! Please fork the repository and submit a pull request with any improvements or bug fixes.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgements
Kaggle Titanic Dataset
Scikit-learn for machine learning tools
