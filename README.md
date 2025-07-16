# 📊 Excel Data Cleaning & Sales Analysis Project

## 🚀 Overview

This project demonstrates **data cleaning, analysis, and visualization** of a messy e-commerce sales dataset using **Excel**. It is designed to practice structured data cleaning techniques, exploratory data analysis, and basic visualization workflows in preparation for **data analyst and business analyst roles**.

---

## 🗂️ Dataset

- **Source:** Synthetic 100-row e-commerce dataset with intentional errors for practice.
- **Columns:**
  - OrderID
  - OrderDate
  - CustomerID
  - ProductCategory
  - ProductName
  - Quantity
  - UnitPrice
  - TotalPrice

---

## 🧹 Data Cleaning Process

✅ **OrderID:**
- Checked for duplicates and corrected/removed them.
- Ensured all IDs started with "O" and had consistent length.

✅ **OrderDate:**
- Converted all text dates to valid Excel date formats (MM/DD/YYYY).
- Corrected impossible dates (e.g., "13/32/2025").
- Standardized date formatting across the dataset.

✅ **CustomerID:**
- Ensured no missing values.
- Checked for consistent "C" prefix and numeric IDs.

✅ **ProductCategory:**
- Checked for typos and corrected invalid categories.
- Valid categories: Electronics, Books, Clothing, Home, Sports.

✅ **ProductName:**
- Validated alignment with ProductCategory and corrected mismatches.

✅ **Quantity:**
- Ensured numeric and positive values.
- Replaced non-numeric entries (e.g., "five" → 5).

✅ **UnitPrice:**
- Ensured numeric and positive values.
- Corrected negative and non-numeric entries (e.g., "twenty" → 20).

✅ **TotalPrice:**
- Verified that `TotalPrice = Quantity * UnitPrice`.
- Recalculated and replaced incorrect or missing values.

---

## 📈 Data Analysis

Using **Excel PivotTables**, the following analyses were conducted:

- **Total Sales by Product Category:** Identified which categories contributed the most to revenue.
- **Top 5 Products by Sales:** Ranked products by total sales value.
- **Monthly Sales Trends:** Analyzed sales patterns over time.
- **Average Order Value:** Computed average sales per order.
- **Orders per Customer:** Counted the number of orders per customer for segmentation.

---

## 📊 Visualizations

Charts created in Excel:
- **Column Chart:** Total Sales by ProductCategory.
- **Column Chart:** Products by total sales.
- **Line Chart:** Monthly sales trend to identify seasonality and growth patterns.

---

## 🛠️ Tools Used

- **Microsoft Excel:** For cleaning, analysis, and visualization.
- **Git & GitHub:** For version control and portfolio sharing.

---

## ✨ Key Learnings

- Developed a systematic approach for cleaning messy datasets in Excel.
- Gained experience in identifying and correcting invalid data entries.
- Strengthened skills in using PivotTables and charts for exploratory analysis.
- Practiced documenting and sharing analysis projects on GitHub for portfolio visibility.

---

## 📂 Files

- `Ecommerce_Data_Cleaned.xlsx`: Cleaned dataset with analysis and visualizations.
- `README.md`: Project documentation (this file).

---

## 🔗 How to View

1. Download `Ecommerce_Data_Cleaned.xlsx` from this repository.
2. Open in **Microsoft Excel**.
3. Navigate to:
   - The **cleaned data tab** for reference.
   - The **PivotTables and charts tab** for interactive analysis exploration.
   - The **README tab inside the Excel file** for in-sheet documentation.

---

## 🤝 Connect

If you have questions about this project or would like to discuss potential opportunities, feel free to connect:

- **LinkedIn:** [Your LinkedIn Profile Link]
- **Email:** [Your Email Address]

---

## 🪄 Future Improvements

- Automate parts of the cleaning workflow using Power Query.
- Add a VBA macro to automate recalculation of TotalPrice.
- Explore advanced Excel charts for better storytelling.
- Extend analysis with external datasets for category enrichment.

---

## 📜 License

This project is provided for **learning and demonstration purposes**.

---

### ⭐ If you find this helpful for your learning, consider starring the repository to support more structured, clear data practice materials for new analysts.
