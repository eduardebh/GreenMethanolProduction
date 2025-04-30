# Green Methanol Potential Assessment

This project assesses the potential for green methanol production across regions in Colombia using hourly solar radiation data, biomass availability, and techno-economic modeling.

## Key Features

- Retrieval of hourly solar radiation data via the PVGIS API.
- Automation of Excel-based energy system models using `xlwings`.
- Calculation of key outputs: Hydrogen, E-Methanol, Bio-Methanol, and Bio-E-Methanol.
- Geographic visualization using `geopandas` and `matplotlib`.
- Statistical analysis and plotting with `pandas`, `seaborn`, and `statsmodels`.

## Requirements

- Python 3.9+
- Libraries: `pandas`, `geopandas`, `xlwings`, `matplotlib`, `seaborn`, `statsmodels`, `scikit-learn`
- Microsoft Excel (required for `xlwings` automation)

## Structure

- `Input_file.xlsx`: input data file with regional information.
- `Output_file.xlsx`: full results per location.
- `Output_file_summary.xlsx`: regional summary with average metrics.
- `images_report/`: folder containing generated plots and maps.
- `departamentos.json`: GeoJSON file with Colombian department boundaries.

## How to Run

1. Adjust file paths in the main script as needed.
2. Execute the script section by section (preferably in Jupyter, Spyder, or similar IDE).
3. Check the `images_report/` folder for visual outputs.

