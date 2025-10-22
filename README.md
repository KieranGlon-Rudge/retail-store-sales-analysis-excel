# retail-store-sales-analysis-excel

## Project Overview
This project involves cleaning and analyzing a retail store sales dataset in Excel. Starting from raw data, I applied transformations to create a clean dataset, generated summaries using formulas and pivot tables, and visualized insights with charts. This demonstrates skills in data cleaning, formula-based calculations, pivot analysis, and business reporting – key for entry-level data/business analyst roles.

## Tools Used 
- **Excel formulas:** XLOOKUP, CONCAT, SUMIFS, SUMPRODUCT, UNIQUE, SORT
- **Features:** Conditional formating, tables & pivot tables with pivot charts

## Changes Made to the Dataset
1. **Converted into a table**: Formatted the raw data as an Excel table for easier filtering and referencing.
2. **Froze the top row (Column Names)**: Locked the header row for better navigation in large datasets.
3. **Removed any duplicate rows based on unique "Transaction ID"**: Used Remove Duplicates tool to ensure data integrity.
4. **Using Find & Select to find all blanks in Price Per Unit replaced with the result of Total Spent/Quantity**: Calculated missing prices via formula (e.g., =[Total Spent]/[Quantity]) and filled blanks.
5. **Using Find & Select to find all blanks in Discount Applied replaced with UNKNOWN (Centered)**: Filled missing values with "UNKNOWN" and centered the text for consistency.
6. **Created Item Value and Item Category tables using UNIQUE and use XLOOKUP to create their respective columns**: Extracted unique values with UNIQUE function, then used XLOOKUP to populate new columns based on item codes.
7. **Created the Item Cleaned column using CONCAT("Item_",Item Value,"_",Item Category)**: Standardized item names with CONCAT for better categorization.
8. **Created the Total Sales by Category section with a drop down and SUMIFS from the drop down**: Added a dropdown (Data Validation) and used SUMIFS to dynamically sum sales by selected category.
9. **Created the Total Sales by Customer section with a drop down and SUMPRODUCT from the drop down**: Similar to above, but used SUMPRODUCT for flexible conditional summing based on dropdown selection.
10. **Created pivot tables to show Sales by customer, Date and Category**: Built three pivot tables for aggregated views (e.g., total sales grouped by customer, quarterly by date, % by category).
11. **Created pivot charts to visualise the different tables**: Added bar/line charts linked to pivots (e.g., bar chart for % Sales by Category, line chart for Sales by Quarter).

