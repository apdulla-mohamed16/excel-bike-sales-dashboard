# 🚲 Bike Sales Data Analysis & Interactive Excel Dashboard

## 📌 Project Overview
This project focuses on analyzing customer demographics and purchasing behavior to identify key trends in bike sales. Using **Microsoft Excel**, the raw dataset was cleaned, transformed, and analyzed to build an interactive dashboard that helps stakeholders understand what drives customer purchasing decisions.

## 🎯 Objectives
* Clean and standardize raw customer and sales data.
* Analyze the relationship between customer demographics (income, age, commute distance, marital status, gender, and region) and bike purchases.
* Build a dynamic, user-friendly Excel dashboard with interactive slicers for quick data exploration.

## 🛠️ Tools & Techniques Used
* **Microsoft Excel**
  * **Data Cleaning:** Removed duplicates, standardized text formatting (e.g., `M`/`F` to `Male`/`Female`, `M`/`S` to `Married`/`Single`), and handled missing values.
  * **Feature Engineering:** Used nested `IF` formulas to group continuous age data into distinct **Age Brackets** (*Adolescent*, *Middle Age*, *Old*) for clearer segmentation.
  * **Pivot Tables & Charts:** Summarized key metrics and built dynamic visualizations (Bar Charts, Line Charts, and Column Charts).
  * **Interactive Slicers:** Added slicers for *Marital Status*, *Region*, and *Education* to allow real-time filtering across the entire dashboard.

## 📂 Repository Structure
```text
├── data/
│   └── Bike_Sales_Raw_Data.xlsx      # Original uncleaned dataset
├── dashboard/
│   └── Bike_Sales_Dashboard.xlsx     # Cleaned data, Pivot Tables, and final Dashboard
├── assets/
│   └── dashboard-preview.png         # Screenshot of the interactive dashboard
└── README.md                         # Project documentation
