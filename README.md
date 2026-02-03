# 🚀 Financial & Operational Insights Dashboard

A high-level **Power BI** dashboard designed to analyze credit card performance, client demographics, and operational efficiency across three decades (1990–2020).

---

## ⚙️ Project Structure & Technical Deep Dive

### Process (Data Engineering & Business Intelligence)

1. **Data Ingestion & ETL:** Utilized Power Query (M Language) to clean and transform raw financial datasets, ensuring consistency in credit limits and client demographics.
2. **Star Schema Architecture:** Designed a high-performance data model that separates transactional facts from descriptive dimensions such as Time, Card Brand, and Card Type.
3. **DAX Engineering:** Implemented complex calculations to track Total Credit Exposure ($88.2M), operational averages, and security adoption (Chip vs. Non-Chip).
4. **UX/UI Professional Design:** Crafted a cohesive "Maroon & White" theme, using strategic white space and visual hierarchy to highlight critical KPIs.
5. **Interactive Analytics:** Deployed synchronized slicers and dynamic filtering to allow cross-category exploration.

---

## ⚙️ Data Model

The data model follows a **Star Schema** design to ensure speed and scalability for long-term historical analysis.

* **Fact Table:** Contains the core financial transactions, total credit limits, and client IDs.
* **Dimension Tables:** Includes **Calendar (1990-2020)**, **Card_Brand** (Visa, Mastercard, Amex, Discover), and **Card_Type** (Credit, Debit, Prepaid).
* **Relationships:** Established **One-to-Many (1:*)** relationships to support demographic cross-analysis.

---
---

## 📊 Visuals Used

* **KPI Cards:** For displaying critical financial scale metrics such as **Total Credit Limit ($88.2M)**, **Average Credit Limit**, and **Maximum Credit Limit**.
* **Metric & Operational Tiles:** Dedicated cards for tracking volume and user activity, including **Total Cards Issued (6K)**, **Total Clients (2K)**, and **Average Customer Age (9.74 years)**.
* **Dual-Axis Line Chart:** Essential for historical trend analysis, specifically showing the correlation between **Total Clients** and **Total Credit Limit** over time (1990 - 2020).
* **Donut Chart:** Used for security status breakdown, visualizing the adoption rate of chip technology (**has_chip**).
* **Clustered Column Charts:** Utilized for categorical financial breakdowns, such as **Average Credit Limit** and **Total Clients** by both **Card Brand** and **Card Type**.

---

## 🖱️ Interactive Slicers (Synced Across Dashboard)

* **Year Slicer:** A vertical list for multi-year selection (e.g., 1991 - 1998) to analyze specific economic periods.
* **Card Brand Slicer:** Single/Multi-select options for deep-diving into performance by brand (**Amex, Discover, Mastercard, Visa**).
* **Card Type Slicer:** Filtering capabilities for different account categories, including **Credit, Debit, and Debit (Prepaid)**.

---

## 🔢 Technical Achievement: Key Measures

The project utilizes advanced **DAX (Data Analysis Expressions)** to move beyond simple aggregations into meaningful business logic:

* **Financial Aggregations:** Calculation of `AVERAGE` and `MAX` Credit Limits to identify credit risk and customer value.
* **Operational Intelligence:** Calculated the **Average Customer Age (9.74 years)** and **Average PIN Changes** to monitor account activity.
* **Proportional Analysis:** Logic to determine the percentage of chipped vs. non-chipped cards (currently at **89.49%**).

---

## 📊 Key Dashboard Sections

1. **Executive Summary (Left Pane):** Focuses on the "Big Numbers"—Total and Maximum credit exposure ($151.2K) to give an immediate sense of financial scale.
2. **Operational KPIs (Top Row):** Provides a snapshot of volume (6K cards) and user demographics to understand the client base.
3. **Historical Growth Analysis (Center):** A comprehensive line chart showing the trajectory from 1990 to 2020, highlighting a significant growth period starting after 2018.
4. **Segment Deep-Dive (Bottom Section):** * **By Brand:** Reveals that **Visa** and **Mastercard** carry the highest average credit limits at $14.7K.
    * **By Type:** Highlights that **Debit** users hold a higher average limit ($18.6K) compared to Credit users in this specific dataset.

---

## ❓ Business Questions Answered Instantly

| Requirement | Insight & Achievement |
| :--- | :--- |
| **Credit Risk Scale** | **Q: What is our total financial exposure?** ($88.2M total credit limit). |
| **Security Adoption** | **Q: What percentage of our cards are modern Chip cards?** (89.49% adoption). |
| **Brand Comparison** | **Q: Which brand has the highest customer limit?** (Visa and Mastercard tied at $14.7K). |
| **Demographic Health** | **Q: What is the average age of our cardholders?** (9.74 years). |

---

## 🔎 Project Insights

* **Security Standard:** The high chip adoption rate (89.49%) indicates a modern and secure card inventory.
* **Growth Surge:** The data shows an exponential spike in credit limits and clients starting around **2018–2019**.
* **Unconventional Findings:** Interestingly, **Debit** accounts command a higher average credit limit ($18.6K) than traditional **Credit** accounts in this dataset.

---

## ⭐ Final Conclusion

This **Financial Insights Dashboard** demonstrates the ability to transform raw transaction and client data into a strategic tool. Through precise **DAX engineering** and **strategic visualization**, the solution provides a 360-degree view of credit operations, enabling data-driven decisions regarding credit limits and market segmentation.
