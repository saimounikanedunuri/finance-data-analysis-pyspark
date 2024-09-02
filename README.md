# Finance Data Analysis with PySpark
## Overview
This project demonstrates how to perform financial data analysis using PySpark. It involves aggregating data and applying window functions to analyze and visualize financial transactions. The dataset used contains 50 records of financial transactions, including categories such as salary, groceries, utilities, rent, and entertainment.

## Project Structure
The project consists of the following key components:

1. Data Loading: Load and prepare the financial dataset.
2. Data Cleaning: Ensure the data is in the correct format for analysis.
3. Aggregations: Compute aggregate statistics by category and location.
4. Window Functions: Apply window functions to calculate running totals and moving averages.
5. Time Series Analysis: Analyze monthly totals for insights into financial trends.

## Dataset
The dataset includes the following columns:

=> transaction_id: Unique identifier for each transaction.
=> transaction_date: Date of the transaction.
=> amount: Amount of money spent or earned.
=> category: Category of the transaction (e.g., Salary, Groceries).
=> location: Location where the transaction took place (e.g., New York, Los Angeles).

### Sample Data:
![image](https://github.com/user-attachments/assets/7de36828-7664-4945-aa0b-44a0f4905340)

## Features
## 1. Aggregations
=> Total Amount by Category and Location: Computes the total, average, maximum, and minimum amounts spent or earned by category and location.
=> Total Amount by Month: Aggregates the total amount for each month and location.

## 2. Window Functions
Running Total by Location: Calculates the cumulative total amount for each location, considering all preceding transactions up to the current row.
7-Day Moving Average by Location: Computes the 7-day moving average of transaction amounts for each location.

## How to Run
### 1. Set Up Environment:
Ensure you have PySpark installed. You can install it via pip if necessary
pip install pyspark

### 2. Run the Project:
Clone the repositor
[git clone https://github.com/yourusername/finance-data-analysis.git](https://github.com/saimounikanedunuri/finance-data-analysis-pyspark)

Navigate to the project directory
cd finance-data-analysis

Open a PySpark session and execute the provided script to load the data, perform aggregations, and apply window functions.

### 3. Review Results:
The results of aggregations and window functions will be printed directly, showing insights into financial data.

## Example Output
## Total Amount by Category and Location
![image](https://github.com/user-attachments/assets/d8cc8657-196c-49de-a96c-289bd14c537d)

## Running Total by Location
![image](https://github.com/user-attachments/assets/31e1a443-85d0-48ea-aef4-2252c85069d2)

## Contributing
Feel free to open issues or pull requests if you have suggestions or improvements. Contributions are welcome!
