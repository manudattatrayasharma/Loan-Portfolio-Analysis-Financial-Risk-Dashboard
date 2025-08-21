Loan Portfolio Analysis & Financial Risk Dashboard

Dashboard Link: https://app.powerbi.com/links/73VX37UHkC?ctid=2e00ccef-2930-4d6f-bf36-4dbc181c566c&pbi_source=linkShare
Problem Statement
This dashboard enables comprehensive analysis of the bank’s loan portfolio, with special focus on default rates, applicant demographics, and financial risk factors. Utilizing a dataset of 200,000+ records and Power BI dataflows for reliable data loading, the dashboard visualizes loan amounts, default trends, applicant segments, and risk dimensions across multiple years, categories, and attributes.

The insights help the bank identify segments at risk of default, understand loan purpose trends, profile borrowers by financial and demographic attributes, and evaluate year-over-year changes in both loan volumes and risk. This empowers targeted interventions, data-driven credit policy, and proactive risk management.

Steps Followed
Step 1: Loaded more than 200,000 loan records using Power BI Dataflows, ensuring scalable and automated ETL.

Step 2: Profiled and cleaned data in Power BI; treated nulls and standardized categorical fields (e.g., employment type, marital status, credit score bins).

Step 3: Created calculated columns and DAX measures for metrics such as default rates, income, age groups, loan purposes, credit score bins, and YoY changes.

Step 4: Built tailored visuals for:

Loan amounts by purpose and age group

Average income by employment type

Default rates by employment type and by year

Applicant and loan segmentation by age, marital status, education, and credit score category

Median and total loan breakdown by credit score bins

Dependency/mortgage impact on loan amounts

Financial risk matrix visualizing YoY changes in portfolio and risk

Sankey and flow diagrams to view composition by credit score and term

Step 5: Used slicers and dynamic legends for interactive deep dives (e.g., filter by income bracket, employment type, age group).

Step 6: Published to Power BI Service, sharing insights with stakeholders and decision-makers.

Dashboard Snapshots
Loan Default & Overview
![Loan default & overview dashboardLoan Amount by Purpose:** Highest for Home, followed by Business, Education, Auto, Other.

Average income by Employment: Peaks at full-time, dips for unemployed.

Default rate by Employment: Unemployed highest (13.6%), full-time lowest (9.5%).

Loan Amount by Age Group: Adults highest; Teens lowest.

Default Rate by Year: Ranges 11.5–11.75% with annual fluctuations.

Applicant Demographics & Financial Profile
page 1 :<img width="1516" height="812" alt="Screenshot 2025-08-21 151440" src="https://github.com/user-attachments/assets/5f97b0ad-8284-4292-92b1-edbc02ea140b" />

page 2 :<img width="1516" height="814" alt="Screenshot 2025-08-21 151533" src="https://github.com/user-attachments/assets/6a37692c-ba05-42a7-9f68-58810441c477" />

page 3:<img width="1513" height="819" alt="Screenshot 2025-08-21 151548" src="https://github.com/user-attachments/assets/0337c2a6-9031-436f-bf41-87cdaf8f4f2d" />

Average Loan by Age & Marital Status: Donut chart shows well-distributed means.

Total Loan (Adults) by Credit Scores: Medium/High scores have highest volume.

Loans (Middle Age Adults) by Mortgage/Dependents: Similar loan volume, regardless of dependency.

Number of Loans by Education: Bachelor's leads, followed by High School, Master's, and PhD.

Financial Risk Matrix
![Financial risk matrix dashboardYoY Loan Amount Change by Year:** Notable dropping in 2014/2017, growth in 2015/2018.

YoY Default Loans Change by Year: Highest risk years in 2015 and 2018.

YTD Loan by Credit Score Bin & Loan Term: Sankey illustrates risk concentration by scores and terms.

Sum of LoanAmount by Income Bracket & EmploymentType: High income and full-time/self-employed are the largest contributors.

Insights
Purpose & Risk: Home and business loans dominate; unemployment correlates with highest default rates and lowest incomes.

Demographics: Older adults and those with lower credit scores request higher median loans.

Default Trends: Annual default rates remain steady (11–12%) over time, with peaks indicating riskier years.

Credit Scores: Lower scores not only correlate with lower medians but also lower total loan volumes among adults.

High-Income Segment: High-income, full-time and self-employed applicants represent largest share of loan volumes, underscoring importance for risk controls in these brackets.

Education: Higher education levels do not necessarily translate to higher number of loans—Bachelor’s degree applicants dominate.

Dependency: For middle-aged adults, mortgage/dependents status does not significantly affect loan volumes.

Year-over-Year Analysis: Down years are visible (2014, 2017 for both loan amounts and defaults), flagging potential macroeconomic or policy effects.

Methodology & Technical Notes
Null, blank, and outlier values treated during dataflow ETL and Power BI transformation.

All aggregates (medians, totals, rates) dynamically update with slicer filters.

DAX used to calculate default rates, segment applicants, and YOY trends.

Rich interactive experience using both legacy and custom Power BI visuals.

Data model supports rapid scalability for larger datasets and ongoing refresh through Power BI Dataflows.

This dashboard is a robust tool for credit risk teams, portfolio managers, and policy analysts to understand loan patterns, monitor risk, and identify opportunities to optimize lending strategy and minimize default exposure.
