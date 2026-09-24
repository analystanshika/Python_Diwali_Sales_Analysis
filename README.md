# Python_Diwali_Sales_Analysis
Diwali Sales Analysis using Python, Pandas, Matplotlib and Seaborn to analyze customer behavior, sales trends and product performance.

## Overview

This project focuses on analyzing Diwali sales data using Python to understand customer purchasing behavior and identify meaningful sales patterns.

The analysis includes data cleaning, exploratory data analysis (EDA), and data visualization using Python libraries. The project explores customer demographics, location, occupation, product categories, orders, and purchase amounts.

## Objectives

- Clean and prepare the raw sales dataset for analysis.
- Understand customer purchasing patterns.
- Analyze sales across gender and age groups.
- Identify important states and occupations based on sales activity.
- Analyze product categories and customer demand.
- Create visualizations to communicate key findings.
- Generate business-oriented insights from the data.

## Dataset

The dataset contains **11,251 records and 15 columns** initially.

After data cleaning, the dataset contains **11,239 records and 13 columns**.

Key columns include:

- `User_ID`
- `Cust_name`
- `Product_ID`
- `Gender`
- `Age Group`
- `Age`
- `Marital_Status`
- `State`
- `Zone`
- `Occupation`
- `Product_Category`
- `Orders`
- `Amount`

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Data Cleaning

The following cleaning steps were performed:

1. Imported the required Python libraries.
2. Loaded the CSV dataset using Pandas.
3. Inspected the dataset using `shape`, `head()`, and `info()`.
4. Removed completely blank columns (`Status` and `unnamed1`).
5. Checked for missing values.
6. Removed 12 records with missing values in the `Amount` column.
7. Converted the `Amount` column from float to integer.

## Exploratory Data Analysis

The project analyzes:

- Gender-wise sales and order activity
- Age-group purchasing behavior
- Marital-status-based sales patterns
- State-wise sales performance
- Occupation-wise sales activity
- Product-category performance
- Product and order trends

## Key Business Questions

- Which gender contributes more to sales?
- Which age group has the highest purchasing activity?
- Which states generate higher sales?
- Which occupations contribute significantly to sales?
- Which product categories are most popular?
- Which products receive higher order activity?
- Which customer segments show stronger purchasing behavior?

## Project Workflow

```text
Raw Dataset
    ↓
Data Loading
    ↓
Data Inspection
    ↓
Data Cleaning
    ↓
Exploratory Data Analysis
    ↓
Data Visualization
    ↓
Business Insights
```

## Results & Insights

The analysis is used to identify major customer segments, high-performing regions, purchasing patterns, and popular product categories.

The exact numerical findings and visual insights are available in the Jupyter Notebook included in this repository.

## Project Structure

```text
Diwali-Sales-Analysis/
│
├── Diwali Sales Data.csv
├── Diwali_Sales_Analysis.ipynb
└── README.md
```

## How to Run

1. Clone or download this repository.
2. Open `Diwali_Sales_Analysis.ipynb` in Jupyter Notebook or JupyterLab.
3. Make sure `Diwali Sales Data.csv` is in the same project folder.
4. Install the required libraries if needed:

```bash
pip install pandas numpy matplotlib seaborn
```

5. Run the notebook cells from top to bottom.

## Skills Demonstrated

- Python
- Data Cleaning
- Pandas
- NumPy
- Exploratory Data Analysis
- Data Visualization
- Matplotlib
- Seaborn
- Data Aggregation
- Business Insights

## Conclusion

This project demonstrates an end-to-end Python-based exploratory data analysis workflow using real-world retail sales data. It showcases practical skills in data cleaning, analysis, visualization, and extracting business-oriented insights from data.

