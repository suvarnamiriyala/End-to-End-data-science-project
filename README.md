# End-to-End-data-science-project

COMPANY : CODTECH IT SOLUTIONS

NAME : MIRIYALA SUVARNA

INTERN ID : CITS13

DOMAIN : DATA SCIENCE

DURATION : 6WEEKS

MENTOR : NEELA SANTOSH KUMAR

DESCRIPTION :

# Demand Prediction System for a Local Shop

## Project Overview

This project is a machine learning-based Demand Prediction System developed using Python in Google Colab. The objective of the project is to predict product demand for a local shop by analyzing factors such as previous sales, temperature, weekend status, and product type. Demand forecasting helps shop owners make better inventory decisions, reduce stock shortages, and minimize excess inventory.

The project begins by generating a synthetic dataset that simulates real-world shop sales data. Various products such as Milk, Bread, Eggs, Rice, and Sugar are included in the dataset. For each record, information such as previous sales, temperature, and whether the day is a weekend is generated. A demand value is then calculated based on these factors to create a dataset suitable for machine learning.

The dataset is stored and managed using the Pandas library. Data preprocessing is performed to prepare the dataset for model training. Since machine learning algorithms require numerical input, the product names are converted into numerical values using Label Encoding. The processed dataset is then divided into input features and target variables.

The project uses the Scikit-learn library to implement a Linear Regression model. The dataset is split into training and testing sets using the train_test_split function. The Linear Regression algorithm is trained on the training dataset and then evaluated using the testing dataset. Model performance is measured using the R² (R-squared) score, which indicates how well the model explains the variation in demand. The model achieved an R² score of approximately 0.93, demonstrating strong predictive performance on the generated dataset.

After training, the model is used to predict future demand based on new input values. This allows users to estimate product demand under different business conditions. The project demonstrates the complete machine learning workflow, including data generation, preprocessing, feature engineering, model training, evaluation, and prediction.

## Technologies and Tools Used

* Python
* Google Colab
* Pandas
* NumPy
* Scikit-learn
* Linear Regression

## Key Features

* Synthetic sales data generation
* Data preprocessing and label encoding
* Feature selection and target variable creation
* Train-test data splitting
* Linear Regression model training
* Demand forecasting and prediction
* Model evaluation using R² Score

## Learning Outcomes

Through this project, I gained practical experience in data preprocessing, machine learning model development, model evaluation, and demand forecasting. I also learned how to use Pandas for data manipulation and Scikit-learn for implementing predictive analytics solutions.

OUTPUT : 
