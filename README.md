# House-price-
This project analyzes the King County housing dataset and performs a machine learning model to predict housing prices. The dataset includes various features like the number of bedrooms, bathrooms, square footage, and other house-related characteristics.

## Dataset

The dataset used is *King County House Sales* which includes information about houses sold in King County, USA. The data contains 21 columns and 21613 rows with no missing values.

## Steps Followed

1. *Data Loading*  
   Loaded the data using pandas and explored the dataset.

2. *Data Exploration*  
   Basic statistical analysis using functions like df.describe(), df.info(), and checking for null values with df.isnull().sum().

3. *Data Preprocessing*  
   - Dropped unnecessary columns like id, date, zipcode, yr_built, and yr_renovated.
   - Changed the data type of price from float to integer.

4. *Visualization*  
   - Used seaborn and matplotlib to plot histograms, scatter plots, and pair plots for feature understanding.
   - Plotted heatmap for feature correlation.

5. *Outlier Removal*  
   Removed outliers using the IQR (Interquartile Range) method.

6. *Modeling*  
   - Target variable: price
   - Features: sqft_living, bedrooms, bathrooms
   - Split data into training and testing sets with a ratio of 67:33.
   - Implemented *Linear Regression* to predict housing prices.
   - Used performance metrics like *Mean Absolute Error (MAE), **Mean Squared Error (MSE), and **R-squared (R²)* to evaluate the model.

## Results

- *Mean Absolute Error (MAE)*: test_1
- *Mean Squared Error (MSE)*: test_2
- *R-squared (R²)*: test_3

## Requirements

- Python 3.x
- Libraries:
  - numpy
  - pandas
  - matplotlib
  - seaborn
  - scikit-learn
