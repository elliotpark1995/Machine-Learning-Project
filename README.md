# Machine Learning Project - Exoplanet Exploration

![exoplanets.jpg](.../Images/exoplanets.jpg)

Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system. In order to help process this data, four machine learning models capable of classifying candidate exoplanets from the raw dataset were created.

## Process

1. Data Cleansing

- Cleaned the data by removing unnecessary columns.
- Scaled the data using MinMaxScaler.
- Separated the data into training and testing data.

2. Tuned the Models

- Used GridSearch to tune model parameters.
- NOTE: Only used GridSearch on the SVM and Logistic Regression models.

3. Quantified the Models

- Found the best score from the trained GridSearch model.
- Made predictions from the hypertuned model.

## Findings

All of the machine learning models scored in the upper 80% range with the Random Forest model being most accurate with an accuracy rate of 89.6%. The use of GridSearch improved the accuracy of the Support Vector Machine and Logistic Regression models, but the efffect was miniscule, improving the accuracy only by 0.9% and 0.1% respectively. 

Model Performance:

Random Forest Model = 89.6% 
Deep Learning Model = 88.4% 
Logistic Regression Model = 88.1% 
Support Vector Machine Model = 87.5% 