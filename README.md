# Hospital Operations Analysis Dashboard — City General Hospital
**Author:**  Saheed Olayinka Adebiyi
**Date:** 2025-11-24
---
## Project Background
City General Hospital is experiencing severe operational issues: ER overcrowding, bed
misallocation, staff burnout, medication mismanagement, financial losses, and high lab retest
rates. This project analyzes available hospital data and produces an interactive Excel dashboard
with actionable recommendations.
---
## Project Objective
The objective is to uncover insights that can improve patient care, operational efficiency, and financial management
- Demographic Variation:  exploring the distribution of patients by age, gender, and blood type etc
- Medical Condition and Treatment Patterns: To examine the frequency and distribution of medical conditions across patients, assess relationships between medical conditions, prescribed     medications, and test results
- Admission and Discharge Insights: Analyze trends in admission types (Elective vs Emergency), calculate average length of hospital stay.
- Financial and Billing Analysis: Evaluate billing amounts to determine cost patterns across patients, identify high-cost cases, and also to analyze insurance provider distribution and     its relationship with billing amounts.
- Build an interactive Excel dashboard to inform board-level decisions 
- Recommend prioritized actions to stabilize hospital operations
---
## Datasets
- **City Hospital dataset.xlsx** — Patient ID, Age, Gender, Blood type, Hospital, Room number, Admission type, Medication, Insurance Provider, Billing Amount, Admission Date, Discharge       Date, Medical Condition, Doctor, and Test Results.

---
## Dashboard Features
- Key KPIs: total patients, average age, total billing, average length of stay, total number of doctors
- Visuals: time-series of visits, age-group distributions, staff workload, gender distribution, % of abnormal test results, etc
- Interactivity: slicers/filters for gender, Date range, Age group, test result, and insurance provider
---
## Key Findings (example)
- Majority of ER visits are from elderly patients → contributes to bed shortages 
- Uneven staff distribution: some doctors are overloaded while others are idle 
- Inventory mismatch: critical drugs are short while others are near expiry 
- 15% of lab tests flagged for retest, increasing workload and delays 
- Revenue leakage from unpaid insurance claims and billing gaps
---
## Recommendations
1. Reallocate beds and triage protocols based on age-group trends 
2. Rebalance staff shifts using workload analytics and consider cross-training 
4. Tighten lab QC processes to reduce retests (target <5%) 
5. Review treatment protocols for conditions frequently associated with abnormal test results.
6. Optimize billing estimation models using length-of-stay predictions.
7. Prioritize Lipitor for restocking due to high usage, and reduce Penicillin as it is the least used
8. Develop targeted care programs for early middle age and early-senior female patients, the largest demographic group.
9. Consider redistributing patients or providing additional support to prevent burnout and maintain quality of care.
10. Train laboratory staff on proper testing procedures and handling to reduce inconclusive results

---
## Tools & Techniques
- Microsoft Excel (Pivot Tables, Pivot Charts, Slicers) 
- Data cleaning and transformation in Excel 
- Dashboard layout and visualization best practices 
- Basic descriptive analytics and KPI design
---
## Project Files (included)
- `City Hospital Dashboard.xlsx` — interactive dashboard file 
- `City Hospital Dataset` — raw data files used for analysis (XLSX) 
- `Presentation.pdf` — boardroom slide deck 
- `README.md` — this documentation
---
## How to Run / View
1. Open `City Hospital Dashboard.xlsx` in Excel (desktop recommended) 
2. Enable content (if prompted) to allow Pivot Tables and slicers to work 
3. Use slicers to filter by Department, Date, Age group, etc. 
4. Refer to `Presentation.pdf` for a summary of insights and recommended actions
---
## Contact
Adebiyi Saheed Olayinka 
Email: olayinkaadebiyi49@gmail.com
LinkedIn: www.linkedin.com/in/olayinkaadebiyi
