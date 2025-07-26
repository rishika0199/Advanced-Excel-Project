# Objective
Develop a data-driven solution that ingests U.S. accident records, transforms them into an interactive Excel dashboard (Power Pivot + DAX), and delivers actionable insights for policymakers and transport planners. The model quantifies casualty burdens, pinpoints high-risk road types, highlights seasonal patterns, and guides interventions that reduce crashes, injuries, and costs nationwide

# Overview
This project blends over 267,000 accident records with contextual factors such as weather, lighting, road layout, speed limits, and junction types. A star schema data model was created using Excel Power Pivot, with calculated columns and DAX measures driving dynamic filters and KPIs. The dashboard includes:

-KPI cards (Total Accidents, Casualties, Severity)

-Dynamic slicers (Date, Severity, Weather, Road Type)

-Heatmaps and time series charts

-Drill-through by month, weekday, or road configuration
 The model is fully interactive and refreshable for new data uploads

# Dashboard sample 
<img width="1187" height="541" alt="Screenshot 2025-07-23 at 11 59 28 PM" src="https://github.com/user-attachments/assets/6d3c4925-e01f-454c-8266-aaa88214bb6d" />

# Key Insights

1.Accident Severity: Slight accidents represent 85% of the 308k total incidents and 84% of all casualties. However, 16% of injuries stem from serious or fatal crashes, indicating significant public health costs.

2.Road Type: Over 73% of crashes happen on single carriageways — more than double any other road type — making them the top priority for infrastructure upgrades.

3.Temporal Trends: Fridays record the most weekday crashes, and November sees the highest monthly spike, correlating with seasonal and weekend driving risks.

4.Weather Impact: Nearly 80% of all crashes occur in clear weather, suggesting driver behavior is a bigger factor than environmental hazards.

5.Risk Zones: Uncontrolled T-junctions and 30 mph zones report the highest accident counts, indicating critical areas for traffic management improvements

# Conclusions & Recommendations

1.Road Upgrades: Focus on improving single carriageways with better lighting, signage, lane markings, and median separations.

2.Behavioral Campaigns: Launch targeted safety initiatives for peak risk periods like Fridays and November to reduce fatigue, distraction, and speeding.

3.Policy Focus: Prioritize behavioral interventions over weather mitigation; most crashes are not climate-driven.

4.Infrastructure Action: Introduce traffic lights or roundabouts at high-risk T-junctions and reassess speed enforcement in 30 mph zones.

5.Ongoing Monitoring: Implement dashboard-triggered MAPE (Mean Absolute Percentage Error) alerts to track outcomes of safety interventions and adjust strategies in near real-time
