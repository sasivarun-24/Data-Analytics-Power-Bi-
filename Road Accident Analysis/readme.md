# 🚗 Road Accident Analysis Dashboard | Power BI

![Road Accident Analysis Dashboard](dashboard.png)

## 📊 Project Overview

The **Road Accident Analysis Dashboard** is an interactive Power BI project designed to analyze road accident and casualty data.

The dashboard provides an overview of accident severity, casualty trends, vehicle types, road conditions, urban/rural distribution, lighting conditions, road types, weather conditions, and geographical accident locations.

The goal of this project is to transform raw accident data into an interactive and easy-to-understand dashboard that can support data-driven analysis of road safety patterns.

---

## 🎯 Project Objectives

The main objectives of this project are to:

- Analyze total road accidents and casualties.
- Compare current-year performance with the previous year.
- Identify accident patterns across different vehicle types.
- Analyze casualty trends over time.
- Compare casualties in urban and rural areas.
- Understand the relationship between casualties and road types.
- Analyze casualties under different lighting conditions.
- Visualize accident locations geographically.
- Allow users to interactively filter the dashboard using road and weather conditions.

---

## 🛠️ Tools & Technologies

- **Power BI Desktop**
- **Power Query**
- **DAX**
- **Microsoft Bing Maps**
- **Data Visualization**
- **Data Transformation & Cleaning**
- **Interactive Slicers**
- **Geospatial Analysis**

---

## 📌 Dashboard Features

### 1. KPI Overview

The dashboard provides key performance indicators for:

- Total CY Casualties
- Total CY Accidents
- CY Fatal Casualties
- CY Serious Casualties
- CY Slight Casualties

The KPIs also include year-over-year percentage comparisons to help identify changes in accident and casualty levels.

---

### 2. Casualties by Vehicle Type

The dashboard breaks down casualties by vehicle type, including:

- Agricultural Vehicle
- Bike
- Bus
- Car
- Goods Vehicle
- Other Vehicle

This helps identify which vehicle categories contribute to the highest number of casualties.

---

### 3. Monthly Casualty Trends

The **CY Casualties vs Casualties Monthly Trends** visualization compares casualty patterns across the months of the year.

The chart allows users to observe:

- Monthly fluctuations
- Seasonal patterns
- Differences between years
- Periods with relatively high or low casualty levels

---

### 4. Casualties by Urban/Rural Area

A donut chart shows the distribution of casualties between:

- Urban areas
- Rural areas

This provides a quick comparison of casualty distribution based on the type of area.

---

### 5. Casualties by Road Type

The dashboard analyzes casualties across different road types, including:

- Single carriageway
- Dual carriageway
- Roundabout
- Slip road
- One way street

This helps identify road types associated with higher numbers of casualties.

---

### 6. Casualties by Light Conditions

The dashboard categorizes casualties based on lighting conditions, including:

- Daylight
- Night

This allows users to compare accident casualties occurring during different lighting conditions.

---

### 7. Geographical Accident Analysis

The interactive map displays accident locations across the United Kingdom.

The map allows users to visually identify geographical patterns and concentrations of road accidents.

The visualization uses:

- Latitude
- Longitude
- Local Authority
- Casualty information

---

## 🎛️ Interactive Filters

The dashboard includes interactive filters that allow users to explore the data dynamically.

### Road Surface Conditions

Users can filter the dashboard based on road surface conditions such as:

- Dry
- Wet/Rainy
- Other available conditions

### Weather Conditions

Users can also filter the dashboard according to weather conditions.

When a filter is selected, the KPI cards and visualizations update dynamically based on the selected conditions.

---

## 📈 Key DAX & Power BI Concepts Used

This project demonstrates several Power BI and DAX concepts, including:

- DAX measures
- Year-over-year calculations
- Current-year calculations
- Previous-year calculations
- Percentage change calculations
- Aggregations
- Conditional formatting
- Interactive slicers
- Data categorization
- Date/calendar tables
- Relationships between tables
- Geographic visualization
- Data transformation using Power Query

---

## 🧹 Data Preparation

The data was prepared and transformed using **Power Query** before being used for visualization.

The preparation process included:

- Data cleaning
- Data type conversion
- Date transformation
- Creating calculated/grouped fields
- Preparing categorical variables
- Creating a calendar table
- Preparing geographical fields
- Structuring the dataset for analysis

---

## 🗂️ Dashboard Structure

The dashboard is organized into several analytical sections:

| Section | Purpose |
|---|---|
| KPI Cards | Overall accident and casualty performance |
| Vehicle Type | Casualties by vehicle category |
| Monthly Trends | Casualty trends over time |
| Urban/Rural | Geographic area comparison |
| Road Type | Casualties by road type |
| Light Conditions | Day vs night analysis |
| Accident Map | Geographical distribution |
| Slicers | Interactive filtering |

---

## 📂 Project Files

```text
Road-Accident-Analysis/
│
├── Road Accident Analysis.pbix
├── dashboard.png
└── README.md
