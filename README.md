# Overview
This project analyzes purchasing card (P-Card) transactions for Oklahoma State University (OSU) in 2014. The goal is to identify policy violations, fraudulent activities, and spending patterns by applying data analysis techniques to transaction records.
# Data Structure
PCard data for each fiscal year from 2010 to 2015. The dataset is ~350 megabytes containing 6 files, 2,281,562 rows of data, and consistent columns but inconsistent formats.
The analysises were conducted on 2014 dataset.
# Key Features
## Data Cleaning & Preprocessing
#### Standardized date formats, text fields, and numerical values.
#### Removed unnecessary columns to optimize the dataset.
#### Converted financial data into proper numeric types for analysis.
## Exploratory Data Analysis (EDA)
#### Identify high-value transactions and monthly spending trends.
![Image](https://github.com/user-attachments/assets/f771d921-3cde-4282-a7e2-68b57f3bb69e)
#### Rank top vendors and employees with the most transactions.
![Image](https://github.com/user-attachments/assets/fd0f727b-ac91-444c-9c75-54ef8eab22cb)
#### Total amount spent by category
![Image](https://github.com/user-attachments/assets/d5825d10-6aa1-462c-a5bb-b9e8d58ad473)
## Internal Control Tests
#### $10,000 Monthly Limit Test: Flag employees exceeding monthly spending limits.
![Image](https://github.com/user-attachments/assets/212d904e-dc21-436d-b4b6-0e6592c9f10f)
#### $5,000 Single Purchase Limit Test: Detect possible split transactions attempting to bypass limits.
![Image](https://github.com/user-attachments/assets/8b63c562-6e9a-4582-9bbc-3b39be8464e7)
## Fraud Detection
#### Benford’s Law Analysis: Check if transaction distributions followed natural patterns.
![Image](https://github.com/user-attachments/assets/42510de8-ecea-4705-929c-443eb00f1e4f)
#### Duplicate Transactions: Check if the credit card company makes a mistake or a vendor submits a payment twice.
![Image](https://github.com/user-attachments/assets/35edfe03-3541-4092-92d1-74a92f6442a6)
#### Worst Offenders: List 10 employees with the most violations.
![Image](https://github.com/user-attachments/assets/65d4fdcd-f8e5-42ec-ae6e-f16fc9e6d36c)
## Insights
