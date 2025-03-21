# PowerBI Sales Performance Dashboard
## Interactive Sales Performance Dashboard with Year-over-Year Comparison

## **Process**
I imported and cleaned sales, accounts, and product data in Power BI, built a data model with relationships, and created DAX measures for YTD, PYTD, and comparisons. Using switch measures, slicers, and conditional formatting, I designed interactive visualizations like KPI cards, waterfall charts, and scatter plots. Finally, I optimized the report layout, added dynamic titles, and published it for insights.

## Key Features and Steps Taken

## 1. Data Preparation & Transformation
Imported an Excel dataset into Power BI containing sales, accounts, and product hierarchy tables.
Cleaned and formatted the data using Power Query, ensuring:
Unique identifiers were assigned to dimension tables.
Duplicates were removed.
Column names were standardized.
Created a date table using DAX (CALENDAR function) to support time intelligence calculations.
Added a calculated "In Past" column to filter prior year-to-date values properly.
## 2. Data Modeling
Defined relationships between:
Fact table (Sales Data) and Dimension tables (Accounts & Products).
Date table connected via Invoice Date to enable time-based calculations.
Ensured a one-to-many relationship structure to maintain data integrity.

## 3. Interactive Visualizations & Insights

I structured the Power BI report layout to be clean, interactive, and intuitive. The key visualizations included:

### a) Dynamic KPI Cards with Conditional Formatting

Displayed YTD, PYTD, and % Difference dynamically based on slicer selection. Applied conditional formatting by color coding positive and negative growth.

### b) Waterfall Chart – Monthly Contribution to YTD vs PYTD

Helped visualize monthly increases/decreases in sales.
Included hierarchy drill-down to analyze by country & product type.

### c) Stacked Column & Line Chart – Performance Trends

The column chart displayed YTD values by month and the line chart overlaid PYTD values for direct comparison.

### d) Scatter Plot – Account Profitability Segmentation

Identified low-sales high-margin and high-sales low-margin accounts.
Helped segment accounts for targeted sales strategies.

### e) Tree Map – Bottom 10 Countries by Performance
Identified underperforming regions contributing to negative growth, highlighting areas for improving sales strategies.

## 5. Report Optimization & Final Touches

Used PowerPoint to design a custom background layout for a polished look.
Applied theme consistency (colors, font sizes, labels).
Created dynamic titles using DAX to update based on slicer selections.
Published the report to Power BI Service for sharing and further insights.

## How This Project Can Add Value to a Business

1. This Power BI report could be used by finance, sales, and operations teams to: Track revenue, profit, and quantity trends.
2. Identify declining regions and products for strategy adjustments.
3. Segment profitable vs non-profitable accounts for better targeting.
4. Improve sales forecasting & business planning.
