# NYC Congestion Pricing Impact on Yellow Taxi and HVFHV Demand

## Project Overview
This project investigates the effect of **NYC congestion pricing** on the demand for **Yellow Taxis** and **High-Volume For-Hire Vehicles (HVFHV)**. Using trip and weather data, it demonstrates data cleaning, feature engineering, and modeling techniques including **Ordinary Least Squares (OLS) Regression** and **Random Forest Regression**.

The analysis explores how congestion pricing influences trip volume and patterns across different vehicle types, accounting for temporal and weather-related factors.

> Note: This project was completed as part of the COMP30034 course at the University of Melbourne. The code and analysis have been adapted for portfolio presentation.

---

## Data Sources

### NYC TLC Trip Records
- **Vehicle Types:** Yellow Taxi & HVFHV  
- **Source:** [NYC TLC Trip Record Data](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)  
- **Periods:** Jan–Jun 2024 and Jan–Jun 2025  

### Weather Data (Hourly)
- **Source:** [NOAA GHCN Hourly](https://www.ncei.noaa.gov/access/search/data-search/global-historical-climatology-network-hourly)  
- **Locations & Periods:**  
  - 2024 Jan–Jun: Central Park station  
  - 2025 Jan–Jun: JFK Airport station (data available until April 2025)  

---

## Key Steps
1. **Data Cleaning & Processing:** Handle missing values, standardize formats, and merge datasets.  
2. **Feature Engineering:** Create time-based, weather-based, and congestion pricing features.  
3. **Modeling:**  
   - **OLS Regression:** Examine linear relationships between congestion pricing and trip demand.  
   - **Random Forest Regression:** Capture non-linear effects and interactions.  
4. **Analysis & Visualization:** Generate plots and metrics to summarize trends and compare vehicle types.
