# Pandas Analyzer & Data Visualization

## Project Overview

Pandas Analyzer & Data Visualization is a Python-based project developed to analyze and visualize sales data. This project uses Pandas and NumPy for data manipulation and analysis, Matplotlib for data visualization, and Seaborn for creating advanced statistical visualizations.

The main objective of this project is to help users understand sales data, identify patterns, perform mathematical operations, generate statistical reports, and create meaningful visualizations that support business decision-making.

## Objectives

- Analyze sales data using Python.
- Perform data cleaning and preprocessing.
- Handle missing values and duplicate records.
- Perform mathematical and statistical operations.
- Search, sort, and filter sales records.
- Generate pivot tables and aggregated summaries.
- Create different types of data visualizations.
- Save charts and analyzed datasets for future use.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- CSV Dataset

## Project Structure

pandas_sales_analyzer/

├── main.py

├── requirements.txt

├── README.md

├── data/

│   └── sales_data.csv

└── outputs/

    ├── project_report.pdf

    ├── cleaned_sales_data.csv

    ├── sales_pivot_table.csv

    ├── bar_sales_by_region.png

    ├── line_sales_trend.png

    ├── boxplot_sales_by_region.png

    └── heatmap_correlation.png

## Features

### 1. Load Dataset
- Load sales data from CSV files.
- Handle file errors during data loading.

### 2. Explore Data
- Display the first five rows.
- Display the last five rows.
- Display column names.
- Display data types.
- Display basic dataset information.

### 3. DataFrame Operations
- Perform mathematical operations.
- Calculate total and average sales.
- Create additional calculated columns.
- Combine multiple DataFrames.
- Split datasets based on regions or other categories.

### 4. Handle Missing Data
- Identify missing values.
- Fill missing numerical values using the median.
- Fill missing categorical values using the mode.
- Remove duplicate records.
- Handle invalid dates and negative sales values.

### 5. Descriptive Statistics
- Calculate mean and median.
- Calculate standard deviation and variance.
- Calculate minimum and maximum values.
- Calculate percentiles.
- Generate descriptive statistical summaries.

### 6. Data Visualization
The project supports the following visualizations:

- Bar Plot
- Line Plot
- Scatter Plot
- Pie Chart
- Histogram
- Stack Plot
- Seaborn Heatmap
- Box Plot

### 7. Save Results
- Save cleaned datasets as CSV files.
- Save pivot tables.
- Save split datasets.
- Export visualizations as PNG images.

## Dataset Information

The project includes a sample synthetic sales dataset containing 60 records.

The dataset includes the following columns:

- SalesID: Unique sales record identification number.
- Date: Date of the sales transaction.
- Product: Name of the product.
- Region: Sales region.
- Sales: Total sales amount.
- Profit: Profit generated from sales.
- Year: Year of the transaction.

## Installation and Setup

### Step 1: Install Python

Install Python 3.9 or above on your computer.

### Step 2: Download the Project

Download or clone the project repository to your computer.

### Step 3: Open the Project Folder

Open the project folder using VS Code, PyCharm, or any Python-supported IDE.

### Step 4: Install Required Libraries

Open the terminal and execute the following command:

pip install -r requirements.txt

### Step 5: Run the Project

Execute the following command:

python main.py

### Step 6: Load the Dataset

When the program starts, select option 1 and enter the following dataset path:

data/sales_data.csv

After successfully loading the dataset, you can use the menu options to perform different data analysis and visualization operations.

## Output

The project generates different outputs, including:

- Dataset information and summaries.
- Cleaned sales data.
- Statistical analysis results.
- Regional sales comparisons.
- Product-wise sales analysis.
- Pivot tables.
- Different graphical visualizations.
- PDF project report.

All generated files are stored in the outputs folder.

## Conclusion

The Pandas Analyzer & Data Visualization project demonstrates how Python can be used for real-world data analysis and visualization.

It provides practical experience in working with Pandas, NumPy, Matplotlib, and Seaborn. It also demonstrates object-oriented programming concepts, data cleaning, data manipulation, statistical analysis, and visualization techniques.

This project helps users understand sales performance, identify useful patterns, and present analytical results in an understandable format.

## Future Improvements

- Add an interactive graphical user interface.
- Connect the application to a database.
- Add more advanced statistical analysis.
- Support larger datasets.
- Generate automated business reports.
- Add interactive dashboards.

## Author

Name: [Your Name]

Project: Pandas Analyzer & Data Visualization

Language: Python
