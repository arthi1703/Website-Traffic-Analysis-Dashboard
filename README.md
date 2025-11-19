📊 Website Traffic Analysis Dashboard — Power BI Project

⭐ Project Overview

This project focuses on analyzing website traffic patterns, user engagement, and marketing effectiveness through an interactive Power BI Dashboard.

The dashboard provides insights on:

🚦 Traffic trends over time

👥 New vs Returning Users

📱 Device usage distribution

🌍 Geographic visitor performance

📈 Conversion & revenue metrics

🔗 Marketing channel performance

📁 Files Included
File Name	Description
web_marketing_data.xlsx / .csv	Raw dataset from Kaggle
website_traffic_cleaned.xlsx	Cleaned dataset for dashboard
website_traffic_analysis.pbix	Power BI dashboard
Website_Traffic_Project_Report.pdf	Full project documentation
README.md	GitHub documentation

🎯 Project Objective

To build a detailed website traffic analysis dashboard that helps:

Track sessions & user activity

Understand daily traffic trends

Measure user engagement

Analyze conversions & revenue

Evaluate marketing source performance

📂 Dataset Description

📌 Source: Kaggle – Web Marketing Campaign Performance Analysis Dataset
📌 Each row = one website session

Key Columns:

user_id

new_user

page_views

session_duration_seconds

device_type

country

source (Direct, Organic, Social, Referral)

conversions

revenue

date

👉 Dataset Link:
[🔗 Click Here to Access Dataset]https://github.com/arthi1703/Website-Traffic-Analysis-Dashboard/blob/main/web_marketing_data.csv

🧹 Data Cleaning & Preparation

✔ Removed duplicates
✔ Managed missing values
✔ Converted date column
✔ Normalized numeric fields
✔ Ensured correct device/source categories
✔ Verified binary values
✔ Exported cleaned dataset

🧮 DAX Measures Used
Total Sessions = COUNTROWS('web_marketing_data')

Total Users = DISTINCTCOUNT('web_marketing_data'[user_id])

New Users = SUM('web_marketing_data'[new_user])

Returning Users = [Total Users] - [New Users]

Total Page Views = SUM('web_marketing_data'[page_views])

Avg Session Duration = AVERAGE('web_marketing_data'[session_duration_seconds])

Conversion Rate = DIVIDE([Total Conversions], [Total Sessions])


Additional Measures:

Page Views per Session

Average Session Duration (Minutes)

Revenue per User

Total Revenue

Sessions by Device

Users by Country

📊 Dashboard Visuals
🟦 1️⃣ KPI Cards

Total Users

New Users

Page Views

Avg Duration

Conversion Rate

📈 2️⃣ Line Chart

Website Traffic trend over time

🎯 3️⃣ Scatter Plot

Page Views vs Session Duration

🍩 4️⃣ Donut Chart

Visitors Divices

📉 5️⃣ Area Chart

Traffic Origin

🗺️ 6️⃣ Map

Top Visitors Country

🖼️ Dashboard Screenshot

<img width="1323" height="739" alt="website_traffic_analysis_screenshot" src="https://github.com/user-attachments/assets/7d5ea953-9b48-4de4-bf39-26ff94e8f9f0" />


📈 Insights

Mobile accounts for the highest user traffic

Direct & Organic sources bring the most visitors

Traffic peaks on key campaign days

Higher page views → longer session duration

US, India, UK, Germany lead visitor count

Conversions reflect strong engagement patterns

🚀 Conclusion

The dashboard helps stakeholders to:

✔ Identify top-performing traffic channels
✔ Analyze user behavior
✔ Improve marketing strategies
✔ Track conversions & revenue growth

✍️ Author
👤 Arthi

Data Analyst






