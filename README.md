### Team Members:

1.  John Doe
2.  Jane Smith
3.  Alex Johnson

### Project Overview

This project aims to predict the revenue of movies using machine learning techniques. We will be using a dataset that includes various features such as names, release dates, scores, genres, and budget information.

### Project Steps

1.  **Data Import and Loading**: We start by importing the necessary libraries and loading the dataset into our environment.
    
2.  **Adding Columns**: We extract additional columns by manipulating existing ones, such as extracting year and month from the release date.
    
3.  **Dataset Information & Visualization**: We perform exploratory data analysis to understand the dataset better, including visualizing distributions and correlations between features. (Optional)
    
4.  **Defining Features & Target Columns**: We define the features (X) and target variable (y) for our model.
    
5.  **Extracting Numerical and Categorical Columns**: We separate numerical and categorical columns for preprocessing.
    
6.  **Pipeline Usage**: We use pipelines to impute missing values and scale numerical columns.
    
7.  **Function Definition**: We define functions for preprocessing and model evaluation.
    
8.  **Model Selection and Evaluation**:
    
    *   Linear Regression
    *   SVR
    *   Decision Tree Regressor
    *   Random Forest Regressor We perform KFold cross-validation to determine the best model.
9.  **SVR Evaluation**: SVR performs poorly, so we exclude it from further analysis.
    
10.  **Fine-Tuning Models**: We use GridSearchCV to fine-tune the hyperparameters of Decision Tree Regressor and Random Forest Regressor.
    
11.  **Predicting & Evaluating Models**: We make predictions using the best model (Random Forest Regressor) and evaluate its performance.
    
12.  **Conclusion**: Random Forest Regressor is selected as the best model for predicting movie revenues.
    
13.  **Sample Prediction**: We provide a sample code snippet to demonstrate how to use the trained model for prediction.