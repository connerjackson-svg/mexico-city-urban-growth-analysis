# Mexico City Urban Growth Analysis (2005–2022)
Geospatial machine learning project analyzing urban expansion in Mexico City and identifying priority zones for green infrastructure investment.

## Overview
A geospatial machine learning project analyzing historical urban expansion in Mexico City, forecasting future growth pressure, and identifying priority zones for green infrastructure intervention.

## Objective
To quantify urban sprawl, predict likely future development areas, and propose sustainability-focused interventions.

## Tools Used
- Google Earth Engine
- JavaScript
- Landsat 7/8
- Random Forest Classification
- SRTM DEM
- Spatial Modeling
- GIS Multi-Criteria Analysis

## Part 1: Urban Change Detection
Landsat composites for 2005 and 2022 were classified into:
- Urban
- Bare Soil
- Vegetation
- Water

### Results
- 249.91 km² of new urban land detected
- Expansion concentrated along peripheral edges
- Vegetation was the most displaced land cover type

## Part 2: Growth Prediction Model
A probabilistic model predicted future development likelihood using:

- Distance to urban areas
- Elevation
- Slope

### Findings
Distance to existing urban land was the strongest predictor.

## Part 3: Green Infrastructure Intervention Strategy
A weighted suitability index identified high-priority investment zones based on:

- Growth probability (40%)
- Distance from green space (30%)
- Slope (20%)
- Land cover type (10%)

### Result
Top 8% of scores selected as priority zones.

## Policy Value
These areas help mitigate:
- Urban heat island effects
- Stormwater runoff risk
- Unequal access to green space

## Skills Demonstrated
Remote sensing, machine learning, spatial analysis, sustainability planning, environmental decision-making
