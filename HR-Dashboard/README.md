# End-to-End HR Analytics Tableau Dashboard
## Project Overview
This project is a comprehensive Human Resources(HR) analytics solution designed to track employee demographics, performance, and income across a global organization. Following a professional BI workflow used at companies like Mercedes-Benz, this project covers everything from data generation to advanced UI design.
## Key Dashboard Features
  ###1. Executive Summary(High-Level Insights)
     - **KPI Bands**: Real-time tracking of Hired, Active, and Terminated employees.
     - **Geospatial Analysis**: State and City-level distribution maps with custom background layers.
     - **Demographic Ratios**: Gender distribution analysed via Doughnut Charts (dual-axis technique).
     - **Correlation Analysis**: Heatmaps showing relationships between Education vs. Performance and Age vs. Education.
  
  ###2. Income and Gap Analysis
     - **Lollipop/Dumbbell Charts**: Visualised the salary gap between genders across different education levels.
     - **Scatter Plots**: Identified outliers in Salary vs. Age, categorised by job roles and departments.

  ###3. Detailed Employee Records
     - **Custom List Design**: A highly stylised "Record View" using shapes and multiple labels per row to display rich employee profiles without the limitations of standard Tableau tables.
     - **Dynamic Filters**: "Show/Hide" filter menus to maximise screen real estate for the data.
## Technical Deep Dive
  - **Advanced Container Nesting**: Utilised 6+ layers of horizontal and vertical containers for a pixel-perfect layout.

  - **DAX-like Logic in Tableau**: Created complex Calculated Fields for:

    - **Length of Hire** (handling both active and terminated dates).

    - **Highlight Max/Min** (Window functions to highlight top-performing categories).

  - **Interactive Tooltips**: Embedded entire charts (Viz-in-Tooltip) to allow managers to see "Top Jobs" just by hovering over a department.
## Screenshots
Overview

<img width="1435" height="833" alt="image" src="https://github.com/user-attachments/assets/c664fc62-dc3c-4958-9e03-671c64b77080" />

Details

<img width="1440" height="830" alt="image" src="https://github.com/user-attachments/assets/ad583152-b0f1-4036-90a3-71656bcded15" />

