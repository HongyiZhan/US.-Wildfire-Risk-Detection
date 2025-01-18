# US.Wildfire Risk Prediction Analysis

This project begins with data ingestion and exploratory data analysis (EDA) to assess and understand wildfire risk data. Using geospatial wildfire data from 1878 to 2019 provided by the USGS, we processed and visualized patterns in wildfire occurrences, acres burned, and fire causes. The EDA highlighted temporal and regional trends, with visualizations like bar plots, pie charts, and heatmaps providing insights into seasonal and geographic patterns.

The first task focused on evaluating the 2018 predictions using 2019 wildfire data. By mapping predicted risks against observed wildfires, we analyzed the model's accuracy, generating confusion matrices and performance metrics (accuracy, precision, recall, and F1-score). Visualizations, such as risk maps and heatmaps, provided spatial insights into prediction quality.

The second task examined model drift, comparing the 2018 and 2022 risk scores to identify changes over time. Statistical tests confirmed significant shifts in predictions, with a transition matrix revealing how risk categories evolved. Clustering analysis highlighted regions with substantial risk changes, such as California and the Pacific Northwest, with notable increases in risk scores in some areas and decreases in others.

Overall, the project provides a comprehensive analysis of wildfire prediction performance, including accuracy evaluation, regional risk shifts, and insights into the model's adaptation to changing conditions.

---

**Wildfire Risk Prediction Analysis Catalog**

1. Data Ingestion
2. Exploratory Data Analysis (Wildfire Shapefile Data)
3. Task 1: Evaluate the 2018 Predictions
4. Task 2: Analyze Model Drift

## Introduction

Wildfires pose significant environmental, economic, and health challenges. This project evaluates predictions made in 2018 by comparing them with actual 2019 wildfire data from the United States Geological Survey (USGS). Additionally, the analysis examines model drift by comparing 2018 risk scores with 2022 scores to understand prediction changes over time.

![Wildfire Risk Analysis](path/to/US.-Wildfire-Risk-Detection/Heatmap)
---

## Data Sources

- **2018 Predictions**: Predictions from the initial wildfire risk model.
- **2019 Actuals**: USGS wildfire data for ground-truth comparison. https://www.sciencebase.gov/catalog/item/5ee13de982ce3bd58d7be7e7
- **2022 Scores**: Updated wildfire risk scores for drift analysis.

---

## Project Objectives

1. **Evaluate Prediction Accuracy**: Compare 2018 predictions against 2019 wildfire data.
2. **Analyze Model Drift**: Assess the changes in risk scores from 2018 to 2022 to determine potential shifts in prediction behavior.

---

## Methods

The project uses the following steps:
1. **Data Cleaning and Preprocessing**: Prepare datasets for analysis by handling missing values and aligning formats.
2. **Model Evaluation**: Compare 2018 predictions with 2019 data to calculate accuracy and other metrics.
3. **Drift Analysis**: Analyze the temporal changes in risk scores between 2018 and 2022.
4. **Visualization**: Create charts and heatmaps to highlight findings.

---
