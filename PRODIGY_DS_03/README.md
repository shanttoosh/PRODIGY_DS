# Loan Prediction Project

The Loan Prediction Project aims to build a predictive model to determine whether a loan application will be approved or rejected based on various features of the applicants. This project involves several stages, including data loading, preprocessing, exploratory data analysis (EDA), model selection, and error analysis.

## Table of Contents

1. [1.Loading the Dataset](#1.loading-the-dataset)
2. [2.Data Preprocessing](#2.data-preprocessing)
3. [3.Exploratory Data Analysis (EDA)](#3.exploratory-data-analysis-eda)
4. [4.Splitting the Dataset](#4.splitting-the-dataset)
5. [5.Model Selection](#5.model-selection)
6. [6.Balancing the Dataset](#6.balancing-the-dataset)
7. [7.Error Analysis](#7.error-analysis)
8. [8.Conclusion](#8.conclusion)
9. [9.Link to Repository](#9.Link-to-Repository)
10. [10.Connect with Me](#10.Connect-with-Me)
11. [11.Resources](11.Resources)

## 1.Loading the Dataset

1. Load the dataset using Google Colab:

## 2.Data Preprocessing

1. **Handling Missing Values**: Dropped rows with missing values.
2. **Data Cleaning**: 
    - Removed currency symbols from columns like `LoanAmount`.
    - Converted columns to numeric data types.
3. **Label Encoding**:
    - Encoded categorical columns: `Gender`, `Married`, `Education`, `Self_Employed`, `Loan_Status`, `Property_Area`.
4. **Scaling**:
    - Standardized numerical features using `StandardScaler`.

## 3.Exploratory Data Analysis (EDA)

1. **Correlation Heatmap**: Visualized feature correlations.

2. **Histograms**:
    - Plotted distributions of features like `ApplicantIncome`, `LoanAmount`, `Loan_Amount_Term`, and `Total_Income` based on `Loan_Status`.

## 4.Splitting the Dataset

1. **Train-Test Split**: Split data into training and testing sets.

## 5.Model Selection

1. **Logistic Regression**:
    - Accuracy: 0.79
    - ROC-AUC Score: 0.78

2. **Decision Tree**:
    - Accuracy: 0.73

3. **Random Forest**:
    - Accuracy: 0.76
    - ROC-AUC Score: 0.83

## 6.Balancing the Dataset

1. **Oversampling**: Applied SMOTE to balance classes.
2. **Undersampling**: Used RandomUnderSampler.
3. **Combining Techniques**: Used SMOTEENN for combined oversampling and undersampling.

## 7.Error Analysis

1. Analyzed misclassified cases to understand errors and their impact on predictions.

## 8.Conclusion

- Conducted data preprocessing and EDA.
- Evaluated multiple models for loan prediction.
- Addressed class imbalance and performed error analysis to enhance model performance.

##  9.Link to Repository

[Repository Link](https://github.com/shanttoosh/PRODIGY_DS/tree/main/PRODIGY_DS_03) 

##  10.Connect with Me

Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/shanttoosh-v-470484289/) and follow my journey in data analytics and visualization!

##  11.Resources

- **COLAB**: Google Colab
- **Data Source**: [Link to Data Source](https://www.kaggle.com/datasets/janiobachmann/bank-marketing-dataset)  


