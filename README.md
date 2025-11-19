# 📊 Website Traffic Analysis Dashboard — Power BI Project
---

## ⭐ Project Overview
---

This project focuses on analyzing website traffic patterns, user engagement, and marketing effectiveness through an interactive **Power BI Dashboard**.

The dashboard provides insights on:

- 🚦 Traffic trends over time  
- 👥 New vs Returning Users  
- 📱 Device usage distribution  
- 🌍 Geographic visitor performance  
- 📈 Conversion & revenue metrics  
- 🔗 Marketing channel performance  

---

## 📁 Files Included
---

| File Name | Description |
|----------|-------------|
| `web_marketing_data.csv` | Raw dataset from Kaggle |
| `website_traffic_cleaned.xlsx` | Cleaned dataset |
| `website_traffic_analysis.pbix` | Power BI dashboard |
| `Website_Traffic_Project_Report.pdf` | Full project report |
| `README.md` | Documentation |

---

## 🎯 Project Objective
---

This dashboard helps to:

- Track sessions & user activity  
- Understand website traffic trends  
- Measure user engagement  
- Analyze conversions & revenue  
- Evaluate marketing channel performance  

---

## 📂 Dataset Description
---

📌 **Source:** Kaggle – *Web Marketing Campaign Performance Dataset*  
📌 **Each row = one website session**

### Key Columns

- `user_id`  
- `new_user`  
- `page_views`  
- `session_duration_seconds`  
- `device_type`  
- `country`  
- `source` (Direct, Organic, Referral, Social)  
- `conversions`  
- `revenue`  
- `date`  

### Dataset Used

web_marketing_data.csv

---

## 🧹 Data Cleaning & Preparation
---

- ✔ Removed duplicates  
- ✔ Handled missing values  
- ✔ Converted date into proper format  
- ✔ Standardized numeric columns  
- ✔ Verified binary values (`new_user`, `conversions`)  
- ✔ Cleaned device_type & source categories  
- ✔ Exported cleaned dataset  

---

## 🧮 DAX Measures Used
---
Total Sessions = COUNTROWS('web_marketing_data')

Total Users = DISTINCTCOUNT('web_marketing_data'[user_id])

New Users = SUM('web_marketing_data'[new_user])

Returning Users = [Total Users] - [New Users]

Total Page Views = SUM('web_marketing_data'[page_views])

Avg Session Duration = AVERAGE('web_marketing_data'[session_duration_seconds])

Total Conversions = SUM('web_marketing_data'[conversions])

Conversion Rate = DIVIDE([Total Conversions], [Total Sessions])


### Additional Measures
- Page Views per Session  
- Avg Session Duration (Minutes)  
- Sessions by Device  
- Revenue per User  
- Total Revenue  
- Users by Country  

---

## 📊 Dashboard Visuals
---

### 🟦 1️⃣ KPI Cards
- Total Users  
- New Users  
- Total Page Views  
- Average Duration  
- Conversion Rate  

### 📈 2️⃣ Line Chart  
Website traffic trend over time  

### 🎯 3️⃣ Scatter Plot  
Page Views vs Session Duration  

### 🍩 4️⃣ Donut Chart  
Device Type (Mobile, Desktop, Tablet)  

### 📉 5️⃣ Area Chart  
Traffic Source Distribution  

### 🗺️ 6️⃣ Map Visualization  
Top Visitor Countries  

---

## 🖼️ Dashboard Screenshot
---

<img width="1323" height="739" alt="website_traffic_analysis_screenshot" src="https://github.com/user-attachments/assets/334bfda0-c919-4b3a-acd9-c691ae9edcae" />


(Replace with your actual screenshot path)

---

## 📈 Insights
---

- 📱 Mobile users form the highest traffic share  
- 🔗 Direct & Organic channels are top traffic sources  
- 📅 Traffic peaks on marketing campaign days  
- ⏱️ Higher page views → longer session duration  
- 🌍 US, India, UK, Germany show highest visitors  
- 🎯 Strong correlation between traffic & conversions  

---

## 🚀 Conclusion
---

This dashboard helps organizations:

- ✔ Identify high-performing traffic channels  
- ✔ Understand user behavior  
- ✔ Improve digital marketing performance  
- ✔ Track conversions & revenue growth  

---

# ✍️ Author
---

### 👤 Arthi  
**Data Analyst**

---




