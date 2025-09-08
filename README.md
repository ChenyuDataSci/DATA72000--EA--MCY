# DATA72000--Environmental Analysis

This is a repository for DATA72000 Extended Research Project

# Reproducibility Material for ERP Report

## 1. Requirements
Create environment:
```bash
pip install -r requirements.txt

## 2. How to Run
1. Prepare data:
   - Place `.tif` raster files in `data/sample_tif/`
   - Place `uk_pm_2020.csv` and `uk_pm_2021-2025.csv` in `data/`

2. Run preprocessing:
```bash
python src/preprocessing.py --config config.yaml
