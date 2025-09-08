# DATA72000--Extended Research Project (Environmental Analysis)

### This repository contains the code and data materials for my MSc ERP project.  

The aim of this study is to compare three modelling approaches for predicting long-term mean PM2.5 concentrations across the United Kingdom:  

•Random Forest (RF) – a non-linear ensemble method  

•Bayesian Neural Network (BNN) – a probabilistic deep learning approach  

•Geographically Weighted Regression (GWR) – a local spatial-statistical model  


The work demonstrates both the strengths and limitations of applying advanced machine learning methods under sparse monitoring conditions, and provides recommendations for environmental monitoring policy.


## data/  

Contains all input datasets required for the analysis.  
•TIF/ – Raster predictor variables (geospatial layers), including:  
	•	AllRoads_1km.tif – total road density  
	•	MajorRoads_1km.tif – major roads (A-roads, motorways)  
	•	Altitude_1km.tif – elevation (1 km resolution)  
	•	Industrial_1km.tif – industrial land-use density  
	•	Nature_1km.tif – natural/green land cover  
	•	Ports_1km.tif – port density  
	•	Residential_1km.tif – residential building density  
	•	TotalBuild_1km.tif – total building footprint density  
	•	UrbanGreen_1km.tif – urban green space  
•uk_pm_2020.csv – Daily PM2.5 monitoring data for 2020 (from UK-AIR)  


### Note: The full daily PM2.5 dataset is too large to upload. It can be downloaded directly from the UK-AIR website (Pollutant = PM2.5, Years = 2020–2025, Format = CSV).  
### https://uk-air.defra.gov.uk/data/  

## code.ipynb

The main Jupyter Notebook containing the full workflow, including:  
•Data preprocessing and feature extraction  
•Exploratory analysis (EDA) and multicollinearity checks (VIF)  
•Model training (Random Forest, Bayesian Neural Network, GWR)  
•Evaluation, visualisation, and uncertainty mapping    

## requirements.txt/
Lists all Python package dependencies (with pinned versions) needed to reproduce the analysis.
