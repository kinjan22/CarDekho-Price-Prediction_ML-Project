# CarDekho-Price-Prediction_ML-Project
This project analyzes a dataset of 15,411 used cars from the CarDekho platform to understand the factors affecting used car prices and build a predictive model for price estimation.  We use EDA (Exploratory Data Analysis), feature engineering, and machine learning to identify key trends and insights.

## Project Statement
The used car market in India is a dynamic and ever-changing landscape. Prices can fluctuate wildly based on a variety of factors including the make and model of the car, its mileage, its condition and the current market conditions. As a result, it can be difficult for sellers to accurately price their cars.

## Project Workflow
Data Loading & Exploration.
* Load dataset using pandas.
* Display basic statistics using .info(), .describe(), and .head().
* Check for missing values.
  
## Data Cleaning & Preprocessing
* Convert vehicle_age to numerical format.
* Remove unnecessary columns like car_name and brand.
* Fill missing values in numerical columns with mean/median.
* Convert categorical columns (fuel_type, transmission_type, seller_type) using One-Hot Encoding.

## Exploratory Data Analysis (EDA)
* Univariate Analysis
Step: Visualizing distributions using histograms, boxplots, and KDE plots
* Bivariate Analysis 
Step: Scatter plots & correlation analysis
* Multivariate Analysis
  
## Feature Engineering
Create new feature: price_per_km = selling_price / km_driven
Remove redundant columns (e.g., car_name)
Normalize features using StandardScaler()

## Conclusion & Business Impact
Key Findings:
* Age and Mileage negatively impact resale price.
* Engine Power and Fuel Type are key factors in pricing.
* Random Forest provides the most accurate predictions.
  
## Business Impact:
* Car dealerships can use this model to set competitive prices.
* Buyers can estimate fair market value before purchasing a used car.
* CarDekho can improve their pricing algorithm for better user experience.

## Technologies Used
* Python (Data Processing & Analysis)
* Pandas & NumPy (Data Handling)
* Seaborn & Matplotlib (Data Visualization)
* Scikit-Learn (Machine Learning)

