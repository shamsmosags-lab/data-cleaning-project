# Data Cleaning Project

A beginner-friendly data cleaning project using Python and Pandas to identify and fix common data quality issues in a customer dataset.

## Project Overview

This project demonstrates the process of preparing messy customer data for reliable analysis.

The dataset intentionally contains common data quality problems such as missing values, duplicate records, inconsistent text formatting, and unrealistic age values.

## Data Quality Problems

The original dataset contained:

* Missing values in Age and Total_Spending
* Duplicate customer records
* Inconsistent Gender formatting
* Inconsistent City formatting
* An unrealistic age value

## Cleaning Process

The project includes:

1. Inspecting the dataset
2. Detecting missing values
3. Handling missing numerical values using the median
4. Removing duplicate records
5. Standardizing Gender values
6. Standardizing City names
7. Detecting unrealistic ages
8. Replacing invalid age values with the median
9. Performing a final data quality check
10. Creating a simple spending analysis by city

## Final Results

After cleaning:

* Missing values: 0
* Duplicate rows: 0
* Valid age range: 22–41
* Gender values: Male, Female
* Cities: Cairo, Giza, Alexandria
* Final dataset size: 9 rows × 6 columns

## Business Insights

* Giza has the highest total customer spending at 3,120.
* Cairo is very close to Giza with total spending of 3,100.
* Alexandria has the lowest total customer spending at 1,560.
* The cleaned dataset is ready for reliable customer analysis.
* Standardizing data improves the reliability of future business decisions.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Google Colab
* Data Cleaning
* Data Analysis

## Project Structure

```text
data-cleaning-project/
│
├── Data_Cleaning_Shams_Mosa.ipynb
└── README.md
```

## Author

Shams Mosa

Aspiring Data Scientist & Data Analyst
