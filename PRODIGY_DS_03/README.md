# Loan Prediction Project

The Loan Prediction Project aims to build a predictive model to determine whether a loan application will be approved or rejected based on various features of the applicants. This project involves several stages, including data loading, preprocessing, exploratory data analysis (EDA), model selection, and error analysis.

## Table of Contents

1. [Loading the Dataset](#loading-the-dataset)
2. [Data Preprocessing](#data-preprocessing)
3. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
4. [Splitting the Dataset](#splitting-the-dataset)
5. [Model Selection](#model-selection)
6. [Balancing the Dataset](#balancing-the-dataset)
7. [Error Analysis](#error-analysis)
8. [Conclusion](#conclusion)
9. [Link to Repository](#Link-to-Repository)
10. [Connect with Me](#.Connect-with-Me)
11. [Resources](Resources)

## Loading the Dataset

1. Load the dataset using Google Colab:

## Data Preprocessing

1. **Handling Missing Values**: Dropped rows with missing values.
2. **Data Cleaning**: 
    - Removed currency symbols from columns like `LoanAmount`.
    - Converted columns to numeric data types.
3. **Label Encoding**:
    - Encoded categorical columns: `Gender`, `Married`, `Education`, `Self_Employed`, `Loan_Status`, `Property_Area`.
4. **Scaling**:
    - Standardized numerical features using `StandardScaler`.

## Exploratory Data Analysis (EDA)

1. **Correlation Heatmap**: Visualized feature correlations.

2. **Histograms**:
    - Plotted distributions of features like `ApplicantIncome`, `LoanAmount`, `Loan_Amount_Term`, and `Total_Income` based on `Loan_Status`.

## Splitting the Dataset

1. **Train-Test Split**: Split data into training and testing sets.

## Model Selection

1. **Logistic Regression**:
    - Accuracy: 0.79
    - ROC-AUC Score: 0.78

2. **Decision Tree**:
    - Accuracy: 0.73

3. **Random Forest**:
    - Accuracy: 0.76
    - ROC-AUC Score: 0.83

## Balancing the Dataset

1. **Oversampling**: Applied SMOTE to balance classes.
2. **Undersampling**: Used RandomUnderSampler.
3. **Combining Techniques**: Used SMOTEENN for combined oversampling and undersampling.

## Error Analysis

1. Analyzed misclassified cases to understand errors and their impact on predictions.

## Conclusion

- Conducted data preprocessing and EDA.
- Evaluated multiple models for loan prediction.
- Addressed class imbalance and performed error analysis to enhance model performance.

## Link to Repository

[Repository Link](https://github.com/shanttoosh/PRODIGY_DS/tree/main/PRODIGY_DS_03) 

## Connect with Me

Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/shanttoosh-v-470484289/) and follow my journey in data analytics and visualization!

## Resources

- **COLAB**: Google Colab
- **Data Source**: [Link to Data Source](https://www.kaggle.com/datasets/janiobachmann/bank-marketing-dataset)  


