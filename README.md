# EBP_Edunet
This project aims to predict employee burnout using a **Linear Regression** model based on various features related to employee behavior, workload, and other factors. The goal is to provide organizations with a predictive tool to identify employees at risk of burnout and intervene proactively. 

## Project Overview

Burnout is a state of emotional, physical, and mental exhaustion caused by excessive and prolonged stress. It can lead to decreased productivity, absenteeism, and other negative outcomes for employees. By using machine learning models, organizations can predict burnout risk and implement preventive measures.

In this project, I used the **Linear Regression** model to predict burnout scores based on several employee-related features.

## Tech Stack

- **Jupyter Notebook** for data analysis and model building
- **Python** programming language
- **Libraries/Packages used**:
  - `pandas` for data manipulation
  - `numpy` for numerical operations
  - `scikit-learn` for implementing machine learning algorithms (Linear Regression)
  - `matplotlib` and `seaborn` for data visualization
  - `sklearn` for preprocessing, model evaluation, and metrics

## Dataset

The dataset used in this project contains information about employees and various factors related to their work environment to predict burnout levels. It includes both numerical and categorical features, such as **Company Type**, **Designation**, **Gender**, **Mental Fatigue Score**, and **Resource Allocation**. The target variable is the **Burnout Score**, a continuous numerical value representing the level of burnout. The dataset is preprocessed by encoding categorical features (such as `Company Type`, `Designation`, and `Gender`) using one-hot encoding, and scaling the numerical features using **StandardScaler** to ensure consistency in their range. The data is then split into training and testing sets for model training and evaluation. The goal is to build a regression model that predicts the burnout score based on these features.

The target variable is the `Burnout Score`, which is the score predicting the level of burnout.

## Approach

1. **Data Preprocessing**: 
   - Handle missing values, encode categorical variables using one-hot encoding.
   - Scale features to standardize the data.
   
2. **Model Training**:
   - Split the dataset into training and testing sets.
   - Train a **Linear Regression** model on the training data.

3. **Model Evaluation**:
   - Evaluate the model performance on both the training and testing data using R-squared (R²) and other metrics.
   - Achieved **R-squared (R²) = 0.86** on the testing data, indicating good predictive performance.

## Results

The final model achieved an R² score of **0.86** on the testing data. This indicates that the model explains 86% of the variance in the burnout scores based on the given features.

## Installation

To get started with this project, clone the repository and install the required dependencies:

```bash
git clone https://github.com/yourusername/employee-burnout-prediction.git
cd employee-burnout-prediction
