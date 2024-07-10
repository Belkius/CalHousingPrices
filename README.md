# Price prediction of california housing

## Overview
This project is a simple example of a price prediction ML Model for california housing using an example dataset.
The project is mostly for learning purposes and to get a better understanding of the machine learning process - mainly preprocessing and regression models.

## Requirements
- Python 3.6 or higher
- Jupyter
- Pandas
- Numpy
- Matplotlib
- Scikit-learn
- Scipy

## Dataset
The data consists of 20640 instances and 10 attributes. The attributes are as follows:
1. `longitude`: A measure of how far west a house is; a higher value is farther west
2. `latitude`: A measure of how far north a house is; a higher value is farther north
3. `housing_median_age`: Median age of a house within a block; a lower number is a newer building
4. `total_rooms`: Total number of rooms within a block
5. `total_bedrooms`: Total number of bedrooms within a block
6. `population`: Total number of people residing within a block
7. `households`: Total number of households, a group of people residing within a home unit, for a block
8. `median_income`: Median income for households within a block of houses
9. `median_house_value`: Median house value for households within a block
10. `ocean_proximity`: Location of the house with reference to ocean/sea

Data used in this project is available under the following link (08.07.2024):
https://raw.githubusercontent.com/ageron/handson-ml2/master/datasets/housing/housing.tgz

## Models
The project uses the following regression models:
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Support Vector Regressor

## Preprocessing
The preprocessing steps include:
- Handling missing values
- Encoding categorical data
- Feature scaling
- Splitting the dataset into training and test sets
- Feature selection
- Training the models
- Evaluating the models
- Hyperparameter tuning
- Cross-validation
- Feature importance
- Model evaluation
- Model comparison