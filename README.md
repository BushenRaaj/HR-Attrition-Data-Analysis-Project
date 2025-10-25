# 🧾 HR Employee Attrition Analysis Project

## 📘 Overview
This project aims to analyze employee attrition using HR data to uncover patterns that influence employee turnover. The process involves cleaning, transforming, and visualizing the data to derive actionable insights that can help improve employee retention strategies.

---

## 🎯 Objectives
- Identify factors contributing to employee attrition.  
- Understand employee satisfaction, income, performance, and tenure trends.  
- Develop Power BI dashboards for data visualization and decision-making support.  

---

## 🧩 Tools & Technologies Used
- **Python (Jupyter Notebook)** – Data cleaning, preprocessing, and transformation.  
- **Pandas, NumPy, Matplotlib, Seaborn** – Data analysis and visualization in Python.  
- **Power BI** – Dashboard creation and KPI visualization.  
- **Excel** – Cleaned dataset storage and manipulation.  

---

## 🧮 Datasets
- **Raw Dataset:** `WA_Fn-UseC_-HR-Employee-Attrition.csv`  
- **Cleaned Dataset:** `Cleaned_HR_Attrition.xlsx`
- **Jupyter Notebook script** `Cleaning_Dataset.ipynb`  
- **Power BI File:** `HR_Attrition_Data_Sheet.pbix`  

---

## 🧱 Steps Involved in Building the Project

### 1. Data Collection
- Imported the raw dataset (`WA_Fn-UseC_-HR-Employee-Attrition.csv`) for analysis.

### 2. Data Cleaning (Python - Jupyter Notebook)
- Handled missing values, standardized column names, and converted categorical data into dummy variables.  
- Exported the cleaned data to Excel as `Cleaned_HR_Attrition.xlsx`.

### 3. Data Transformation (Power BI)
- Dropped redundant columns including `OverTime_Yes`, `Department_Research & Development`, `JobRole_Manager`, etc.  
- Added calculated columns such as:  
  - **Age Group**, **Salary Band**, **Employee Tenure**, **Risk Score**, and **Risk Category**.  
- Created **DAX measures** for key metrics like:  
  - `Total Employees`, `Avg Monthly Income`, `Attrition Rate`, `Avg Job Satisfaction`, etc.

### 4. Visualization (Power BI Dashboard)
- Designed interactive visuals showing attrition distribution, income vs. tenure, satisfaction vs. performance, etc.  
- Highlighted high-risk groups and key trends using custom KPIs.

---

## 📊 Key Insights
- Younger employees and those with lower monthly incomes had higher attrition rates.  
- Employees with poor job satisfaction or limited career growth showed higher attrition risk.  
- The Risk Score model effectively categorized employees into **Low**, **Medium**, and **High** attrition risk levels.  

---

## 🧠 Conclusion
The analysis provides valuable insights into employee attrition trends and influencing factors.  
By leveraging **Power BI dashboards** and **predictive metrics**, HR departments can take proactive measures to retain employees and improve job satisfaction.

---
