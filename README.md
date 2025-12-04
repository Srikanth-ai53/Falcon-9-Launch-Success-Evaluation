# Falcon-9-Launch-Success-Evaluation

This repository presents an end-to-end data science project analyzing SpaceX Falcon 9 launch missions to identify technical, operational
, and environmental factors influencing launch success. The project is implemented as a production-oriented analytical workflow, covering data acquisition,
transformation, exploratory analysis, interactive visualization, dashboard delivery, and predictive modeling.

---

## Project Workflow

**Data Collection**
- Falcon 9 launch data collected programmatically using REST APIs
- Supplemental mission data obtained via web scraping

**Data Wrangling**
- Cleaning, transformation, and feature engineering using Python
- Relational querying and aggregation performed using SQL for structured analysis

**Exploratory Data Analysis (EDA)**
- Statistical and visual exploration of launch outcomes
- Analysis across payload mass, orbit type, booster version, and launch site
- Combination of distribution analysis and grouped comparisons

**Geospatial Analysis**
- Interactive geospatial analysis using Folium
- Mapping and spatial evaluation of launch sites with respect to:
  - Railways
  - Highways
  - Coastlines

**Interactive Dashboard**
- A lightweight interactive dashboard developed to support dynamic analysis
- Dropdown selectors and sliders enable:
  - Launch site-based filtering
  - Payload range adjustment
  - Real-time observation of launch success rates

**Machine Learning**
- Multiple supervised classification models developed to predict launch success:
  - Logistic Regression
  - Support Vector Machine (SVM)
  - Decision Tree Classifier
  - K-Nearest Neighbors (KNN)
- Models evaluated using train/test split and cross-validation
- **Decision Tree Classifier achieved the highest performance with approximately 94% test accuracy**, demonstrating strong predictive capability on the given feature set

---

## Interactive Visualizations

Geospatial visualizations created with Folium are exported as standalone HTML files and are not rendered interactively within GitHub notebook previews.

✅ Recommended viewing method: **GitHub Pages**

🔗 **Live Dashboard**  
[https://srikanth-ai53.github.io/Falcon-9-Launch-Success-Evaluation/](https://srikanth-ai53.github.io/Falcon-9-Launch-Success-Evaluation/)

The deployed dashboard and maps support full interactivity, including zooming, panning, tooltips, dropdown controls, and sliders.

---

## Repository Structure

---

## Summary
This project demonstrates applied, full-cycle data science execution — from raw data ingestion to interactive 
analytical delivery and predictive modeling. Emphasis is placed on deploying interpretable, decision-support tools rather than static notebook-only outputs, 
aligning with real-world data analyst and junior data scientist expectations.

---

**Author**  
Srikanth
