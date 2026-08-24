# 🏥 Health Insurance Premium Prediction using Machine Learning

## 📌 Project Overview

This project focuses on predicting **health insurance charges** using Machine Learning techniques. The model learns relationships between customer characteristics such as age, BMI, smoking status, number of children, sex, and region to estimate medical insurance charges.

The project demonstrates an end-to-end Machine Learning workflow, including **data preprocessing, exploratory data analysis, feature engineering, categorical encoding, regression model development, prediction, and model evaluation**.

## 🎯 Objective

The primary objective is to develop a regression-based Machine Learning model capable of predicting an individual's insurance charges based on their demographic and health-related attributes.

## 📊 Dataset Features

| Feature  | Description                              |
| -------- | ---------------------------------------- |
| Age      | Age of the individual                    |
| Sex      | Gender of the individual                 |
| BMI      | Body Mass Index                          |
| Children | Number of children/dependents            |
| Smoker   | Smoking status                           |
| Region   | Residential region                       |
| Charges  | Medical insurance cost — Target Variable |

## 🔎 Exploratory Data Analysis

The dataset was explored to understand:

* Data types and dataset structure
* Numerical feature distributions
* Relationships between features and insurance charges
* Influence of age and BMI on charges
* Differences in charges based on smoking status
* Regional variations in insurance charges
* Statistical characteristics of the dataset

Some key observations from the analysis include an average age of approximately **39.21 years**, an average BMI of approximately **30.66**, and average insurance charges of approximately **13,270.42**.

## ⚙️ Data Preprocessing

The dataset contains both numerical and categorical features.

Numerical features include:

* Age
* BMI
* Children

Categorical features include:

* Sex
* Smoker
* Region

Categorical variables were transformed into numerical representations using encoding so that they could be processed by the regression algorithm.

## 🛠️ Feature Engineering

Feature engineering was performed to transform categorical information into machine-readable numerical features.

One-hot encoding was used to represent categorical values as binary features. This allows regression algorithms to work with variables such as smoking status, sex, and region.

## 🤖 Machine Learning Models

### 1. Simple Linear Regression

A baseline regression model was developed using a limited feature set to understand the basic relationship between an input feature and insurance charges.

### 2. Multiple Linear Regression

Multiple numerical features were incorporated to improve the model's ability to explain variations in insurance charges.

### 3. Full Feature Regression Model

The final model incorporated the relevant numerical and encoded categorical features:

* Age
* Sex
* BMI
* Children
* Smoker
* Region

This allowed the model to learn from a broader set of factors that may influence insurance charges.

## 📈 Model Evaluation

The models were evaluated using:

### Mean Squared Error (MSE)

MSE measures the average squared difference between actual and predicted insurance charges.

**Lower MSE indicates better prediction performance.**

### R² Score

R² measures the proportion of variance in the target variable explained by the regression model.

A value closer to **1** generally indicates stronger explanatory performance.

## 🔄 Machine Learning Workflow

```text
Raw Dataset
     ↓
Data Loading
     ↓
Data Understanding
     ↓
Data Cleaning
     ↓
Exploratory Data Analysis
     ↓
Feature Engineering
     ↓
Categorical Encoding
     ↓
Train-Test Split
     ↓
Model Training
     ↓
Insurance Charge Prediction
     ↓
Model Evaluation
     ↓
Model Comparison
```

## 💡 Key Learning Outcomes

Through this project, I gained practical experience in:

* Understanding a real-world regression problem
* Performing exploratory data analysis
* Identifying numerical and categorical features
* Performing feature engineering
* Encoding categorical variables
* Splitting data into training and testing sets
* Building regression models
* Generating predictions
* Evaluating models using MSE and R²
* Understanding the complete Machine Learning workflow

## 🧰 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## 📌 Future Improvements

Possible improvements to the project include:

* Testing additional regression algorithms
* Hyperparameter tuning
* Cross-validation
* Feature importance analysis
* Outlier treatment
* Model deployment using Flask or Streamlit
* Creating an interactive prediction interface
* Monitoring model performance on new data

## 👩‍💻 Author

**Ansim Fathima M**

B.Sc. Data Science Student

Interested in Data Analytics, Machine Learning, and Data Science.
