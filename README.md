
# Sales Store Analysis and Prediction

## Overview
This project focuses on analyzing and predicting store sales based on various features such as store area, items available, and daily customer count. The goal is to build and evaluate different regression models to predict store sales and understand the relationships between the features.

## Dataset
The dataset used in this project consists of the following columns:
- `Store ID`: Identifier for the store
- `Store_Area`: Area of the store in square feet
- `Items_Available`: Number of items available in the store
- `Daily_Customer_Count`: Daily customer count for the store
- `Store_Sales`: Sales amount for the store

## Project Structure
1. **Data Preprocessing**
   - Load the dataset and check for null values.
   - Display basic statistics of the dataset.
   - Analyze the correlation between different variables.

2. **Exploratory Data Analysis**
   - Visualize the distribution of each feature using histograms.
   - Plot scatter plots to understand the relationships between `Store_Sales` and other features.

3. **Outlier Detection**
   - Calculate z-scores to identify outliers in the dataset.

4. **Regression Modeling**
   - Split the data into training and testing sets.
   - Train and evaluate Linear Regression, Ridge Regression, and Lasso Regression models.
   - Calculate and display performance metrics such as Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared (R2) for each model.

5. **Model Evaluation**
   - Perform cross-validation to assess the robustness of the models.
   - Conduct hyperparameter tuning using Grid Search for the Ridge Regression model.
   - Analyze residuals to understand the errors in predictions.
   - Visualize the actual vs. predicted sales and the distribution of residuals.
### Conclusion
This project demonstrates how to analyze and predict store sales using various regression techniques. The analysis shows that while Store_Area and Items_Available are highly correlated, the overall model performance indicates there are other factors influencing store sales that need to be considered for better predictions.

## Installation
To run this project, you need to have Python installed along with the following libraries:
- pandas
- scikit-learn
- matplotlib
- seaborn

You can install these libraries using pip:
```bash
pip install pandas scikit-learn matplotlib seaborn
