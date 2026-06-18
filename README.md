Sales Data Cleaning and EDA

End-to-end data cleaning and exploratory data analysis on a dirty cafe sales dataset using Python and Pandas.


Project Overview

This project demonstrates a complete data cleaning and analysis pipeline on a real-world dirty dataset. The raw data contains missing values, junk entries, incorrect data types, and inconsistent formatting — all common issues in client and research datasets. The goal was to clean the data systematically, engineer useful features, and extract actionable business insights through visualization.


Dataset


Source: Cafe Sales — Dirty Data for Cleaning Training (Kaggle)
Raw shape: 10,000 rows × 8 columns
Clean shape: 9,909 rows × 11 columns
Time period: January 2023 – December 2023
Total revenue analyzed: $88,443


##  Project Structure
```text
sales-data-cleaning-and-eda/
│
├── data/
│   ├── dirty_cafe_sales.csv      # Original raw dataset (never modified)
│   └── cafe_sales_cleaned.csv    # Cleaned dataset after preprocessing
│
├── 01_exploration.ipynb          # Data profiling and issue identification
├── 02_cleaning.ipynb             # Complete data cleaning workflow
├── 03_visualization.ipynb        # Exploratory Data Analysis (EDA) and insights
├── requirements.txt              # Project dependencies
└── README.md                     # Project documentation
```
