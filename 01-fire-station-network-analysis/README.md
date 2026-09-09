# Region of Waterloo Fire Station Network Analysis

## Overview
This project evaluates the impact of adding new fire stations in Elmira and New Hamburg on emergency response times across the Region of Waterloo. 

## Tools Used
- ArcGIS Pro (Network Analyst, Spatial Analyst)

## Methodology
- Built a routable network dataset from regional road infrastructure, configuring travel time costs and one-way restrictions.
- Executed Service Area analysis (2, 5, and 10-minute driving ranges) to map current coverage.
- Ran a Location-Allocation analysis using 26,000+ historical fire calls as demand points to compare three scenarios: Base Case (16 stations), Scenario AB (+Elmira), and Scenario BA (+New Hamburg).

## Key Findings
- The Base Case leaves significant gaps in 10-minute coverage in northern and western rural areas.
- Adding a station in New Hamburg (Scenario BA) reduced the system-wide average response time from 3.01 to 2.42 minutes.
- Scenario BA also cut the proportion of fire calls exceeding the 10-minute coverage window by nearly 50%.

## Maps
The final map layouts for the Service Area and Location-Allocation analyses are included in this folder.

