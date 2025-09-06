# 🛡️ NATO Defense Spending (2014–2024) – Power BI Report

## ✨ Description
This project presents an analysis of NATO defense spending from 2014 to 2024.  
The report provides key insights into spending levels (% of GDP and per capita), soldier counts, country rankings, and time-based comparisons.

## 📌 Key Findings and Observations
- NATO countries can be compared by **% of GDP** devoted to defense, **per-capita** spending and **share in total NATO spending**.
- The report highlights **country rankings** (e.g., USA has the largest share) and **year-over-year changes** vs the previous year or a selected baseline year.
- Interactive slicers (Country, Year) allow focused views and benchmarking of individual members.

## 🧩 Data Model
The report is built using a constellation/star schema and consists of:
- **2 fact tables**: `FactWydatki` (expenditure, GDP, military personnel), `FactPopulacja` (population)
- **Dimension tables**: `DimKraje`, `DimKalendarz`, `DimKalendarz2` (for comparisons), plus a measures table `_Miarki`
- **Relationships** are one-to-many between dimensions and facts

## 🔗 Data Source
- Defense, GDP and population data aggregated from public/open sources.  
  *(Replace with your exact sources and links, e.g. World Bank / NATO / SIPRI.)*

## ▶️ How to Run the Report
1. Download the `NATO_Defense_Spending_2014_2024.pbix` file from the repository.  
2. Open it in **Power BI Desktop**.  
3. Use the slicers (Country, Year) and explore KPIs, rankings and comparisons.

---

**Author:** Filip Kinczewski  
**Publication Date:** January 2025
