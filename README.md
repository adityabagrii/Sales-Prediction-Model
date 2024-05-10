# Sales-Prediction-Model

This is my group project for the course CSE342 - Statistical Machine Learning.

This model tries to predict the future sales of the Items for a store using various data columns provided in the dataset.
The dataset info is as follows:
RangeIndex: 8523 entries, 0 to 8522
Data columns (total 12 columns):
 #   Column                     Non-Null Count  Dtype  
---  ------                     --------------  -----  
 0   Item_Identifier            8523 non-null   object 
 1   Item_Weight                7060 non-null   float64
 2   Item_Fat_Content           8523 non-null   object 
 3   Item_Visibility            8523 non-null   float64
 4   Item_Type                  8523 non-null   object 
 5   Item_MRP                   8523 non-null   float64
 6   Outlet_Identifier          8523 non-null   object 
 7   Outlet_Establishment_Year  8523 non-null   int64  
 8   Outlet_Size                6113 non-null   object 
 9   Outlet_Location_Type       8523 non-null   object 
 10  Outlet_Type                8523 non-null   object 
 11  Item_Outlet_Sales          8523 non-null   float64
dtypes: float64(4), int64(1), object(7)

We first check for missing values in the dataset and then treat them accordingly.

Then, we split the training data by 80% and 20% for the training and testing sets, respectively.
We further split the training set into two training sets.

We use multiple models such as Decision Tree Regressor, Random Forest, Linear Regression, ADA Boosting and Gradient Boosting to predict the values of Item Sales. We further plot their scatter plots against true values, and we plot the accuracy of each model on a histogram using RMSE as the Loss function.
