# Illinois Hospital Readmission Dashboard

![Power BI](https://img.shields.io/badge/Tool-Power%20BI-yellow?logo=powerbi)

This Power BI dashboard analyzes hospital readmissions in Illinois using publicly available data.

## 📊 Visuals Included
- Hospitals ranked by readmission volume
- Hospitals ranked by readmission rate score
- Most common readmission conditions
- Interactive map of hospitals
- Hospital slicer to filter conditions

## 📁 Files
- `IL_HSP_READMISSION_RATES.pbix`: Power BI project file
- `IL READMISSION POWER BI DASHBOARD.png`: Screenshot of the full dashboard

## 🔍 Tools Used
- Power BI
- DAX
- Public hospital readmission data

## 💡 Insights
- Surgical care improvement is the top cause of readmissions
- Chicago hospitals dominate the high-volume readmission list
- Interactive filters allow hospital-specific condition insights

## 📂 Data Source

Data obtained from [Kaggle – Hospital Readmission Rates Dataset](https://www.kaggle.com/datasets/thedevastator/hospital-care-quality-measures).  
Original source: Centers for Medicare & Medicaid Services (CMS)

🔧 Data Preparation
The original dataset included nationwide hospital readmission data. For the purpose of this analysis, I filtered the data to include only Illinois hospitals, focusing specifically on the Chicago metropolitan area. I also performed data cleaning to remove duplicates, standardize hospital names, and ensure consistency across fields such as city, condition type, and readmission scores.

Data transformations were performed using Power BI’s Power Query Editor, including column filtering, type conversion, and renaming for clarity
