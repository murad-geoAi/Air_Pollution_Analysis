# Technical Methodology

## Data Sources
- **Sentinel-5P TROPOMI:** Tropospheric NO₂ column density (OFFL/L3_NO2).
- **GPWv4 (CIESIN):** Gridded Population of the World, Version 4.11, Population Count.
- **GAUL (FAO):** Global Administrative Unit Layers (2015) for regional boundaries.

## Analysis Workflow
1. **Masking:** Applied a cloud fraction threshold of 0.3 to Sentinel-5P imagery to ensure data quality.
2. **Aggregation:** Calculated median composites for March 2019 (Baseline) and March 2020 (Lockdown).
3. **Population Weighting:** Computed population-weighted concentrations using the formula:
   $$Exp = \sum \left( \frac{P_i}{P_{total}} \times C_i \right)$$
   where $P_i$ is pixel population and $C_i$ is NO₂ concentration.

## Algorithms
- **GEE Reducers:** `ee.Reducer.mean()` and `ee.Reducer.sum()` were used for spatial aggregation.
- **Visual Comparison:** Implementation of `ui.SplitPanel` for side-by-side interactive map comparison.
