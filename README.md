# Car Rental Demand Analysis and Forecasting

## General Project Description

The project involves the analysis and forecasting of demand for cars in a rental company. The goal was to develop a predictive model that could accurately forecast future demand for cars in the rental service. All the data used in this project are fictitious and were generated under laboratory conditions. Therefore, they are not perfect and may affect some analysis results.

## Project Idea

The main goal of the project was to build a model that would predict car rental demand based on historical rental data. Such forecasts are crucial for optimizing the car fleet, minimizing costs, and improving vehicle availability for customers.

## Project Cells

### 1. Importing Libraries and Data
At the beginning of the project, necessary libraries such as Pandas, NumPy, Matplotlib, and Scikit-learn were imported. The data was loaded from a CSV file, allowing for further analysis.

### 2. Exploratory Data Analysis (EDA)
An exploratory data analysis was conducted, which included:
- Statistical summary of the data.
- Data visualizations using charts to understand the distribution and relationships between variables.

### 3. Data Preparation
Data was processed to be ready for modeling:
- Missing values were removed.
- Categorical variables were transformed into numerical ones.
- Data was split into training and testing sets.

### 4. Model Selection and Training
Various models were chosen for forecasting car rental demand, including linear regression, decision tree, and neural networks. Each model was tested, and the one with the best performance was selected.

### 5. Model Evaluation
The chosen model was evaluated using various metrics such as:
- **MSE (Mean Squared Error)**: An MSE of 80.147 indicates a relatively low error.
- **RMSE (Root Mean Squared Error)**: An RMSE of 8.952 means that the average prediction error is low.
- **MAE (Mean Absolute Error)**: An MAE of 6.943 indicates a low average difference between predicted and actual values.
- **R² (R-squared)**: An R² of 0.999484 means the model fits the data very well, explaining almost 100% of the data variability.

### 6. Conclusions
Based on the results, it can be concluded that the neural network model is highly effective in forecasting car rental demand. The model shows low values for MSE, RMSE, and MAE, indicating minimal prediction errors. The very high R² suggests that the model explains almost all the variability in the data.

## Summary
The project was successful, and the chosen predictive model achieved very good results. However, it should be noted that the data used in the project are fictitious and do not reflect actual car rental statistics. Therefore, the results may not be perfect and should be interpreted with caution.
