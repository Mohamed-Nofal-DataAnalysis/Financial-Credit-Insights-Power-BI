🚀 Project Overview
Financial & Operational Insights Dashboard built with Power BI. This project focuses on credit card performance analytics, featuring a clean UX/UI, comprehensive financial modeling, and advanced DAX calculations to track credit limits, client demographics, and operational trends across three decades of data.

⚙️ Project Structure & Technical Deep Dive
Process (Data Engineering & Visualization)
Data Ingestion: Cleaned and transformed credit/client data using Power Query, ensuring types for credit limits and dates were optimized.

Star Schema Design: Implemented a robust data model linking transaction facts with dimensions like Card Brands, Card Types, and Time.

DAX Development: Created measures for tracking Total Credit Limit ($88.2M), Average Customer Age (9.74 years), and complex "has_chip" distribution logic.

UI/UX Design: Used a professional "White & Maroon" theme with high-contrast visuals for better readability and executive reporting.

Interactivity: Integrated synchronized slicers (Year, Brand, Type) that filter the entire landscape of financial metrics instantly.

⚙️ Data Model
The model is built to handle historical data (from 1991 to 2020) efficiently.

Fact Table: Contains core metrics like Credit Limits and Client IDs.

Dimension Tables: Includes Year/Calendar, Card Brand (Amex, Discover, Mastercard, Visa), and Card Type (Credit, Debit, Prepaid).

Relationships: Optimized One-to-Many (1:*) relationships to ensure precise filtering of averages and totals across the timeline.

Visuals Used:
KPI Cards: High-level summaries for Total Credit Limit ($88.2M), Average Credit Limit ($14.3K), and Max Credit Limit ($151.2K).

Metric Tiles: Dedicated cards for Total Cards Issued (6K), Total Clients (2K), and Operational metrics like Average PIN Changes (3).

Dual-Axis Line Chart: Tracks the correlation between Total Clients and Total Credit Limit by Year (1990 - 2020).

Donut Chart: Visualizes the adoption of chip technology (has_chip), showing an 89.49% "YES" rate.

Clustered Column Charts: Comparative analysis of Average Credit Limit vs. Total Clients across card_brand and card_type.

Interactive Slicers:
Year Slicer: Vertical list for multi-year trend selection (1991-1998 visible).

Card Brand Slicer: Radio selection for Amex, Discover, Mastercard, and Visa.

Card Type Slicer: Filter for Credit, Debit, and Debit (Prepaid) categories.

🔢 Technical Achievement: Key Measures
Calculated using advanced DAX (Data Analysis Expressions) to provide real-time insights:

Financial Aggregations: Calculation of AVERAGE and MAX Credit Limits to identify credit risk and customer value.

Operational Averages: Calculated the Average Customer Age (9.74 years) and Average PIN Changes to monitor account activity.

Proportional Analysis: Logic to determine the percentage of chipped vs. non-chipped cards (89.49% vs 10.51%).

📊 Key Dashboard Sections
1. Executive Summary (Left Pane)
Focuses on the "Big Numbers" — Total and Maximum credit exposure to give an immediate sense of the financial scale.

2. Operational KPIs (Top Row)
Provides a snapshot of the volume (6K cards) and user demographics (Average Age) to understand the client base.

3. Historical Growth (Middle Section)
A long-term trend analysis showing how credit limits scaled alongside client acquisition from the 1990s through 2020.

4. Segment Breakdown (Bottom Section)
By Brand: Identifies that Visa and Mastercard carry the highest Average Credit Limits ($14.7K).

By Type: Highlights that Debit users surprisingly hold a higher average limit ($18.6K) compared to Credit users in this specific dataset.

🔎 Project Insights
Chip Adoption: A significant majority of the cards (nearly 90%) are chipped, indicating a modern and secure card inventory.

Growth Surge: The "Total Clients and Credit Limit" chart shows an exponential spike starting around 2018-2019, following a long period of steady, slow growth.

Brand Performance: Visa and Mastercard are the dominant brands both in terms of client volume and credit limit allocation.

⭐ Final Conclusion
This Financial Insights Dashboard demonstrates the ability to transform raw transaction and client data into a strategic tool. By combining historical trends with categorical breakdowns, it provides a 360-degree view of credit operations, enabling data-driven decisions regarding credit limits and market segmentation.
