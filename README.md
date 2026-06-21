# Excel-Data-Modeling-Project
excel power-query power-pivot data-cleaning data-modeling star-schema sales-analytics excel-dashboard
Aapke profile (**Rohit Yadav**, aspiring Data Analyst) ke hisab se GitHub README ko professional bana diya hai:

# 📊 Sales Analytics Data Model (Excel + Power Query + Power Pivot)

## 📌 Project Overview

This project demonstrates an end-to-end Sales Data Cleaning, Transformation, and Data Modeling workflow using Microsoft Excel, Power Query, and Power Pivot.

The raw sales dataset contained inconsistent values, duplicate records, mixed data formats, invalid entries, and data quality issues. Using Power Query, the data was cleaned, standardized, and transformed into an analytics-ready dataset. A Star Schema Data Model was then created using Power Pivot to support reporting and dashboard development.

---

## 🛠 Tools & Technologies

* Microsoft Excel
* Power Query
* Power Pivot
* Data Model
* Data Cleaning
* Data Transformation
* Data Modeling

---

## 🔄 Data Cleaning & Transformation

### Data Preparation

* Promoted first row as headers
* Removed duplicate records
* Removed blank rows
* Trimmed extra spaces
* Cleaned inconsistent text values

### Data Standardization

* Standardized Category values
* Standardized State names
* Standardized Product names
* Standardized Sales Channel values
* Standardized Payment Mode values
* Standardized Order Status values
* Added country code (+91) to phone numbers

### Data Type Conversion

* Order Date → Date
* Quantity → Whole Number
* Unit Price → Decimal Number
* Discount → Decimal Number
* Shipping Fee → Decimal Number

### Data Validation

* Fixed invalid values
* Removed error rows
* Handled missing values
* Corrected inconsistent formats

---

## 📈 Business Calculations

### Gross Sales

Gross Sales = Quantity × Unit Price

### Discount Amount

Discount Amount = Gross Sales × Discount

### Net Sales

Net Sales = Gross Sales − Discount Amount

### Final Sales

Final Sales = Net Sales + Shipping Fee

---

## 📅 Time Intelligence

Created the following date-based columns:

* Month
* Quarter
* Year
* Month-Year

Examples:

* Jan-2026
* Q1-2026
* 2026

---

## 🏗 Data Modeling

### Product Dimension (DimProduct)

Created a Product Master table containing:

* Product
* Category

Duplicate products were removed to ensure unique records.

### Calendar Dimension (DimCalendar)

Created a Calendar Table based on the sales date range.

Included:

* Date
* Month
* Quarter
* Year

---

## ⭐ Star Schema

DimCalendar
|
|
FactSales
|
|
DimProduct

### Relationships

DimCalendar[Date]
→ FactSales[Order Date]

DimProduct[Product]
→ FactSales[Product]

---

## 🎯 Key Skills Demonstrated

* Microsoft Excel
* Power Query
* Power Pivot
* Data Cleaning
* Data Transformation
* Data Modeling
* Star Schema Design
* Data Validation
* Analytical Thinking
* Business Reporting

---

## 🚀 Future Improvements

* Interactive Excel Dashboard
* KPI Tracking
* Sales Trend Analysis
* Customer Insights Dashboard
* Power BI Integration

---

## 👨‍💻 Author

### Rohit Yadav

Aspiring Data Analyst

**Skills:** Excel • SQL • Power BI • Python • Power Query • Power Pivot

 
