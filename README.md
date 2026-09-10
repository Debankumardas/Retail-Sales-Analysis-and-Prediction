# Retail Sales Analysis and Prediction Using Python and Machine Learning

## Project Overview

This project analyzes retail sales data to identify patterns in sales, profit, products, categories, regions, and time periods.

Exploratory Data Analysis (EDA) is performed using Python, Pandas, Matplotlib, and Seaborn. Machine learning models are then developed to predict sales and compare their performance.

## Objectives

- Understand and clean retail transaction data
- Analyze sales and profit trends
- Identify high-performing categories and products
- Analyze regional and monthly sales patterns
- Investigate relationships between sales, profit, quantity, and discount
- Build machine learning models for sales prediction
- Compare Linear Regression and Random Forest models
- Generate business recommendations

## Dataset

The project uses a Superstore retail dataset obtained from Kaggle.

The dataset contains 10,194 records and 21 columns covering order, customer, product, geographical, sales, quantity, discount, profit, and date information.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Machine Learning Models

### Linear Regression

MAE: 266.08  
RMSE: 710.02  
R²: 0.0343

### Random Forest

MAE: 210.73  
RMSE: 628.03  
R²: 0.2444

Random Forest performed better than Linear Regression across all three evaluation metrics.

## Key Findings

- Technology recorded the highest sales and profit among the three categories.
- Furniture generated substantial sales but comparatively low profit.
- The West region recorded the highest sales.
- The South region recorded the lowest sales.
- Canon imageCLASS 2200 Advanced Copier was the top product by both sales and profit.
- Quantity was the most important feature in the Random Forest model.

## Business Recommendations

- Focus on high-performing Technology products.
- Investigate the low profitability of Furniture.
- Examine factors contributing to lower sales in the South region.
- Maintain availability of high-performing products.
- Use machine learning as a decision-support tool for sales planning.

## Project Structure

```text
retail-sales-analysis-and-prediction/
│
├── data/
├── notebook/
    └── retail_sales_analysis.ipynb
