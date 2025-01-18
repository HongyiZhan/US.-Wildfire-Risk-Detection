# US.-Wildfire-risk-detection

# Wildfire Risk Prediction Analysis

This project evaluates wildfire risk predictions and analyzes model drift over time using historical wildfire data. The primary focus is to assess the accuracy and evolution of predictions to improve wildfire management and prevention.

---

## Table of Contents

- [Introduction](#introduction)
- [Data Sources](#data-sources)
- [Project Objectives](#project-objectives)
- [Methods](#methods)
- [Usage](#usage)
- [Results](#results)
- [Dependencies](#dependencies)
- [Future Work](#future-work)
- [Contributing](#contributing)
- [License](#license)

---

## Introduction

Wildfires pose significant environmental, economic, and health challenges. This project evaluates predictions made in 2018 by comparing them with actual 2019 wildfire data from the United States Geological Survey (USGS). Additionally, the analysis examines model drift by comparing 2018 risk scores with 2022 scores to understand prediction changes over time.

---

## Data Sources

- **2018 Predictions**: Predictions from the initial wildfire risk model.
- **2019 Actuals**: USGS wildfire data for ground-truth comparison.
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

## Usage

### Prerequisites
- Install the required Python libraries listed in `requirements.txt`.
- Ensure you have access to the datasets for 2018, 2019, and 2022.

### Running the Analysis
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/wildfire-risk-prediction.git
