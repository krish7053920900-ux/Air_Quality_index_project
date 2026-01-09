# Air_Quality_index_project
Air Quality Index Monitoring & Pollution Impact Analytics
Project Overview
This project provides a comprehensive analysis of global air quality trends, focusing on the concentration of key pollutants and their impact across different cities and countries. The dashboard was built using Power BI to visualize data processed through Python.

Dataset Description
Source: Global Air Quality Dataset (CSV format).

Key Features: - Pollutants: PM2.5, PM10, NO2, SO2, O3, and CO.

Geographic Data: Country and City-level information.

Temporal Data: Year-on-year tracking (Data shown for 2024).

Environmental Factors: Temperature (°C) and Humidity (%).

Key Metrics & KPIs
Based on the analytics dashboard, the following key metrics were calculated:

Overall Average AQI: 164.64.

Total Days Monitored: 668K days from start.

Pollutant Averages:

PM10 Average: 154.79 µg/m³.

NO2 Average: ~53 ppb.

SO2 Average: 25.94 ppb.

CO Average: 5.02 ppm.

O3 Average: 105.33 ppb.

Data Visualizations & Insights
Pollutant Concentration:

CO Levels: A gauge chart shows an average of 5.02 ppm, which is approximately 50% of the recorded 10.05 threshold.

SO2 Levels: Stable at 25.94 ppb, visualized through both bar and donut charts for distribution analysis.

Geographic Trends:

Highest AQI by City: Delhi recorded the highest average AQI (170.58), followed by Tokyo (169.60) and São Paulo (168.77).

Country-Wise Average: India and Japan lead in higher AQI averages compared to the USA and Australia.

City-Level Comparison: A line chart illustrates a downward trend in AQI from Delhi towards New York (155.08).

Environmental Correlation:

The dashboard tracks the Sum of Temperature and Humidity alongside pollutant levels to identify potential environmental correlations with air quality.

Tools Used
Data Processing: Python (Google Colab / .py script).

Visualization: Power BI Desktop.

Documentation: Markdown.

How to Navigate the Repository
/Data: Contains the raw .csv dataset.

/Notebooks: Includes the .ipynb file used for KPI calculations and data cleaning.

/Dashboard: Contains the .pbix Power BI file and high-resolution screenshots.
