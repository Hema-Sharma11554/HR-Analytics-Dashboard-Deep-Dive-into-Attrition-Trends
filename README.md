HR Analytics - Attrition Analysis - Project Overview

This project analyzes an organization of 1470 employees to identify key drivers of attrition. Out of the total workforce, 1233 employees are active and 237 have exited, resulting in an Attrition Rate of 16%.

The dashboard is split into 3 views covering workforce composition, attrition deep-dives, and satisfaction/performance correlations.

📑 Dashboard Breakdown
<img width="835" height="490" alt="Image" src="https://github.com/user-attachments/assets/3e882143-6bb7-4d8b-a242-65b7996fe50f" />
<img width="849" height="479" alt="Image" src="https://github.com/user-attachments/assets/55d7de5d-00bf-43cc-9f5d-036ffbb1535e" />
<img width="742" height="497" alt="Image" src="https://github.com/user-attachments/assets/1a42eebc-da88-482a-9387-5b419f6b9839" />


🔑 Key KPIs - Metric	Value

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


**Recommendations - **
1. Fix the First-Year Churn - Highest Priority
Data: Attrition rate by Years at Company shows 58+ exits in Year 0-1, then a second spike at Year 10 (14 exits). After Year 12, attrition is almost 0.
Recommendation: Launch a 30-60-90-180 day onboarding & mentorship program. Assign buddies, monthly manager check-ins, and clear role clarity in first year. Also do a 10-year career refresh interview.

2. Focus on R&D and Sales
Data: R&D = 133 exits (56% of all attrition), Sales = 92. HR = only 12. Page 2 also shows R&D is 65% of your total workforce (961).
Recommendation: R&D needs immediate retention action — career pathing, skill upskilling to Leadership, and lab workload review. For Sales, review compensation (Average Monthly Income is only 7K vs Rate 14K).

3. Single Employees are 2x More Likely to Leave
Data: Single = 51% of attrition (120) while they are only 31.97% of workforce (470). Married = 35% of attrition but 45.78% of workforce.
Recommendation: Single employees value flexibility and growth more than stability. Offer flexible work, learning stipends, and social engagement activities.

4. Branch Office + Remote = 86% of Exits
Data: Branch Office 103, Remote 101, Head Office only 33.
Recommendation: Branch/Remote isolation is real. Introduce quarterly HQ visits, better manager connect, and remote engagement budget. Even though rate is similar (∼5.5%), volume is killing you.

5. Age Group 25-34 is Your Risk Zone
Data: 112 exits (47.26%) are in 25-34 band. Next is 35-44 with 51 exits (21.5%).
Recommendation: This is your high-potential, high-market-value group. Create fast-track promotions, compensation benchmarking for 25-34 males (Male attrition is 150 vs Female 87), and work-life balance improvement (Avg WLB is only 2.76/4).

6. Training Makes a Difference
Data: Attrition by Training: Excel Work = 92, None = 90, Leadership Training = 55 (lowest).
Recommendation: Move people from 'No Training' to Leadership training. Make leadership training mandatory after 2 years. It cuts attrition by ∼40%.

7. Environment Satisfaction is Lower Than Performance
Data: Avg Performance Rating 3.15 but Env Satisfaction 2.72 and WLB 2.76. Job Satisfaction Rating: 223 people gave Rating 1 (lowest).
Recommendation: Performance is not the issue, environment is. Focus on manager training (Job Role: Manager 97, Research Director 78), recognition, and workload. Especially for roles: Sales Executive (269 headcount), Research Scientist (245), Lab Technician (197) — check their satisfaction spread.

8. Education Field Hiring Strategy
Data: Life Sciences 606 (41.22%) + Medical 464 (31.56%) = 73% of workforce and most of the attrition.
Recommendation: You are over-dependent on these two pools. Diversify hiring or create a retention bonus for these hot skills, as market demand for them is high.


Quick Win Action Plan:

30 days: Exit interview audit for 25-34, Single, R&D, Year 0-1 leavers
90 days: First-year engagement program + Remote connect program
180 days: Leadership training for all with 'None' + WLB policy review


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
