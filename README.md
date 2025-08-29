# msstate_portal

This repository contains the code that powers the [Mississippi River Basin Weather Data Portal](https://experience.arcgis.com/experience/8fcc16b9920e4d5fae2ee4c7ad1379c4/page/Home).

## Overview
- The portal provides daily environmental data (precipitation, temperature, wind, humidity, solar radiation, soil moisture, and evapotranspiration) across the Mississippi River Basin.  
- Data processing and updates are handled using **ArcGIS Online (AGOL) Notebooks** integrated with **Google Earth Engine (GEE)**.  
- A **scheduled task** in AGOL runs the script daily, exporting data to related tables and updating the maps used in the portal.  

## Environment
Note: This code is designed to run inside the **AGOL Notebooks environment** with scheduling enabled. It may require adjustments to execute locally.  
