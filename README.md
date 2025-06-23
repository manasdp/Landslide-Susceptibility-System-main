# Landslide Susceptibility System

This project provides a machine learning–based framework to assess and predict **landslide susceptibility** using geospatial and environmental features. It aims to support disaster risk reduction and early warning systems by identifying regions prone to landslides based on terrain and climate-related data.

---

## Overview

Landslides are a serious hazard in many geographic regions. Accurate and data-driven prediction can help reduce risk to life and infrastructure. This project builds and evaluates a model to classify areas as **landslide-prone** or **safe** based on key features such as:

- Slope
- Elevation
- Soil type
- Rainfall
- Distance to roads and rivers
- Land cover

---

## Features

- Data preprocessing pipeline for geospatial terrain and environmental datasets
- Feature engineering based on domain knowledge (DEM, land use, hydrology)
- Classification using:
  -  Random Forest
  -  Logistic Regression
  -  Decision Tree
- Evaluation metrics:
  -  Accuracy
  -  Precision, Recall, F1-score
  -  ROC-AUC
-  Visualizations:
  -  Heatmaps of susceptibility
  -  Feature importance plots
  -  Confusion matrix and ROC curve

---
## Results
- Model Accuracy: ~90% (varies by dataset)
- Top features: Slope, rainfall, soil type
- Visual Outputs:
  - Susceptibility heatmap
  - ROC curve
  - Feature importance rankings
    
---
## Use Cases
- Early warning systems for landslide-prone regions
- Risk assessment in urban planning and infrastructure development
- Environmental research and disaster management

---
## License
MIT License © 2025 Manas Patil
