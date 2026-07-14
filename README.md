# Sales Data Analysis Project

**CloudExify Summer Internship 2026 — Project 1** **Date:** July 15, 2026

**Intern ID:** `[CX-INT-2026-DS-0178]`

---

## Project Overview

This project focuses on performing **Exploratory Data Analysis (EDA)** and generating business intelligence from a retail sales dataset. Over the course of this project, I engineered a robust data pipeline using Python inside Jupyter Notebook to load, clean, analyze, and visualize transactional sales data.

---

## What I Did Today (Key Milestones)

### 1. Environment & Workspace Setup

* Configured and launched a local **Jupyter Notebook** environment to serve as the development playground.


* Installed and imported critical scientific computing and visualization libraries, specifically `pandas`, `NumPy`, and `matplotlib`.



### 2. Data Loading & Initial Exploration (EDA)

* Loaded the primary `sales_data.csv` dataset using `pandas`.


* Inspected the raw structure of the dataset utilizing `.head()`, `.shape`, and `.info()` to understand columns, dimensions, and data types.


* Checked class balance using `.value_counts()` to look at sales frequency across products.



### 3. Rigorous Data Cleaning

* Identified and handled missing values using `.dropna()` to ensure mathematical operations run without errors.


* Found and pruned redundant rows with `.drop_duplicates()`.


* Converted the date series into a standardized datetime format using `pd.to_datetime()`.



### 4. Mathematical & Descriptive Statistics

* Calculated vital statistics on sales revenue, including:
* **Mean (Average) Sale Value** 
* **Median (Middle) Sale Value** 
* **Standard Deviation (Spread of Sales)** 
* Grouped transactional records by product category to calculate total revenue generated and physical unit volumes sold.



### 5. Advanced Visualizations (Matplotlib)

Built and exported three key graphical figures:

1. **Top 10 Products (Bar Chart)**: Visualized best-selling products ranked by revenue.
2. **Monthly Sales Trends (Line Plot)**: Traced overall performance progression over a 6-month period.
3. **Sales Distribution by Region (Pie Chart)**: Analyzed geographic market share percentages across the North, East, South, and West regions.



### 6. Automated Reporting

* Built an automated script to format and compile the computed data statistics into a final text file (`report.txt`) in my local workspace.



---

## 📂 Repository Structure

Your repository should look like this:

```bash
├── sales_analysis.ipynb   # My completed Jupyter Notebook containing code & charts
├── sales_data.csv         # The raw dataset used for analysis
├── report.txt             # The generated plaintext summary report
└── README.md              # Project documentation (this file)

```
