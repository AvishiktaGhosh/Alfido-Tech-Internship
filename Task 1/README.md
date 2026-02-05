# Task 1: Sales Data Cleaning

## Data Cleaning Steps
The sales dataset was obtained from Kaggle in CSV format and initially contained missing values, inconsistent data types, and unparsed date fields. Missing values were identified and handled by removing incomplete records where necessary to ensure data consistency. The ORDERDATE column was converted into a proper datetime format to enable time-based analysis. Numeric fields such as SALES and QUANTITYORDERED were validated for correct data types, and categorical variables including PRODUCTLINE, STATE, and TERRITORY were checked for consistency. After cleaning, the dataset was saved as cleaned_sales_data.csv and used for further analysis and visualization.
