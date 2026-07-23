### Traffic Accident Risk Analysis & High-Risk Zone Identification Dashboard

An interactive Power BI dashboard designed to analyze traffic accident patterns, identify accident-prone locations, and uncover the key factors contributing to road accidents. The solution combines Python-based data cleaning and exploratory data analysis (EDA) with Power BI visualizations to support data-driven road safety decisions.

### Short Description / Purpose

The Traffic Accident Risk Analysis Dashboard is an interactive business intelligence solution built using Python and Power BI. It enables stakeholders to monitor accident trends, identify high-risk locations, analyze temporal and environmental factors, and uncover actionable insights that support accident prevention and efficient traffic management.

The dashboard is intended for transportation authorities, city planners, road safety departments, and policymakers to improve public safety through data-driven decision-making.

### Tech Stack

The dashboard was built using the following tools and technologies:

📊 Power BI Desktop – Interactive dashboard development and visualization.
🐍 Python (Pandas, NumPy, Matplotlib, Seaborn) – Data cleaning, preprocessing, Exploratory Data Analysis (EDA), and feature engineering.
⚡ Power Query – Data transformation, loading, and preparation.
🧠 DAX (Data Analysis Expressions) – Dynamic KPI calculations, measures, and business metrics.
🔗 Data Modeling – Relationships between tables to enable cross-filtering and efficient reporting.
📍 Power BI Maps – Geographical visualization of accident hotspots.
🎨 Power BI Visuals & Slicers – Interactive filtering and drill-down analysis.
📁 File Formats: .pbix, .ipynb, .csv, .png

### Data Source

## Source: Public Traffic Accident Dataset

The dataset contains detailed accident records including:

Accident ID
Location ID
Date
Month
Day of Week
Hour of Day
Weather Condition
Road Type
Lighting Condition
Vehicle Count
Average Vehicle Speed
Traffic Violations
Accident Severity

The data was first analyzed using Python to identify patterns, clean missing values, and validate data quality before importing into Power BI for dashboard development.

### Features / Highlights
## Business Problem

Traffic accidents continue to cause significant loss of life, property damage, and economic costs. Transportation authorities often struggle to identify accident hotspots and understand the factors contributing to accidents due to scattered and unstructured data.

Key business questions include:

1. Which locations experience the highest accident frequency?
2. Which road types are most accident-prone?
3. How do weather and lighting conditions affect accidents?
4. During which days and hours do accidents peak?
5. Which locations require immediate safety improvements?
6. What factors contribute most to accident occurrence?
## Goal of the Dashboard

The dashboard aims to:
1. Identify accident-prone locations.
2. Detect temporal accident patterns.
3. Analyze environmental and infrastructural risk factors.
4. Enable proactive road safety planning.
5. Support resource allocation and emergency response.
6. Assist policymakers in reducing accident rates through data-driven decisions.

## Dashboard Walkthrough
## Page 1 – Executive Overview
# Key KPIs
Total Accidents
Total Traffic Violations
Total Vehicles
Average Vehicle Speed
# Key Visuals
# Road Type Analysis

Compares accidents across Urban, Highway, and Rural roads.

Business Question Answered
Which road type contributes the most accidents?

# Weather Impact Analysis

Analyzes accident distribution under different weather conditions.

Business Question Answered
Which weather conditions increase accident risk?

# Lighting Condition Analysis

Shows accident occurrence during Day, Night, and Dusk/Dawn.

Business Question Answered
Does lighting influence accident occurrence?

# Accident Severity Distribution

Visualizes the proportion of Low, Minor, and Serious accidents.

Business Question Answered
How severe are most reported accidents?

# Interactive Filters
Month
Hour
Day of Week
Weather
Road Type

![Dashboard Preview](https://github.com/Nagulasuprika/Traffic-Accident-Risk-Analysis/blob/a8e4a641bd6a9f7c87f747fc0c7d2e36f29a913a/Traffic%20Accidents%20Summary.png)

## Page 2 – Time Analysis

Focuses on identifying accident trends across different time dimensions.

# Visuals
# Total Accidents by Day

Ranks accident frequency across weekdays.

Business Question Answered
Which day experiences the highest number of accidents?

# Peak Accident Hours

Analyzes hourly accident trends.

Business Question Answered
At what time do accidents occur most frequently?

# Traffic Volume Analysis

Compares traffic volume with accident occurrence.

Business Question Answered
Is traffic volume related to accident frequency?

# Monthly Accident Trend

Displays accident patterns across months.

Business Question Answered
Which months require additional traffic monitoring?

# Interactive Filters
Month
Hour
Weather
Road Type
Day of Week

![Dashboard Preview](https://github.com/Nagulasuprika/Traffic-Accident-Risk-Analysis/blob/d4bb8db012828f8c7946211fc080f129377d0ee1/Traffic%20Accidents%20Location%20Analysis.png)

## Page 3 – Location Analysis

Focuses on identifying accident hotspots and geographical risk areas.

# Visuals
# Accident vs Traffic Violations

Compares accidents and violations across locations.

Business Question Answered
Do locations with more traffic violations also experience more accidents?

# Road Type Distribution by Location

Shows dominant road types across accident locations.

Business Question Answered
Which road infrastructure contributes most to accidents?

# Accident Hotspot Map

Displays accident locations geographically.

Business Question Answered
Where should authorities prioritize safety improvements?

# Weather Impact by Location

Shows weather-related accident distribution across locations.

Business Question Answered
Which weather conditions increase accident risk in each location?

# Interactive Filters
Day
Month
Hour
Weather
Road Type

![Dashboard Preview](https://github.com/Nagulasuprika/Traffic-Accident-Risk-Analysis/blob/981b4e80ba82ca341b0fbc16e22524056e26ab13/Traffic%20Accidents%20Time%20Analysis.png)

## Business Insights
# Executive Overview
Urban roads account for the majority of reported accidents.
Rainy weather significantly increases accident occurrence.
Nighttime records more accidents than daytime.
Most reported accidents fall under the Low Severity category.
# Time Analysis
Thursday records the highest accident frequency.
Morning and evening rush hours experience accident peaks.
Traffic volume closely follows accident trends.
Month 5 records the highest number of accidents.
# Location Analysis
L008 is the highest accident hotspot.
Locations with higher traffic violations generally report more accidents.
Urban areas show the greatest accident concentration.
Rain contributes significantly to accidents across major locations.

## Business Impact

This dashboard enables organizations to:
1. Identify accident-prone locations requiring immediate intervention.
2. Improve traffic signal placement and road infrastructure planning.
3. Optimize emergency response deployment.
4. Support evidence-based traffic safety policies.
5. Monitor accident trends through interactive analytics.
6. Allocate traffic management resources more effectively.
   
### Business Success Criteria
Reduce accidents at identified high-risk locations by 20%.
Improve accident hotspot identification accuracy.
Enhance traffic monitoring and planning.
Enable proactive decision-making using real-time insights.

### Economic Success Criteria
Reduce emergency response and medical costs.
Lower infrastructure repair expenses.
Improve allocation of traffic enforcement resources.
Minimize economic losses caused by road accidents.

### Recommendations

Based on the dashboard insights, the following actions are recommended:

# Strengthen Safety at High-Risk Locations
Install additional traffic signals, warning boards, and speed-calming measures at accident hotspots such as L008 and other high-risk locations.
# Improve Weather-Based Traffic Management
Implement weather-responsive traffic control systems and display dynamic speed advisories during rainfall to reduce weather-related accidents.
# Enhance Nighttime Road Safety
Upgrade street lighting, reflective road markings, and visibility signs in areas with frequent nighttime accidents.
# Increase Enforcement During Peak Hours
Deploy additional traffic police and automated speed monitoring during morning and evening rush hours when accident frequency is highest.
# Improve Urban Road Infrastructure
Prioritize maintenance of urban roads, redesign dangerous intersections, and improve pedestrian crossings in high-risk zones.
# Monitor Traffic Violations Continuously
Increase surveillance using CCTV and AI-enabled traffic monitoring systems to reduce violations in accident-prone areas.
# Conduct Public Safety Awareness Campaigns
Launch awareness programs on safe driving during adverse weather, peak traffic hours, and high-risk road conditions.
# Use Dashboard for Continuous Monitoring
Integrate the dashboard into regular traffic management workflows to monitor trends, evaluate interventions, and support data-driven policy decisions.
