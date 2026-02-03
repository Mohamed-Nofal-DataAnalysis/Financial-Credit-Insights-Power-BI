# 🚀 Financial & Operational Insights Dashboard

A comprehensive **Power BI** dashboard designed to analyze credit card performance, client demographics, and credit limit distributions across three decades (1990 - 2020).

---

## ⚙️ Project Overview
This project transforms complex financial datasets into actionable insights using advanced DAX modeling and professional UX design. It focuses on:
* **Credit Performance:** Tracking limits and risk.
* **Operational Trends:** Monitoring card issuance and security features.
* **Demographics:** Understanding customer profiles and age groups.

---

## 🛠️ Technical Deep Dive

### 1. Data Engineering Process
* **Data Ingestion:** Cleaned and transformed credit/client data using **Power Query**, ensuring types for credit limits and dates were optimized.
* **Star Schema Design:** Implemented a robust data model linking transaction facts with dimensions like Card Brands, Card Types, and Time.
* **UI/UX Design:** Used a professional "White & Maroon" theme with high-contrast visuals for executive-level reporting.

### 2. Data Model Details
The model is built to handle historical data efficiently using:
* **Fact Table:** Core metrics like Credit Limits and Client IDs.
* **Dimension Tables:** Includes `Year/Calendar`, `Card Brand` (Amex, Discover, Mastercard, Visa), and `Card Type` (Credit, Debit, Prepaid).
* **Relationships:** Optimized **One-to-Many (1:*)** relationships for precise filter propagation.

---

## 🔢 Technical Achievement: Advanced DAX
Calculated using **Data Analysis Expressions (DAX)** to provide real-time insights:
* **Financial Aggregations:** Dynamic calculation of `AVERAGE` and `MAX` Credit Limits.
* **Operational Metrics:** Measures for **Average Customer Age (9.74 years)** and **Average PIN Changes**.
* **Proportional Logic:** DAX formulas to determine the percentage of chipped vs. non-chipped cards.

---

## 📊 Dashboard Visuals & Interactivity

### Key Visuals:
* **KPI Cards:** Summaries for Total Credit Limit (**$88.2M**) and Max Credit Limit (**$151.2K**).
* **Dual-Axis Line Chart:** Tracks the correlation between Total Clients and Total Credit Limit by Year.
* **Donut Chart:** Visualizes chip technology adoption (**89.49%** adoption rate).
* **Clustered Column Charts:** Comparative analysis of limits across brands and card types.

### Interactive Slicers:
* **Year Slicer:** Vertical selection for historical trend analysis.
* **Card Brand & Type:** Quick
