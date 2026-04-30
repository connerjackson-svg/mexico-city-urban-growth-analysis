

# Mexico City Urban Growth Analysis (2005–2022)

## Overview
Geospatial machine learning project analyzing historical urban expansion in Mexico City, forecasting future development pressure, and identifying priority zones for green infrastructure investment.

## Project Objective
This project combines remote sensing, predictive spatial modeling, and sustainability planning to evaluate how Mexico City has expanded and where future growth may create environmental stress.

## Methods

### Part 1 — Urban Change Detection
Landsat 7/8 satellite composites for 2005 and 2022 were classified into four land-cover categories:

- Urban
- Bare Soil
- Vegetation
- Water

A Random Forest classifier trained on manually selected samples was used to generate land-cover maps and quantify change over time.

### Key Result
- 249.91 km² of new urban land added between 2005 and 2022
- Expansion concentrated along the metropolitan fringe
- Vegetation was the primary displaced land-cover type

### Part 2 — Growth Prediction
A probabilistic urban growth model was developed using:

- Distance to existing urban areas
- Elevation (SRTM)
- Slope

A 70/30 train-test split evaluated predictive performance.

### Key Result
Distance to existing urban land was the strongest predictor of future expansion.

### Part 3 — Green Infrastructure Targeting
A weighted multi-criteria suitability index was constructed using:

- Urban growth probability (40%)
- Distance from green space (30%)
- Slope (20%)
- Land cover type (10%)

The top 8% of scores were identified as priority intervention zones.

### Policy Value
Recommended areas can help mitigate:

- Urban heat island intensification
- Reduced stormwater absorption
- Unequal green space access

## Tools & Technologies

- Google Earth Engine
- JavaScript
- Landsat 7/8
- Random Forest Classification
- SRTM DEM
- GIS Spatial Analysis
- Remote Sensing

## Links

[View GEE script](maps/)    
[View all maps](maps/)  
[View all reports](maps/)  

## Skills Demonstrated

Remote sensing, geospatial analytics, machine learning, environmental planning, data visualization, sustainability strategy
