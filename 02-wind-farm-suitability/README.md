# Multi-Criteria Site Suitability for Small-Scale Wind Farms

## Overview
This project identifies viable, regulation-compliant locations for small-scale wind farms in the Niagara Region, Ontario. A multi-criteria decision analysis (MCDA) was conducted to assess wind speed potential, distance from infrastructure, and compliance with provincial safety guidelines.

## Tools Used
- ArcGIS Pro (Spatial Analyst, Weighted Overlay)

## Methodology
- Conducted a GIS-based Multi-Criteria Decision Analysis (MCDA) integrating 6 spatial criteria: wind speed (40%), distance to roads (20%), buildings (15%), built-up areas (10%), forests (10%), and aviation safety (5%).
- Performed Euclidean distance analysis and raster reclassification to convert vector data into a common 1 to 5 suitability scale.
- Enforced strict regulatory exclusion zones (assigned a value of 0/Restricted), including areas with wind speeds under 4.17 m/s, within 550m of buildings, 1000m of airports/urban areas, or 70m of roads.
- Applied a Weighted Overlay to combine the reclassified rasters into a final suitability map.

## Key Findings
- Identified 2 viable proposed sites, each covering an area of 20,087 m².
- Calculated that each site can accommodate 4 turbines in a square pattern with 141m spacing.
- This spacing meets the 60m to 300m provincial turbine spacing guidelines while staying under the 5-turbine limit for small-scale wind farm definitions.
- Both sites avoid all regulatory exclusion buffers and are located in areas with moderate to strong wind potential.

## Maps

<img width="100%" alt="Proposed Small-Scale Wind Farms in Niagara Region, Ontario" src="Proposed Small-Scale Wind Farms in Niagara Region, Ontario.jpg" />
<p align="center"><small>Figure 1: Multi-criteria suitability map showing proposed small-scale wind farm sites in the Niagara Region, Ontario.</small></p>
