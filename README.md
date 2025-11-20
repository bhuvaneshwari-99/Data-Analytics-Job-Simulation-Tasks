# Data-Analytics-Job-Simulation-Tasks
# Daikibo Analytics Project

This repository contains two analyses for Daikibo Industrials: telemetry data analysis and gender pay equality classification.

---

## Task 1: Telemetry Data Analysis (Tableau)

**Objective:** Analyze machine downtime across factories and device types.

**Process:**
- Imported `daikibo-telemetry-data.json` into Tableau.
- Created a calculated field **Unhealthy** (10 minutes per unhealthy status).
- Built bar charts: **Down Time per Factory** and **Down Time per Device Type**.
- Designed an interactive dashboard linking both charts with filtering by factory.
- Identified the factory with the highest downtime and captured a screenshot.

**Results:**
- Screenshot: `screenshots/Dashboard_Filtered.png`
- Tableau workbook: `Task1_Telemetry_Analysis/Tableau_Workbook.twbx`

---

## Task 2: Gender Pay Equality Analysis (Excel)

**Objective:** Classify employee roles based on gender pay equality scores.

**Process:**
- Opened `Equality Table.xlsx` and added a new column **Equality Class**.
- Classification logic:
  - **Fair:** Score between -10 and +10 (inclusive)
  - **Unfair:** Score between -20 and -11 or 11 and 20
  - **Highly Discriminative:** Score < -20 or > 20
- Applied classification to all rows and saved as `Equality_Table_Classified.xlsx`.

**Results:**
- Classified Excel file: `Task2_Gender_Pay_Equality/Equality_Table_Classified.xlsx`

---

## Resources
- Tableau Free Trial: [Link]
- Original JSON: `Task1_Telemetry_Analysis/daikibo-telemetry-data.json`
- Original Excel: `Task2_Gender_Pay_Equality/Equality_Table.xlsx`



