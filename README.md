# Layoff Analysis (SQL Project)

## Overview

The objective of this project was to walk though the data cleaning process for the layoff database.

## Skills Demonstrated

* Create staging table
* Remove duplicates
* Standarize text fields
* Convert dates
* Handle null values
* Remove helper column
* Create analytical view

## Dataset
Table: layoffs
Columns:
company text 
location text 
industry text 
total_laid_off int 
percentage_laid_off text 
date text 
stage text 
country text 
funds_raised_millions int

## Key Analysis

* Find duplicates by using row_number over partition query
* Create CTE, then staging table to remove duplicate rows
* Ensure standardized date formatting in the dataset
* Standarized spacing and handle null values

## How to Run

1. Open MySQL Workbench
2. Create database - data_cleaning
3. Upload data
4. Run the SQL script
6. Execute analysis queries
