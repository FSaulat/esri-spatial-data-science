# Section 3: Finding Optimal Locations Using Suitability Models

This folder contains the coursework, notebooks, and data for Week 3 of the Esri Spatial Data Science MOOC.

## Overview
In this module, we explore Suitability Modeling to determine the best locations for a specific purpose based on multiple criteria. This process involves combining raster data layers (such as slope, land cover, and proximity to roads) through weighted analysis to create a final suitability map.

## Learning Objectives
By the end of this section, I will be able to:
- Understand the fundamentals of Multi-Criteria Decision Analysis (MCDA).
- Transform data layers into a common measurement scale (Reclassification).
- Apply weights to different criteria based on their importance.
- Combine raster layers to generate a final suitability model.
- Interpret the results to identify optimal locations.

## Contents
(Update this list as you add files)

- data/: Contains the raw and processed datasets used for the analysis (e.g., shapefiles, rasters).
- notebooks/: Jupyter Notebooks containing the Python analysis.
    - 01_data_preparation.ipynb: Loading and cleaning spatial data.
    - 02_suitability_analysis.ipynb: Performing the weighted overlay analysis.
- outputs/: Generated maps and visualizations resulting from the analysis.

## Tools and Libraries Used
- ArcGIS API for Python (arcgis)
- ArcPy (if applicable)
- Pandas and NumPy for data manipulation
- Matplotlib / Seaborn for visualization

## Key Concepts
1. Reclassification: Standardizing different data types (e.g., distance in meters vs. slope in degrees) into a uniform scale (e.g., 1-10).
2. Weighting: Assigning relative importance to criteria (e.g., "Proximity to Water" is more important than "Elevation").
3. Weighted Overlay: The mathematical process of combining the layers to produce a suitability score.

## Notes
- This workflow is commonly used for real estate site selection, conservation planning, and urban development.
- Ensure all raster datasets share the same coordinate system and cell size before running the analysis.
