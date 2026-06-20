# 📊 People Analytics Dashboard: Workforce, Attendance, Performance & Payroll Insights

## 📌 Overview

This project presents an end-to-end Human Resource Analytics solution developed using **Microsoft Excel** and **Power BI**. The objective is to transform raw HR datasets into actionable insights through data cleaning, modeling, visualization, and dashboarding.

The dashboard provides comprehensive insights into workforce demographics, attendance patterns, employee performance, recruitment effectiveness, and payroll expenses to support strategic HR decision-making.

---

## 🎯 Objectives

The primary objectives of this project are:

- To clean and preprocess HR datasets using Microsoft Excel.
- To develop an interactive People Analytics Dashboard using Power BI.
- To monitor workforce demographics and employee distribution.
- To analyze attendance trends and absenteeism patterns.
- To assess employee performance and productivity metrics.
- To evaluate payroll costs and compensation structures.
- To support data-driven HR decision-making.

---

## 📂 Dataset Information

The project consists of five major datasets.

| Dataset | Number of Records |
|---------|------------------|
| Employees | 20,000 |
| Attendance | 150,000 |
| Recruitment | 12,000 |
| Performance | 60,000 |
| Payroll | 180,000 |

### Domain
Human Resource Analytics

### Timeline
2023 – 2025

---

## 🛠 Tools & Technologies Used

### Microsoft Excel

Used for:

- Data Cleaning
- Handling Missing Values
- Removing Duplicates
- Data Transformation
- Pivot Table Analysis
- Feature Engineering

### Power BI

Used for:

- Power Query
- Data Modeling
- Relationship Building
- DAX Calculations
- Interactive Dashboard Creation
- KPI Development

---

## 📋 Data Preprocessing

The following preprocessing activities were performed:

### Data Cleaning

✔ Removed duplicates

✔ Standardized date formats

✔ Corrected inconsistent values

✔ Handled missing records

### Data Transformation

Created analytical columns such as:

- Engagement Band
- Satisfaction Band
- Experience Band
- Stability Group

### Data Segmentation

Created separate tables:

- Employees
- Attendance
- Recruitment
- Performance
- Payroll

---

## 🧮 DAX Measures Implemented

Examples of DAX calculations used in the project:

```DAX
Total Employees =
COUNT(Employees[Employee_ID])


Active Employees =
CALCULATE(
COUNT(Employees[Employee_ID]),
Employees[Employment_Status]="Active"
)


Inactive Employees =
CALCULATE(
COUNT(Employees[Employee_ID]),
Employees[Employment_Status]="Terminated"
)


Attrition Rate =
DIVIDE(
[Inactive Employees],
[Total Employees]
)


Average CTC =
AVERAGE(Employees[CTC])


Average Engagement =
AVERAGE(Employees[Engagement_Score])


Average Satisfaction =
AVERAGE(Employees[Satisfaction_Score])


Attendance Percentage =
DIVIDE(
SUM(Attendance[Present_Days]),
SUM(Attendance[Present_Days])
+
SUM(Attendance[Absent_Days])
)


Total Overtime Hours =
SUM(Attendance[Overtime_Hours])


Average Gross Pay =
AVERAGE(Payroll[Gross_Pay])


Average Net Pay =
AVERAGE(Payroll[Net_Pay])


Average KPI Score =
AVERAGE(Performance[KPI_Score])


Average Productivity =
AVERAGE(Performance[Productivity_Score])


Total Promotions =
SUM(Performance[Promotion_Count])
```

---

## 📊 Dashboard Pages


### Employee Summary

KPIs Included

• Total Employees

• Active Employees

• Attrition Rate

• Average CTC

• Employee Engagement



### Workforce Analysis

Visualizations Included

• Department-wise Employee Distribution

• Gender Analysis

• Location Analysis

• Work Mode Analysis

• Experience Band Distribution

• Employee Stability Analysis



### Attendance Analysis

Visualizations Included

• Attendance Percentage

• Present vs Absent Days

• Overtime Trends

• Late Mark Analysis

• Leave Without Pay Analysis



### Payroll Analysis

Visualizations Included

• Gross Pay Analysis

• Net Pay Analysis

• Bonus Distribution

• PF Contribution

• ESI Analysis

• Payroll Cost Trend



### Performance Analysis

Visualizations Included

• KPI Score Analysis

• Productivity Trends

• Manager Rating Analysis

• Promotion Summary

• Training Hours Analysis



---

## 📈 Key Insights

### Descriptive Insights

- Workforce distribution varies significantly across departments.

- Employee satisfaction levels are generally moderate to high.

- Attendance trends reveal opportunities to reduce absenteeism.


### Diagnostic Insights

- Departments with high overtime tend to experience lower engagement scores.

- Attrition is influenced by employee satisfaction and stability.


### Predictive Insights

- Employees with lower engagement levels are more likely to leave the organization.


### Prescriptive Insights

- HR teams should implement engagement improvement programs.

- Attendance management initiatives can reduce absenteeism.

- Targeted training interventions may enhance productivity.



---

## 📷 Dashboard Screenshots

Place screenshots inside the Images folder.

```text
Images/

Employee_Summary.png

Workforce_Analysis.png

Attendance_Analysis.png

Payroll_Analysis.png

Performance_Analysis.png
```


Display Images


```markdown
![Employee Summary](Images/Employee_Summary.png)

![Workforce Analysis](Images/Workforce_Analysis.png)

![Attendance Analysis](Images/Attendance_Analysis.png)

![Payroll Analysis](Images/Payroll_Analysis.png)

![Performance Analysis](Images/Performance_Analysis.png)
```


---

## 📁 Project Structure


```text
People-Analytics-Dashboard/

│

├── Dataset/

│ └── HR_Analytics_Cleaned_Dataset.xlsx


├── PowerBI/

│ └── People_Analytics_Dashboard.pbix


├── Images/

│ ├── Employee_Summary.png

│ ├── Workforce_Analysis.png

│ ├── Attendance_Analysis.png

│ ├── Payroll_Analysis.png

│ └── Performance_Analysis.png


├── Documentation/

│ └── Project_Report.pdf


└── README.md
```


---

## 🚀 Future Enhancements

- Attrition Prediction Model

- Machine Learning Integration

- Sentiment Analysis

- Automated Refresh using Power BI Service

- HR KPI Benchmarking Dashboard



---

## 👨‍💻 Author

### Balachander V

Data Analyst | Power BI Developer | HR Analytics Enthusiast


### Connect with Me

LinkedIn:
www.linkedin.com/in/vbalachander


GitHub:
https://github.com/Balachander7


Email:
vbcchandru777@gmail.com



---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

Thank you for visiting my project repository!
