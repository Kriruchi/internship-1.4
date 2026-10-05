# Task 3: Sales Prediction using Linear Regression

## Project Overview
This project predicts future sales revenue based on historical sales data using a Linear Regression model.

## Dataset
- File: Cleaned_Sales_Data.xlsx
- Records: 24 months (2024-01 to 2025-12)
- Columns: Date, Revenue, Profit, Region, Department

## Methodology
1. Created and cleaned sales data
2. Split data into Train (80%) and Test (20%) using train_test_split with random_state=42
3. Trained Linear Regression model
4. Evaluated model performance

## Model Used
Linear Regression

## Results
- R2 Score: 0.95
- MAE (Mean Absolute Error): 2124.50

The R2 Score of 0.95 indicates the model explains 95% of the variance in revenue, showing high accuracy.

## Visualization
File: regression.png
The graph shows Actual vs Predicted Revenue, confirming the model follows the upward sales trend correctly.

## Files in this Repository
1. Cleaned_Sales_Data.xlsx - Cleaned dataset
2. regression.png - Actual vs Predicted graph
3. Task3_Sales_Prediction.ipynb - Google Colab code.
