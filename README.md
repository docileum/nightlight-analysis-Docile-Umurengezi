# nightlight-analysis-Docile-Umurengezi

## Overview

This project visualizes nightlight intensity data across Rwanda, combining raster satellite imagery with administrative boundaries at multiple levels (country, Districts). The goal is to provide a clear spatial understanding of lighting patterns, which can serve as a proxy for population distribution, infrastructure development, and economic activity. It ends by showing the ten most lighted cells 

## Approach

### 1. Data Preparation
Loaded Rwanda entire raster data and the Rwanda raster was clipped. 
Imported administrative boundaries from shapefiles (ADM0 for country, ADM2 for District)

### 1. Visualization
Two plots:
1. Clipped raster showing raw nightlight intensity.
2. Raster overlaid with District boundaries and their names.

A Raster of Rwandan nightlight and a file (excel) containing cell stats were stored in an ouputs folder. 