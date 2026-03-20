#  HR Analytics Dashboard (Excel)

An interactive HR Analytics Dashboard built in Microsoft Excel to analyze workforce trends, employee distribution, hiring patterns, and attrition.

---

##  Dashboard Preview

![Dashboard](screenshots/hr_dashboard_screenshot.png)

---

##  Tools & Skills Used

- Microsoft Excel
- Pivot Tables & Pivot Charts
- Data Cleaning & Transformation
- KPI Design using Shapes
- Slicers for Interactivity
- Excel Functions:
  - `DATEDIF`
  - `COUNTIF`
  - `AVERAGE`
  - `IF`

---

##  Features

- Interactive dashboard with slicers:
  - Gender
  - Location
  - Hire Source
  - Contract Type

- KPI Cards:
  - Total Hires
  - Active Employees
  - Total Exits
  - Average Age
  - Average Tenure
  - Employee Attrition Rate

- Visual Insights:
  - Hiring by Year
  - Employees by Gender
  - Employees by Location
  - Employees by Department
  - Employees by Hire Source

---

##  Key Insights

- Employee attrition rate is **38.74%**, indicating moderate retention challenges.
- Hiring peaked in earlier years and shows a **declining trend in recent years**.
- Workforce is concentrated in **New York and Austin**, though many records contain "Unknown" values.
- Recruitment is driven mainly through **career fairs, referrals, and agencies**.
- **IT and Marketing** departments have the highest employee count.
- Average tenure (~7.9 years) suggests strong long-term retention among active employees.

---

##  Challenges

- Presence of **missing/unknown values** in:
  - Location
  - Department
- Data quality impacts accuracy of insights
- KPI cards were not updating dynamically after connecting them to pivot table values using slicers.
- After reopening the Excel file, KPI-linked cells started behaving like static text instead of dynamic values.

---

##  Improvements (Future Scope)

- Integrate with Power BI for advanced visualization
- Use SQL for scalable data handling
- Apply data validation to reduce missing values
- Add time-based attrition analysis

---

##  Project Structure
Dataset → data/hr_dataset.xlsx
Dashboard → dashboard/hr_dashboard.xlsx

---

##  Conclusion

This project demonstrates:

- End-to-end data analysis in Excel
- Dashboard design and storytelling
- Ability to extract actionable insights from HR data

---


