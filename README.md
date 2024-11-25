# Linear_regression_model
# Life Expectancy Analysis Using Linear Models
This project analyzes life expectancy data from the World Health Organization (WHO) to understand the factors influencing life expectancy across different countries. The analysis employs various linear regression models to predict life expectancy based on multiple health and socioeconomic indicators.

### Table of Contents
Overview

Dataset

Data Preprocessing

Data Analysis

Modeling

Results

Technologies Used

### Overview
Life expectancy is a crucial indicator of a country's health and development status. This project aims to analyze life expectancy data and build predictive models to identify significant factors influencing life expectancy. The models used include Linear Regression, Ridge, Lasso, and ElasticNet.

### Dataset
The dataset used in this project was obtained from Kaggle:

Dataset URL: https://www.kaggle.com/datasets/kumarajarshi/life-expectancy-who

The dataset contains 2938 entries with the following relevant features:

Country: Name of the country.
Year: Year of the data.
Status: Development status (Developed or Developing).
Life Expectancy: Average life expectancy in years.
Adult Mortality: Adult mortality rate.
Infant Deaths: Number of infant deaths per 1,000 live births.
Alcohol: Alcohol consumption per capita.
Hepatitis B: Percentage of the population vaccinated against Hepatitis B.
GDP: Gross Domestic Product per capita.
Schooling: Average years of schooling.

### Data Preprocessing
Loading the Data: The dataset is loaded into a pandas DataFrame.
Handling Missing Values: Missing values are addressed using median and mean imputation for relevant columns.
Data Type Conversion: The 'Year' column is converted to a datetime format for better analysis.
Encoding Categorical Variables: The 'Status' column is converted into a binary format using one-hot encoding.

### Data Analysis
Histograms are plotted to visualize the distribution of missing values of key variables such as life expectancy, adult mortality, alcohol consumption, and GDP.
A correlation heatmap is generated to identify relationships between numerical features.

### Modeling
The following linear models are implemented to predict life expectancy:

######Linear Regression

Cross-validation is used to evaluate model performance.
Mean R² score: 0.802.

######Ridge Regression

Regularization is applied to prevent overfitting.
Mean R² score: 0.802.

######Lasso Regression

Lasso is used for feature selection and regularization.
Mean R² score: 0.802.

######ElasticNet

Combines L1 and L2 regularization.
Mean R² score: 0.802.
