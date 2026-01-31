# 📊 UK Study & Work Sponsorship – Overview Dashboard

---

##  Project Overview

This project analyzes **UK Study and Work Sponsorship migration trends** using official UK Government data.  
An **interactive Power BI dashboard** was developed to explore historical sponsorship patterns, extensions, nationalities, regions, institutions, and industries from **2010–2023**.

The project demonstrates the integration of **SQL Server**, **T-SQL**, **Power BI**, and **Advanced DAX** to support **data-driven public sector decision-making**.

---

##  Objectives

- Analyze trends in UK **study and work sponsorship applications**
- Compare **study vs work migration patterns**
- Identify **top nationalities, regions, institutions, and industries**
- Examine **repeat sponsorships and extension rates**
- Build an **interactive analytical dashboard**

---

##  Tech Stack

- **Database:** Microsoft SQL Server  
- **Query Language:** T-SQL  
- **Visualization:** Microsoft Power BI  
- **Analytics:** Advanced DAX  
- **Data Source:** UK Government Open Data (data.gov.au)

---

##  Datasets

### Study Sponsorship
- CAS_D01 – Study Sponsorship Applications  
- CAS_D02 – Study Sponsorship Extensions  

### Work Sponsorship
- CoS_D01 – Work Sponsorship Applications  
- CoS_D02 – Work Sponsorship Extensions  

Final merged tables:
- `merge_study`
- `merge_work`

---

##  Methodology (Summary)

1. Imported datasets into **SQL Server**
2. Created **Sponsorship** database
3. Cleaned numeric fields using **T-SQL**
4. Merged study and work datasets
5. Imported cleaned tables into **Power BI**
6. Built **DAX measures** and date tables
7. Developed an **interactive dashboard**

---

##  Dashboard Features

- Total Study & Work Applications by Year
- Quarterly Trends with YoY Growth
- Top 10 Nationalities by Visa Type
- Repeat Sponsorships by Region (Map)
- Extension Rate Analysis (Decomposition Tree)
- Applications by Institution & Industry
- KPI Cards & Interactive Slicers

---

##  Key Insights

- Study visas consistently exceed work visas
- China dominates study visas; India dominates work visas
- Work visas show higher extension rates than study visas
- Migration patterns vary strongly by region, sector, and time

---


