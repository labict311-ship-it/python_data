# python_data

# Seaborn Diamonds Dataset — A to Z Exploratory Data Analysis (EDA)

This repository contains a complete **Exploratory Data Analysis (EDA)** and automated insights workflow on the built-in **`diamonds`** dataset from **Seaborn** (53,940 rows and 10 columns), created in Google Colab.

## 📌 Project Overview 
The goal of this analysis is to explore the structure, quality, distributions, relationships, and key price drivers of diamonds using Python data science libraries.

### Key Steps Covered
1. **Initial Inspection:** Dataset shape, column data types, sample rows, and missing value checks.
2. **Summary & Duplicates:** Descriptive statistics (`describe()`), duplicate checks, and category value counts (`cut`, `color`, `clarity`).
3. **Data Cleaning & Feature Engineering:** Detecting invalid zero dimensions (`x == 0`, `y == 0`, or `z == 0`) and creating derived features such as approximate `volume` (`x * y * z`) and `price_per_carat`.
4. **Univariate Analysis:** Distribution of `price`, `carat`, and `cut` counts.
5. **Bivariate & Multivariate Analysis:** Relationship between `carat` and `price`, price variation across `cut`, correlation heatmap, and median price across `cut` and `color`.
6. **Automated Insights:** A Python function (`generate_diamonds_insights()`) that prints a structured summary of data quality, price/carat statistics, top correlated features, and category insights.

## 🛠️ Tech Stack
- **Python**
- **Pandas & NumPy**
- **Matplotlib & Seaborn**
- **Google Colab**

## 📂 Repository Structure
```text
├── diamonds_eda_analysis.ipynb   # Main Colab notebook with step-by-step EDA & visualizations
└── README.md                     # Project documentation
