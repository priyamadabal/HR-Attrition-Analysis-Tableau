# HR Attrition Analysis Dashboard
Data analysis and visualisation of HR attrition factors using Tableau.

## Overview

This project focuses on analyzing and visualizing Human Resources (HR) attrition data to provide actionable insights for employee retention at the fictional ABC Organization.

The goal was to transform raw employee data into a comprehensive, interactive dashboard that allows the HR department to easily identify key drivers of attrition and make data-driven decisions to sustain the workforce. The solution fully addresses the requirements outlined in the provided problem statement.

## Key Features of the Dashboard

The Tableau dashboard was built according to the provided requirements, offering the following specific visualizations and metrics:

* **Key Metrics Table:** Employee Count, Attrition Count, Attrition Rate, Active Employees, Average Age.
* **Demographic Analysis:** Attrition by Gender (Lollipop Chart), Attrition Rate by Gender across Age Groups (Donut Chart).
* **Departmental & Role Analysis:** Pie Chart for Department-wise Attrition and a Highlight Table for Job Satisfaction by Job Role.
* **Driving Factors:** Histogram for Employee Count by Age Group (using a dynamic bin size parameter) and a Bar Chart for Attrition based on Education Field.

## Technologies and Tools

| Category | Tool/Technology | Purpose |
| :--- | :--- | :--- |
| **Data Source** | `HR Data.csv` | Raw employee dataset containing various employee attributes. |
| **Visualization** | **Tableau Desktop** | Used to create the interactive and linked dashboard (`.twbx` file). |

## Key Insights & Impact 

* **1. HR Attrition Scorecard:** The analysis revealed the following critical organizational metrics as a baseline for all subsequent departmental and demographic findings:
| Metric | Value |
| :--- | :--- |
| **Employee Count** | 1,470 |
| **Attrition Count** | 237 |
| **Attrition Rate** | **16.12%** |
| **Active Employees** | 1,233 |
| **Average Employee Age** | 36.92 |

* **2. Attrition by Gender:** Attrition is higher among male employees with 150 departures compared to female employees with 87 departures. This needs to be investigated why male employees depature is higher? Is it because of work-life balance or career development or something else.
  
* **3. Departmental Priority:** While the **Research & Development (R&D)** department has the highest total number of attritions, the **Sales** department shows the highest proportional **Attrition Rate**. This suggests that retention efforts must be targeted towards addressing issues specific to the high-pressure sales environment.

* **4. Job Satisfaction and Level Correlation:** There is a clear correlation between employees at **Job Level 1** (entry-level) with **Low Job Satisfaction** (Rating 1 or 2) and high attrition. This identifies a critical need to improve the work experience, mentorship, or career path clarity for entry-level staff.

* **5. Overtime and Work-Life Balance Risk:** Employees reporting a **poor Work-Life Balance** combined with frequent **Over Time** usage had an exceptionally high attrition rate. This quantifiably highlights high workload and poor scheduling as a major, actionable risk factor for voluntary resignation.

* **6. Critical Age Demographic:** The analysis of the Age Distribution Histogram reveals that employees in the **25-34 Age Band** account for the highest volume of attrition. This points to a failure in retaining high-potential, early-to-mid-career talent, which requires immediate investigation into career pathing and salary competitiveness.

## Project Files

* `HR Data.csv`: The source dataset used for the analysis.
* `HR Attrition Analysis.twbx`: The packaged Tableau workbook containing the entire dashboard and all visualizations.
* `Problem Statement_Visualization in Tableau.docx`: The official problem brief defining the project requirements.

## How to View the Dashboard

1.  Download the `HR Attrition Analysis.twbx` file from this repository.
2.  Open the file using **Tableau Reader** (free) or **Tableau Desktop**.
