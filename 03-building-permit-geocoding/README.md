# City of Kitchener Building Permit Geocoding & Spatial Analysis (1999–2022)

## Overview
This project involves the geocoding and spatial-temporal analysis of new construction building permits issued in the City of Kitchener over a 23-year period. The goal was to visualize urban growth patterns and identify construction hotspots to inform municipal infrastructure planning.

## Tools Used
- ArcGIS Pro (Geocoding, Custom Address Locator, Spatial Aggregation)

## Methodology
- Filtered a dataset of 26,027 records to isolate "New Construction" permits issued between 1999 and 2022.
- Built a custom geocoding locator with optimized field mapping to maximize match rates while avoiding commercial geocoding credit costs.
- Manually reviewed and resolved tied address records to ensure spatial accuracy.
- Applied hexagonal binning (aggregation) set to 2 standard deviations to visualize point density, effectively highlighting construction hotspots and reducing visual clutter from tens of thousands of overlapping points.

## Key Findings
- **Geocoding Success:** Achieved a 94% successful match rate (24,497 matched records), with only 1 tied record manually resolved and ~5.8% unmatched due to addresses not yet existing in the city's reference database.
- **Spatial Patterns:** Construction hotspots are heavily concentrated around the edges of the city, indicating outward urban expansion and "greenfield development," which aligns with the City of Kitchener’s 2009 Growth Management Strategy.
- **Temporal Trends:** Identified distinct peaks in construction activity in 2005 and 2016, with a notable downturn from 2008 to 2013 that strongly correlates with the economic impact of the 2008 Global Financial Crisis.

## Maps

<img width="100%" alt="New Construction Building Permits Issued in the City of Kitchener, 1999-2022" src="New Construction Building Permits Issued in the City of Kitchener, 1999-2022.jpg" />
<p align="center"><small>Figure 1: Hexagonal binning map showing spatial density and hotspots of new construction building permits in Kitchener (1999-2022).</small></p>
