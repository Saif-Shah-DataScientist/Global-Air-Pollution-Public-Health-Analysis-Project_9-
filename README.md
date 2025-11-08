# Global Air Pollution and Public Health Analysis

## Project Overview
This project analyzes global air quality data to understand pollution patterns, pollutant relationships, and public health risks. The goal is to identify high-risk regions, major pollutants, and actionable strategies for improving air quality.

## Objectives
- Assess overall air quality (AQI) levels across cities and countries  
- Identify major pollutants contributing to poor air quality  
- Detect high-risk clusters with severe pollution levels  
- Analyze correlations between pollutants and overall AQI  
- Provide policy-level recommendations to reduce pollution and protect public health  

## Dataset
- File: global_air_pollution_data.csv (or equivalent)  
- Source: OpenAQ / World Air Quality Index Dataset  
- Key Columns: Country, City, AQI_Value, PM2.5_AQI_Value, NO2_AQI_Value, Ozone_AQI_Value, CO_AQI_Value, AQI_Category, Pollution_Intensity_Score, High_Risk_Flag

## Tools and Libraries
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Jupyter Notebook  

## Steps Performed
1. Data loading and inspection  
2. Data cleaning and handling of missing or inconsistent values  
3. Feature engineering (e.g., PM2.5 share, pollution intensity score, high-risk flag)  
4. Exploratory Data Analysis (EDA)  
5. Correlation analysis of pollutants with overall AQI  
6. Visualization of pollution distribution and high-risk zones  
7. Insights and policy recommendations  

## Key Insights
- **PM2.5 is the dominant pollutant**, contributing the largest share to overall air pollution levels in most cities.  
- **High-risk clusters** (AQI > 150) are identifiable and represent critical regions needing immediate intervention.  
- **Pollutant correlation:** AQI is strongly associated with PM2.5 and NO₂, showing that when these pollutants rise, air quality deteriorates rapidly.  
- **Mixed contributors:** Some cities exhibit high AQI due to cumulative effects of multiple pollutants rather than one dominant source.  
- **Country-level patterns:** Pollution intensity varies by country; some face widespread moderate pollution, while others have localized severe hotspots.

## Policy and Health Recommendations
- Target **PM2.5 and NO₂** reductions through industrial, transport, and emission control programs.  
- Prioritize **high-risk clusters** for immediate mitigation efforts.  
- Develop integrated policies addressing **multi-pollutant sources** (traffic, industry, seasonal burning).  
- Establish **regional monitoring and forecasting systems** to anticipate pollution surges.  
- Encourage **international collaboration** to support clean air initiatives and data sharing.  

## Requirements
To install the required libraries, run:
