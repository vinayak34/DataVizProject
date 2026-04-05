# Hospital Patient Wait List Analysis

## Project Overview
This project focuses on analysing hospital patient waiting lists from 2018 to 2021. Using a 9-step Power BI development lifecycle, the dashboard provides insights into patient categories (Inpatient, Outpatient, and Day Case), historical trends, and demographic distributions to healthcare administrators optimise resource allocation.

## The 9-step Development Process
To ensure a professional-grade delivery, this project followed a standard industry workflow:

  1. Requirement Gathering: Identified KPIs (Average vs. Median wait times).
  
  2. Data Collection: Imported multi-year CSV files via folder connection.
  
  3. Data Transformation: Cleaned data and handled outliers in Power Query.
  
  4. Data Modelling: Established relationships between speciality and time dimensions.
  
  5. Blueprint: Wireframed a two-page report (Summary & Detailed).
  
  6. Dashboard Layout: Developed a user-friendly UI with consistent branding.
  
  7. Interactivity: Implemented slicers, page navigation, and custom tooltips.
  
  8. Testing: Validated measures against raw data totals.
  
  9. Maintenance: Built a scalable model for monthly data refreshes.

## Key Insights and Features
### 1. Executive Summary Page
- **KPI Tracking**: Real-time monitoring of the latest month's waitlist vs. the previous year.

- **Case Distribution**: A donut chart visualizes the volume split, revealing that Outpatients typically comprise the largest portion of the waitlist.

- **Trend Analysis**: Dual line charts showing the divergent trends between Inpatient/Day Case and Outpatient volumes.

### 2. Granular Analysis
- **Age Profile**: Detailed breakdown showing high concentrations in the 16–64 age bracket.

- **Specialty Deep-Dive**: Identification of the Top 5 specialties (e.g., Accident & Emergency) requiring immediate attention.

- **Time Banding**: Analysis of how long patients have been waiting, categorized by duration.

## Technical Highlights
- **Outlier Management**: Utilized Median wait times alongside Average to prevent extreme values from skewing the operational reality.

- **DAX Measures**: * Latest Month Waitlist

Prior Year Waitlist

Dynamic Tooltip Labels

- **Navigation**: Integrated a seamless "View Details" button for drill-through capabilities.

