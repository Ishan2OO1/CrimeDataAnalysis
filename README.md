#  Los Angeles Crime Data Analysis (2020–Present)

## About the Project

This project analyzes crime data from the City of Los Angeles spanning 2020 to the present. Using Python and Seaborn-based visualizations, it explores temporal patterns, geographic hotspots, victim demographics, crime types, and weapons usage to uncover actionable insights from nearly one million crime records. The project also includes a time-series forecasting component using ARIMA to predict short-term crime trends.

## Aim

- Perform end-to-end data cleaning, transformation, and exploratory data analysis on LA crime data.
- Identify when, where, and how crimes occur most frequently across the city.
- Analyze victim demographics to understand who is most affected.
- Forecast future crime counts using ARIMA time-series modeling.

## Why This Matters

Understanding crime patterns is essential for informed public safety decisions. By identifying peak crime hours, high-risk neighborhoods, and the most common crime types, this analysis can support law enforcement in resource allocation, help policymakers design targeted interventions, and raise public awareness about safety trends in Los Angeles.

## Dataset

The dataset is sourced from the [Los Angeles Open Data Portal](https://data.lacity.org/) and contains approximately 990,293 records with 28 features, including crime type, date/time of occurrence, victim age, sex, and descent, weapon used, premises description, LAPD area, geographic coordinates, and case status.

## Results

- Crime peaks around **noon (12 PM)** with a secondary evening spike; **Fridays** have the highest crime counts.
- **Central, 77th Street, and Pacific** are the most crime-dense LAPD areas.
- **Vehicle theft, battery, and burglary** are the most common crime types.
- **Young adults (18–35)** are the most victimized age group, and **Hispanic/Latino and Black** populations are disproportionately represented among victims.
- The majority of cases remain under **"Investigation Continued"** status.
- ARIMA forecasting indicates a **stable short-term crime trend** over the next 30 days.
