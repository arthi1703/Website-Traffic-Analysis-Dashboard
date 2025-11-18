📊 Website Traffic Analysis Dashboard — Power BI Project

📌 Project Overview

This project focuses on analyzing website traffic patterns, user engagement, and marketing performance using an interactive Power BI dashboard. The dashboard visualizes real-time insights such as traffic trends, user behavior, device usage, conversion metrics, and geographic distribution of visitors.

The analysis helps understand:

Which channels bring maximum traffic

How users interact with the website

Conversion performance across traffic sources

Device and country distribution of visitors

Day-wise session behavior and duration

📁 Files Included
File	Description
web_marketing_data.xlsx / csv	Raw dataset collected from Kaggle
website_traffic_cleaned.xlsx	Cleaned & preprocessed dataset used for dashboard
website_traffic_analysis.pbix	Power BI dashboard file
Website_Traffic_Project_Report.pdf	Project report including objectives, dataset description, cleaning steps, dashboard design & insights
README.md	Documentation for GitHub

🎯 Project Objective

To build a data-driven website traffic analysis dashboard that helps track user activity, identify marketing channel performance, observe traffic trends, and measure conversions using Power BI.

📂 Dataset Description

The dataset was sourced from Kaggle:
“Web Marketing Campaign Performance Analysis Dataset”

Key columns include:

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

Each row represents one website session.

🔧 Tools Used

Power BI Desktop – Dashboard creation

Excel – Data cleaning and preprocessing

Python (optional) – Additional formatting/processing

Kaggle Dataset – Data source

🧹 Data Cleaning & Preparation

The following steps were applied during cleaning:

✔ Removed duplicates
✔ Checked and handled missing values
✔ Converted date column into proper date format
✔ Normalized numerical columns (session duration, page views)
✔ Ensured new_user & conversions were binary values
✔ Validated device_type, country, traffic source categories
✔ Exported cleaned dataset as Excel file

🧮 DAX Measures Used

Some key measures used in the dashboard:

Total Sessions = COUNTROWS('web_marketing_data')

Total Users = DISTINCTCOUNT('web_marketing_data'[user_id])

New Users = CALCULATE(SUM('web_marketing_data'[new_user]))

Returning Users = [Total Users] - [New Users]

Total Page Views = SUM('web_marketing_data'[page_views])

Avg Session Duration = AVERAGE('web_marketing_data'[session_duration_seconds])

Conversion Rate = DIVIDE([Total Conversions], [Total Sessions])

Total Conversions = SUM('web_marketing_data'[conversions])


Additional measures included:

Average Session Duration(Minutes)

Sessions by Device

Page Views per Session

Revenue per Session

Revenue per User

Total Revenue

Users by Country

📊 Dashboard Visuals

The Power BI dashboard includes:

1️⃣ KPI Cards

Total Users

New Users

Total Page Views

Page Views per Session

Avg Session Duration

Conversion Rate

2️⃣ Line Chart

Website Traffic Trend Over Time (Daily Sessions)

3️⃣ Scatter Plot

Page Views vs Session Duration

4️⃣ Donut Chart

Visitors Divices (Mobile / Tablet / Desktop)

5️⃣ Area Chart

Traffic Origin (Direct, Organic, Social, Referral)

6️⃣ Map Visualization

Top Visitors Country (India, USA, UK, Germany, Australia, Canada)

📈 Insights & Observations

Majority of users accessed via Mobile devices

Traffic peaked around specific days, showing campaign activity

Direct and Organic channels drove the highest traffic

USA, India, UK, and Germany contributed highest visitor numbers

Higher page views correlated with higher session duration

Conversion rate indicates user engagement performance

🚀 Conclusion

This dashboard provides a complete view of website performance and user interaction.
Marketers, analysts, and business teams can use it to:

✔ Identify top-performing traffic channels
✔ Improve marketing campaign decisions
✔ Track user behavior and activity patterns
✔ Monitor conversion and revenue trends