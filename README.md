# DATA72000--Environmental Analysis

### This repository contains the code and data materials for my MSc ERP project.  

The aim of this study is to compare three modelling approaches for predicting long-term mean PM2.5 concentrations across the United Kingdom:  

•Random Forest (RF) – a non-linear ensemble method  

•Bayesian Neural Network (BNN) – a probabilistic deep learning approach  

•Geographically Weighted Regression (GWR) – a local spatial-statistical model  


The work demonstrates both the strengths and limitations of applying advanced machine learning methods under sparse monitoring conditions, and provides recommendations for environmental monitoring policy.

data/
│
├── TIF/                  # Raster predictor variables (geospatial layers)
│   ├── AllRoads_1km.tif
│   ├── Altitude_1km.tif
│   ├── Industrial_1km.tif
│   ├── MajorRoads_1km.tif
│   ├── Nature_1km.tif
│   ├── Ports_1km.tif
│   ├── Residential_1km.tif
│   ├── TotalBuild_1km.tif
│   └── UrbanGreen_1km.tif
│
├── uk_pm_2020.csv        # Daily PM2.5 monitoring data for 2020
└── uk_pm_2021-2025.csv   # Daily PM2.5 monitoring data for 2021–2025
