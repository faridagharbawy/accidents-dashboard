# Road Accident Analysis Dashboard
## Project Overview
This project analyzes road accident data to identify patterns related to casualties, vehicle types, and environmental conditions. The goal is to provide a central intelligence hub for road safety authorities to visualize where and why accidents occur.

## Key Features
Primary KPIs: Real-time tracking of Total Casualties (195.7K), Total Accidents (144.4K), and severity levels (Fatal, Serious, Slight).

YoY Performance: Interactive line charts comparing 2021 vs. 2022 trends with percentage indicators for growth/decline.

Geospatial Mapping: Integrated Map visuals to identify accident hotspots across the UK.

Environmental Analysis: Dynamic filtering by Weather Conditions, Road Surface, and Light Conditions (Day vs. Dark).

Vehicle Breakdown: Analysis of casualties across 6 vehicle categories, highlighting cars as the highest-risk group (155K).

## Technical Stack
Power BI Desktop: Core visualization and report layout.

DAX: Used for Time Intelligence (YoY growth), conditional formatting of KPI indicators, and complex measures for casualty counts.

Power Query: Data cleaning to categorize "Urban vs. Rural" and "Road Type" for better scannability.

Data Modeling: Optimized for performance using a Star Schema.

## How to Use
Open the /Dashboard folder and download the .pbix file.

Use the Top Filter Bar to select specific weather or road conditions.

Hover over the Map or Line Chart to see detailed tooltips.
