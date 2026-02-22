# Customer Data Cleansing Project

Hi! Welcome to my data cleansing project. In this project, I took a messy customer list and cleaned it up using Python and Pandas. The goal was to make the data usable for a real-world calling list.

## Project Overview
I worked with a dataset called `Customer Call List.xlsx` which had several issues like duplicate entries, inconsistent formatting, and missing values. I used a step-by-step approach to fix these problems.

## What I Did:
Here is a breakdown of the cleaning process:

1. **Removing Duplicates**: First things first, I removed any duplicate customer IDs to make sure every entry is unique.
2. **Cleaning Names**: Fixed the formatting in the `Last_Name` column by removing unnecessary characters like slashes and dots.
3. **Standardizing Phone Numbers**: 
   - Cleaned up non-numeric characters (like `/`, `-`, and `|`).
   - Formatted everything into a consistent `123-456-7890` style.
   - Handled "NaN" or "N/a" values to keep the column clean.
4. **Splitting Address**: Broke down the single `Address` string into separate columns for `Street Address`, `State`, and `Zip_Code` for better organization.
5. **Normalizing "Yes/No" Columns**: 
   - Changed "Yes" to "Y" and "No" to "N" in the `Paying Customer` and `Do_Not_Contact` columns for consistency.
6. **Filtering Data**: Removed customers who requested not to be contacted or those who didn't have a phone number at all.
7. **Final Touch**: Dropped unnecessary columns and reset the index to give the dataframe a fresh, clean look.

## Tools Used
* **Language**: Python
* **Library**: Pandas
* **Environment**: Jupyter Notebook

## Why This Matters
As a Data Analyst, I know that real data is rarely clean. This project shows my ability to handle "dirty" data and transform it into a reliable source of information for business decisions.

---
*Feel free to check out the code in the `.ipynb` file to see the full process!*
