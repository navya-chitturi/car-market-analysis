# Car Market Analysis

## Project Overview

This project analyzes used car market data from Car Dekho to identify patterns and factors that influence used car selling prices.

The analysis focuses on selling prices based on fuel type, seller type, transmission type, ownership, manufacturing year, kilometers driven, and present price.

## Objectives

- Analyze the distribution of used car selling prices.
- Compare selling prices across different fuel types.
- Compare selling prices between dealer and individual sellers.
- Analyze the effect of transmission type on selling price.
- Study relationships between numerical variables and selling price.
- Identify important factors associated with used car prices.

## Dataset

The dataset contains used car information with the following columns:

- Car_Name
- Year
- Selling_Price
- Present_Price
- Kms_Driven
- Fuel_Type
- Seller_Type
- Transmission
- Owner

After data cleaning, the dataset contains **299 records and 9 columns**.

## Data Cleaning

The dataset was checked for:

- Missing values
- Duplicate records

No missing values were found, and duplicate records were removed before analysis.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## Analysis Performed

The project includes:

- Selling Price Distribution
- Present Price vs Selling Price
- Fuel Type vs Selling Price
- Seller Type vs Selling Price
- Transmission Type vs Selling Price
- Manufacturing Year vs Selling Price
- Kilometers Driven vs Selling Price
- Correlation Heatmap

## Key Findings

- Diesel cars have the highest average selling price at **10.10 lakhs**.
- Dealer-sold cars have a higher average selling price (**6.63 lakhs**) than individually sold cars (**0.87 lakhs**).
- Automatic cars have a higher average selling price (**9.07 lakhs**) than manual cars (**3.92 lakhs**).
- Present Price has a strong positive correlation with Selling Price (**0.876**).
- Year has a positive correlation with Selling Price (**0.234**).
- Kms Driven has a very weak correlation with Selling Price (**0.029**).
- Owner has a weak negative correlation with Selling Price (**-0.088**).

## Project Files

- `Untitled13.ipynb` – Complete Python analysis notebook.

## Conclusion

The analysis shows that Present Price is strongly associated with used car Selling Price. Fuel type, seller type, and transmission type also show noticeable differences in average selling prices within the dataset.
