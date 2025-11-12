# Los Angeles Crime Analysis
## 📘 Project Overview
   This project presents a detailed data analysis and visualization of crime incidents in Los Angeles, California, spanning the years 2020 to 2025. The goal is to uncover crime trends, Seasonal patterns, and insights across time, locations, victim demographics, and crime types.The project was executed in Microsoft Excel, featuring two interactive dashboards:
1. Crime Overview Dashboard – high-level insights on crime trends and patterns.
2. Crime Analysis Dashboard – detailed breakdowns by Crime type, sex, and LAPD divisions.



## 🎯 Objectives

1. Identify yearly crime trends and variations from 2020–2025.
2. Determine the top 5 LAPD divisions or areas with the highest number of crimes.
3. Identify which months, days of the week, and hours of the day have the highest crime rates.
4. Examine victim demographics (e.g., gender and age).
5. Analyze which crimes are increasing or decreasing over time
7. Create an interactive dashboard for dynamic data exploration.

   

## 🧰 Tools Used

Tool	Purpose
1. Microsoft Excel	Data cleaning, analysis, and dashboard creation
2. Pivot Tables	Summarizing large datasets
3. Slicers	Enabling interactive filtering by year, month, day, and hour
4. Charts & Graphs	Visual representation of trends and comparisons



## 🔍 Data Cleaning and Preparation
The dataset was cleaned and transformed using Power Query in Excel. Key steps included:
*. Column Renaming for clarity (e.g., Date Rptd → Date Reported)
*. Date & Time Formatting: Converted time values like 845 to 08:45 AM
*. Handling Missing Values: Replaced nulls in Victim_Sex and Victim_Race with "Unknown"
*. Add new column to extract Years, Month, Days and Time
*. Delete Victim Age with Negative sign

###
*. No Duplicates, No removal of any columns
*. Loaded Clean Data into Excel for analysis and visualization


## 📊 Dashboard 1 – Crime Overview (2020–2025)

### KPI:
a. Total Crimes: 735,632 incidents reported between 2020 and 2025.
b. Average Crimes per Day: 105,090 per day (across 5 years)
c. % Change (2023 vs 2024): A notable decline of 54.45%, indicating possible enforcement effectiveness or data reduction factors.
d. Cities Covered: 21 within the Los Angeles region.

### Crime Count
Crime counts rose from 151,525 (2020) to a peak of 179,175 (2022), before declining sharply in 2024–2025.
2025 shows an extreme drop (data likely incomplete or still being updated due to the fact the year is till in progress).

<img width="728" height="394" alt="image" src="https://github.com/user-attachments/assets/4713ff88-09a6-4255-b9cc-e7f6d936fa78" />


### Top Crime Months:
Crime peaks in early and mid-year.

<img width="731" height="377" alt="image" src="https://github.com/user-attachments/assets/70658f8d-a493-4c02-905a-67308462fad5" />


### Day-of-Week Pattern:
Friday and Saturday recorded the highest crime count. Crimes are lower on weekdays, indicating a spike on weekends.

<img width="753" height="375" alt="image" src="https://github.com/user-attachments/assets/590f1fce-abd2-48a0-9184-e76841061dc2" />


### Top 10 Crime Hours:
Peak at 12 PM, followed by 6 PM & 7 PM — suggesting afternoon to evening is the most active crime period.

<img width="754" height="391" alt="image" src="https://github.com/user-attachments/assets/18d88ae7-a3e0-42a9-8309-9ef0bfad0659" />


## 📈 Dashboard 2 – Crime Analysis (2020–2025)

### KPI:
a. Total Victims: 735,632
b. Average Victim Age: 40 years

### Crimes by Gender:
Male victims, followed by Female victims and Others/Unknown

<img width="747" height="287" alt="image" src="https://github.com/user-attachments/assets/6c75ece8-43aa-4067-9f69-4e1a991987a9" />


### Top 5 LAPD Areas by Crime Count:
Central Los Angeles, followed by Southwest, 77th Street, Pacific and Hollywood.

<img width="752" height="406" alt="image" src="https://github.com/user-attachments/assets/685a9065-1abc-42d3-bd2c-3c10074b90f2" />


### Top 10 Crime Types:
Yearly Crime Comparison by Offense Type: Battery – Simple Assault, Theft of Identity, Theft (Petty & Grand), Vandalism (Felony), Burglary from Vehicle
Most major crime types (assault, theft, vandalism) peaked between 2021–2022 and declined afterward.

<img width="1526" height="476" alt="image" src="https://github.com/user-attachments/assets/aec37773-4a84-492e-9907-95af06c1359d" />



🔍 Observations & Recommendations

1. Temporal Patterns:

Crimes are more frequent on Fridays and Saturdays, particularly midday to evening.

Targeted patrols during these periods could deter crime.



2. Location Focus:

Central, Southwest, and 77th Street divisions consistently report higher crime counts — should be focus areas for safety measures.



3. Crime Type Trends:

Theft and Assault-related crimes dominate; public education and neighborhood watch programs may reduce these offenses.



4. Gender Insights:

Males are slightly more affected, but both genders experience high victimization levels — tailored prevention awareness may help.



5. Future Work:

Integrate geo-mapping (using Power BI or Tableau) for spatial visualization.

Expand analysis to include crime resolution rates and suspect demographics.





---

📂 Files Included

File	Description

LA_Crime_Dataset_2020_2025.xlsx	Cleaned dataset used for analysis
LA_Crime_Overview_Dashboard.png	Overview dashboard image
LA_Crime_Analysis_Dashboard.png	Detailed analysis dashboard image
README.md	Project documentation (this file)



---

📜 Conclusion

This analysis provides a data-driven perspective on Los Angeles crime patterns from 2020–2025.
Despite fluctuations, the insights suggest strong temporal and spatial trends that can guide police resource allocation, community safety programs, and policy planning.


---

🧑‍💻 Author

Esther Adewumi
Data Analyst | Excel Enthusiast | Crime Data Researcher
📧 [Insert Email or LinkedIn link here]
