# Chittagong Air Pollution Analysis (AQI-GEE)

[![Google Earth Engine](https://img.shields.io/badge/Google%20Earth%20Engine-4285F4?style=flat&logo=google-earth&logoColor=white)](https://earthengine.google.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A professional Earth Engine based analysis of Nitrogen Dioxide (NO₂) concentration changes in Chittagong, Bangladesh, focusing on the impact of COVID-19 lockdowns in 2020. This repository leverages Sentinel-5P TROPOMI data to quantify air quality variations and population-weighted exposure.

## 🚀 Key Features
- **Spatial Analysis:** High-resolution mapping of tropospheric NO₂ using Sentinel-5P.
- **Population Weighting:** Advanced exposure analysis using Gridded Population of the World (GPWv4) data.
- **Time Series:** Comparative analysis between 2019 (Baseline) and 2020 (Lockdown).
- **Visualization:** Integrated split-panel maps and dynamic charts within the GEE interface.

## 📂 Repository Structure
- `src/`: Core Google Earth Engine JavaScript source code.
- `results/`: Visualization outputs, maps, and statistical charts.
- `docs/`: Technical methodology and detailed project documentation.

## 🛠️ Getting Started
1. Open the [Google Earth Engine Code Editor](https://code.earthengine.google.com/).
2. Copy the contents of [`src/analysis.js`](src/analysis.js) into a new script.
3. Select your study area (Default: Chittagong) and run the script.

## 📊 Results Summary
The analysis observed a significant reduction in NO₂ levels during the March 2020 lockdown period compared to the 2019 baseline. Population-weighted concentrations highlight that urban centers experienced the most dramatic changes in exposure levels.

For detailed visual reports, see the [Results gallery](results/).

## ⚖️ License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🏷️ Citation
If you use this code or data in your research, please cite it as follows:
```text
Ahmed, T. (2025). Chittagong Air Pollution Analysis (AQI-GEE). GitHub Repository.
```
See [CITATION.cff](CITATION.cff) for more details.
