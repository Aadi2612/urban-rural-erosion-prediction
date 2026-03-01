**Urban vs Rural Soil Erosion Prediction using Machine Learning & GIS
**

**Project Overview
**
This project compares and studies urban and rural soil erosion prediction models using geospatial data and Machine Learning models . The workflow integrates Machine Learning, GIS processing (QGIS), and Web Visualization.
The system predicts erosion risk and provides prevention strategies through a web-based decision support interface. It also compares the functioning between different ML models and compares for the best output .

**Objectives
**
1.Develop separate ML models for Urban and Rural regions
2.Compare erosion behaviour in Chennai (Urban) and Thanjavur (Rural)
3.Integrate ML outputs with GIS heatmaps
4.Provide erosion risk label and actionable steps 
5.Deploy predictions through an interactive web map

**Data Used
**

DEM (Elevation)
NDVI (Vegetation Index)
Rainfall
Soil K-Factor (ISED)
Soil Moisture (for rural)
LULC (land use)
Boundary shapefile
Soil Grids (Clay and Sand content)
All rasters were clipped to study area boundary and extracted to point datasets using QGIS.

**Machine Learning Model
**
Model: Gradient Boosting
Evaluation Metrics:
R² Score
RMSE

Feature Importance Analysis performed
Separate models trained for:

Urban Region (Chennai)
Rural Region (Thanjavur)

**GIS Workflow
**
Raster preprocessing in QGIS
Extraction of raster values to points
CSV export for ML training
Prediction export to CSV
Conversion to GeoJSON
Heatmap visualization
Website integration using Leaflet.js

**Web Application Features
**
Location dropdown selector
Erosion prediction visualization
Risk classification
Prevention recommendation system
Interactive Leaflet map
GeoJSON integration

**Project Pipeline
**
Data Collection → Data Cleaning → ML Training → Prediction Export → GIS Visualization → Web Deployment

## Large Dataset Notice
Raw raster datasets are not included due to size limitations.
They can be provided upon request.
