Medicare Post-Acute Care Data Analysis

This project explores Medicare post-acute (home health) data using SQL and Python. The analysis focuses on provider-level metrics such as episode counts, service days, care minutes by discipline (PT, OT, SLP, Nursing), provider charges, and Medicare payments.

Project Goals

Practice SQL queries and python programming for healthcare datasets

Explore service utilization patterns across states

Compare provider charges to Medicare reimbursements

Visualize care delivery by discipline

Tools & Skills

SQL (SQLite in Jupyter Notebook)

Python (Pandas, Matplotlib, Seaborn)

Simple Data Cleaning & Wrangling 

Exploratory Data Analysis (EDA)

Key Insights

Service Days: Average service days per episode vary widely by state.

Discipline Minutes: Skilled nursing is the primary service contributor, with PT and OT as secondary contributors.

Cost vs Reimbursement: Charges consistently exceed standardized Medicare payments. This can lead to questions of how providers can continue to sustain daily operations with repeated reimbursement cuts.

Episodes vs Service Days: Higher episode counts generally correlate with higher service days which is to be expected, but, there is still variation across states.

Sample Visualization

<img width="1382" height="586" alt="image" src="https://github.com/user-attachments/assets/e713cef6-a90a-45c9-b89e-a8d5cd8216ee" />

Total care minutes compared to provider charges and Medicare payments by state.

Repository Structure

Medicare Post-Acute Care Data Analysis Project.ipynb → Main analysis notebook

Potential Next Steps

Extend analysis with patient demographic factors (age, primary diagnosis)

Build interactive dashboards (Plotly or Power BI) for stakeholder insights

This project demonstrates end-to-end data analysis: SQL querying, Python EDA, visualization, and business insights in a healthcare context. 
