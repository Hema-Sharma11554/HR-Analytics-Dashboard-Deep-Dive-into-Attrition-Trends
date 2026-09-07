HR Analytics Dashboard - Attrition Analysis
An interactive Power BI dashboard analyzing employee attrition patterns across demographics, job roles, satisfaction, work-life balance, and tenure to help HR reduce turnover and improve retention.

Image unavailable. Please retry the request.

📊 Project Overview
This project analyzes an organization of 1470 employees to identify key drivers of attrition. Out of the total workforce, 1233 employees are active and 237 have exited, resulting in an Attrition Rate of 16%.

The dashboard is split into 3 views covering workforce composition, attrition deep-dives, and satisfaction/performance correlations.

Tool: Power BI (Dark Theme - Teal/Pink)
Dataset: HR Employee Attrition Dataset (1470 records)

🔑 Key KPIs
Metric	Value
Total Strength	1470
Current Employees	1233 (83.88%)
Attrition Count	237 (16.12%)
Attrition Rate %	16%
Average Age	37 years
Average Standard Hours	80
Average Monthly Rate	14K
Average Monthly Income	7K
Avg. Total Working Years	11 years
Avg. Years at Company	7 years
Avg. Years in Current Role	4 years
Average Performance Rating	3.15 / 4
Average Environment Satisfaction	2.72 / 4
Average Work-Life Balance	2.76 / 4


📑 Dashboard Breakdown
<img width="835" height="490" alt="Image" src="https://github.com/user-attachments/assets/3e882143-6bb7-4d8b-a242-65b7996fe50f" />
<img width="849" height="479" alt="Image" src="https://github.com/user-attachments/assets/55d7de5d-00bf-43cc-9f5d-036ffbb1535e" />
<img width="742" height="497" alt="Image" src="https://github.com/user-attachments/assets/1a42eebc-da88-482a-9387-5b419f6b9839" />
Page 1: Overall Attrition Overview (HR_ANALYTICS_1.png)
Goal: High-level snapshot of who is leaving.

Total Strength by Attrition Label: Waterfall chart showing Active (1233) vs Exits (237) -> Total 1470.
Attrition by Marital Status: Single 51% (120), Married 35% (84), Divorced 14% (33). Singles show highest attrition.
Business Travel by Department: Travel_Rarely = 1.04K employees dominates; Travel_Frequently = 0.28K, Non-Travel = 0.15K.
Attrition by Gender: Male 63.29% (150), Female 36.71% (87).
Attrition by Department: R&D = 133 (highest), Sales = 92, HR = 12.
Attrition by Work Location: Branch Office = 103, Remote = 101, Head Office = 33. Branch & Remote are critical.
Attrition by Training: Most attrited employees had 'Excel' (92) or 'None' (90) training background vs 'Leadership Training' (55).
Job Satisfaction Rating: Matrix by Job Role (Rating 1-4). Sales Executive has highest headcount (269) but low satisfaction spread. Research Scientist (245), Laboratory Technician (197) also large. Total satisfaction counts: Rating 4=407, 3=369, 2=234, 1=223.
Region and Work Location: US map visual - workforce spread across Branch, Head Office, and Remote.
Job Satisfaction by Department: Dual line chart - both count and satisfaction drop from R&D -> Sales -> HR.
Page 2: Demographic & Tenure Deep-Dive (HR_ANALYTICS_2.png)
Goal: Understand when and which age groups leave.

Employee Count by Department: R&D 65% (961), Sales 30% (446), HR 4% (63).
Sum of Attrition by Age Band (CF_age_band): Highest attrition in 25-34 age group (112, 47.26%), followed by 35-44 (51, 21.52%), 45-54 (38, 16.03%), 18-24 (25, 10.5%).
Attrition by Work Location: Rate view - Head Office 5.60, Branch 5.57, Remote 5.54 - almost equal rate, but volume higher in Branch/Remote.
Attrition by Business Travel: Active 1233 vs Attrition 237 (19%). Indicates base rate.
Attrition rate by Years at Company: Sharp spike at Year 1 (55+ attrition) and Year 0 (13). Second spike at Year 10 (14). After 12 years, attrition stabilizes near 0-3. New joiners are highest risk.
Age band, Gender wise Attrition: Stacked area chart - Male attrition peaks in 25-44 bands, Female peaks in 25-34. Both genders show low attrition after 55+.
Page 3: Compensation, Education & Satisfaction (HR_ANALYTICS_3.png)
Goal: Correlate pay, education, and work-life with attrition.

Attrition Count by Marital Status (Overall workforce): Married 45.78% (673), Single 31.97% (470), Divorced 22.24% (327) - total base.
Attrition Count by Education: Life Sciences 41.22% (606), Medical 31.56% (464), Marketing 10.82% (159), Technical Degree 8.98% (132), Other 5.58% (82), Human Resources 1.84% (27).
Attrition by Education Field: Life Sciences 35.5% (606), Medical 27.18% (464), Marketing 9.31% (159), Technical Degree 7.73% (132) etc.
Attrition Count by Departments (Pie): R&D 65.37% (961), Sales 30.34% (446), HR 4.29% (63).
Age band by Work Life Balance: Treemap shows majority have WLB rating 2 & 3 in 25-54 bands.
Attrition Rate by Working Hours & Employment Status: High working hours correlate with attrition (0 vs 1 status).
Attrition by Department with Performance Rating: R&D has highest performance sum (3.0K) but also highest attrition count (1.0K). Sales: 1.4K performance vs 0.4K attrition.


💡 Key Insights & Findings
High-Risk Segment: Single, Male, Age 25-34, in R&D or Sales, working in Branch/Remote, with <2 years at company.
Tenure Risk: First year is critical - 58+ attrition in year 0-1. A second risk window at 10 years.
Department Focus: R&D accounts for 56% of all attrition (133/237) despite being 65% of workforce. Needs retention programs.
Location Parity: Branch and Remote have ~3x more attrition than Head Office by volume, though rate is similar.
Satisfaction Link: Lower Environment Satisfaction (2.72) and Work-Life Balance (2.76) vs Performance (3.15) suggests environment, not capability, drives exits.
Education: Life Sciences + Medical background = ~68% of workforce and attrition - domain-specific hiring pressure.


🛠️ Recommendations
Implement a First-Year Engagement Program (mentorship, 30-60-90 check-ins).
Targeted retention for Single employees and R&D roles - flexible work, career pathing.
Reduce Branch/Remote isolation - improve engagement for distributed teams.
Training Investment: Move employees from 'No Training' to Leadership training - 40% lower attrition observed.
Review Travel Policy: Rare travelers still leave - travel is not the main driver, focus on WLB.


📁 Project Structure
/HR-Analytics-Attrition
│── /screenshots
│   ├── HR_ANALYTICS_1.png (Overview)
│   ├── HR_ANALYTICS_2.png (Demographics & Tenure)
│   └── HR_ANALYTICS_3.png (Compensation & Education)
│── HR_Analytics_Dataset.csv
│── HR_Analytics_Dashboard.pbix
└── README.md

Project BY
Hemlata Sharma - Business Analyst Consultant
MBA - Data Science & business Analytics
