# Bike Sales Dashboard

This project focuses on analyzing data from a Bike Buyers dataset in Excel. The objective was to clean and organize the data, create meaningful pivot tables, and design an interactive dashboard for exploring customer insights.

## Project Overview

- **Data Cleaning**: Conducted various data cleaning tasks using a working sheet to avoid overwriting the original data.
- **Pivot Tables & Charts**: Developed three key pivot tables to examine income, commute distance, and age brackets.
- **Interactive Dashboard**: Created a dashboard with slicers that allow users to filter data by marital status, region, and education level.

## Key Features

### 1. Data Cleaning
- **Gender**: Replaced `M`/`F` values with `Male` and `Female` for clarity.
- **Age Brackets**: Added an `Age Brackets` column to categorize ages into:
  - **Adolescent**: 18–30
  - **Middle Age**: 31–50
  - **Old**: 51+
- Created a working sheet to perform cleaning operations like categorizing data and renaming columns, ensuring the main dataset remained unchanged.

### 2. Pivot Tables & Charts
- **Pivot 1: Average Income per Purchase**
  - **Description**: Displays the average income of customers who purchased or did not purchase a bike.
  - **Chart Type**: Bar chart with a gender legend for further breakdown.
  
- **Pivot 2: Customer Commute Distance**
  - **Description**: Shows customer commute distance compared to bike purchases (Yes/No).
  - **Chart Type**: Line chart with two lines representing purchased vs. not purchased.
  
- **Pivot 3: Customer Age Bracket**
  - **Description**: Analyzes bike purchases across different age brackets (Adolescent, Middle Age, Old).
  - **Chart Type**: Bar chart with a legend for bike purchase (Yes/No).

### 3. Dashboard Overview
The dashboard includes:
- **Three Pivot Charts**:
  - Average Income per Purchase
  - Customer Commute Distance
  - Customer Age Bracket
- **Three Slicers** for filtering:
  - **Marital Status**: Filter data by married or single customers.
  - **Region**: Filter by geographic region (Europe, Pacific, etc.).
  - **Education**: Filter by education level (Bachelors, Graduate Degree, High School, Partial College, Partial High School).

### 4. Files
- **bike_sales_dashboard.xlsx**: Contains the pivot tables, visuals, and the dashboard.
- **working_sheet.xlsx**: Data cleaning sheet where data was cleaned without altering the original dataset.
