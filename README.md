# Indian Bike Sales Dataset (Cleaned & Processed)

This repository contains a cleaned, transformed, and feature-engineered version of the Indian Bike Sales dataset, ready for data analysis, visualization, and machine learning projects.

## 📊 Dataset Overview
- **Total Rows:** 500 (Cleaned subset)
- **Format:** CSV (`bike_sales_india.csv`)
- **Domain:** Automotive / E-commerce Sales Analysis

## 🛠️ Data Processing Steps Performed
The dataset has undergone the following preprocessing stages using Python (Pandas):

1. **Data Cleaning:**
   - Removed all missing and null values.
   - Dropped duplicate records to ensure data accuracy.
2. **Data Transformation:**
   - Cleaned string columns by removing unwanted whitespaces.
3. **Feature Engineering:**
   - **Bike_Age:** Calculated the age of the bike based on the current year (2026 minus the Registration Year).
   - **Price_Per_CC:** Created a new metric evaluating resale price relative to engine capacity.

## 📂 File Structure
- `bike_sales_india.csv`: The final processed dataset containing 500 rows with newly added features.

## 🚀 How to Use in Python
You can easily load this cleaned dataset directly into your Google Colab or Jupyter Notebook using the GitHub Raw link:



url = "PASTE_YOUR_GITHUB_RAW_LINK_HERE"
df = pd.read_csv(url)

# Display the first few rows
print(df.head())
