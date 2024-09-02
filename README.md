# Diwali Sales Data Analysis

## Project Overview

This project involves the analysis of Diwali sales data sourced from a CSV file on the web. The primary objective is to explore various customer-related metrics, including their occupation, buying habits, and geographical location, to uncover trends and insights that can inform business decisions. The project includes data preprocessing, cleaning, analysis, and visualization using Python libraries such as Pandas, Seaborn, and NumPy. The final conclusions are drawn based on the comprehensive analysis conducted.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Tools and Libraries](#tools-and-libraries)
- [Data Preprocessing and Cleaning](#data-preprocessing-and-cleaning)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Conclusion](#conclusion)
- [How to Run the Project](#how-to-run-the-project)

## Dataset

The dataset contains information on sales transactions during the Diwali festival, including customer demographics, transaction details, and product information. The data was sourced from a CSV file available on the web.

### Attributes:

- Customer ID: Unique identifier for each customer
- Gender: Gender of the customer
- Age: Age group of the customer
- Occupation: Profession of the customer
- Location: Geographical location of the customer
- Product Category: Category of the product purchased
- Purchase Amount: Total amount spent by the customer

## Tools and Libraries

The project leverages the following Python libraries:

- Pandas: For data manipulation and analysis
- NumPy: For numerical computations and handling arrays
- Seaborn: For statistical data visualization
- Matplotlib: For creating static, animated, and interactive visualizations
- Scikit-learn: For data preprocessing and machine learning tasks (if applicable)

## Data Preprocessing and Cleaning

### Steps:

1. Loading Data:
   - Imported the dataset from a CSV file using Pandas.
   - Verified the successful import by checking the dataset's head, tail, and summary statistics.

2. Handling Missing Values:
   - Identified missing values in critical columns.
   - Used appropriate imputation techniques, such as filling with mean/median values or dropping rows with extensive missing data.

3. Data Type Conversion:
   - Ensured all columns have the correct data types for analysis, converting types where necessary (e.g., dates to datetime format, categorical data to appropriate labels).

## Exploratory Data Analysis (EDA)

### Metrics Evaluated:

1. Customer Demographics:
   - Analyzed age distribution, gender balance, and occupation types to understand the customer base.

2. Geographical Analysis:
   - Evaluated customer distribution across various locations, identifying regions with the highest sales volume.

3. Purchase Patterns:
   - Investigated buying habits, including average purchase amount, frequency of purchases, and product preferences.

4. Customer Segmentation:
   - Grouped customers based on key attributes such as age, gender, and occupation to identify distinct customer segments.

5. Seasonal Trends:
   - Analyzed sales trends over the Diwali period, including peak sales days and product categories in high demand.

### Insights:

- The EDA revealed significant differences in purchasing habits based on occupation and location.
- Certain regions exhibited a higher propensity for purchasing specific product categories.
- Younger age groups showed a preference for certain types of products, influencing stock and marketing strategies.

### Key Findings from Visual Analysis:

- Visualizations highlighted the dominance of specific customer segments during the Diwali sale.
- Identified outlier behaviors that could indicate unique purchasing trends or data errors.
- Correlation analysis provided insights into which factors most strongly influence purchase decisions.

## Conclusion

The analysis of the sales data has revealed several key insights:

- Gender and Purchasing Power: The majority of the buyers are female, and they exhibit a higher purchasing power compared to their male counterparts.
   
- Age Demographics: The predominant age group of buyers is between 26-35 years, with females being the most significant demographic within this group.

- Geographical Insights: The highest number of orders and total sales come from the states of Uttar Pradesh, Maharashtra, and Karnataka, indicating these regions as key markets.

- Marital Status and Purchasing Behavior: A significant proportion of buyers are married women, who also demonstrate higher purchasing power, making them a crucial segment in consumer analysis.

- Occupational Distribution: Most of the buyers are professionals working in the IT, Healthcare, and Aviation sectors, suggesting that these industries could be targeted for tailored marketing strategies.

- Product Categories: The top-selling product categories include Food, Clothing, and Electronics, indicating these areas as the most popular among consumers.

These insights can significantly impact future sales strategies and customer engagement efforts, optimizing both revenue and customer satisfaction during festive seasons.

## How to Run the Project

### Prerequisites:
- Python 3.0.0
- Jupyter Notebook or any Python IDE
- Required Python libraries.
