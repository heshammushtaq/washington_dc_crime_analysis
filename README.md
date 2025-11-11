# Overview
This project explores publicly available Washington DC crime data (2009–2025) to uncover patterns and insights through comprehensive data analysis and visualization. It demonstrates skills in data wrangling, statistical analysis, and visual storytelling using Python, Pandas, Matplotlib, and Seaborn.

# Objective
1. Combine multiple yearly crime datasets into a single dataset.
2. Create two distinct visualizations using Matplotlib and Seaborn.
3. Derive meaningful insights from the observed patterns and trends.

# Skills Demonstrated
1. Data cleaning and merging with Pandas
2. Exploratory Data Analysis (EDA)
3. Data visualization using Matplotlib and Seaborn
4. Analytical storytelling with data

# Visualizations & Insights
Visualization 1: Crime Trends by Year and Offense Type
A stacked bar chart showing total crime incidents per year (2009–2025), segmented by offense types.

Key Insights:
1. Crime incidents rose steadily from 2009–2014, peaking around 2016.
2. From 2017–2019, crime levels stabilized but remained below the peak years.
3. A sharp decline occurred during 2020–2022, likely influenced by COVID-19 restrictions.
4. A gradual rebound appeared in 2023, followed by a decline in 2024.
5. The 2025 data shows the lowest incident count since 2009 — likely because the year is incomplete.
6. Theft/Other remains the most common offense each year, followed by Theft/Auto.

Visualization 2: Crime Distribution by Shift (Boxplot)
A boxplot showing the distribution of yearly crime incidents across different police shifts over all 17 years.

Key Insights:
1. The Evening shift has the highest median and a wider interquartile range, indicating higher variability and more crime
activity during this period.
2. This suggests that evening hours see more crimes due to greater public activity, nightlife, and reduced visibility.
3. The Midnight shift shows the lowest median and a tighter range, reflecting fewer offenses during late-night hours.
4. The plot also reveals some low-value outliers, suggesting that in certain years, DC experienced unusually low crime counts in specific shifts.

# Data Source
The dataset consists of Washington DC crime data from 2009–2025, with one CSV file per year. All files were compiled into a single dataset for this analysis.
