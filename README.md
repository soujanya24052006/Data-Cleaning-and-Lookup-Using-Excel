# Data-Cleaning-and-Lookup-Using-Excel
Excel project focused on data cleaning, fixing data quality issues, and resolving VLOOKUP errors using proper lookup techniques.

 Excel Data Cleaning & Transformation Project

##  Project Overview

This project focuses on cleaning and transforming a production dataset using Microsoft Excel. The dataset contained multiple data quality issues such as inconsistent values, duplicate entries, and lookup mismatches.

The goal was to standardize the data and ensure accurate mapping using Excel functions like VLOOKUP

## Problem Statement

The dataset had the following issues:

* Multiple ages for the same manager
* Missing values (`#N/A`) during lookup
* Inconsistent data across sheets
* Lookup failures due to incorrect referencing
* 
##  Steps Performed

### 1. Data Cleaning

* Removed inconsistencies in manager names
* Checked for duplicate entries
* Standardized data across sheets

### 2. Handling Lookup Errors

* Identified `#N/A` errors in VLOOKUP
* Fixed lookup issues by:

  * Ensuring exact match of values
  * Cleaning text using TRIM/CLEAN
  * Locking table array using `$`

### 3. Correct VLOOKUP Implementation

Used the following formula:

```excel
=VLOOKUP(D2,Sheet1!$A$2:$B$11,2,FALSE)
```

### 4. Key Fix Applied

* Locked lookup range using `$` to prevent shifting
* Ensured consistent data mapping from master sheet

---

## 📈 Outcome

* Successfully mapped correct age for each manager
* Eliminated `#N/A` errors
* Improved data consistency and reliability


## Skills Demonstrated

* Data Cleaning
* Data Validation
* Excel Functions (VLOOKUP, TRIM, CLEAN)
* Debugging Excel Errors
* Data Transformation


##  Future Improvements

* Replace VLOOKUP with XLOOKUP for better performance
* Automate cleaning using Power Query
* Add dashboard visualization



##  Files Included

* `transformation_removing_data_qulity_issues.xlsx`

 

 
