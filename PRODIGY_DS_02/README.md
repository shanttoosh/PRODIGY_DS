# Data Cleaning and Exploratory Data Analysis (EDA) for Titanic Dataset

This project focuses on data cleaning and exploratory data analysis (EDA) for a dataset related to Titanic passengers. The aim is to preprocess the data, handle missing values, and gain insights through various visualizations.

## Table of Contents
1. [Introduction](#introduction)
2. [Dataset Overview](#dataset-overview)
3. [Data Cleaning](#data-cleaning)
    - [Handling Missing Values](#handling-missing-values)
    - [Removing Unnecessary Columns](#removing-unnecessary-columns)
    - [Data Type Verification](#data-type-verification)
    - [Duplicate Removal](#duplicate-removal)
4. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
    - [Distribution of Age](#distribution-of-age)
    - [Distribution of Fare](#distribution-of-fare)
    - [Class Distribution (Pclass)](#class-distribution-pclass)
    - [Gender Distribution (Sex)](#gender-distribution-sex)
    - [Port of Embarkation (Embarked)](#port-of-embarkation-embarked)
    - [Correlation Heatmap](#correlation-heatmap)
5. [Conclusion](#conclusion)
6. [Link to Repository](#link-to-repository)
7. [Connect with Me](#connect-with-me)
8. [Resources](#resources)

## Introduction
This project involves cleaning the Titanic dataset and performing exploratory data analysis (EDA) to uncover patterns, correlations, and insights. The goal is to prepare the dataset for further analysis and model building.

## Dataset Overview
The dataset includes the following columns:
- `PassengerId`: A unique identifier for each passenger.
- `Pclass`: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd).
- `Name`: Passenger's name.
- `Sex`: Gender of the passenger.
- `Age`: Age of the passenger.
- `SibSp`: Number of siblings/spouses aboard.
- `Parch`: Number of parents/children aboard.
- `Ticket`: Ticket number.
- `Fare`: Passenger fare.
- `Cabin`: Cabin number.
- `Embarked`: Port of Embarkation (C = Cherbourg; Q = Queenstown; S = Southampton).

## Data Cleaning

### Handling Missing Values
- **Age**: Imputed with the median value due to missing values.
- **Fare**: Imputed with the median value for the single missing instance.
- **Cabin**: Dropped due to the high percentage of missing values.

### Removing Unnecessary Columns
- **Cabin**: Removed from the dataset as the majority of values were missing.

### Data Type Verification
- Ensured all columns have the correct data types, particularly numeric columns.

### Duplicate Removal
- Checked and confirmed that the dataset does not contain any duplicate entries.

## Exploratory Data Analysis (EDA)

### Distribution of Age
- The age distribution was visualized using a histogram with a KDE (Kernel Density Estimate) overlay.

### Distribution of Fare
- The fare distribution was analyzed and visualized to understand the range and typical values.

### Class Distribution (Pclass)
- A count plot was used to visualize the distribution of passengers across different ticket classes.

### Gender Distribution (Sex)
- The gender distribution was visualized to understand the ratio of male to female passengers.

### Port of Embarkation (Embarked)
- A count plot was used to analyze the distribution of passengers by their port of embarkation.

### Correlation Heatmap
- A heatmap was created to visualize the correlations between numeric variables in the dataset, highlighting relationships such as the negative correlation between `Pclass` and `Fare`.

## Conclusion
The data cleaning and EDA processes have provided valuable insights into the Titanic dataset, preparing it for further analysis and model development. The steps taken ensure that the data is in a good state for predictive modeling or other analytical tasks.

##  Link to Repository

[Repository Link](https://github.com/shanttoosh/PRODIGY_DS/tree/main/PRODIGY_DS_02)  

##  Connect with Me

Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/shanttoosh-v-470484289/) and follow my journey in data analytics and visualization!

##  Resources

- **COLAB**: Google Colab
- **Data Source**: [Link to Data Source](https://www.kaggle.com/c/titanic/data?select=test.csv)  

