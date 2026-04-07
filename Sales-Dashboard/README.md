# Sales Performance & Customer Insights Dashboard
## Project Overview
This project delivers two high-impact Tableau dashboards designed to help stakeholders analyze Year-over-Year (YoY) sales performance and customer trends. By utilizing dynamic parameters, the solution allows users to select any historical year as the "Current Year" for automated comparison against the "Previous Year."
## The 4-Phase Implementation
1. **Requirement Gathering**: Translated user stories into specific KPIs: Sales, Profit, and Quantity.
2. **Data Modeling**: Connected and structured multi-table CSV data (Orders, Customers, Products, and Locations) in the Tableau Data Source layer.
3. **Visualization Design**: Developed a mix of Big Aggregate Numbers (BANs), Sparklines for monthly trends, and Histograms for customer distribution.
4. **Interactive Dashboarding**: Built a cohesive UI with custom navigation buttons, show/hide filter menus, and synchronized formatting.
## Dashboard 1: Sales Performance
### Key Features:
- **Executive KPI BANs**: Displays Total Sales, Profit, and Quantity for the selected year with automated YoY percentage growth indicators.
- **Monthly Sparklines**: Continuous line charts highlighting the Maximum and Minimum values using a dual-axis circle technique.
- **Subcategory Comparison**: A Bar-in-Bar Chart comparing sales performance between the current and previous years at a product level.
- **Weekly Trend Analysis**: Step-line charts with Reference Lines that dynamically color-code data points as "Above Average" or "Below Average".
## Dashboard 2: Customer Insights
### Key Features:
- **Customer Distribution Histogram**: Uses LOD (Level of Detail) Expressions to group customers by their total number of orders placed in the selected year.
- **Top 10 Customers List**: A detailed ranking of customers by profit, including their last order date, total sales, and order count.
- **Sales per Customer**: Advanced calculation dividing current year sales by the distinct count of customers to track average basket value.
