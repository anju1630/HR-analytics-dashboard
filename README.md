# HR-analytics-dashboard
power bi dashboard


## 📌 Project Overview

This project is an interactive **HR Analytics Dashboard built using Microsoft Power BI** to analyze employee workforce data, attrition, retention, salary, attendance, performance, and hiring trends.

The dashboard consists of two interactive pages:

1. **Workforce Overview**
2. **Attrition & Retention Analysis**

The goal of this project is to transform raw HR data into meaningful insights that can help understand workforce patterns and employee attrition.

---

## 🎯 Objectives

- Analyze total, active, and resigned employees
- Calculate and visualize employee attrition rate
- Analyze resignations across departments and job titles
- Understand employee tenure and retention patterns
- Compare salary, attendance, and performance
- Analyze hiring and exit trends over time
- Build an interactive HR dashboard using Power BI

---

## 📊 Dashboard Pages

### 1. Workforce Overview

The first dashboard provides an overall view of the workforce.

**Key KPIs:**
- Total Employees
- Active Employees
- Resigned Employees
- Attrition Rate
- Average Salary

**Analysis includes:**
- Attrition Rate by Department
- Average Salary by Department
- Average Salary by Gender
- Resigned Employees by Gender
- Average Attendance by Department
- Average Rating by Department
- Attendance vs Performance Analysis

**Interactive Filters:**
- Department
- Gender
- Employee Status

---

### 2. Attrition & Retention Analysis

The second dashboard focuses specifically on employee attrition and retention.

**Analysis includes:**
- Resigned Employees by Department
- Resigned Employees by Job Title
- Resigned Employees by Tenure
- Average Tenure by Employee Status
- Hiring vs Exit Trend
- Employee Status Distribution

**Interactive Filters:**
- Department
- Gender

---

## 🛠️ Tools & Technologies

- **Microsoft Power BI**
- **Power Query**
- **DAX**
- **Data Modeling**
- **Data Visualization**

---

## 🔄 Data Preparation

The raw HR data was prepared using **Power Query**.

Major steps included:

- Data cleaning
- Handling missing values
- Correcting data types
- Date transformation
- Creating calculated columns
- Creating tenure bands
- Preparing data for analysis
- Creating DAX measures for KPIs

> Missing `Exit Date` values represent employees who are currently active and were therefore retained as NULL rather than being filled or removed.

---

## 📐 Key DAX Measures

Some of the major measures created in the project include:

- Total Employees
- Active Employees
- Resigned Employees
- Attrition Rate
- Average Salary
- Average Tenure
- Hired Employees
- Exited Employees

---

## 📁 Repository Structure

```text
HR-Analytics-PowerBI/
│
├── README.md
│
├── PowerBI/
│   └── HR_Analytics_Dashboard.pbix
│
├── Dataset/
│   ├── employees.csv
│   ├── departments.csv
│   ├── ...
│
├── Dashboard/
│   ├── Page1_Workforce_Overview.png
│   └── Page2_Attrition_Retention.png
│
└── Documentation/
    └── Project_Notes.pdf
💡 Key Insights

The dashboard helps identify:

Departments with higher employee attrition
Job roles with more resignations
Tenure groups where employees are more likely to leave
Differences between active and resigned employees
Hiring and exit patterns over time
Relationship between employee attendance and performance
📸 Dashboard Preview
Workforce Overview

Add dashboard screenshot here

Attrition & Retention

Add dashboard screenshot here

🚀 Learning Outcomes

Through this project, I gained practical experience in:

Power BI dashboard development
Power Query data transformation
DAX calculations
Data modeling
Interactive visualization
HR analytics
Data storytelling
👤 Author

Anjali Rode

⭐ If you found this project useful, feel free to explore the repository.

```text
HR-Analytics-PowerBI
│
├── Dataset
│   ├── employees.csv
│   ├── ...
│
├── Dashboard
│   ├── HR_Analytics_Dashboard.pbix
│   ├── Workforce_Overview.png
│   └── Attrition_Retention.png
│
└── README.md
