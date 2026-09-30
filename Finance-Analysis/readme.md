# Finance Analysis and Transaction Performance Dashboard
An interactive, end-to-end Power BI analytics solution designed to evaluate transaction volumes, revenue growth, customer segmentation, tax/fee distributions, and regional performance.

This project bridges raw transactional records into actionable insights, enabling stakeholders to monitor organisational health, identify high-margin segments, and analyze Year-over-Year trajectories.

## Business Overview and Problem Statement
Financial organisations process millions of transactional data points across various product categories, customer demographies, and regions. Without centralised visibility, leadership faces significant friction in:

- Tracking top-line transactional growth alongside operational fees and taxes collected.
- Evaluating conversion health (transaction success rates vs failure patterns).
- Isolating high-performing customer tiers and geographical regions.
- Assessing customer demographic spending patterns (occupation, gender, customer type).
- Measuring Year-over-Year (YoY) variance in transaction volumes and values.

**Objective:** Build a dynamic Power BI reporting engine that provides executive level summaries alongside granualar drill down paths for transaction status, customer demographics, and geographic distribution. 

## Key Business Questions Answered

1. **Revenue & Volume:** What is the total transaction volume and gross processed value across fiscal years?
2. **Year over Year:** How do current period volumes, fees, and taxes compare against historical baselines?
3. **Transaction Integrity:** What percentage of transactions fail or encounter exceptions, and which payment methods/categories drive them?
4. **Demographics:** How do spend patterns vary across customer occupations and gender profiles?
5. **Geographical Footprint:** Which states lead in transaction volume, and where are operational fees highest?

## Dashboard Architecture & Core KPIs
### Executive KPI Summary Cards
* **Total Transaction Amount:** Total gross financial value processed(with YoY growth indicators).
* **Total Transactions:** Overall transactional count and transaction velocity over time.
* **Average Transaction Value(ATV):** Mean revenue ticket size per transaction ('Total Amount/ Total Volume').
* **Total Fees Collected:** Operational transaction fees captured across payment channels.
* **Total taxes Collected:** Aggregate statuory tax liabilities generated per transaction.

### Visual Breakdown Sections
* **Monthly Financial Trends:** Continuous line/area charts displaying seasonality in trasaction volume and revenue.
* **Transaction Status Breakdown:** Donut/bar charts isolating successful vs failed transaction percentages.
* **State-Wise Performance: Regional:** distribution map/matrix highlighting top performing geographic markets.
* **Category and Occupation Matrix:** Contribution analysis evaluating spend distribution by industry segment and profession.
* **Gender and Demographic Analysis:** Comparative spending trends across demographic cohorts.

## Interactive Features and Dynamic Controls

-**Dynamic Measure Slicers:** Parameter-driven slicers allowing users to toggle visual outputs between *Total Amount*, *Total Fees*, and *Total taxes* on the fly without changing pages.
-**Hierarchial Date Slicers:** Multi-level temporal filtering(Year, Quarter, Month) to analyze cyclic seasonality.
-**Demographic and Categotical Filtering:** Cross-filtering across occupation, customer category, and transaction state.
-**Custom tooltips:** Contextual hover cards displaying exact percentage splits and YoY variance.
