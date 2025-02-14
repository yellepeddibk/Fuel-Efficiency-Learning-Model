# Fuel-Efficiency Learning Model

## Overview
This project utilizes automobile data to predict the fuel efficiency (measured in city MPG) of vehicles based on their price. By analyzing the relationship between price and fuel efficiency, I apply various machine learning techniques, including linear regression and polynomial regression, to build and evaluate predictive models.

The project includes data cleaning, exploratory data analysis, and the development of regression models. Additionally, it includes test scenarios to demonstrate the model's performance and limitations.

---

## Features
- **Data Preprocessing**:
  - Removal of vehicles with diesel engines for a focused analysis.
  - Handling missing values by replacing them with column medians for consistency.
  - Conversion of string-based numerical data to numeric formats for proper processing.

- **Data Visualization**:
  - Scatter plots to visualize relationships between variables.
  - Box plots and histograms to explore data distribution.

- **Machine Learning Models**:
  - **Linear Regression**: Establishes a basic predictive model for city MPG.
  - **Polynomial Regression**: Enhances the model for a better fit to the data.

- **Performance Metrics**:
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - Coefficient of Determination (R²)

- **Test Scenarios**:
  - Predicting city MPG for vehicles priced at $15,000, $35,000, and $60,000.
  - Observations highlight the model's accuracy and limitations with extrapolated data.

---

## Requirements
To run this project, you need the following Python libraries:
- pandas
- numpy
- scikit-learn
- seaborn
- matplotlib

Install the dependencies using:
```bash
pip install pandas numpy scikit-learn seaborn matplotlib
