# 🏡 U.S. Housing Market Trends (2016–2025)

This interactive dashboard explores housing market trends across the United States from 2016 to 2025 using data from Zillow and Realtor.com. The goal is to visualize state-level patterns in home prices, inventory, and days on market, while identifying key performance indicators and correlations across time.

## 📌 Project Overview

- **Objective:** Analyze and visualize U.S. housing market trends from 2016 to 2025  
- **Tools Used:** SQL, Python, R, Excel, Tableau  
- **Data Sources:**  
  - [Zillow Research](https://www.zillow.com/research/data/)  
  - [Realtor.com Data Center](https://www.realtor.com/research/data/)  

---

## 📊 Dashboard Features

This project is structured as a multi-slide interactive story dashboard with the following sections:

### 1. **Overview**  
- Context on the U.S. housing market and data limitations

### 2. **Market Charts**  
- Interactive visualizations of:  
  - Average listing price  
  - Average active inventory  
  - Average pending inventory  
  - Average days on market  
- ✅ **Sortable by State and Year using filters**

### 3. **KPI Summary & Correlation Heatmap**  
- Summary table includes min, max, median, and standard deviation of key metrics  
- Correlation heatmap showing average correlations between selected variables  
- Filters:  
  - **State** and **Year** (used in both sections)  
  - **KPI Type** (KPI Summary only)  
  - **Variable 1 & 2** (Correlation Heatmap)

### 4. **Market Trends Summary**  
- Written summary of trends, correlations, and data interpretations

---

## 🧠 Key Insights

- **Listing Prices:** Rose steadily from 2016 to 2023, then continued rising at a slower pace into 2024. Some states showed stabilization or slight declines in 2024, more pronounced in Realtor.com data.
- **Inventory Trends:** Fluctuated year to year; lower inventory generally aligned with higher prices and faster sales. Realtor.com shows consistently higher inventory due to its MLS-based data, compared to Zillow’s reliance on public records.  
- **Market Speed:** Days on market decreased in high-demand states, indicating quicker sales.  
- **Correlations:** Strong negative correlation between inventory levels and listing prices — as inventory decreases, prices rise. Negative correlations between days on market and both inventory and price indicate faster sales when inventory and prices are higher.  
- **Source Differences:** Realtor.com typically reports more inventory than Zillow because of different data collection methods (MLS feeds vs. public records and tax assessments).

---

## 📎 Data Considerations

- Zillow data is based on public records and tax assessments.  
- Realtor.com pulls from MLSs and focuses on active listings.  
- Although data is available dating back to 2002, this project concentrates on **2016–2025** for consistent comparison between sources.  
- Zillow and Realtor.com data were analyzed separately to maintain methodological accuracy; trends should be interpreted as **complementary, not directly comparable**.

---

## 📁 Project Structure

The repository contains the following folders:

- **raw_data** — Original downloaded datasets from Zillow and Realtor.com  
- **final_data** — Cleaned and processed datasets ready for analysis  
- **scripts** — SQL, Python, and R scripts used for data cleaning and analysis  
- **tableau** — Tableau workbooks and dashboard files for visualization

---
