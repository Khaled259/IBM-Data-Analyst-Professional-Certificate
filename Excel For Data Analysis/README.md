# 🧮 Excel for Data Analysis – Final Assignment (Parts 1 & 2)

## 📚 Course
**IBM Data Analyst Professional Certificate**  
Module: Excel for Data Analysis  
Assignment: Peer-Graded Final Assignment – Parts 1 & 2  

---

## 🧾 Assignment Overview

This project simulates the work of a Junior Data Analyst in a local government office. You're tasked with cleaning, preparing, and analyzing inventory data for a fleet of government vehicles. This is completed in two parts:

- **Part 1** focuses on **data cleaning** and preparation.
- **Part 2** focuses on **pivot table analysis** using the cleaned data.

All work is performed using **Excel for the Web**, a browser-based spreadsheet tool recommended for consistency with course labs.

---

## 📁 Files

| File | Description |
|------|-------------|
| `Montgomery_Fleet_Equipment_Inventory_FA_PART_1_START.csv` | Raw dataset (as provided) |
| `Montgomery_Fleet_Equipment_Inventory_FA_PART_1_END.xlsx` | Cleaned dataset after Part 1 |
| `Montgomery_Fleet_Equipment_Inventory_FA_PART_2_START.xlsx` | Cleaned dataset ready for pivot analysis |
| `Montgomery_Fleet_Equipment_Inventory_FA_PART_2_END.xlsx` | Final file with pivot tables from Part 2 |

---

## ✅ Part 1: Data Cleaning Tasks

1. **Convert File to .XLSX**  
   - Converted from `.csv` to `.xlsx` using Excel for the Web.

2. **Adjust Column Widths**  
   - Ensured all data is visible in cells.

3. **Remove Empty Rows**  
   - Used filter and manual inspection.

4. **Remove Duplicate Records**  
   - Used Excel’s `Remove Duplicates` feature.

5. **Correct Spelling Mistakes**  
   - Manually reviewed and fixed obvious typos.

6. **Whitespace Cleanup**  
   - Removed all double-spaces using Find & Replace.

7. **Fix Department Name Splits**  
   - Used `Flash Fill` to merge department names spread across two columns.
   - Removed the extra columns.

---

## 📊 Part 2: Data Analysis with Pivot Tables

1. **Format Data as Table**  
   - Applied Excel’s "Format as Table" styling to the dataset.

2. **AutoSum Calculations on Column C**  
   - Calculated and recorded:
     - **SUM**
     - **AVERAGE**
     - **MIN**
     - **MAX**
     - **COUNT**

3. **Create First Pivot Table**
   - Rows: `Department`
   - Values: `Equipment Count` (SUM)
   - Sorted in descending order.

4. **Create Two More Identical Pivot Tables**
   - Duplicated structure of the original pivot table into two additional worksheets.

5. **Modify Second Pivot Table**
   - Added `Equipment Class` **below** `Department` in rows.
   - Collapsed all groups except `Transportation`.

6. **Modify Third Pivot Table**
   - Added `Equipment Class` **above** `Department` in rows.
   - Collapsed all groups except `CUV`.

---

## 🔧 Tools Used

- **Excel for the Web**
- Core Features:
  - Table Formatting
  - Filter & Sort
  - Remove Duplicates
  - Flash Fill
  - Find & Replace
  - Pivot Tables
  - AutoSum

---

## 📝 Learning Outcomes

- Data cleaning and preparation using spreadsheet tools
- Familiarity with Excel’s built-in data wrangling features
- Creation and manipulation of pivot tables
- Understanding of categorical grouping and aggregation

---

## 🔗 Dataset Source

Public Domain Dataset:  
[Montgomery County Fleet Equipment Inventory](https://data.montgomerycountymd.gov/Government/Fleet-Equipment-Inventory/93vc-wpdr)  
(*Modified version used in course*)

---

## 📥 How to Use This Project

1. Clone or download this repository.
2. Open the `.xlsx` files in Excel (preferably Excel for the Web).
3. Review each worksheet and pivot table.
4. Reproduce the steps if you're learning Excel or prepping for certification.

---

## 💡 Notes

This project is part of the final peer-graded assignment in the IBM Data Analyst Certificate course on Excel. It demonstrates foundational skills in spreadsheet-based data analysis, useful in entry-level analyst roles across industries.

