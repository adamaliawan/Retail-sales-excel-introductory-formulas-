# Retail Sales Data Analysis Project

This project is an introductory exploration into retail sales data using Excel formulas. The dataset used contains transaction-level data for a retail business, allowing for the application of basic Excel functions and formulas to gain insights. This project demonstrates proficiency in using Excel for data analysis, focusing on fundamental formulas and calculations.

## Project Overview

The main goals of this project are to:
- Showcase the use of Excel to handle a retail sales dataset.
- Apply introductory formulas to analyze sales, commissions, and product categories.
- Provide a structured approach to understanding and interpreting retail sales data.

## Dataset

The dataset consists of two sheets:
1. **Retail Sales Dataset**:
   - Contains detailed information about each transaction, such as transaction date, customer details, product type, quantity sold, and total sales.
   - Includes calculated commissions for 2023 and 2024.

   | Column Name          | Description                                          |
   |----------------------|------------------------------------------------------|
   | Transaction ID       | Unique identifier for each transaction               |
   | Date                 | Date of the transaction                              |
   | Customer ID          | Unique identifier for each customer                  |
   | Gender               | Gender of the customer                               |
   | Age                  | Age of the customer                                  |
   | Product              | Product name                                         |
   | Quantity             | Number of units sold                                 |
   | Price per Unit        | Price of each unit                                   |
   | Total Sales          | Total sales value for the transaction                |
   | Commission 2023      | Commission earned in 2023                            |
   | Commission 2024      | Commission earned in 2024                            |

2. **Transactions**:
   - Summarizes the total sales for each transaction and categorizes products into specific categories.

   | Column Name          | Description                                          |
   |----------------------|------------------------------------------------------|
   | Transaction ID       | Unique identifier for each transaction               |
   | Total Sales          | Total sales value                                    |
   | Product Category     | The category of the product sold                     |

## Key Excel Formulas Used
- **SUM**: To calculate the total sales for specific product categories and periods.
- **AVERAGE**: To find the average sales value across all transactions.
- **IF**: Used for conditional logic to calculate commissions based on sales thresholds.
- **VLOOKUP**: Applied to fetch data from the secondary 'Transactions' sheet for detailed analysis.
- **PIVOT TABLES**: Used to summarize data across different dimensions like product categories and customer demographics.

## Key Insights
- A breakdown of sales performance by product category.
- A commission calculation for two consecutive years (2023 and 2024).
- Basic sales trends over time (monthly or yearly breakdowns).

## How to View the Project
- Download the Excel file from this repository.
- Open the file in Excel and explore the various formulas and analyses applied within the dataset.
- Utilize the built-in pivot tables to further explore different segments of the data.

## Future Enhancements
- Automating the analysis using Excel macros.
- Expanding the dataset to include additional customer demographics for more detailed segmentation.
- Creating visual dashboards for easier interpretation of the data.
