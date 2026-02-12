# Falcon 9 Launch Success and Cost Optimization Analytics System

This repository presents an end-to-end data science and analytics project analyzing SpaceX Falcon 9 launch missions to identify key drivers of launch success, booster reusability, and mission cost efficiency using machine learning and interactive dashboards.

The project demonstrates a production-style analytical workflow including data acquisition, transformation, exploratory analysis, predictive modeling, and dashboard-based insight delivery aligned with real-world data scientist responsibilities.

------------------------------------------------------------

## Business Objective

Space launches involve extremely high operational cost and technical risk.  
Understanding factors influencing launch success and reusable booster recovery can significantly improve mission planning, reliability, and cost efficiency.

This project analyzes Falcon 9 mission data to:

- Identify key drivers of launch and landing success  
- Predict first-stage booster landing outcomes  
- Analyze impact of payload mass, orbit type, and launch site  
- Evaluate cost efficiency of reusable rocket technology  
- Deliver interactive dashboard for analytical and decision support  

------------------------------------------------------------

## Tech Stack

Programming: Python, SQL  
Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Folium  
Machine Learning: Logistic Regression, Support Vector Machine, Decision Tree, K-Nearest Neighbors  
Visualization: Power BI, Interactive Dashboard  
Data Sources: SpaceX REST API, Web Scraping  
Deployment: GitHub Pages (Interactive dashboard hosting)

------------------------------------------------------------

## Live Interactive Dashboard

Project Link:  
https://srikanth-ai53.github.io/Falcon-9-Launch-Success-Evaluation/

Dashboard features:
- Launch success rate analysis  
- Payload vs success relationship  
- Launch site performance comparison  
- Booster reuse and landing insights  
- Interactive filtering for dynamic analysis  

------------------------------------------------------------

## End-to-End Data Science Workflow

### Data Collection
- Extracted structured launch data using SpaceX REST APIs  
- Supplemented dataset through web scraping of mission records  

### Data Processing and Transformation
- Cleaned and preprocessed raw data using Python  
- Structured dataset using SQL queries and aggregations  
- Performed feature engineering for modeling  

### Exploratory Data Analysis
- Analyzed launch success patterns across payload mass, orbit type, and launch site  
- Evaluated impact of booster reuse on mission outcomes  
- Conducted statistical and visual analysis to identify trends  

### Geospatial Analysis
- Built interactive geospatial visualizations using Folium  
- Evaluated geographic influence of launch site location on operations  

### Machine Learning Modeling
Developed supervised classification models to predict landing success:

- Logistic Regression  
- Support Vector Machine  
- Decision Tree Classifier  
- K-Nearest Neighbors  

Best Performing Model: Decision Tree  
Accuracy: ~94% on test dataset  

Models evaluated using cross-validation and performance metrics.

### Dashboard and Insight Delivery
- Designed interactive dashboard for KPI and trend analysis  
- Visualized launch success patterns and cost efficiency drivers  
- Built decision-support views for mission planning analysis  
- Enabled dynamic filtering by payload and launch site  

------------------------------------------------------------

## Key Insights

- Reusable boosters significantly improve mission cost efficiency  
- Payload mass strongly influences landing success probability  
- Orbit type and configuration affect mission outcomes  
- Launch site selection impacts reliability and recovery success  
- Predictive modeling enables estimation of booster landing probability  

------------------------------------------------------------

## Project Impact

This project demonstrates a complete real-world data science workflow:

- API-based data extraction and web data collection  
- SQL-based data transformation and structured analysis  
- Machine learning model development and evaluation  
- Interactive dashboard creation for decision support  
- End-to-end analytics pipeline from raw data to insight delivery  

Represents a production-style analytical system aligned with modern data scientist and analytics roles.

------------------------------------------------------------

## Author

Srikanth Ponnala  
Data Scientist | Machine Learning and Analytics
