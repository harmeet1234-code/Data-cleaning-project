# Data-cleaning-project
 
# SWYNEX Technologies – Data Cleaning & Preparation

## Data Analyst Internship – Task 1

This project was completed as part of my **Data Analyst Internship at SWYNEX Technologies**.

The objective of this task was to identify and resolve common data-quality issues in an employee dataset and prepare the data for further analysis.

---

## Dataset Overview

| Detail        | Information                 |
| ------------- | --------------------------- |
| Dataset       | Employee Dataset            |
| Total Records | 500                         |
| Total Columns | 8                           |
| Tool Used     | Microsoft Excel             |
| Task          | Data Cleaning & Preparation |

### Dataset Columns

1. Employee ID
2. Name
3. Gender
4. Age
5. City
6. Department
7. Salary
8. Email

---

## Data Cleaning Process

### 1. Missing Values

The dataset was checked for missing or blank values across all columns.

**Result:** No missing values were found in the dataset.

* Total missing values: **0**

---

### 2. Duplicate Records

The dataset was checked for:

* Duplicate complete records
* Duplicate Employee IDs

**Result:**

* Duplicate complete records: **0**
* Duplicate Employee IDs: **0**

No duplicate records were found, so no duplicate records were removed.

---

### 3. Data Type Validation

The data types of the columns were reviewed and validated.

| Column      | Data Type  |
| ----------- | ---------- |
| Employee ID | Identifier |
| Name        | Text       |
| Gender      | Text       |
| Age         | Integer    |
| City        | Text       |
| Department  | Text       |
| Salary      | Numeric    |
| Email       | Text       |

---

### 4. Inconsistent Values

Categorical values were checked for inconsistent formatting.

The **City** column contained variations caused by inconsistent capitalization, such as:

* `lahore` → `Lahore`
* `islamabad` → `Islamabad`
* `karachi` → `Karachi`
* `peshawar` → `Peshawar`
* `quetta` → `Quetta`

These values were standardized to maintain consistency throughout the dataset.

---

### 5. Email Validation

Email values were checked for consistency and proper formatting.

**Final result:** 500 out of 500 email values were properly formatted.

---

### 6. Salary Validation

The Salary column was reviewed to ensure that salary values remained numeric and suitable for analysis.

The original salary values were preserved without artificially changing the underlying data.

---

### 7. Dataset Structure

Unnecessary columns from the working dataset were removed.

The final cleaned dataset contains:

* **500 records**
* **8 relevant columns**
* Clean and structured data suitable for further analysis.

---

## Final Data Quality Check

| Check                  |               Result |
| ---------------------- | -------------------: |
| Total Records          |                  500 |
| Total Columns          |                    8 |
| Missing Values         |                    0 |
| Duplicate Records      |                    0 |
| Duplicate Employee IDs |                    0 |
| City Values            |         Standardized |
| Email Values           | 500/500 Valid Format |
| Age                    |            Validated |
| Salary                 |              Numeric |
| Extra Columns          |              Removed |

---

## Tools Used

* Microsoft Excel
* Data Cleaning
* Data Validation
* Data Standardization
* Excel Formatting

---

## Project Files

This repository contains the following project files:

* **Original Dataset** – Original employee dataset before cleaning
* **Cleaned Dataset** – Final cleaned and prepared dataset
* **Task 1 Demo** – Screen recording demonstrating the cleaning process
* **README.md** – Project documentation

---

## Key Learning

Through this project, I gained practical experience in:

* Identifying data-quality issues
* Checking missing values
* Checking duplicate records
* Validating duplicate Employee IDs
* Standardizing inconsistent values
* Validating data types
* Cleaning and structuring datasets in Excel
* Maintaining data integrity
* Preparing data for further analysis
* Documenting a data-cleaning workflow

---

## Internship Information

**Organization:** SWYNEX Technologies
**Program:** Data Analyst Internship
**Task:** Task 1 – Data Cleaning & Preparation
**Tool:** Microsoft Excel

This project is part of my Data Analytics internship journey. The upcoming tasks will involve further data analysis, visualization, dashboard development, and a final analytics project.

---

## Author

**Harmeet Singh**

Data Analytics Intern
