# Housing Price Prediction using Linear Regression

This project uses a dataset (`housing.csv`) containing various features of residential houses to predict their market price using a Linear Regression model.
The goal is to understand how different factors such as area, number of rooms, and amenities impact housing prices, and to build a regression model to make price predictions.

## Dataset Overview

The dataset includes the following columns:

| Column           | Description                                       | Type        |
|------------------|---------------------------------------------------|-------------|
| price            | Target variable - house price (in ₹)              | Numeric     |
| area             | Area in square feet                               | Numeric     |
| bedrooms         | Number of bedrooms                                | Numeric     |
| bathrooms        | Number of bathrooms                               | Numeric     |
| stories          | Number of floors                                  | Numeric     |
| mainroad         | House has access to main road (yes/no)            | Categorical |
| guestroom        | Has guest room (yes/no)                           | Categorical |
| basement         | Has basement (yes/no)                             | Categorical |
| hotwaterheating  | Has hot water heating (yes/no)                    | Categorical |
| airconditioning  | Has air conditioning (yes/no)                     | Categorical |
| parking          | Number of parking spaces                          | Numeric     |
| prefarea         | Located in a preferred residential area (yes/no)  | Categorical |
| furnishingstatus | Furnishing type: unfurnished, semi-furnished, furnished | Categorical |


##  Project Workflow

1. Import Libraries
   - pandas, numpy, matplotlib, seaborn, sklearn

2. Load and Explore Data
   - View data structure, check for missing values

3. Preprocessing
   - Encode binary (yes/no) columns
   - Apply One-Hot Encoding to furnishingstatus
   - Ensure all features are numeric

4. Train-Test Split
   - Split dataset into training (80%) and testing (20%)

5. Model Training
   - Use LinearRegression from sklearn

6. Evaluation
   - MAE (Mean Absolute Error)
   - MSE (Mean Squared Error)
   - R² Score (Model Accuracy)

7. Visualization
   - Scatter plot of actual vs predicted prices
   - Interpretation of model coefficients


##  Sample Output

- Coefficient Interpretation
- Evaluation Metrics
- Regression Plot



