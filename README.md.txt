# HR Analytics Dashboard

Analysis of employee attrition trends using the IBM HR Analytics dataset, built with Google Sheets.

## Tools Used
- Google Sheets — data analysis, pivot tables, and visualization
- Formulas: COUNTIF, COUNTIFS, AVERAGEIF

## Project Steps
1. Cleaned and validated the HR employee dataset (1470 records)
2. Calculated key metrics using formulas: overall attrition rate, attrition by department, income comparison, attrition by job satisfaction
3. Built a pivot table and charts to visualise attrition patterns
4. Summarised findings into a business insights report

## Key Insights
1. Overall attrition rate is 16.12% — roughly 1 in 6 employees leave.
2. Sales has the highest attrition rate (20.63%), followed by HR (19.05%) and R&D (13.84%) — despite R&D having the most total leavers due to its larger size.
3. Employees who left earned significantly less on average (4,787) compared to those who stayed (6,833) — a ~30% pay gap, suggesting compensation is a key driver of attrition.
4. Employees with low or medium job satisfaction (levels 1-2) show notably higher attrition (~16%) compared to those with high satisfaction (~11%).
5. Recommendation: Focus retention efforts on the Sales department and review compensation bands for at-risk roles, alongside initiatives to improve job satisfaction scores.

## Dashboard Preview
![Summary Dashboard](summary_dashboard.png)

## Files
- `hr_data.csv` — raw dataset
- `hr_dashboard.xlsx` — full Google Sheets analysis (exported as Excel)
- `summary_dashboard.png` — screenshot of key insights summary page