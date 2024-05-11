# Sales Prediction Model

## Introduction

This repository contains the code for a group project completed for the course CSE342 - Statistical Machine Learning. The goal of this project is to predict the future sales of items for a store using various data columns provided in the dataset.

## Dataset Information

The dataset contains information on items sold in a store. It has the following columns:

- `Item_Identifier`: Unique identifier for each item
- `Item_Weight`: Weight of the item (some values are missing)
- `Item_Fat_Content`: Fat content of the item
- `Item_Visibility`: Visibility of the item in the store
- `Item_Type`: Type of the item
- `Item_MRP`: Maximum Retail Price of the item
- `Outlet_Identifier`: Unique identifier for each outlet
- `Outlet_Establishment_Year`: Year of establishment of the outlet
- `Outlet_Size`: Size of the outlet (some values are missing)
- `Outlet_Location_Type`: Location type of the outlet
- `Outlet_Type`: Type of the outlet
- `Item_Outlet_Sales`: Sales of the item in the outlet

## Preprocessing

1. **Handling Missing Values**: Missing values in columns `Item_Weight` and `Outlet_Size` are treated accordingly.
   
2. **Data Splitting**: The training data is split into 80% training set and 20% testing set. The training set is further split into two subsets.

## Models Used

The following machine learning models are used for prediction:

1. Decision Tree Regressor
2. Random Forest
3. Linear Regression
4. ADA Boosting
5. Gradient Boosting

Later feature selection and feature scaling is performed to increase the accuracy in decision trees, which drastically affects the accuracies of all models.

It increases the accuracy of Decision Trees and Random Forests but decreases the accuracy of the rest models.

## Evaluation
- Plot of mean and median replaced values against orginal dataset.
- Plot of interpolation replaced values against original dataset.
- Scatter plots are generated to visualize the predictions of each model against true values.
- Correlation Matrix and feature importance graph is plotted.
- The accuracy of each model is plotted on a histogram using Root Mean Squared Error (RMSE) as the loss function.
- Other evaluation metrics like MAE, MSE, RMSE are also used to compare the results.

## Contributors

- Aditya Bagri - 2022029
- Suyash Kumar - 2021293
