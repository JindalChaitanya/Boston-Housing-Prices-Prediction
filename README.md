# Boston Housing Prices Prediction

In this project, we predict the housing prices in Boston using machine learning techniques. The Boston Housing dataset serves as a foundation to explore various regression algorithms. By analyzing features like crime rate, number of rooms, and proximity to highways, we aim to build an accurate predictive model. This project is ideal for understanding the basics of data preprocessing, model training, and evaluation in a real-world context.

## Problem Statement

Housing prices are influenced by various factors such as location, crime rate, number of rooms, and proximity to highways. The goal is to create a predictive model that can accurately estimate the value of a house based on these features.

## Dataset

The Boston Housing dataset includes 506 instances, each containing 13 features that describe different aspects of housing (such as the average number of rooms per dwelling, crime rate, proximity to amenities, and more). The target variable is the median value of owner-occupied homes.

The dataset features include:

 - CRIM: Per capita crime rate by town
 - ZN: Proportion of residential land zoned for lots over 25,000 sq. ft.
 - INDUS: Proportion of non-retail business acres per town
 - CHAS: Charles River dummy variable (1 if tract bounds river; 0 otherwise)
 - NOX: Nitric oxide concentration (parts per 10 million)
 - RM: Average number of rooms per dwelling
 - AGE: Proportion of owner-occupied units built prior to 1940
 - DIS: Weighted distances to five Boston employment centers
 - RAD: Index of accessibility to radial highways
 - TAX: Full-value property tax rate per $10,000
 - PTRATIO: Pupil-teacher ratio by town
 - B: Proportion of Black population by town
 - LSTAT: Percentage of lower status of the population

The target variable is:

 - MEDV: Median value of owner-occupied homes in $1000's

## Tools and Technologies Used:

 - pandas: For data manipulation and analysis.
 - numpy: For numerical operations.
 - matplotlib and seaborn: For data visualization.
 - scikit-learn: For building and evaluating machine learning models.