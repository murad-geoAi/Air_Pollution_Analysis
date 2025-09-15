# Chittagong Air Pollution Analysis

Welcome to the repository for my project analyzing air pollution changes in the Chittagong division, Bangladesh, using Google Earth Engine (GEE). This work explores the impact of COVID-19 lockdowns on nitrogen dioxide (NO₂) concentrations, enhanced with advanced machine learning algorithms and time series analysis for predictive insights. This repository was last updated at 05:02 AM +06 on Monday, September 15, 2025.

## Project Overview
Inspired by the insights from "Chapter A1.4: Air Pollution and Population Exposure" by Zander Venter and Sourangsu Chowdhury, this project leverages Sentinel-5P data to quantify NO₂ variations. The analysis highlights significant reductions in NO₂ levels during the March 2020 lockdown compared to the 2019 baseline, with a focus on population-weighted exposure in urban areas. To push the boundaries further, I integrated machine learning models like LSTM and XGBoost for time series forecasting, enabling predictions of future air quality trends.

## Key Features
- **Data Processing:** Utilizes GEE to process Sentinel-5P data, generating time series and split-panel maps.
- **Exposure Analysis:** Calculates population-weighted NO₂ concentrations to assess human exposure.
- **Machine Learning:** Applies LSTM and XGBoost for forecasting NO₂ trends based on historical patterns.
- **Visualization:** Includes charts (DOY time series, mean vs. population-weighted NO₂) and a baseline vs. lockdown map.

## Results
The project reveals:
- A notable drop in mean NO₂ levels during the lockdown, reflecting reduced emissions.
- Higher exposure in populated zones, emphasizing the need for targeted air quality measures.
- Predictive models offering a glimpse into future pollution scenarios.

Check out the [results](results/) for visualizations, including:
- DOY time series chart (2019 vs. 2020)
- Mean and population-weighted NO₂ time series
- Baseline vs. lockdown split-panel map

