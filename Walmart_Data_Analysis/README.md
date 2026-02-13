\# 📊 Walmart Data Analysis - Task 2



This project is a dedicated \*\*Data Analysis Task\*\* focused on exploring and extracting insights from the \*\*Walmart USA\*\* dataset. The goal was to demonstrate proficiency in data handling, statistical exploration, and business-related calculations using Python.



\## 📝 Task Objectives

The primary objective of this task was to perform a deep dive into retail data to understand:

\* Data structure and integrity.

\* Profit distribution and frequency.

\* Sales performance and transaction-level details.



\## 📂 Project Structure

The repository is organized to ensure clarity and reproducibility:

\* \*\*data/\*\*: Contains the processed `walmart\_analysis.csv` file.

\* \*\*Task 2 in Data Analysis.ipynb\*\*: The core Jupyter Notebook containing the full analytical workflow.

\* \*\*README.md\*\*: Documentation of the task and findings.



\## 🛠️ Analysis Steps (What I did)

In this notebook, I followed a structured data analysis process:



1\. \*\*Data Loading \& Setup\*\*: Integrated the dataset using `Pandas` and handled initial data frame configurations.

2\. \*\*Exploratory Data Analysis (EDA)\*\*:

&nbsp;   \* Used `.head()` and `.tail()` to inspect the data boundaries.

&nbsp;   \* Utilized `.info()` and `.describe()` to understand data types and statistical distributions.

3\. \*\*Targeted Data Selection\*\*:

&nbsp;   \* Focused on specific columns such as `City`, `Category`, `Sales`, and `Profit`.

&nbsp;   \* Performed slicing and filtering to isolate key business metrics.

4\. \*\*Profit Analysis\*\*:

&nbsp;   \* Identified the \*\*top 3 most frequent profit values\*\* using `.nlargest()`.

&nbsp;   \* Identified the \*\*bottom 3 least frequent profit values\*\* using `.nsmallest()`.

&nbsp;   \* Analyzed unique value counts to understand profit consistency.

5\. \*\*Data Export\*\*: Automated the creation of a local directory to save the cleaned analysis for further reporting.



\## 🚀 Technologies Used

\* \*\*Python 3.x\*\*

\* \*\*Pandas\*\*: For data manipulation and frequency analysis.

\* \*\*Openpyxl\*\*: For Excel file compatibility.

\* \*\*OS Module\*\*: For automated file system management.



\## ⚙️ How to Run

1\. Clone the repository.

2\. Ensure you have the required libraries:

&nbsp;  ```bash

&nbsp;  pip install pandas openpyxl

