# Daikibo Telemetry Data Analysis – Tableau

## Project Overview
This project focuses on analyzing Daikibo telemetry data using Tableau Public. The main objective is to understand machine downtime across different factories and device types through interactive data visualizations.

## Objectives
- Analyze unhealthy machine status across factories.
- Identify factories with higher downtime.
- Compare downtime across different machine types.
- Build an interactive dashboard for factory-level analysis.

## Tools & Technologies
- Tableau Public
- Data Visualization
- Calculated Fields
- Interactive Dashboards

## Data Preparation and Analysis

### 1. Calculated Field
Created a calculated field named `Unhealthy` to identify unhealthy machine status.

```tableau
IF [Status] = "unhealthy" THEN 10 ELSE 0 END
```

### 2. Downtime Per Factory
Created a bar chart to compare unhealthy status values across different factories.

### 3. Downtime Per Machine
Created another bar chart to compare unhealthy status values across different device types.

### 4. Interactive Dashboard
Combined both charts into one dashboard and enabled the factory filter.

Selecting a factory in the first chart dynamically updates the second chart to display the corresponding machine downtime.

## Dashboard Preview
<img width="1422" height="858" alt="Daikibo_Tableau_Dashboard png" src="https://github.com/user-attachments/assets/0caf1c29-40b2-4a9f-bf3f-af84e274ef78" />


## Key Learning Outcomes
- Understanding Tableau's Data pane and calculated fields.
- Creating bar charts using dimensions and measures.
- Developing interactive dashboards.
- Applying filters to connect multiple visualizations.
- Improving data analysis and visualization skills.

## How to View the Project
1. Download the Tableau packaged workbook (`.twbx`) if you have permission to share the dataset.
2. Open it using Tableau Public.
3. Navigate to Dashboard 1.
4. Select a factory to explore machine downtime.

## Project Status
Completed.

## Author
M Bhuvana

B.Tech – Artificial Intelligence and Data Science

Interested in Data Analytics and Data Visualization.
