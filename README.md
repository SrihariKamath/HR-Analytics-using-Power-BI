# HR Analytics Dashboard with Power BI
---

## 🚀 Project Overview

This project demonstrates the power of Microsoft Power BI in HR analytics, enabling HR professionals at Atlas Labs to visualize, analyze, and act on key workforce metrics. The dashboard provides a comprehensive view of employee data, focusing on attrition drivers, demographic trends, and departmental breakdowns.

---

## 🎯 Project Goals

- **Integrate and model HR data**: Combine employee, performance, and satisfaction datasets for holistic analysis.
- **Visualize key metrics**: Track headcount, active/inactive employees, and attrition rates.
- **Analyze workforce trends**: Explore demographics, department/job role distributions, and hiring patterns.
- **Identify attrition drivers**: Examine the impact of job role, business travel, and overtime on turnover.
- **Enable interactive exploration**: Empower HR users to filter and segment data for deeper insights.

---

## 🛠️ Tech Stack

- **Power BI Desktop**: Core analytics and visualization tool
- **Power Query**: Data loading, cleaning, and transformation (ETL)
- **Power Pivot/Data Model**: Data relationships and schema
- **DAX**: Custom metrics and calculated columns
- **Data Sources**: Excel/CSV files (employee, performance, and dimension tables)

---

## 📊 Dashboard Structure

### 1. Overview Page

- **KPI Cards**:  
  - Total Employees: 1,470  
  - Active Employees: 1,233  
  - Inactive Employees: 237  
  - Attrition Rate: 16.12%
- **Trends**:  
  - *Total Employees by Year* (Line Chart): Shows workforce fluctuations from 2012–2022.
- **Diversity & Pay**:  
  - *Bar & Line Combo*: Total employees and average salary by ethnicity.
- **Department & Role Breakdown**:  
  - *Treemap*: Visualizes employee counts by department and job role (e.g., Technology, Sales, HR).
- **Interactive Slicer**:  
  - Attrition filter ("No"/"Yes") updates all metrics and visuals for targeted analysis.

### 2. Attrition Page

- **Attrition by Job Role**:  
  - *Horizontal Bar Chart*: Highlights roles with highest attrition (e.g., Sales Rep 39.76%, Recruiter 37.5%, Data Scientist 23.75%).
- **Attrition by Business Travel**:  
  - *Bar & Line Combo*: Attrition rate and employee count by travel frequency (Frequent Traveller: 24.91%, Some Travel: 14.96%, No Travel: 8%).
- **Attrition by Overtime**:  
  - *Bar Chart*: Overtime workers face much higher attrition (Yes: 30.53%, No: 10.44%).

---

## 💡 Key Insights

- **High-risk roles**: Sales Representative, Recruiter, and Data Scientist have the highest attrition rates.
- **Travel and overtime**: Frequent business travel and overtime are strongly linked to increased attrition.
- **Departmental focus**: Technology is the largest department, but some roles require targeted retention strategies.
- **Diversity & compensation**: Employee distribution and average salary vary by ethnicity, offering opportunities for DEI initiatives.
- **Trend monitoring**: Headcount trends reveal periods of contraction and recovery, supporting strategic planning.

---

## 📷 Screenshots

**Overview Page**  
![Overview](./screenshots/overview.jpg)

**Attrition Page**  
![Attrition](./screenshots/attrition.jpg)

---

## ✅ How to Use

1. Open `HR-Analytics-Dashboard.pbix` in Power BI Desktop.
2. Explore the **Overview** page for high-level workforce metrics.
3. Use the **Attrition** page to analyze turnover drivers by job role, business travel, and overtime.
4. Apply the **Attrition slicer** to filter and segment data as needed.

---

## 🏆 Why Power BI for HR Analytics?

Power BI democratizes HR analytics, turning complex data into clear, interactive visuals that drive better decision-making, improve retention, and enhance employee satisfaction.

---

*For questions or feedback, connect with me on LinkedIn or GitHub!*
