# Employee Attrition Analysis (Excel)

An interactive Excel dashboard that shows **who is leaving a company and why**, so HR can take action to keep employees.

## Objective
Analyze employee data to find the main reasons behind attrition (employees leaving) and suggest simple ways to reduce it.

## Dataset
300 fictional employee records created for practice. The data is not copied from any company or website.

| Column | Meaning |
|---|---|
| Employee ID | Unique ID |
| Department | Sales, IT, HR, Finance, Operations, Marketing |
| Gender, Age | Employee details |
| Years at Company | How long the employee has worked here |
| Monthly Salary | Salary in rupees |
| Job Satisfaction | 1 (low) to 4 (high) |
| Overtime | Yes / No |
| Attrition | Yes = the employee left |
| Tenure Group, Salary Band | Calculated with formulas |

## Workbook Structure
| Sheet | Purpose |
|---|---|
| README | Project overview and key terms |
| Dashboard | Department dropdown, 5 KPI cards, auto-updating insights, 4 charts |
| Data | Employee records stored as an Excel Table |
| Analysis | Summary tables for department, overtime, satisfaction, tenure and salary band |

## Excel Skills Used
- Excel Table and calculated columns (`IF`)
- `COUNTIFS`, `AVERAGEIFS`, `INDEX/MATCH`, `TEXT`, `IFERROR`
- Data Validation dropdown that filters the whole dashboard
- Conditional Formatting (colour scales and highlights)
- Bar and column charts with data labels
- Dashboard design with KPI cards

## Key Insights
- Overall attrition rate is **24.7%** (74 of 300 employees left).
- **Sales** has the highest attrition (32.8%), and **Finance** has the lowest (17.1%).
- Employees working **overtime** leave at **40.0%**, compared with **17.0%** for those who do not.
- Employees with the **lowest job satisfaction** leave at **34.3%**, versus **15.1%** for the most satisfied.
- **New joiners** (0-2 years) have the highest attrition at **35.2%**.

## Recommendations
1. Reduce overtime, especially in Sales and Operations, or pay and reward it better.
2. Run regular satisfaction surveys and follow up with employees who score 1 or 2.
3. Create a strong onboarding and mentoring program for the first two years.
4. Review the Sales team's workload and targets.

## How to Use
1. Download `Employee_Attrition_Analysis.xlsx` and open it in Excel.
2. On the **Dashboard** sheet, click the yellow cell and choose a department.
3. The KPI cards, insights, and three of the four charts update for that department.

## Dashboard Preview
![Dashboard](dashboard (1).png)

## Possible Improvements
- Add a PivotTable with slicers
- Add age group and gender analysis
- Build a simple risk score to flag employees likely to leave

## Author
**Vasireddy JayaBalaji**
[LinkedIn](https://www.linkedin.com/in/vasireddyjayabalaji)
