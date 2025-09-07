# House Price Prediction

**Author:** Genius Technology Center  
**Objective:** Build a machine learning model to predict California house prices.

## Project Description

This project uses a dataset of California housing data to predict the median house value. The notebook performs the full machine learning workflow:

- Load the dataset (`housing.csv`)  
- Explore the data  
- Preprocess numeric and categorical features manually  
- Train Linear Regression and Random Forest models  
- Evaluate model performance using RMSE and R²  
- Display feature importances  
- Save the trained model and preprocessing for later use  

## Dataset

The dataset contains the following columns:

- `longitude` – geographic coordinate  
- `latitude` – geographic coordinate  
- `housing_median_age` – median age of houses in the block  
- `total_rooms` – total number of rooms  
- `total_bedrooms` – total number of bedrooms  
- `population` – population in the block  
- `households` – number of households  
- `median_income` – median income in block  
- `median_house_value` – target variable (house price)  
- `ocean_proximity` – categorical feature indicating proximity to ocean  

## Requirements

- Python 3.x  
- pandas  
- numpy  
- scikit-learn  
- matplotlib  
- joblib  

Install dependencies via pip:

```bash
pip install pandas numpy scikit-learn matplotlib joblib
