# Day 01 – Restaurant Data Exploration and Analysis

## Project Overview

This project is my first practical exercise in data analytics. I used Python and Pandas to explore restaurant transaction data and understand basic business patterns.

The analysis focuses on customer bills, tips, party sizes, dining periods, and activity across different days of the week.

## Project Objectives

- Understand the structure of a real-world dataset.
- Inspect rows, columns, data types, and summary statistics.
- Check for missing values and duplicate records.
- Calculate basic restaurant business metrics.
- Create a tip percentage column.
- Compare restaurant activity across days and dining periods.
- Practise explaining data findings in business terms.

## Dataset

**Dataset:** Seaborn Tips Dataset

The dataset contains 244 restaurant transactions and 7 columns:

| Column | Description |
|---|---|
| total_bill | Total amount of the restaurant bill |
| tip | Tip amount |
| sex | Recorded customer gender category |
| smoker | Smoking status category |
| day | Day of the week |
| time | Lunch or dinner |
| size | Number of people in the dining party |

**Dataset attribution:** [Seaborn Tips Dataset](https://github.com/mwaskom/seaborn-data/blob/master/tips.csv)

## Tools and Technologies

- Python
- Pandas
- NumPy
- Jupyter Notebook
- Git and GitHub

## Analysis Performed

### 1. Initial Data Exploration
- Loaded the CSV file using Pandas.
- Inspected the first and last records.
- Checked dataset dimensions and column names.
- Reviewed data types and descriptive statistics.

### 2. Data Quality Checks
- Checked columns for missing values.
- Checked for duplicate records.
- Identified one duplicate record in the dataset.
- Kept the original records unchanged during this exercise.

### 3. Business Metric Calculations

Calculated:
- Total bill amount.
- Average bill amount.
- Average tip amount.
- Maximum dining party size.
- Tip percentage for each transaction.

### 4. Group-Based Analysis

Compared:
- Total bill amount by day.
- Average tip by day.
- Average bill during lunch and dinner.
- Average tip and tip percentage between smoker groups.
- Daily revenue and estimated customer counts.

## Key Findings

The analysis produced the following observations:

- The dataset contains 244 transactions and 7 columns.
- The total bill amount across all records is approximately 4,827.77 dataset currency units.
- The average bill is approximately 19.79.
- The average tip is approximately 3.00.
- Saturday has the highest total bill amount at 1,778.40.
- Sunday has the highest average bill at approximately 21.41.
- Sunday also has the highest average tip at approximately 3.26.
- Average bills are higher during dinner (approximately 20.80) than lunch (approximately 17.17).
- The average tip percentage is approximately 15.93% for non-smokers and 16.32% for smokers.

These are descriptive observations from this dataset, not proof that one factor causes another.

## Business Understanding

The results demonstrate why total revenue and average spending should be examined separately.

For example, Saturday generates the highest total bill amount, while Sunday has the highest average bill. A business analyst should consider both transaction volume and average transaction value when evaluating restaurant performance.

The smoker comparison also shows why tip amounts and tip percentages are different measures.

## Skills Practised

- Python fundamentals
- Pandas DataFrame operations
- Dataset inspection
- Basic data quality checks
- Aggregation using `groupby()`
- Calculating business metrics
- Interpreting analytical results
- Communicating findings

## Project Structure

```text
Day-01/
├── Day_01_Restaurant_Data_Analysis.ipynb
├── tips.csv
└── README.md
```

## How to Run This Project

1. Clone or download the repository.
2. Install Python and Pandas.
3. Open the notebook in VS Code or Jupyter Notebook.
4. Make sure `tips.csv` is in the same folder as the notebook.
5. Run the notebook cells from beginning to end.

Install the required libraries:

```bash
pip install pandas numpy jupyter
```

## Learning Progress

**Learning challenge:** 20 Days of Data Analytics

**Day completed:** Day 01 – Data Exploration with Pandas

This project represents the beginning of my practical data analytics portfolio. Future projects will build on these foundations by introducing data cleaning, SQL, statistics, visualization, and business problem-solving.