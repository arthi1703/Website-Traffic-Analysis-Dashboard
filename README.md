# 📊 Website Traffic Analysis Dashboard — Power BI Project

## ⭐ Project Overview
This project analyzes website traffic patterns, user engagement, and marketing performance using an interactive **Power BI Dashboard**.

The dashboard provides insights on:

 🚦 Traffic trends over time  
 👥 New vs Returning Users  
 📱 Device usage distribution  
 🌍 Geographic visitor performance  
 📈 Conversion & revenue metrics  
 🔗 Marketing channel performance  

## 📁 Files Included

| File Name                         | Description                          |
|----------------------------------|--------------------------------------|
| web_marketing_data.csv / .xlsx   | Raw dataset from Kaggle              |
| website_traffic_cleaned.xlsx     | Cleaned dataset used in dashboard    |
| website_traffic_analysis.pbix    | Power BI dashboard                   |
| Website_Traffic_Project_Report.pdf | Full project documentation         |
| README.md                        | Project documentation                |
| website_traffic_analysis_visual  | Dashboard Overview Snapshot          |

## 🛠️ Tools Used

### 🟦 Power BI Desktop  
Used to build the complete dashboard — data modeling, visuals, and reporting.

### 🟩 Power Query Editor  
Used for cleaning, transforming, and shaping the raw CSV dataset.

### 🟨 DAX (Data Analysis Expressions)  
Used to create KPIs, calculated measures, and advanced metrics.

### 📄 Excel / CSV Dataset  
Used as the primary data source for website traffic analysis.

### 🎨 Power BI Visualizations  
Used to design charts such as line, bar, donut, scatter, area, and map visuals.


## 🎯 Project Objective
To build a website traffic analysis dashboard that helps:

 ✔ Track sessions & user activity  
 ✔ Understand daily traffic trends  
 ✔ Measure user engagement  
 ✔ Analyze conversions & revenue  
 ✔ Evaluate marketing source performance  

## 📂 Dataset Description

**Source:** Kaggle – Web Marketing Campaign Performance Analysis Dataset  
**Each row represents:** One website session  

### Key Columns
- user_id  
- new_user  
- page_views  
- session_duration_seconds  
- device_type  
- country  
- source (Direct, Organic, Social, Referral)  
- conversions  
- revenue  
- date  

👉 **Dataset Link:**  
https://github.com/arthi1703/Website-Traffic-Analysis-Dashboard/blob/main/web_marketing_data.csv

## 🧹 Data Cleaning & Preparation

Performed cleaning tasks:

  ✔ Removed duplicates  
  ✔ Managed missing values  
  ✔ Converted and formatted date column  
  ✔ Normalized numeric fields  
  ✔ Verified device and channel categories  
  ✔ Checked binary values  
  ✔ Exported cleaned dataset  

## 🧮 DAX Measures Used

Total Sessions = COUNTROWS('web_marketing_data')

Total Users = DISTINCTCOUNT('web_marketing_data'[user_id])

New Users = SUM('web_marketing_data'[new_user])

Returning Users = [Total Users] - [New Users]

Total Page Views = SUM('web_marketing_data'[page_views])

Avg Session Duration = AVERAGE('web_marketing_data'[session_duration_seconds])

### Additional Measures
- Conversion Rate
- Total Conversions 
- Page Views per Session  
- Average Session Duration (Minutes)
- Revenue per Session 
- Revenue per User  
- Total Revenue  
- Sessions by Device  
- Users by Country



## 📊 Dashboard Visuals

### 🟦 KPI Cards
- Total Users  
- New Users  
- Page Views  
- Avg Session Duration  
- Conversion Rate  

### 📈 Line Chart
- Daily traffic trends  

### 🎯 Scatter Plot
- Page Views vs Session Duration  

### 🍩 Donut Chart
- Device usage distribution  

### 📉 Area Chart
- Traffic source comparison  

### 🗺️ Map
- Visitors by country

### 🟩 Column Chart
- Ranks campaigns based on Total Revenue generated.


## 🖼️ Dashboard Screenshot
<img width="1324" height="740" alt="website_traffic_analysis_visual " src="https://github.com/user-attachments/assets/9eb50d19-9f01-4ac0-a115-17e2704f8383" />



## 📈 Insights
- Mobile devices drive the majority of traffic  
- Direct & Organic channels bring maximum visitors  
- Traffic peaks align with time  
- Higher page views → longer session duration  
- India, USA, UK & Germany contribute the most traffic  
- Conversion patterns show moderate engagement
- Identifies which campaigns are generating the most revenue
- Helps in budget allocation: you can invest more in high-performing campaigns



## 🚀 Conclusion
This dashboard supports:

  ✔ Tracking of traffic & marketing performance  
  ✔ Better user engagement analysis  
  ✔ Optimized decision-making for campaigns  
  ✔ Monitoring revenue & conversions confidently  



## ✍️ Author
**👤 Arthi**  
_Data Analyst_  

