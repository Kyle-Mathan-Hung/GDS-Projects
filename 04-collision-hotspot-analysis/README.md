# Motor Vehicle Collision Hotspot Analysis

## Overview
This project examines the spatial distribution of motor vehicle collisions within the City of Kitchener between 2015 and 2022. The goal was to identify persistent high-risk zones to inform resource allocation for the Waterloo Regional Police Service and City of Kitchener planners.

## Tools Used
- ArcGIS Pro (Spatial Analysis, Generate Tessellation, Spatial Join)

## Methodology
- Converted raw CSV collision data into spatial point features using the NAD 1983 UTM Zone 17N coordinate system for accurate distance calculations.
- Generated a 1 km² hexagonal tessellation grid to aggregate individual collision points. Hexagons were chosen over squares to reduce edge effects and show spatial patterns more naturally.
- Performed a Spatial Join to count the total number of collisions per hexagon, turning individual data points into grouped density values.
- Clipped the hexagonal grid to the City of Kitchener municipal boundary to ensure data accuracy.
- Applied Natural Breaks (Jenks) classification to create both choropleth and graduated symbol maps, effectively highlighting high-collision areas in an unevenly distributed dataset.

## Key Findings
- Motor vehicle collisions are heavily concentrated in the downtown core, specifically centered around the Queen Street North and King Street East intersection.
- Despite a sharp drop in the city's total collision count between 2015 and 2022, the downtown core consistently remained the highest-collision area. This indicates that hotspots are driven by street layout, dense commercial activity, and pedestrian crossings rather than just overall traffic volume.
- Secondary high-risk zones align with major arterial roads and highway connectors, such as the Homer Watson Blvd and Huron Rd interchange.
- These spatial insights allow police to focus speed checks and collision prevention downtown during peak hours, and allow city planners to prioritize traffic signal improvements at specific high-risk intersections.

## Maps

<img width="100%" alt="Motor Vehicle Collisions in the City of Kitchener" src="Motor Vehicle Collisions in the City of Kitchener.jpg" />
<p align="center"><small>Figure 1: Spatial analysis of motor vehicle collisions in the City of Kitchener (2015-2022), highlighting persistent hotspots in the downtown core and along major arterial interchanges.</small></p>
