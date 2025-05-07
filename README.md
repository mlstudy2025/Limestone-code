# Data Description – Limestone Prediction Model

This folder contains the datasets used for developing and evaluating the machine learning model for predicting limestone suitability for cement production.

## Files Included

### 1. `geochemical_data.csv`
- **Description**: Geochemical composition of limestone samples, including major oxide percentages.
- **Columns**:
  - Sample_ID
  - SiO2 (%)
  - Al2O3 (%)
  - Fe2O3 (%)
  - CaO (%)
  - MgO (%)
  - LOI (%)
  - [Other oxides if applicable]

### 2. `borehole_data.csv`
- **Description**: Basic borehole information and limestone thickness per borehole location.
- **Columns**:
  - Borehole_ID
  - Location (Latitude, Longitude)
  - Limestone_Thickness (m)
  - Limestone_Overburden (m)
  - [Other parameters, if any]

## Notes
- All data were collected for academic research purposes.
- Units for oxide contents are in percentage weight (%).
- Coordinate values (if included) are referenced in WGS84.
- Some minor preprocessing was applied to remove outliers and ensure consistency.

## License
These datasets are shared under the [MIT License](../LICENSE) for research and educational use only. Users must cite the source when used.

