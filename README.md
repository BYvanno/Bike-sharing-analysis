🚴‍♂️ Analyzing Factors Affecting Bike-Sharing Demand in Seoul

This project explores the key environmental and temporal factors that influence daily bike-sharing demand in Seoul. Using the Seoul Bike Sharing Dataset, the analysis uncovers patterns in weather, seasons, holidays, working days, and time-related features that shape rental behavior.

📊 Project Overview

The goal of this project is to understand what drives bike-sharing demand and how usage patterns change across seasons, days, and weather conditions. The findings can help optimize operations, improve planning, and support data-driven decisions in urban mobility systems.

🛠 Tools & Technologies

Python

pandas, NumPy

matplotlib, seaborn

Jupyter Notebook

🔍 Key Steps
1. Data Preprocessing

Converted date column into useful time features (year, month, day, weekday)

Handled missing values & ensured data quality

Created additional features for deeper insight

2. Exploratory Data Analysis (EDA)

Summary statistics

Rental distribution

Time-series trends

Weather-based analysis

Correlation heatmap

📈 Major Findings
✨ Temporal Insights

Strong seasonality:
Rentals peak in summer and drop sharply in winter.

Weekday vs Weekend:
Higher demand on weekdays—indicating commuter usage.

Hour of day:
Two demand peaks at 8–9 AM and 6–7 PM, matching typical commuting times.

🌦 Environmental Insights

Temperature:
High positive correlation with rentals (strongest factor). Moderate to warm temperatures bring the highest usage.

Humidity & Rainfall:
Rentals decrease significantly during rainy or highly humid conditions.

Visibility & Solar Radiation:
Positively associated with higher rentals but less impactful than temperature.

📅 Operational Factors

Functioning days > Non-functioning days
People heavily rely on the system on regular working days.

Holidays show lower usage, suggesting the system is used more for daily routines than leisure.

🧠 Conclusion

Weather conditions and time-based variables play a major role in shaping bike-sharing demand.
These insights support:

Better fleet distribution

Policy and infrastructure planning

Demand forecasting models

Weather-aware operational strategies
