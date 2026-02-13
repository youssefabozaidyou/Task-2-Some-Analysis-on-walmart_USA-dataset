# 📊 Walmart Data Analysis - Task 2

This project is a dedicated **Data Analysis Task** focused on exploring and extracting insights from the **Walmart USA** dataset. The goal was to demonstrate proficiency in data handling, statistical exploration, and business-driven data cleaning using Python.

## 📝 Task Objectives
The primary objective of this task was to perform a deep dive into retail data to understand:
* Data structure, integrity, and statistical distribution.
* Profitability patterns and frequency analysis.
* **Portfolio Optimization**: Refining the dataset by removing non-profitable entries.

## 📂 Project Structure
The repository is organized to ensure clarity and reproducibility:
* **data/**: Contains the processed `walmart_analysis.csv` file.
* **Task 2 in Data Analysis.ipynb**: The core Jupyter Notebook containing the full analytical workflow.
* **README.md**: Documentation of the task and findings.

## 🛠️ Analysis Steps (What I did)
In this notebook, I followed a structured data analysis process:

1. **Data Loading & Setup**: Integrated the dataset using `Pandas` and handled initial data frame configurations.
2. **Exploratory Data Analysis (EDA)**:
   * Used `.head()` and `.tail()` to inspect the data boundaries.
   * Utilized **`.info()`** and **`.describe()`** to understand data types, identify null values, and analyze the statistical spread of Sales and Profit.
3. **Data Cleaning & Filtering (Loss Removal)**:
   * Analyzed the `Profit` column to identify transactions resulting in losses.
   * **Filter Implementation**: Cleaned the dataset by removing any products or transactions with zero or negative profit (`Profit <= 0`) to focus on the profitable core of the business.
4. **Targeted Data Selection**:
   * Focused on specific columns such as `City`, `Category`, `Sales`, and `Profit`.
   * Performed slicing and filtering to isolate key business metrics after the cleaning phase.
5. **Profit Frequency Analysis**:
   * Identified the **top 3 most frequent profit values** using `.value_counts().nlargest()`.
   * Identified the **bottom 3 least frequent profit values** using `.value_counts().nsmallest()`.
6. **Data Export**: Automated the creation of a local directory to save the refined, profitable-only dataset for further reporting.

## 🚀 Technologies Used
* **Python 3.x**
* **Pandas**: For data manipulation, frequency analysis, and filtering.
* **Openpyxl**: For Excel file compatibility.
* **OS Module**: For automated file system management.

## ⚙️ How to Run
1. Clone the repository.
2. Ensure you have the required libraries:
   ```bash
   pip install pandas openpyxl
