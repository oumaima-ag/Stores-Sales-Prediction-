# Stores-Sales-Prediction-
This project focuses on predicting weekly sales in physical retail stores using machine learning techniques. The primary goal is to develop a predictive model that can accurately forecast the weekly sales for various retail stores.
# Stores Sales Prediction Notebook

This Jupyter Notebook provides a step-by-step guide to predicting weekly sales in physical retail stores. The objective is to develop and evaluate a predictive model for forecasting weekly sales based on various features.

## Step 1: Import Libraries and Load Data

- Import necessary libraries for data analysis, visualization, and modeling.
- Load the dataset from an Excel file using the pandas library.

## Step 2: Data Exploration and Visualization

- Display the first few rows of the dataset to get a sense of the data.
- Display general information about the dataset, including data types and missing values.
- Compute summary statistics of numerical features.
- Visualize relationships between features using pairplots and correlation heatmaps.
- Create boxplots and histograms to analyze the distribution of categorical and numerical variables.
- Visualize the relationship between specific features and the target variable using scatter plots and histograms.
- Visualize average weekly sales per store using bar plots.

## Step 3: Data Preprocessing and Feature Engineering

- Extract year, month, and day from the date column.
- Perform advanced feature engineering by creating a new feature "days_since_start" representing the number of days since the beginning of the dataset.
- Standardize numerical features using the StandardScaler.
- Select specific features based on insights gained from visualization.

## Step 4: Model Selection and Hyperparameter Tuning

- Split the data into training and testing sets.
- Train an XGBoost model with initial hyperparameters.
- Evaluate the model's performance using root mean squared error (RMSE) and R-squared (R2) score.
- Evaluate the final model's performance on the test set and visualize predicted vs. actual values.
- Calculate feature importance and create a bar plot to visualize it.
- Create a residual plot to analyze the model's residuals.
- Perform cross-validation to assess model performance using different folds and calculate mean and standard deviation of RMSE and R2 scores.
- Perform hyperparameter tuning using GridSearchCV for the XGBoost model.
- Print the best parameters and the performance metrics of the tuned model.

## Step 5: Model Improvement using Ensembling

- Add additional models (Random Forest, Linear Regression, LightGBM) to create a Stacking ensemble model.
- Define hyperparameters for the Stacking model, including those specific to LightGBM.
- Perform hyperparameter tuning using GridSearchCV.
- Get the best Stacking model from the grid search.
- Make predictions using the best Stacking model.
- Calculate and print the RMSE for the Stacking model.
- Save predictions to an output Excel file.

## Conclusion

This notebook guides you through the process of predicting weekly sales in retail stores using data preprocessing, feature engineering, model selection, hyperparameter tuning, and ensembling techniques.

For questions or further information, feel free to contact OUMAIMA AGOURAM at oumaimaagouram@gmail.com.

