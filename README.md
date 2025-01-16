# House Sales in King County, USA

## Project Description
This project focuses on predicting house prices in King County, USA, using regression techniques. The primary objective is to analyze the dataset, identify key factors influencing house prices, and build models to achieve accurate price predictions.

---

## Dataset
The dataset contains information about house sales in King County, USA, including detailed features about the houses sold between May 2014 and May 2015.

### Key Columns:
- **id**: Unique identifier for each house.
- **date**: Date of the sale.
- **price**: Sale price of the house.
- **bedrooms**: Number of bedrooms.
- **bathrooms**: Number of bathrooms.
- **sqft_living**: Living area size in square feet.
- **sqft_lot**: Lot size in square feet.
- **floors**: Number of floors in the house.
- **waterfront**: Indicates if the house has a waterfront view.
- **view**: Number of times the house was viewed.
- **condition**: Condition of the house (scale of 1-5).
- **grade**: Overall grade given to the house (scale of 1-13).
- **sqft_above**: Square footage of the house apart from the basement.
- **sqft_basement**: Square footage of the basement.
- **yr_built**: Year the house was built.
- **yr_renovated**: Year the house was renovated (if applicable).
- **zipcode**: ZIP code of the house.
- **lat**: Latitude coordinate.
- **long**: Longitude coordinate.
- **sqft_living15**: Living area size of the 15 nearest neighbors.
- **sqft_lot15**: Lot size of the 15 nearest neighbors.

---

## Objectives
1. Perform exploratory data analysis to understand the dataset and uncover patterns.
2. Identify key factors that influence house prices.
3. Build regression models to predict house prices.
4. Compare the performance of different models and select the best-performing one.

---

## Project Structure
The project consists of the following files:

- **`houseprice_pred.ipynb`**: Jupyter Notebook containing the analysis, feature engineering, and model building processes.
- **Dataset**: The dataset used for the analysis, available on [Kaggle](https://www.kaggle.com/code/malakhossam1/houseprice-pred).

---

## Analysis Overview
### Data Cleaning
- Handled missing values.
- Corrected data types where necessary.
- Identified and removed outliers.

### Exploratory Data Analysis (EDA)
- Distribution of house prices and key features.
- Correlation analysis to identify relationships between variables.
- Analysis of the impact of features like **sqft_living**, **grade**, and **location** on house prices.

### Modeling
- **Linear Regression**: Built a baseline model.
- **XGBoost**: Implemented an advanced gradient boosting model for improved accuracy.
- Evaluated models using metrics like Mean Absolute Error (MAE) and R-squared.

---

## Results
- Key insights and relationships were identified from the data analysis.
- **XGBoost** outperformed **Linear Regression** in terms of predictive accuracy.

---

## Insights and Recommendations
1. Houses with higher **grade**, **sqft_living**, and **view** tend to have higher prices.
2. Properties with waterfront views command a significant premium.
3. Renovations and newer houses positively impact house value.
