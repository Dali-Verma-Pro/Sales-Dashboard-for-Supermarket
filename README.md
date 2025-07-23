# Sales-Dashboard-for-Supermarket
📘 Project Report: “Superstore Sales Analysis (2014–2017)”
1. Executive Summary
This project analyzes transactional data from 2014–2017 (with partial data in 2018), focusing on sales trends, regional performance, product category insights, and the impact of discounts on profit, using Excel and Python for data cleaning and Pivot reporting.

2. Data Validation & Cleaning
Order Date field: Successfully parsed into a datetime format.

Order Year extracted (2014–2017); no missing years detected.

Identified a small record set labeled “2018” due to partial or incomplete transactions.

Created a standardized column Order Year for reliable year-wise aggregation.

3. Yearly Sales Trends
2014: ₹470.38 K

2015: ₹479.44 K (+1.9%)

2016: ₹611.33 K (+27.4%)

2017: ₹730.89 K (+19.6%)

2018: ₹5.16 K (incomplete month)

Total sales (2014–2017): ₹2,292.05 K; Grand Total: ₹4,594.40 K including 2018.

Insight: A steady upward trend through 2017, suggesting growth momentum; 2018 should be revisited once complete.

4. Regional Performance
Top-performing region: West

Followed by: East and Central

Lowest sales: South

Recommendation: Leverage strategies from West region campaigns to uplift other regions.

5. Product Category Analysis
Best Sales & Profits: Technology

Strong Sales, Lower Margins: Furniture

High Discounts & Lower/Negative Profits: Office Supplies

6. Discount vs. Profit Analysis
Noticed a negative correlation: as discounts increase, profit margins decline

Office Supplies show the worst profitability under higher discount levels

Recommendation: Limit discounting in low-margin categories, or bundle products to retain margins.

7. Recommendations
Address Incomplete 2018 Data: Validate and supplement missing orders for full trend analysis.

Regional Strategy: Replicate high-performing initiatives from the West across East and Central.

Discount Policy: Re-assess discount thresholds, especially in Office Supplies.

Category Expansion: Invest in Technology category based on consistent growth.

Reporting Framework: Automate monthly data cleaning and report updates via Python + Excel template.

8. Project Implementation Steps
Imported data into a Pandas DataFrame

Cleaned and validated date formats

Created Pivot tables in Excel for summarization (sales by year, region, category)

Visualized trends (line chart for years, bar charts for region and category)

Correlation assessed between discounts and profit

✍️ Suggested README.md Outline for GitHub
markdown
Copy
Edit
# Superstore Sales Analysis

## 📈 Overview
- Period: 2014–2017 (with partial 2018)
- Goal: Understand sales trends, regional performance, and discount impact

## 🧰 Tools & Data
- Tools: Python (pandas), Excel, Pivot Tables, Charts
- Data: `Sample – Superstore.csv`

## 📊 Key Insights
- Steady annual sales growth through 2017
- West region leads in performance
- Tech category is most profitable; Office Supplies suffer under discounting

## ✅ Recommendations
- Validate 2018 data
- Optimize discount strategy
- Expand initiatives from high-performing regions

## 📂 Project Structure
- `/data` – Raw dataset
- `/notebooks` – Python cleaning & analysis scripts
- `/reports` – Pivot tables and report visuals
- `/README.md` – Documentation
