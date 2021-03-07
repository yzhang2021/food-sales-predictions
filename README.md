# Food-Sales-Predictions
## Overview
The purpose of this project is for sales prediction for food items sold at various stores. The dataset contains the following columns: 
 1   Item_Weight               
 2   Item_Fat_Content           
 3   Item_Visibility           
 4   Item_Type                  
 5   Item_MRP                   
 6   Outlet_Identifier          
 7   Outlet_Establishment_Year  
 8   Outlet_Size                
 9   Outlet_Location_Type      
 10  Outlet_Type                
 11  Item_Outlet_Sales 

## Data Cleaning
Use imputation to replace missing values.
Fix the inconsistency of the values. Replace "LF" "low fat" with 'Low Fat" and "reg" with "Regular"

## Data Visualization
Add column for Profit to see how the variables impact profit
Make plot to show sales and profit by food item, fat content and outlet type

## Statistical Analysis
Create histogram and boxplot to show the distribution of profit
Create heatmap to show which variable is more associate with profit

## Machine Learning Model
Deal with categorical variables
Build Linear Regression and KNN model for sales prediction

## Model Comparison
Build Bagged trees and Random Forest 
Use RandomisedSearchCV to optimize hyperparameters to improve the model
