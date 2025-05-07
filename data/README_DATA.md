# Data Description

This folder contains the datasets used for training and validating the limestone suitability prediction model.

## 1. geochemical_data.csv

- **Description**: Major oxide geochemistry of limestone samples collected from core logs.
- **Columns** (example):
  - `Sample_ID`: Unique identifier for each sample
  - `SiO2`, `Al2O3`, `Fe2O3`, `CaO`, `MgO`, `LOI`: Major oxides in wt%
  - `CIA`, `WIP`: Weathering indices (if applicable)
- **Source**: Laboratory analysis (e.g., XRF, AAS)
- **Purpose**: Used to assess limestone purity and infer suitability for cement production.

## 2. borehole_data.csv

- **Description**: Simplified borehole thickness and location data used to model limestone quantity and depth.
- **Columns**:
  - `Borehole_ID`
  - `Latitude`
  - `Longitude`
  - `Limestone_Thickness and overburden thickness` (in meters)
- **Purpose**: Used to spatially constrain and correlate geochemical data with subsurface information.

---

All datasets are anonymized and shared under the [MIT License](../LICENSE). Use only for academic or non-commercial research.
