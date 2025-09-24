# Water Vapor Pressure Correlation Analysis

## Project Description
This project analyzes the correlation between temperature and vapor pressure of water using Python data science tools. The analysis demonstrates the strong exponential relationship between these two physical properties and provides statistical insights through correlation analysis.

## Dataset
The dataset contains 11 data points of water vapor pressure measurements at different temperatures:
- **Temperature range**: 273 K to 373 K (0°C to 100°C)
- **Vapor pressure range**: 4.7 to 760 mmHg
- **Data source**: `datasets/Correlation.csv`

## Features
- Data visualization with scatter plots
- Statistical correlation analysis
- Exponential curve fitting (when scipy is available)
- Basic data summary statistics
- Professional matplotlib visualizations with proper labels and formatting

## Dependencies
- pandas
- numpy
- matplotlib
- scipy (optional, for curve fitting)

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/jidhu-mohan/Correlation_Vapor-Pressure.git
   cd Correlation_Vapor-Pressure
   ```

2. Install required dependencies:
   ```bash
   pip install pandas numpy matplotlib scipy
   ```

## Usage
Open and run the Jupyter notebook:
```bash
jupyter notebook "Vapour_Pressure_Correlation copy.ipynb"
```

Or use any Jupyter-compatible environment like VS Code, JupyterLab, or Google Colab.

## Results
The analysis reveals:
- **Strong positive correlation** between temperature and vapor pressure
- **Exponential relationship** following the Clausius-Clapeyron equation
- **R² value** close to 1.0, indicating excellent model fit

## Physical Background
The relationship between vapor pressure and temperature follows the Clausius-Clapeyron equation, which predicts an exponential increase in vapor pressure with temperature. This fundamental relationship is crucial in thermodynamics, meteorology, and chemical engineering.

## License
This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.

## Contributing
Feel free to submit issues, fork the repository, and create pull requests for any improvements.

## Author
- jidhu-mohan