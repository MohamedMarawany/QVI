# QVI Analysis - Professional Summary & Recommendations

This document provides a comprehensive summary of the analysis performed in the notebook `QVI_Analysis_Marawany.ipynb`, highlighting key findings, insights, and actionable recommendations for stakeholders.

## 1. Project Overview
The analysis explores customer purchase behaviour and transaction data for a major snack brand, aiming to uncover trends, segment customers, and identify business opportunities.

## 2. Data Preparation & Cleaning
- **Data Sources:**
    - `QVI_purchase_behaviour.csv`: Customer lifestage and premium status.
    - `QVI_transaction_data.xlsx`: Transaction-level sales, product, and store data.
- **Cleaning Steps:**
    - Converted date columns to datetime format.
    - Removed duplicates and handled missing values (minimal, except for Christmas Day).
    - Detected and removed outliers (e.g., transactions with 200 packs or $650 sales).
    - Engineered features: `Pack_Size (g)`, `Brand`, `Spend_per_Transaction`, `Unit_Price`.
    - Standardized brand names for consistency.

## 3. Data Understanding
- **Purchase Behaviour:**
    - ~70,000 unique customers.
    - 7 lifestage categories, 3 premium segments.
- **Transaction Data:**
    - ~264,000 transactions over one year (July 2018 - June 2019).
    - One day missing (Christmas), otherwise complete.

## 4. Exploratory Data Analysis (EDA)
### Customer Segmentation
- **Lifestage:**
    - Largest group: Mainstream families and retirees.
    - Premium customers represent ~20% of the base.
    - Visualized with bar plots for clear distribution.

### Brand & Product Insights
- **Top Brands by Sales:**
    - Kettle, Doritos, Smiths, Red Rock Deli, Grain Waves.
    - Brand standardization improved accuracy of insights.
- **Pack Size:**
    - Most popular: 175g, 150g, 134g.
    - Larger pack sizes drive higher average spend per transaction.
    - Preferences vary by customer segment.

### Store Performance
- **Top Stores:**
    - Top 10 stores identified by total sales.
    - Outlier customer data saved for further investigation.

### Time-based Trends
- **Monthly Sales:**
    - Peak in December, likely due to holiday season.
    - Trough in January, consistent with post-holiday decline.
- **Daily Sales:**
    - Highest: December 24, 2018.
    - Lowest: May 18, 2019.
    - Trends visualized with annotated line charts.

### Cross Analysis
- **Spend by Segment:**
    - Premium and older lifestage customers tend to spend more per transaction.
    - Brand and pack size preferences differ by segment, suggesting targeted marketing opportunities.

## 5. Key Insights
- **Customer Behaviour:**
    - Most transactions are for 1–5 packs, with a strong preference for mainstream brands and mid-to-large pack sizes.
    - Premium and older customers are valuable segments with higher average spend.
- **Product & Brand:**
    - Kettle, Doritos, and Smiths dominate sales; focus on these for promotions.
    - Brand loyalty is evident, but some confusion existed before standardization.
- **Store & Channel:**
    - A small number of stores drive a large share of sales; investigate top performers for best practices.

- **Seasonality:**
    - Sales spike in December; plan inventory and marketing accordingly.
    - January dip is expected; consider off-season promotions.

## 6. Recommendations for Stakeholders
1. **Target High-Value Segments:**
    - Develop tailored offers for premium and older customers, who have higher spend per transaction.
2. **Optimize Product Mix:**
    - Focus on stocking and promoting top-selling brands (Kettle, Doritos, Smiths) and popular pack sizes (175g, 150g).
3. **Seasonal Planning:**
    - Increase inventory and marketing efforts ahead of December.
    - Launch post-holiday campaigns in January to counteract seasonal dips.
4. **Store Performance Management:**
    - Analyze top-performing stores for replicable strategies.
5. **Brand Standardization:**
    - Continue efforts to standardize product and brand naming for accurate reporting.
6. **Customer Engagement:**
    - Use insights on lifestage and premium status to personalize communications and loyalty programs.

## 7. Visualizations & Reporting
- The notebook includes:
    - Boxplots, histograms, and bar charts for distribution analysis.
    - Line charts for time trends.
    - Annotated plots highlighting key findings.
- For detailed code, statistics, and visualizations, refer to `QVI_Analysis_Marawany.ipynb`.

---

This summary provides actionable insights and recommendations to support data-driven decision making for the QVI snack brand business.
