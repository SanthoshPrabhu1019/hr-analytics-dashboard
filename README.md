# HR Analytics Dashboard (Power BI)

This repository contains a Power BI dashboard project that analyzes HR data to uncover meaningful insights about employee attrition, job roles, departments, age groups, salary trends, and more.

## 📊 Dashboard Features

- High-level KPIs like total employees, attrition count, average age, salary, and tenure
- Drill-down visualizations of attrition by department, role, age, education, and salary
- Salary slab and work experience correlation with attrition
- Matrix of job roles vs age-wise attrition count

## 📁 Files

| File | Description |
|------|-------------|
| `HR_Analytics.pbix` | Power BI dashboard file containing all visuals and data |
| `HR_Analytics.xlsx` | Source Excel dataset used in the report |
| `HR_Analytics_Dashboard.pdf` | Exported static view of the dashboard for quick preview |
| `screenshots/` | (Optional) Folder containing preview images of the dashboard |

## 🚀 How to Use

1. Clone or download this repository.
2. Open `HR_Analytics.pbix` using Power BI Desktop.
3. If prompted, reconnect to the `HR_Analytics.xlsx` data source.
4. Explore the dashboard visuals and filters to analyze attrition patterns.


## 📷 Preview

You can either:
- View the [PDF dashboard preview](./HR_Analytics_Dashboard.pdf)
- Or open the full interactive `.pbix` report in Power BI Desktop

---

## 📈 Chart Explanations

### 1. **Total Employees (Card)**
Shows the overall number of employees in the dataset (1470). Useful as a reference point for percentages.

### 2. **Attrition (Card)**
Displays the total number of employees who left the organization (237).

### 3. **Average Age (Card)**
Shows the average age of employees, which is ~36.9 years. Helps understand workforce demographics.

### 4. **Average Salary (Card)**
Shows average monthly salary (₹6.5K). Indicates general pay scale.

### 5. **Average Years (Card)**
Displays the average years spent at the company (7 years). Provides insight into tenure.

### 6. **Attrition by Education (Bar Chart)**
Breaks down attrition rates across education fields (e.g., Life Sciences, Medical, Marketing, etc.).

### 7. **Attrition by Age Group (Bar Chart)**
Shows how many employees left within age ranges like 18–25, 26–35, etc.

### 8. **Attrition by Job Role and Age Group (Matrix)**
A detailed breakdown of attrition counts across both job role and age groups. Helps pinpoint combinations with high turnover (e.g., young Lab Technicians).

### 9. **Attrition by Salary Slab (Bar Chart)**
Visualizes attrition in salary ranges such as Upto ₹5K, ₹5K–10K, etc. Highlights how lower salary slabs tend to show higher turnover.

### 10. **Attrition by Job Role and Salary (Horizontal Bar Chart)**
Compares roles like Lab Technician, Sales Executive, etc., based on attrition count and salary slab.

### 11. **Attrition by Years at Work (Bar Chart)**
Displays attrition based on employee experience (in years). Reveals if employees leave early in their tenure.

### 12. **Attrition by Department (Column Chart)**
Shows attrition count across departments such as HR, Sales, and R&D.

---

## 🧠 Key Insights

- 🔺 **High Attrition in Lower Salary Bands**  
  Employees earning below ₹10K show significantly higher attrition compared to higher earners.

- 🧪 **Lab Technicians and Sales Executives Are Most Affected**  
  These roles consistently rank highest in attrition across age and salary bands.

- 🕒 **Early-Career Attrition is Common**  
  A large number of employees leave within the first 5 years of joining.

- 🧓 **Younger Age Groups Are More Likely to Leave**  
  Age groups 18–25 and 26–35 show higher attrition counts, suggesting early-career dissatisfaction or job-hopping.

- 📉 **R&D and Sales Departments See the Most Turnover**  
  These departments need better engagement and retention strategies.

- 🎓 **Education Field Influences Retention**  
  Fields like Life Sciences and Technical Degrees are more prone to attrition than Medical or Marketing.

---


