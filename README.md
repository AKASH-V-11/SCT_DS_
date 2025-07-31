# 🚗 Traffic Accident Data Analysis (Task 4) – DATA SCIENCE Internship
SKILLCRAFT TECHNOLOGY

This project focuses on analyzing a large-scale U.S. traffic accident dataset to uncover patterns related to **road conditions**, **weather**, **time of day**, and **geographic hotspots**. The dataset is massive, so we use **Dask** for scalable data processing.

---

## 📁 Dataset Features

The dataset includes millions of records with features such as:

- `Start_Time`, `End_Time`, `Start_Lat`, `Start_Lng`
- `Weather_Condition`, `Temperature(F)`, `Visibility(mi)`
- Road features like `Traffic_Signal`, `Junction`, `Crossing`, etc.
- `Severity` of the accident
- Time indicators like `Sunrise_Sunset`, `Timezone`

---

## 📁 Dataset Details

- Dataset used: `sobhanmoosavi/us-accidents` from Kaggle  
- Total records: ~7 million  
- Key features analyzed:
  - `Start_Time`, `Start_Lat`, `Start_Lng`
  - `Weather_Condition`, `Crossing`, `Junction`, `Traffic_Signal`
  - Extracted: Year, Hour, Day of Week, Time of Day

---

## 🎯 Objectives

- Analyze accidents by **time of day** (Morning, Afternoon, Evening, Night)
- Understand how different **weather conditions** affect accident counts
- Study the role of **road features** in accident occurrence
- Generate **visualizations** of accident hotspots using geographic coordinates

---

## 🧪 Tools & Technologies

- **Python** (Pandas, Dask, Seaborn, Matplotlib)
- **Dask** for parallel, large-scale data processing
- **Seaborn/Matplotlib** for plotting
- **Basemap** for geospatial mapping
- **Kaggle** for dataset of US accidents

---

## 📌 Visualizations Included

- **Countplot**: Accidents by Time of Day
- **Barplot**: Accidents under different Weather Conditions
- **Scatterplot**: Temperature vs Visibility colored by Time of Day
- **Basemap Plot**: Geographic accident scatter
- **Heatmap (2D binned)**: Intensity of accident hotspots across USA

---

## 📂 How to Run

1. Clone this repository to your local system or open in Google Colab.
2. Install dependencies if needed:
   ```python
   !pip install dask[complete] basemap matplotlib seaborn
   ```
3. Run the Jupyter/Colab notebook step-by-step to:
   - Load & process the data
   - Extract time & weather features
   - Generate plots and statistical summaries

---

## 📈 Sample Statistics

## 📊 Output 1: Accidents by Time of Day

This bar chart shows how accidents are distributed across different parts of the day:
- **Morning (5AM–12PM)**  
- **Afternoon (12PM–5PM)**  
- **Evening (5PM–9PM)**  
- **Night (9PM–5AM)**  

> **Insight:** Morning and Afternoon are peak accident periods, likely due to rush hour traffic.

---
## 📊 Output 2: Accidents by Hour of the Day

A countplot displaying accidents for each hour from 0 to 23.

> **Insight:** Peak hours range from 7 AM to 9 AM and 4 PM to 6 PM.

---
## 📊 Output 3: Accidents by Day of the Week

Accident frequency for each day from Monday to Sunday.

> **Insight:** Weekdays, especially **Friday**, see higher accident rates due to work-related travel.

---
## 📊 Output 4: Weather Conditions during Accidents

Top 10 weather conditions were analyzed to check accident influence.

> **Insight:** Surprisingly, most accidents occur in **Fair** and **Clear** weather — suggesting driver behavior and congestion are stronger factors than poor weather.
---
## 📊 Output 5: Road Infrastructure Influence

We analyzed the count of accidents where specific road features were involved:
- **Traffic Signals**
- **Crossings**
- **Junctions**

> **Insight:** Traffic signals had the highest accident count, followed by crossings and junctions — these are critical urban design zones.

---
## 🌍 Output 6: Geographic Accident Hotspot Map

An interactive heatmap plotted using 100,000+ GPS coordinates of accident locations across the USA.

> **Insight:** Dense hotspots are seen in:
- **California (LA, San Francisco)**
- **Texas (Houston, Dallas)**
- **Florida**
- **East Coast urban belt**

> These areas require more traffic control, awareness, and infrastructure upgrades.
---
## 📈 Summary of Key Insights

| Category            | Findings |
|---------------------|----------|
| 🕒 Time             | Morning and Afternoon have highest accidents |
| 🌤️ Weather         | Fair/Clear weather dominate accident counts |
| 🛣️ Road Features   | Traffic signals and crossings are high-risk |
| 🌎 Location         | Urban zones are most accident-prone |

---
##LINKEDIN :
- https://www.linkedin.com/in/akash-v-9249b2296?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app

## ✅ Conclusion

This analysis demonstrates that while weather does play a role in traffic accidents, **time of day and road features** are often more critical. Strategic improvements at high-risk locations like traffic signals and crossings, combined with behavioral awareness during peak hours, can significantly enhance road safety.

## 🎥💻VIDEO :
-
https://www.linkedin.com/posts/akash-v-9249b2296_skillcrafttechnology-dataanalystintern-datascienceintern-activity-7355144442309238784-fMVS?utm_source=share&utm_medium=member_android&rcm=ACoAAEex2awBF83VC-fxl3uuiPf2qnkwSc8A5_0
