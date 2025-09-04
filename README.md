# Analyzing Crime in Los Angeles

## Overview
This project explores crime data from Los Angeles, aiming to uncover patterns and insights that can help inform public safety strategies. Using real-world data, the analysis covers temporal trends, geographic hotspots, and victim demographics, providing actionable findings for law enforcement and community stakeholders.

## Dataset
- **Source:** Modified version of the Los Angeles Open Data crime dataset.
- **Columns:**
  - `DR_NO`: Record number
  - `Date Rptd`, `DATE OCC`: Dates reported and occurred
  - `TIME OCC`: Time of occurrence (24-hour format)
  - `AREA NAME`: Geographic area
  - `Crm Cd Desc`: Crime description
  - `Vict Age`, `Vict Sex`, `Vict Descent`: Victim demographics
  - `Weapon Desc`: Weapon used
  - `Status Desc`: Crime status
  - `LOCATION`: Street address

## Key Analyses & Visualizations

### 1. Temporal Patterns in Crime
- **Monthly, Weekly, and Hourly Trends:**
  Visualizations reveal when crimes are most frequent, highlighting peak months, days, and hours.

### 2. Area-Based Crime Hotspots
- **Geographic Analysis:**
  Bar and stacked bar plots show which areas experience the most crime, and how day/night patterns differ across neighborhoods.

### 3. Victim Demographics
- **Age Group Analysis:**
  Bar charts display which age groups are most affected.
- **Sex and Descent:**
  Grouped bar plots explore how crime types and times vary by victim sex and descent.

## Skills Demonstrated
- Data cleaning and feature engineering (e.g., extracting hour, categorizing age groups)
- Advanced visualizations with Matplotlib and Seaborn
- Grouped and stacked bar plots for categorical comparisons
- Use of markdown for storytelling and insight communication

## Insights & Recommendations
- Certain hours and areas have significantly higher crime rates, suggesting targeted patrols.
- Nighttime crimes are concentrated in specific neighborhoods.
- Some age groups and demographic segments are more affected by particular crime types.

## How to Run
1. Install required libraries:
   `pip install pandas numpy matplotlib seaborn`
2. Place `crimes.csv` in the project directory.
3. Open and run the notebook in Jupyter or VS Code.

## Next Steps
- Add interactive visualizations (Plotly, Folium) for deeper exploration.
- Explore predictive modeling to forecast crime risk.
- Integrate geospatial data for mapping crime locations.

## Author
Alaeddin B.
*Aspiring Data Scientist | Portfolio Project*
