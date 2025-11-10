# Power BI - HR Attrition Analytics Dashboard

## 📌 Objective
Analyze employee attrition and discover patterns across:
- Age
- Salary band
- Job role
- Education
- Department

## ✅ Key Insights
- Highest attrition in XYZ department
- OverTime employees contribute to majority attrition
- Low salary band shows maximum attrition %

## 🛠 Skills Used
Power BI • Power Query • DAX • Data Modeling • ETL • KPIs • Storytelling with Data

## 🧠 DAX Measures
Total Employees = COUNTROWS(HR)
Attrition Count = CALCULATE(COUNTROWS(HR), HR[Attrition] = "Yes")
Attrition % = DIVIDE([Attrition Count], [Total Employees], 0)

## 🔗 Live Dashboard
https://app.powerbi.com/reportEmbed?reportId=d953923c-19db-4717-98c7-fda6159f38a3&autoAuth=true&ctid=68fa027e-d599-4724-8870-99bdcaded2f9

## 📁 Files Included
- Dashboard.pbix
- Screenshots
- README.md
