# HR Attrition Analysis  
**IBM SkillsBuild Decoding Data PBL Program 2025 – Final Project**

---

## 📌 Project Overview  
Employee attrition is a critical challenge faced by organizations, leading to increased hiring costs, loss of experienced talent, and reduced team performance.  
This project analyzes **HR Attrition Data** using **Microsoft Excel** and **Power BI** to uncover patterns, identify high-risk groups, and support HR teams with **data-driven decision-making**.  

---

## 🎯 Objectives  
- Identify key factors contributing to employee attrition.  
- Compare attrition across **departments, job roles, and age groups**.  
- Calculate average tenure of employees leaving the organization.  
- Develop an **interactive Power BI dashboard** for HR insights.  
- Recommend actionable strategies for employee retention.  

---

## 🛠️ Tools & Technologies  
- **Microsoft Excel** → Data cleaning & preprocessing.  
- **Power BI** → Dashboard design & visualization.  
- **DAX (Data Analysis Expressions)** → Custom calculations (Attrition Rate, Avg Age, Tenure).  

---

## 📂 Dataset  
- **Source**: [IBM HR Analytics Employee Attrition Dataset (Kaggle)](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)  
- **Records**: 1,470 employees  
- **Features**: 35 columns  
- **Key Attributes**: Age, Gender, Department, Job Role, Tenure, Attrition Status, Work Environment  

---

## 🧹 Data Preprocessing  
- Removed redundant columns: `Over18`, `EmployeeCount`, `StandardHours`  
- Standardized categorical values (e.g., department names)  
- Created new derived features:  
  - `AgeGroup` (Under 30, 30–40, Over 40)  
  - `Tenure` (based on Total Working Years)  
- Verified dataset integrity → No missing/null values  

---

## 📊 Data Analysis & Insights  
- **Highest Attrition**: Sales & HR Departments  
- **At-risk Group**: Employees **under 30 years**, especially in **Sales roles**  
- **Average Tenure of Attrition Cases**: < 4 years  
- **Job Roles**: Sales Representatives & Lab Technicians → highest attrition  

👉 Insight: Younger employees in sales-oriented, high-pressure jobs are most likely to leave.  

---

## 🧪 Hypothesis  
> Employees **under the age of 30 in Sales roles** are more likely to leave than others.  

- **Rationale**: Younger employees seek career growth, and Sales roles are high-stress.  
- **Validation**: Power BI analysis confirmed higher attrition in this segment.  

---

## 💡 Solution Design  
- **Power BI Dashboard** with interactive visualizations:  
  - Attrition by Department (Bar Chart)  
  - Attrition by Age Group (Pie Chart)  
  - Tenure vs Attrition (Column Chart)  
  - Job Role vs Attrition Rate (Stacked Bar)  
- Interactive Filters: Department, Job Role, Age Group, Gender  

🔗 **Dashboard Link**: [GitHub Repository](https://github.com/RAMANADAM-VENKATA-SIVA-SAI/Power-bi-dashboard-)  

---

## ✅ Impact  
- Helps HR monitor attrition trends in real-time.  
- Identifies **high-risk employee groups**.  
- Enables **data-driven retention strategies**.  
- Reduces recruitment & training costs.  

---

## 🔮 Future Scope  
- Integrate **machine learning models** for attrition prediction.  
- Add **employee survey/feedback data** for deeper insights.  
- Automate **alerts** for rising attrition trends.  
- Expand dashboard to track **diversity, engagement, and performance metrics**.  

---

## 🌍 Alignment with SDGs  
- **SDG 8**: Decent Work & Economic Growth – Improve job satisfaction & retention.  
- **SDG 9**: Industry, Innovation & Infrastructure – Leverage data-driven HR solutions.  

---

## 👥 Team – Brainy Bunch (Mohan Babu University)  
- **Team Leader**: V. Devi Sree – [Email](mailto:vuppalapatidevisree@gmail.com)  
- **Members**:  
  - Ramanadam Venkata Siva Sai  
  - Dasa Haritha  
  - Gundavarapu N H S H S Nithya  
  - Aduri Sai Manikanta Lohith  

---

## 📚 References  
- IBM HR Analytics Dataset (Kaggle)  
- Microsoft Excel & Power BI Documentation  
- Research articles on workforce retention & attrition prediction  

---
