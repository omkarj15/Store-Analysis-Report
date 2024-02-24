# Store-Analysis-Report

## Overview
The Store Analysis Report project aims to provide insights into store data using ETL/ELT processes, unsupervised machine learning techniques, and Tableau visualization. The project involves data extraction, transformation, and loading, followed by the application of unsupervised ML algorithms to identify loyal customers. Additionally, it includes the creation of a Tableau dashboard for business insights.

## Project Structure

The project follows a Medalian Architecture, organized into the following directories:

## ETL Process

1. **Data Scrapping:**
   - Data is extracted from the MS SQL Database using Python scripts.
   - Raw data is stored in the `DataStorage/Bronze` folder in parquet format.

2. **Data Cleaning (Silver):**
   - Duplicates are treated, missing values are handled, and noise data is checked.
   - Cleaned data is saved in the `DataStorage/Silver` folder in parquet format.

3. **Data Transformation (Gold):**
   - Further data transformation is performed, resulting in the final format.
   - Transformed data is saved in the `DataStorage/Gold` folder in parquet format.

## Unsupervised Machine Learning
- Unsupervised ML algorithms, such as RFM (Recency, Frequency, Monetary) analysis, are applied to identify loyal customers.
- Python scripts in the `ML_Models` folder implement the ML algorithms and group customers based on their behavior.

## Tableau Dashboard
- A Tableau dashboard is created to visualize insights derived from the data analysis.
- The Tableau dashboard files are located in the `Tableau_Dashboard` folder.

